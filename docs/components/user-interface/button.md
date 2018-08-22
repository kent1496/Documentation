# Button


## Overview

A button is a basic UI element with which the user can interact with your apps by tapping or 
clicking on it to perform an action.


<br><br>
![Preview of button](/assets/images/components/user-interface/button/preview.png){: class="preview-img"}

A typical button
{: .img-caption}


## Properties

{!includes/bgcolor-property.md!}

!!! caution ""
    If the _[Image](#image)_ property is set, then this is overriden.


### Border Shadow

![](/assets/images/components/user-interface/button/d_border-shadow.png)

_**\(** Advanced | Setter only | Designer**\)**  
`Type: Color`_

The color of ripple effect when touching the button.


{!includes/enabled-property.md!}


{!includes/all-font-properties.md!}


{!includes/height-property.md!}


### Image

![](/assets/images/components/user-interface/button/d_image.png) ![](/assets/images/components/user-interface/button/p_image.png)

_**\(** Getter + Setter **\)**  
`Type: Asset`_ 

The image that is displayed on the button as a background.

!!! caution ""
    This property overrides the [Background Color](#background-color) property.


### Rotation Angle

![](/assets/images/components/user-interface/button/d_rotation-angle.png) ![](/assets/images/components/user-interface/button/p_rotation-angle.png)

_**\(** Getter + Setter **\)**  
`Type: Number`_ 

The degrees that the **Button** is rotated around the pivot point. Increasing values result in clockwise rotation.


### Shape

![](/assets/images/components/user-interface/button/d_shape.png)

_**\(** Setter only | Designer**\)**  
`Type: Text`_ 

The shape of the **Button**.

Options              | []()
-------------------- | ------------
`Default`            | The default shape of the button i.e a standard button.
`Rectangular`        | The button is in rectangular shape , similar to `Default` shape.
`Rounded`            | The corners of the button are rounded giving it a shape like rounded rectangle.
`Oval   `            | The **Button** is in the shape of an oval.


### Show Feedback

![](/assets/images/components/user-interface/button/d_show-feedback.png) ![](/assets/images/components/user-interface/button/p_show-feedback.png)

_**\(** Advanced | Getter + Setter **\)**  
`Type: Number`_ 

Determines whether the **Button** shows a visual feedback for a button that has an image as background.


### Touch Color

![](/assets/images/components/user-interface/button/d_touch-color.png) ![](/assets/images/components/user-interface/button/p_touch-color.png)

_**\(** Advanced | Setter only **\)**  
`Type: Color`_

The color of ripple effect when touching the button.


{!includes/text-property.md!}


{!includes/width-property.md!}


{!includes/visible-property.md!}



## Methods

### Button Click
_**\(** None **\)**_ 

Perform a Button click. The Click event is also fired when this method is executed.



## Events

### Click
_**\(** None **\)**_ 

Indicates that the user has clicked the button \(i.e pressed and released\)


### Got Focus
_**\(** None **\)**_

Indicates the has been cursor moved over the button so it is now possible to click it.


### Long Click
_**\(** None **\)**_

Indicates that the user has clicked and held down the button. _Click_ event is not 
fired when the Button is long clicked.


### Lost Focus
_**\(** None **\)**_

Indicates the cursor moved away from the button so it is now no longer possible to click it.