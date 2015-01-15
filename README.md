# Learn how to use style frameworks
	By:patterns
	Markups: "using Emmlet syntax" http://docs.emmet.io/cheat-sheet/

#Founation 
##VISIBILITY CLASSES
```sass
 @import "foundation/components/visibility";
```
SHOW visibility classes to show certain strings of text based on the device on which users view a page.
Markup:	
```
div.panel+span.show-for-small-only+.show-for-medium-up
```	
Pattern: .{action}-for-{sizes}-{quantity}
{action}:show|hide
{sizes}: small|medium|large|xlarge|xxlarge
{quantity}: only|up
####Orientation Detection
Pattern:.show-for-{orintation}
{oriantation}:landscape|portrait
####Touch Detection
```	
pattern:.{action}-for-touch
```
####Accessibility
pattern:
```
.hidden-for-{sizes}-{quantity}
```
##OFF-CANVAS
Off-canvas menus are positioned outside of the viewport and slide in when activated. 

MARKUP: 
```.off-canvas-wrap>.inner-wrap+a.left-off-toggle+aside.left-off-canvas-menu>ul>li*^(p+a.exit-off-canvas)
```

#Bootstrap

