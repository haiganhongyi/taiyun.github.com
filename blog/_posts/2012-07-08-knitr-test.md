



---
layout: post
title: knitr动画测试
author: <a href="http://taiyun.github.com/">Taiyun</a>
---



```r
set.seed(123)
rnorm(5)
```

```
[1] -0.56048 -0.23018  1.55871  0.07051  0.12929
```

```r
x <- 1:10
library(corrplot)
corrplot(cor(mtcars))
```

```r
corrplot(cor(mtcars), order = "AOE")
```

```r
corrplot(cor(mtcars), order = "hclust")
```


<div class="scianimator"><div id="test_r2swf" style="display: inline-block;"></div></div>
<script type="text/javascript">
  (function($) {
    $(document).ready(function() {
      $("#test_r2swf").scianimator({
          "images": ["http://taiyun.github.com/blog/pic/test-r2swf1.svg", "http://taiyun.github.com/blog/pic/test-r2swf2.svg", "http://taiyun.github.com/blog/pic/test-r2swf3.svg"],
          "delay": 1000,
          "controls": ["first", "previous", "play", "next", "last", "loop", "speed"],
      });
      $("#test_r2swf").scianimator("play");
    });
  })(jQuery);
</script>





```r
set.seed(123)
rnorm(5)
```

```
[1] -0.56048 -0.23018  1.55871  0.07051  0.12929
```

```r
x <- 1:10
library(corrplot)
corrplot(cor(mtcars))
```

```r
corrplot(cor(mtcars), order = "AOE")
```

```r
corrplot(cor(mtcars), order = "hclust")
```


<div class="scianimator"><div id="test_r2" style="display: inline-block;"></div></div>
<script type="text/javascript">
  (function($) {
    $(document).ready(function() {
      $("#test_r2").scianimator({
          "images": ["http://taiyun.github.com/blog/pic/test-r21.svg", "http://taiyun.github.com/blog/pic/test-r22.svg", "http://taiyun.github.com/blog/pic/test-r23.svg"],
          "delay": 1000,
          "controls": ["first", "previous", "play", "next", "last", "loop", "speed"],
      });
      $("#test_r2").scianimator("play");
    });
  })(jQuery);
</script>

```r
## setwd('G:');knitr::knit2html('knitr-test001.Rmd')
```





```r
set.seed(123)
rnorm(5)
```

```
[1] -0.56048 -0.23018  1.55871  0.07051  0.12929
```

```r
x <- 1:10
library(corrplot)
corrplot(cor(mtcars), order = "AOE")
library(ggplot2)
qplot(wt, mpg, data = mtcars) + facet_grid(vs ~ am, label = label_both)
```

<img src="http://taiyun.github.com/blog/pic/test-r1.svg" width="800px" height="800px"  alt="plot of chunk test-r" title="plot of chunk test-r" /> <img src="http://taiyun.github.com/blog/pic/test-r2.svg" width="800px" height="800px"  alt="plot of chunk test-r" title="plot of chunk test-r" /> 





$latex P(E) = {n \choose k} p^k (1-p)^{n-k}$

$$latex
  \begin{aligned}
  \dot{x} & = \sigma(y-x) \\
  \dot{y} & = \rho x - y - xz \\
  \dot{z} & = -\beta z + xy
  \end{aligned}
$$

