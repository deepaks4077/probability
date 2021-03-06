<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tfp.edward2.LogNormal" />
<meta itemprop="path" content="Stable" />
</div>

# tfp.edward2.LogNormal


<table class="tfo-notebook-buttons tfo-api" align="left">

<td>
  <a target="_blank" href="https://github.com/tensorflow/probability/blob/master/tensorflow_probability/python/experimental/edward2/interceptor.py">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td></table>



Create a random variable for LogNormal.

### Aliases:

* `tfp.experimental.edward2.LogNormal`


``` python
tfp.edward2.LogNormal(
    *args,
    **kwargs
)
```



<!-- Placeholder for "Used in" -->

See LogNormal for more details.

#### Returns:

RandomVariable.


#### Original Docstring for Distribution

Construct a log-normal distribution.

The LogNormal distribution models positive-valued random variables
whose logarithm is normally distributed with mean `loc` and
standard deviation `scale`. It is constructed as the exponential
transformation of a Normal distribution.

#### Args:


* <b>`loc`</b>: Floating-point `Tensor`; the means of the underlying
  Normal distribution(s).
* <b>`scale`</b>: Floating-point `Tensor`; the stddevs of the underlying
  Normal distribution(s).
* <b>`validate_args`</b>: Python `bool`, default `False`. Whether to validate input
  with asserts. If `validate_args` is `False`, and the inputs are
  invalid, correct behavior is not guaranteed.
* <b>`allow_nan_stats`</b>: Python `bool`, default `True`. If `False`, raise an
  exception if a statistic (e.g. mean/mode/etc...) is undefined for any
  batch member If `True`, batch members with valid parameters leading to
  undefined statistics will return NaN for this statistic.
* <b>`name`</b>: The name to give Ops created by the initializer.