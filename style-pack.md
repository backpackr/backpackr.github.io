<head>
    <script src="https://cdn.jsdelivr.net/gh/backpackr/style-pack/app.js"></script>
</head>

<div class="container">

# style-pack demo

### contents

-   [container](#container)
-   [color](#color)
-   [align](#align)
-   [flex_grid](#flex_grid)

## container

```html
<div style="overflow: auto;" class="container">
    <div style="width: 300px; height: 300px;" class="container">
        class="contaienr"
    </div>
    <div style="width: 300px; height: 300px;" class="container_left">
        class="container_left"
    </div>
    <div style="width: 300px; height: 300px;" class="container_right">
        class="container_right
    </div>
</div>
```

<div style="overflow: auto;" class="container">
    <div style="width: 300px; height: 300px;" class="container color_point_01_back">class="contaienr"</div>
    <div style="width: 300px; height: 300px;" class="container_left color_point_01_back">class="container_left"</div>
    <div style="width: 300px; height: 300px;" class="container_right color_point_01_back">class="container_right</div>
</div>

## color

```html
<div
    style="width: 300px; height: 300px; border: 3px solid;"
    class="container color_point_01_font color_grayscale_01_back color_sub_01_border"
>
    sample
</div>
```

<div style="width: 300px; height: 300px;" class="container color_point_01_font color_grayscale_01_back color_sub_01_border">sample</div>

> `_back`: background-color
> `_font`: color
> `_border`: border-color

### List of colors

-   color_point_01
-   color_point_02
-   color_point_03
-   color_point_dark_01
-   color_point_dark_02
-   color_point_dark_03
-   color_point_light_01
-   color_point_light_02
-   color_point_light_03
-   color_point_light_04
-   color_sub_01
-   color_sub_02
-   color_sub_03
-   color_sub_dark_01
-   color_sub_light_01
-   color_sub_light_02
-   color_sub_light_03
-   color_grayscale_01
-   color_grayscale_02
-   color_grayscale_03
-   color_grayscale_04
-   color_grayscale_light_01
-   color_grayscale_light_02
-   color_grayscale_light_03

<div class="container flex_grid align_center_text_center">
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

> We are working on it!

## flex_grid

You can change `width` of each `flex_grid` and see how they response.

### default

```html
<div class="container flex_grid align_center_text_center">
    <div class="flex_col_1 color_point_01_back">col 1</div>
    <div class="flex_col_2 color_sub_01_back">col 2</div>
    <div class="flex_col_3 color_grayscale_01_back">col 3</div>
    <div class="flex_col_4 color_point_02_back">col 4</div>
    <div class="flex_col_5 color_sub_02_back">col 5</div>
    <div class="flex_col_6 color_grayscale_02_back">col 6</div>
    <div class="color_point_03_back">col 1</div>
    <div class="color_sub_03_back">col 1</div>
    <div class="color_grayscale_03_back">col 1</div>
    <div class="color_point_dark_01_back">col 1</div>
    <div class="color_sub_dart_01_back">col 1</div>
    <div class="color_grayscale_04_back">col 1</div>
</div>
```

<div class="container flex_grid align_center_text_center">
    <div class="flex_col_1 color_point_01_back">col 1</div>
    <div class="flex_col_2 color_sub_01_back">col 2</div>
    <div class="flex_col_3 color_grayscale_01_back">col 3</div>
    <div class="flex_col_4 color_point_02_back">col 4</div>
    <div class="flex_col_5 color_sub_02_back">col 5</div>
    <div class="flex_col_6 color_grayscale_02_back">col 6</div>
    <div class="color_point_03_back">col 1</div>
    <div class="color_sub_03_back">col 1</div>
    <div class="color_grayscale_03_back">col 1</div>
    <div class="color_point_dark_01_back">col 1</div>
    <div class="color_sub_dart_01_back">col 1</div>
    <div class="color_grayscale_04_back">col 1</div>
</div>

### flex_grid_6

```html
<div class="container flex_grid_6 align_center_text_center">
    <div class="flex_col_1 color_point_01_back">col 1</div>
    <div class="flex_col_2 color_sub_01_back">col 2</div>
    <div class="flex_col_3 color_grayscale_01_back">col 3</div>
    <div class="flex_col_4 color_point_02_back">col 4</div>
    <div class="flex_col_5 color_sub_02_back">col 5</div>
    <div class="flex_col_6 color_grayscale_02_back">col 6</div>
    <div class="color_point_03_back">col 1</div>
    <div class="color_sub_03_back">col 1</div>
    <div class="color_grayscale_03_back">col 1</div>
    <div class="color_point_dark_01_back">col 1</div>
    <div class="color_sub_dart_01_back">col 1</div>
    <div class="color_grayscale_04_back">col 1</div>
</div>
```

<div class="container flex_grid_6 align_center_text_center">
    <div class="flex_col_1 color_point_01_back">col 1</div>
    <div class="flex_col_2 color_sub_01_back">col 2</div>
    <div class="flex_col_3 color_grayscale_01_back">col 3</div>
    <div class="flex_col_4 color_point_02_back">col 4</div>
    <div class="flex_col_5 color_sub_02_back">col 5</div>
    <div class="flex_col_6 color_grayscale_02_back">col 6</div>
    <div class="color_point_03_back">col 1</div>
    <div class="color_sub_03_back">col 1</div>
    <div class="color_grayscale_03_back">col 1</div>
    <div class="color_point_dark_01_back">col 1</div>
    <div class="color_sub_dart_01_back">col 1</div>
    <div class="color_grayscale_04_back">col 1</div>
</div>

</div>
