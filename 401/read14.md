# Matplotlib 

![](matplotlib.png)
matplotlib is also a massive library, and getting a plot to look just right is often achieved through trial and error. Using one-liners to generate basic plots in matplotlib is fairly simple, but skillfully commanding the remaining 98% of the library can be daunting.

# Ipmort Matplotlib
```
import numpy as np

```

# Plot 


```
X = np.linspace(-np.pi, np.pi, 256, endpoint=True)
C, S = np.cos(X), np.sin(X)
```

# plot configuration

## change color ,line width ..etc

```
plt.figure(figsize=(10,6), dpi=80)
plt.plot(X, C, color="blue", linewidth=2.5, linestyle="-")
plt.plot(X, S, color="red",  linewidth=2.5, linestyle="-")

```
## add legend 

```
plt.legend(loc='upper left', frameon=False)

```


check [documentaion](https://matplotlib.org/)