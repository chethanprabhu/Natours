Notes
Note: Allignment may not to good here. Please download repo and view using your editor.
-------
1) Clip path: clip-path: //AnyShape ex - polygon
   We can build build in shapes at https://bennettfeely.com/clippy/

2) Box sizing: box-sizing: //value. ex - border-box
   basically there are 2 types. Border box and content box. By default it's content box.
   Content box means that the padding, border etc etc we apply will add to the total width.
   Ex - if width is 500px. Now if we add padding of 10px and border of 2px. Then the total width will be 512px
   Border box(recommended) means that the padding, border etc wont be added to toal width.
   Ex - if width is 500px. Now if we add padding of 10px and border of 2px. Then the total width will remain at 500px.
   There is another called box-sizing: inherit. Which simply inherits the box sizing of parent.

3) For main headings where is the size is big give and less font weight and for sub headings where the 
   size is less give more font weight. 

4) animation shorthand: animation: animation-name time timing-function delay.

5) box-shadow shorthand: box-shadow: right-side bottom-side blue color;

6) user-select: none -> does not allow user to select that particular element using mouse.

7) !important has highiest speficity. Then inline CSS, then IDs, then classes and lastly element selectors.
   ex - 1 ID has higher speficity than 1000 classes.
      #heading {
         color: green;
      }

      .heading heading-red heading-bold heading-main {
         color: red;
      }
      here green will be applied.