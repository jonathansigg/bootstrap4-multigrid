# bootstrap4-multigrid
Multiple Grids for Bootstrap 4

**Install**
Install with bower:
```
bower install bootstrap4-multigrid --save
```

You can adjust grids with variable:
```
$multiple-grid: (
  columns_1: 16,
  columns_2: 20,
  columns_3: 12
);
```

Now you can use more than 1 gridsize. Just append new class ```col-xs-12```  ```-grid-[your grid columns]```
Here is an example:
```
<div class="row">
  <div class="col-xs-12 col-md-4-grid-20 col-lg-2-grid-16"></div>
  <div class="col-xs-12 col-md-4-grid-20 col-lg-2-grid-16"></div>
  <div class="col-xs-12 col-md-4-grid-20 col-lg-2-grid-16"></div>
  <div class="col-xs-12 col-md-4-grid-20 col-lg-2-grid-16"></div>
  <div class="col-xs-12 col-md-4-grid-20 col-lg-2-grid-16"></div>
</div>
```

On Screen bigger and equal then medium, there will be 5 columns total. And for screen bigger and equal then large there will be 8 columns
