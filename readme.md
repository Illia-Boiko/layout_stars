# Stars block
- [DEMO LINK](https://illia-boiko.github.io/layout_stars/)
- [TEST REPORT LINK](https://illia-boiko.github.io/layout_stars/report/html_report/)

## The task
Implement the [`stars` block](https://www.figma.com/file/euXjY316CHKYkPRO1K0kjLsF/Moyo-Catalog?node-id=11325%3A2961) used in card and catalog.
You DON'T need to implement the card now, just the stars block.

![Stars](./reference/stars.png)
___

- You can find star images in `images` folder
- Reset browser's default `margin`
- Implement 6 blocks with `stars` class
  - The first should have `stars--0` class
  - The next 5 blocks should have an extra class `stars--1`, `stars--2` ... `stars--5` (one extra class per block)
- Each block should have exactly 5 stars styled as in the card design
- The number of active (yellow) stars should be different for all 6 blocks depending on modifier class
  - The first block (with just `stars` class) don't have active stars
  - The other 5 blocks have exactly N fisrt stars active where N is a numbers in an additional css class (modifier) `stars--N`
  - Add images in CSS, instead of using the HTML "img" or "svg" tags
- Each star in a block should have a class `stars__star` and no extra classes or inline styles
  - The star size is fixed (see in the design)
  - The distance between the stars is also fixed 
  - Use `display: flex` for the `stars` block to avoid an issue with extra spaces between individual stars
