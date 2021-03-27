# SkewedNormalDist

A python class for calculating the probability density function of a skewed normal distribution given its **mode** (i.e. location of the peak), standard deviation, and alpha (skewness parameter).

Example:

`snd = SkewedNormalDist(mode=2, std=1, alpha=3)
x = np.arange(-3, 7, 0.1)
y = snd.pdf(x)
plt.plot(x,y)
plt.grid()
`

![image](https://user-images.githubusercontent.com/41363258/112726061-1ba00a80-8f24-11eb-9513-01c7bfa841e8.png)
