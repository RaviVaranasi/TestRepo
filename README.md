# Store-Systems (3.78.2 - 3.78.3)

### [146481677](https://www.pivotaltracker.com/story/show/146481677) - Correct problem with hanging progress dialog while creating an order from a GoShop! cart in CSD
#### QA Owner ```Lisa Wynne```
 - [x] QA - create a GoShop cart and create an order with that cart while in CSD
 - [x] QA - verify 6AV/LEX still work

### [146002769](https://www.pivotaltracker.com/story/show/146002769) - With decor drawer fronts when lids are added, the labels do not reflect the lid has been added
#### QA Owner ```Lisa Wynne```
 - [x] QA - if lids are added for either smoke or translucent drawers a "L" indicator in the label should appear
 - [x] QA - if lids are removed the "L" should go away
 - [x] QA - verify lids are not an option for mesh drawers
 - [x] QA - verify product list - lids are added or removed as appropriate
 - [x] QA - verify regular decor drawers work the same as they always do
 - [x] QA - verify still works for hanging drawers as they always do
 - [x] QA - june elfa SKU feature off
 - [x] QA - accessory tray drawer fronts work as expected
 - [x] QA - verify dividers are still an option for mesh drawers

### [146525547](https://www.pivotaltracker.com/story/show/146525547) - Fix NPE error in RodFigure validation
#### QA Owner ```Lisa Wynne```
 - [x] QA - Regress closet rod figure scenarios
 - [x] QA - Maybe try the duplicate hang tool from floor view.

### [144389593](https://www.pivotaltracker.com/story/show/144389593) - Add Closet Rod Bracket holder in product list (decor drawer fronts with hanging)
#### QA Owner ```Lisa Wynne```
 - [x] QA - if decor fronts on one side, should have the correct (left or right) closet rod bracket cover
 - [x] QA - if decor drawer fronts on both sides of the rod, should have a left and a right closet rod holder bracket cover
 - [x] QA -verify shelf is not required over the rod when using 2 closet rod holder bracket covers
 - [x] QA - if remove the decor drawer fronts, the closet rod holder bracket cover should convert to closet rod holder and all current validation should apply 
 - [x] QA - verify the SKUs are correct
 - [x] QA - verify a shelf is required on one side if only 1 drawer front
 - [x] QA - validation is correct for a rod under a solid shelf = NOT allowed
 - [x] QA - rod under a 20 inch ventilated or decor shelf NOT allowed
 - [x] QA - rod should be able to go under a  shelf basket
 - [x] QA - add a drawer front with a 4 foot rod and only a 2 foot shelf at opposite end of the rod from the drawer front and verify validation is correct
 - [x] QA - verify if a 4 foot rod with a drawer front on one end and a shelf at the other end that there is a validation 
