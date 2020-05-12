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

## Example
col-sm-*:

code:

<!DOCTYPE html>
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

 * Here it occupies into threee equal parts which is equalto 12   
