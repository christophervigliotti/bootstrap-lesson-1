# Bootstrap 5 Course: The Complete Guide

## Quick Setup

1. grabbed the examples at https://getbootstrap.com/docs/5.1/examples/ 
2. dropped in a folder and got a web server rolling via `sudo python3 -m http.server 80` 

## Notes By Section

## 2.9 Grids for multiple devices

* `col-lg-x` and `col-md-x`

```
<div class="container">
    <div class="row">
    <div class="col-lg-8 col-md-8">
        <div class="box"></div>
    </div>
    <div class="col-lg-4 col-md-8">
        <div class="box"></div>
    </div>
    </div>
    <div class="row">
    <div class="col-lg-3 col-md-3">
        <div class="box"></div>
    </div>
    <div class="col-lg-3 col-md-3">
        <div class="box"></div>
    </div>
    <div class="col-lg-3 col-md-3">
        <div class="box"></div>
    </div>
    <div class="col-lg-3 col-md-3">
        <div class="box"></div>
    </div>
    </div>
</div>
```

## 2.8 Grids Part 2

* grid system is divided into 8 columns

```
<!-- variable column widths! -->
    <div class="container">
      <div class="row">
        <div class="col-8">
          <div class="box"></div>
        </div>
        <div class="col-4">
          <div class="box"></div>
        </div>
      </div>
    </div>
```

## 2.7 Grids Part 1

* working with classes container, row and column (cool stuff)

## 2.6 Containers

```
container           xs      s       m       l       xl      xxl
---------           --      -       -       -       --      ---
.container          540     720     960     1140    1140    1320
.container-sm
.container-md
.container-lg
.container-xl
.container-xxl
.contianer-fuild    100%    100%    100%    100%    100%    100%
```

## 2.5 Breakpoints in Bootstrap 5

"Breakpoints are customizable widths that determine how your responsive layout behaves across device or viewport sizes in Bootstrap" via https://getbootstrap.com/docs/5.0/layout/breakpoints/ 

```
breakpoint          class infix     dim
----------          -----------     ---
x-small             none            0-576px
small               sm              >=576px
medium              md              >=768px
large               lg              >=992px
extra large         xl              >=1200px
extra extra large   xxl             >=1400px
```

### 1.4 Bootstrap 5 Document Structure (& quiz notes)
* we can use CDN for bootstrap 5 and not the local file
* swapped local file for CDN to test it out
* integrity attribute specifies that the file is unmodified

### 1.3 Hello World
* downloaded starter template, outputted Hello World zzz