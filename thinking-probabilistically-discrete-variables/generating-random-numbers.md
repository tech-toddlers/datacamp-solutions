---
description: In this section we learn how to generate random numbers using np.random
---

# Generating random numbers

Solution:

```text
# Seed the random number generator
np.random.seed(42)

# Initialize random numbers: random_numbers
random_numbers = np.empty(100000)

# Generate random numbers by looping over range(100000)
for i in range(100000):
    random_numbers[i] = np.random.random()

# Plot a histogram
_ = plt.hist(random_numbers)

# Show the plot
plt.show()
```

Plot output:

![](../.gitbook/assets/screenshot-2020-08-08-at-3.12.15-pm.png)

