# Bootstrap 5 Course: The Complete Guide

## Quick Setup

1. grabbed the examples at https://getbootstrap.com/docs/5.1/examples/ 
2. dropped in a folder and got a web server rolling via `sudo python3 -m http.server 80` 

## Notes By Section

Many notes are found in the code of their respective sections

## 4.section_number section_title
notes_go_here

## 4.section_number section_title
notes_go_here

## 4.16 Styling the Form
see index.4.16.html

## 4.15 Designing form holder with custom & built-in css

Added classes to the div that is the parent of the form tag

`<div class="border border-info mt-3 my_form rounded">`
* border-info gives it a blue border
* mt-3 gives it a margin-top of 3 px
* rounded gives it rounded corners
* my_form is a custom class


## 4.14 Basic Login Form
Created a basic form with little Bootstrap styling...in preparation for the next section

## Quiz 3
aced it

## 3.13 Tables
notes in index.3.13.html cool stuff

## 3.12 Images
various image classes, notes in index.3.12.html

## 3.11 Typography
emphasis on h1 tags.  cool stuff, curious about if some of this will 508 or not.
notes in index.3.11.html

## Quiz 2
100%, baby!

## 2.10 Align Columns in Grid

vertical alignment using my custom class 'height' along with bootstrap row classes...

```
align-items-start   (aligns to top of box)
align-items-???     (aligns to vertical center of box)
align-items-end     (aligns to bottom of box)
```

horizintal alignment using bootstrap row classes... 

```
justify-content-start   (aligns to BLAH)
justify-content-center  (aligns to BLAH)
justify-content-end     (aligns to BLAH)
```

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

### 1.4 Bootstrap 5 Document Structure (& Quiz 1)
* we can use CDN for bootstrap 5 and not the local file
* swapped local file for CDN to test it out
* integrity attribute specifies that the file is unmodified

### 1.3 Hello World
* downloaded starter template, outputted Hello World zzz