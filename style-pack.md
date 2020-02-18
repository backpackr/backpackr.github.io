<head>
  <script src="https://cdn.jsdelivr.net/gh/backpackr/style-pack/app.js"></script>
</head>

# style-pack demo

### contents

- [container](#container)
- [color](#color)
- [align](#align)
- [flex_grid](#flex_grid)
- [grid](#grid)
- [radius](#radius)
- [overflow](#overflow)

## container

### default

```html
<div style="overflow: auto;" class="container">
  <div
    style="width: 300px; height: 300px; color: white;"
    class="container color_point_01_back"
  >
    class="contaienr"
  </div>
  <div
    style="width: 300px; height: 300px; color: white;"
    class="container_left color_sub_01_back"
  >
    class="container_left"
  </div>
  <div
    style="width: 300px; height: 300px; color: white;"
    class="container_right color_grayscale_01_back"
  >
    class="container_right
  </div>
</div>
```

<div style="overflow: auto;" class="container">
  <div style="width: 300px; height: 300px; color: white;" class="container color_point_01_back">class="contaienr"</div>
  <div style="width: 300px; height: 300px; color: white;" class="container_left color_sub_01_back">class="container_left"</div>
  <div style="width: 300px; height: 300px; color: white;" class="container_right color_grayscale_01_back">class="container_right</div>
</div>

### container_layout

Container for layout. It will set width with screen size.

```css
@media screen and (min-width: 720px) {
  .container_layout {
    width: 1080px;
  }
}
@media screen and (max-width: 720px) {
  .container_layout {
    width: 100%;
  }
}
```

```html
<div
  style="height: 300px; color: white;"
  class="container_layout color_point_01_back"
>
  container_layout
</div>
```

<div style="height: 300px; color: white;" class="container_layout color_point_01_back">container_layout</div>

## color

```html
<div
  style="width: 300px; height: 300px; border: 3px solid;"
  class="container color_point_01_font color_grayscale_01_back color_sub_01_border"
>
  sample
</div>
```

<div style="width: 300px; height: 300px; border: 3px solid" class="container color_point_01_font color_grayscale_01_back color_sub_01_border">sample</div>

> `_back`: background-color  
> `_font`: color  
> `_border`: border-color

### List of colors

- color_point_01
- color_point_02
- color_point_03
- color_point_dark_01
- color_point_dark_02
- color_point_dark_03
- color_point_light_01
- color_point_light_02
- color_point_light_03
- color_point_light_04
- color_sub_01
- color_sub_02
- color_sub_03
- color_sub_dark_01
- color_sub_light_01
- color_sub_light_02
- color_sub_light_03
- color_grayscale_01
- color_grayscale_02
- color_grayscale_03
- color_grayscale_04
- color_grayscale_light_01
- color_grayscale_light_02
- color_grayscale_light_03

<div class="flex_grid_6 align_text_center">
  <div style="height: 100px;" class="color_point_01_back">color_point_01</div>
  <div style="height: 100px;" class="color_point_02_back">color_point_02</div>
  <div style="height: 100px;" class="color_point_03_back">color_point_03</div>
  <div style="height: 100px;" class="color_point_dark_01_back">color_point_dark_01</div>
  <div style="height: 100px;" class="color_point_dark_02_back">color_point_dark_02</div>
  <div style="height: 100px;" class="color_point_dark_03_back">color_point_dark_03</div>
  <div style="height: 100px;" class="color_point_light_01_back">color_point_light_01</div>
  <div style="height: 100px;" class="color_point_light_02_back">color_point_light_02</div>
  <div style="height: 100px;" class="color_point_light_03_back">color_point_light_03</div>
  <div style="height: 100px;" class="color_point_light_04_back">color_point_light_04</div>
  <div style="height: 100px;" class="color_sub_01_back">color_sub_01</div>
  <div style="height: 100px;" class="color_sub_02_back">color_sub_02</div>
  <div style="height: 100px;" class="color_sub_03_back">color_sub_03</div>
  <div style="height: 100px;" class="color_sub_dark_01_back">color_sub_dark_01</div>
  <div style="height: 100px;" class="color_sub_light_01_back">color_sub_light_01</div>
  <div style="height: 100px;" class="color_sub_light_02_back">color_sub_light_02</div>
  <div style="height: 100px;" class="color_sub_light_03_back">color_sub_light_03</div>
  <div style="height: 100px;" class="color_grayscale_01_back">color_grayscale_01</div>
  <div style="height: 100px;" class="color_grayscale_02_back">color_grayscale_02</div>
  <div style="height: 100px;" class="color_grayscale_03_back">color_grayscale_03</div>
  <div style="height: 100px;" class="color_grayscale_04_back">color_grayscale_03</div>
  <div style="height: 100px;" class="color_grayscale_light_01_back">color_grayscale_light_01</div>
  <div style="height: 100px;" class="color_grayscale_light_02_back">color_grayscale_light_02</div>
  <div style="height: 100px;" class="color_grayscale_light_03_back">color_grayscale_light_03</div>
</div>

## align

### default

```html
<div class="container align_flex-start_center">
  <div class="color_point_01_back">example</div>
  <div class="color_point_01_back">example</div>
  <div class="color_point_01_back">example</div>
</div>
<div class="container align_center_flex-end">
  <div class="color_point_01_back">example</div>
  <div class="color_point_01_back">example</div>
  <div class="color_point_01_back">example</div>
</div>
<div class="container align_flex-end_flex-start">
  <div class="color_point_01_back">example</div>
  <div class="color_point_01_back">example</div>
  <div class="color_point_01_back">example</div>
</div>
```

<div style="height: 200px; border: 1px solid black;" class="container align_flex-start_center">
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
</div>
<div style="height: 200px; border: 1px solid black;" class="container align_center_flex-end">
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
</div>
<div style="height: 200px; border: 1px solid black;" class="container align_flex-end_flex-start">
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
  <div style="width: 100px; height: 100px;" class="color_point_01_back">example</div>
</div>

### align_text

```html
<h2 class="align_text_left">I'm text-align left!</h2>
<h2 class="align_text_center">I'm text-align center!</h2>
<h2 class="align_text_right">I'm text-align right!</h2>
```

<h2 class="align_text_left">I'm text-align left!</h2>
<h2 class="align_text_center">I'm text-align center!</h2>
<h2 class="align_text_right">I'm text-align right!</h2>

## flex_grid

You can change `width` of each `flex_grid` and see how they response.

### default

```html
<div class="flex_grid align_text_center">
  <div class="flex_col_1">col 1</div>
  <div class="flex_col_2">col 2</div>
  <div class="flex_col_3">col 3</div>
  <div class="flex_col_4">col 4</div>
  <div class="flex_col_5">col 5</div>
  <div class="flex_col_6">col 6</div>
  <div>col 7</div>
  <div>col 8</div>
  <div>col 9</div>
  <div>col 10</div>
  <div>col 11</div>
  <div>col 12</div>
</div>
```

<div class="flex_grid align_text_center">
  <div class="flex_col_1 color_point_01_back">col 1</div>
  <div class="flex_col_2 color_sub_01_back">col 2</div>
  <div class="flex_col_3 color_grayscale_01_back">col 3</div>
  <div class="flex_col_4 color_point_02_back">col 4</div>
  <div class="flex_col_5 color_sub_02_back">col 5</div>
  <div class="flex_col_6 color_grayscale_02_back">col 6</div>
  <div class="color_point_03_back">col 7</div>
  <div class="color_sub_03_back">col 8</div>
  <div class="color_grayscale_03_back">col 9</div>
  <div class="color_point_dark_01_back">col 10</div>
  <div class="color_sub_dart_01_back">col 11</div>
  <div class="color_grayscale_04_back">col 12</div>
</div>

### flex_grid_number

```html
<div class="flex_grid_6 align_text_center">
  <div class="flex_col_1">col 1</div>
  <div class="flex_col_2">col 2</div>
  <div class="flex_col_3">col 3</div>
  <div class="flex_col_4">col 4</div>
  <div class="flex_col_5">col 5</div>
  <div class="flex_col_6">col 6</div>
  <div>col 7</div>
  <div>col 8</div>
  <div>col 9</div>
  <div>col 10</div>
  <div>col 11</div>
  <div>col 12</div>
</div>
```

<div class="flex_grid_6 align_text_center">
  <div class="flex_col_1 color_point_01_back">col 1</div>
  <div class="flex_col_2 color_sub_01_back">col 2</div>
  <div class="flex_col_3 color_grayscale_01_back">col 3</div>
  <div class="flex_col_4 color_point_02_back">col 4</div>
  <div class="flex_col_5 color_sub_02_back">col 5</div>
  <div class="flex_col_6 color_grayscale_02_back">col 6</div>
  <div class="color_point_03_back">col 7</div>
  <div class="color_sub_03_back">col 8</div>
  <div class="color_grayscale_03_back">col 9</div>
  <div class="color_point_dark_01_back">col 10</div>
  <div class="color_sub_dart_01_back">col 11</div>
  <div class="color_grayscale_04_back">col 12</div>
</div>

## grid

You can change `width` of each `grid` and see how they response.

### default

```html
<div class="grid container">
  <div class="col_0_2">col 1</div>
  <div class="col_2_4">col 2</div>
  <div class="col_0_6">col 3</div>
  <div>col 4</div>
  <div>col 5</div>
  <div>col 6</div>
  <div>col 7</div>
  <div>col 8</div>
  <div>col 9</div>
  <div>col 10</div>
  <div>col 11</div>
  <div>col 12</div>
</div>
```

<div class="grid container">
  <div style="border: 1px solid black;" class="col_0_2">col 1</div>
  <div style="border: 1px solid black;" class="col_2_4">col 2</div>
  <div style="border: 1px solid black;" class="col_0_6">col 3</div>
  <div style="border: 1px solid black;">col 4</div>
  <div style="border: 1px solid black;">col 5</div>
  <div style="border: 1px solid black;">col 6</div>
  <div style="border: 1px solid black;">col 7</div>
  <div style="border: 1px solid black;">col 8</div>
  <div style="border: 1px solid black;">col 9</div>
  <div style="border: 1px solid black;">col 10</div>
  <div style="border: 1px solid black;">col 11</div>
  <div style="border: 1px solid black;">col 12</div>
</div>

### grid_number

```html
<div class="grid_7 container">
  <div class="col_0_2">col 1</div>
  <div class="col_2_4">col 2</div>
  <div class="col_0_6">col 3</div>
  <div>col 4</div>
  <div>col 5</div>
  <div>col 6</div>
  <div>col 7</div>
  <div>col 8</div>
  <div>col 9</div>
  <div>col 10</div>
  <div>col 11</div>
  <div>col 12</div>
</div>
```

<div class="grid_7 container">
  <div style="border: 1px solid black;" class="col_0_2">col 1</div>
  <div style="border: 1px solid black;" class="col_2_4">col 2</div>
  <div style="border: 1px solid black;" class="col_0_6">col 3</div>
  <div style="border: 1px solid black;">col 4</div>
  <div style="border: 1px solid black;">col 5</div>
  <div style="border: 1px solid black;">col 6</div>
  <div style="border: 1px solid black;">col 7</div>
  <div style="border: 1px solid black;">col 8</div>
  <div style="border: 1px solid black;">col 9</div>
  <div style="border: 1px solid black;">col 10</div>
  <div style="border: 1px solid black;">col 11</div>
  <div style="border: 1px solid black;">col 12</div>
</div>

## radius

You can choose radius size in `2, 5, 10, 15, 20, 25, 30`.

```html
<div>
  <div class="radius_2">test</div>
  <div class="radius_5_top">test</div>
  <div class="radius_10_bottom">test</div>
  <div class="radius_15_right">test</div>
  <div class="radius_20_left">test</div>
</div>
```

<div>
  <div style="width: 100px; height: 100px; margin: 5px;" class="radius_2 color_point_02_back">radius</div>
  <div style="width: 100px; height: 100px; margin: 5px;" class="radius_5_top color_point_02_back">radius top</div>
  <div style="width: 100px; height: 100px; margin: 5px;" class="radius_10_bottom color_point_02_back">radius bottom</div>
  <div style="width: 100px; height: 100px; margin: 5px;" class="radius_15_right color_point_02_back">radius right</div>
  <div style="width: 100px; height: 100px; margin: 5px;" class="radius_20_left color_point_02_back">radius left</div>
</div>

## overflow

### overflow_auto

```html
<div class="overflow_auto">
  <div>test</div>
  <div>test</div>
  <div>test</div>
  <div>test</div>
  <div>test</div>
</div>
```

<div style="width: 300px; height: 100px; border: 2px solid black;" class="overflow_auto">
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
</div>

### overflow_auto_hidescroll

```html
<div class="overflow_auto_hidescroll">
  <div>test</div>
  <div>test</div>
  <div>test</div>
  <div>test</div>
  <div>test</div>
</div>
```

<div style="width: 300px; height: 100px; border: 2px solid black;" class="overflow_auto_hidescroll">
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
  <div style="width: 100; height: 100; margin: 0 5px;" class="color_point_01_back">test</div>
</div>
