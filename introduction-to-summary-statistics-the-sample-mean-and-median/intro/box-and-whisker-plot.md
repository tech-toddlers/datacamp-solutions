---
description: In this section we will learn how to plot box plot.
---

# Box-and-whisker plot

#### Final Solution:

```text
# Create box plot with Seaborn's default settings
sns.boxplot(x='species', y='petal length (cm)', data=df)

# Label the axes
_ = plt.xlabel('species')
_ = plt.ylabel('petal length (cm)')

# Show the plot
plt.show()

```

Final out:

![](../../.gitbook/assets/screenshot-2020-08-08-at-12.56.19-pm.png)

