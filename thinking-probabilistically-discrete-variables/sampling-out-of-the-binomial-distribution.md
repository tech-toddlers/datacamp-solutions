# Sampling out of the Binomial distribution

#### Final solution:

```text
# Take 10,000 samples out of the binomial distribution: n_defaults
n_defaults = np.random.binomial(100, 0.05, 10000)

# Compute CDF: x, y
x, y = ecdf(n_defaults)

# Plot the CDF with axis labels
plt.plot(x,y, marker='.', linestyle='none')
plt.xlabel('number of defaults')
plt.ylabel('CDF')


# Show the plot
plt.show()

```

![](../.gitbook/assets/screenshot-2020-08-08-at-8.31.16-pm.png)

