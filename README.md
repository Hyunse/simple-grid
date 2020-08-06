## Simple-Grid

Simeple-Grid is a 12 column grid system.

**Deployed Link**

- https://hyunse.github.io/simple-grid/

**Technologies Used**

- CSS
- Grid Layout

**Contributors:** [Hyunse Kim](https://github.com/Hyunse)

---

## How to use

Add [CSS file](./grid.css)

```html
<head>
  ...
  <link type="text/css" href="grid.css" rel="stylesheet" />
  ...
</head>
```

This is a **12** column grid system. And it provides **responsive** columns.
|               | sm       | md     |
| ------------- |:--------:| :-----:|
| Width         | < 768px  |>= 768px|


```html
<div class="row">
  <div class="col-md-6 col-sm-6">
    column 1
  </div>
  <div class="col-md-6 col-sm-6">
    column 2
  </div>
</div>
```

## Todo
- [ ] Align items