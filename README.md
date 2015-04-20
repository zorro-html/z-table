# table

表格

支持的样式特性有：`[bordered]`、`[striped]`、`[hover]`

注：需要在最外层 (如 `<html>` 标签中) 加入一个特性 `z`，即：`<html z>`

## Examples

```
<table bordered striped hover>
  <thead>
    <tr><th>h1</th><th>h2</th><th>h3</th><th>h4</th></tr>
  </thead>
  <tbody>
    <tr><td>a1</td><td>a2</td><td>a3</td><td>a4</td></tr>
    <tr><td>b1</td><td>b2</td><td>b3</td><td>b4</td></tr>
    <tr><td>c1</td><td>c2</td><td>c3</td><td>c4</td></tr>
    <tr><td>d1</td><td>d2</td><td>d3</td><td>d4</td></tr>
  </tbody>
</table>
```
