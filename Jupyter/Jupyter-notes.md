
> Written with [StackEdit](https://stackedit.io/).

## Render and align images on Jupyter Lab

To render an image inside a Markdown dell use:

```
![](../imgs/logistic-function-01.png)
```

To align an image inside a Markdown cell use:

```
<img align="center" width="300" height="300" src="../imgs/logistic-function-01.png">
```
To align an images inside a code cell:

```python
%%html
<img src="../imgs/logistic-function-01.png" width="240" height="240" align="center"/>
```

or 

```python
from IPython.display import Image
Image(filename="../imgs/logistic-function-01.png", width=400, height=400)
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMjc0OTI2NjldfQ==
-->