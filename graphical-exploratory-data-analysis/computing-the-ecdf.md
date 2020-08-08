---
description: >-
  In this exercise, you will write a function that takes as input a 1D array of
  data and then returns the x and y values of the ECDF.
---

# Computing the ECDF

{% hint style="info" %}
Check out this video for ECDF: [https://www.youtube.com/watch?v=ap4mfGvgDsM](https://www.youtube.com/watch?v=ap4mfGvgDsM)
{% endhint %}

## Solution for Exercise: 

{% tabs %}
{% tab title="ecdf.py" %}
```python
def ecdf(data):
    """Compute ECDF for a one-dimensional array of measurements."""
    # Number of data points: n
    n = len(data)

    # x-data for the ECDF: x
    x = np.sort(data)

    # y-data for the ECDF: y
    y = np.arange(1, n+1) / n

    return x, y

```
{% endtab %}

{% tab title="output" %}
```

```
{% endtab %}
{% endtabs %}



