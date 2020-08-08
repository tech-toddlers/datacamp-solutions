# What are the chances of a horse matching or beating Secretariat's record?

{% tabs %}
{% tab title="solution.py" %}
```text
# Take a million samples out of the Normal distribution: samples
samples = np.random.normal(mu, sigma, 1000000)

# Compute the fraction that are faster than 144 seconds: prob
prob = np.sum(samples <= 144)/ len(samples)

# Print the result
print('Probability of besting Secretariat:', prob)

```
{% endtab %}

{% tab title="output" %}
```
Probability of besting Secretariat: 0.000635
```
{% endtab %}
{% endtabs %}



