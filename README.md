# `<z-table>`

Styled table element

## Usage

Just add `[z]` attribute to any parent element of the target table like `<html z>`

## Attributes

- `bordered`: bordered table style
- `striped`: striped table style
- `hover`: has hover effect

## Examples

```
<div z>
  <table>
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
</div>
```
