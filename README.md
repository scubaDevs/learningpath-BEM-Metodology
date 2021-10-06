# learningpath-BEM Metodology
 Learning BEM methodology for css

 BEM = Block Element Modifier

 Block = Content that HTML tags are the elemen ts inside the Block.

 Modifier = Change the css from a previus status to one other.

 Block:

 Just class can be used
 The block class on css must be away separate from other classes.

 .block {

 };
 ok

 .block__item{


 }; 
 ok

.block .block__item{

};
NOT OK on BEM rulles.
The scss is more readable with hierarchy