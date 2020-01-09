page_type: reference
<style>{% include "site-assets/css/style.css" %}</style>

<!-- DO NOT EDIT! Automatically generated file. -->

# tf.compat.v1.test.test_src_dir_path


<table class="tfo-notebook-buttons tfo-api" align="left">

<td>
  <a target="_blank" href="https://github.com/tensorflow/tensorflow/tree/r2.0/tensorflow/python/platform/test.py#L79-L90">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td></table>



Creates an absolute test srcdir path given a relative path.

``` python
tf.compat.v1.test.test_src_dir_path(relative_path)
```



<!-- Placeholder for "Used in" -->


#### Args:


* <b>`relative_path`</b>: a path relative to tensorflow root.
  e.g. "core/platform".


#### Returns:

An absolute path to the linked in runfiles.