# documentation3
# Bootstrap 4 Grid System:
  Grid System nested of rows class. In the bootstrap grid system allows upto 12 columns across the page. we can use the grid as per our requirement but total of grids is must be 12.

## How Works the bootstrap Grid System:
   The grid system is the bundle of classes. There are 12 columns and a 1-row total bundle of 13 classes. There is no limitation for the use of columns. But you have to mind one thing, The thing is the total of your grids must be 12. This is the biggest reason for the system is flexible with all the screen sizes. This grid system supports a max value of 12 columns. Anything after the 12th column will be shifted to a new line.
   
   This will re-arrange as per the device’s screen size. You can use the grid in the .row class. Row class is must be required for grids. because this will help to arrange the columns of the grid. and the row class should be nested of .container class. You can use rows in the .container class.
   
Grid Classes:
There are four classes in Bootstrap Grid System:
  * xs(for phones)
  * sm(for tablets)
  * md(for desktops)
  * lg(for larger desktops)
  
Bootstrap 4 Grid Classes:
There are 5 classes in Bootstrap grid system.
* .col-(extra small devices)
* .col-sm- (small devices)
* .col-md- (medium devices)
* .col-lg- (large devices)
* .col-xl- (xlarge devices)

 
   
   
## Size of grids in different screens:
____
**Screen Size** | **Columns work**
---|---
Less then 575px | col-*
Between 575px to 768px | col-sm-*
Between 768px to 992px | col-md-*
Between 992px to 1200px | col-lg-*
More then 1200px | col-xl-*

## Container:
* .container, which sets a max-width at each responsive breakpoint
* .container-fluid, which is width: 100% at all breakpoints

## Grid:
<img src="grid table.png" alt="Grid image"/>


## Example
col-sm-*:

code:

```<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <link rel="stylesheet" href="/css/bootstrap.min.css">
    <title></title>
    <style>
      .row_data{
        border: 2px dashed red;
        padding: 1%;
      }
      .col_data{
        border: 2px dotted blue;
        margin: 1%;
      }
    </style>
  </head>
  <body>
    <div class="container">
  <div class="row bg-light row_data">
    <div class="col-sm col_data">
      venkata
    </div>
    <div class="col-sm col_data">
      surya
    </div>
    <div class="col-sm col_data">
      narayana
    </div>
  </div>
</div>
  </body>
</html>
```

 * The above example creates three equal-width columns on small, medium,      large, and extra large devices using our predefined grid classes. Those    columns are centered in the page with the parent .container.
 
## Equal-width multi-line
* Create equal-width columns that span multiple lines by inserting a .w-100 where you want the columns to break to a new line. Make the breaks responsive by mixing .w-100 with some responsive display utilities.

```<div class="container">
  <div class="row">
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="w-100"></div>
    <div class="col">col</div>
    <div class="col">col</div>
  </div>
</div>
```

## Responsive classes
* Bootstrap’s grid includes five tiers of predefined classes for building complex responsive layouts. Customize the size of your columns on extra small, small, medium, large, or extra large devices however you see fit.

## All breakpoints
 * For grids that are the same from the smallest of devices to the largest, use the .col and .col-* classes. Specify a numbered class when you need a particularly sized column; otherwise, feel free to stick to .col.
 
 ```<div class="container">
  <div class="row">
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
  </div>
  <div class="row">
    <div class="col-8">col-8</div>
    <div class="col-4">col-4</div>
  </div>
</div>
```

## Stacked to horizontal:
* Using a single set of .col-sm-* classes, you can create a basic grid system that starts out stacked and becomes horizontal at the small breakpoint (sm).

```<div class="container">
  <div class="row">
    <div class="col-sm-8">col-sm-8</div>
    <div class="col-sm-4">col-sm-4</div>
  </div>
  <div class="row">
    <div class="col-sm">col-sm</div>
    <div class="col-sm">col-sm</div>
    <div class="col-sm">col-sm</div>
  </div>
</div>
```



```<div class="row" style="justify-content:center">
      <div class="col-md-4 col-sm-8 col-lg-4">
        <div class="card">
          <div class="card-header bg-success text-light"> Card header</div>
           <div class="card-body"> Card body</div>
          <div class="card-footer">card footer</div>
        </div>
     </div>
     <div class="col-md-4 col-sm-8 col-lg-4">
        <div class="card-header"> Card header</div>
        <div class="card-body"> Card body</div>
        <div class="card-footer">card footer</div>
     </div>
</div>
```
    
  In col-lg:
  <img src="col-lg.png" alt="image"/>

  
  In col-md:
   <img src="col-md.png" alt="image"/>
   
   col-sm:
    <img src="col-sm.png" alt="image"/>
  




 
