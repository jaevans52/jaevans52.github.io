# CodeLou_FrontEnd

## Description
```
This is a website that I can link  to give more personalized information on my Cell Phone Repair Business.  One completely controlled by me that I can show my customers my personality.

```



## Custom CSS Classes
```
.thank-you-class {
  text-align:center;
  padding: 10px 100px;
	background-color: #047CFC;
  position: relative;
  text:white
}

creates a contrasting box around the revealed Thank You! message


iframe, object, embed {
  max-width: 100%;
}

Stretches google map to fill full width of any device

.row { 
  display: flex; 
  justify-content: space-around; 
  flex: 1; 
}

Makes all rows flex and evenly spaced while also being centered.

.footer {

  text-align:center;
  padding: 0px 0;
    width:auto;
	margin: 0 auto;
	background-color: #047CFC;
 }

add padding to top and bottom, 
align all text to center of page,
stretch to fit all width devices,
change background color to match theme,
of .footer
```



## Custom JavaScript Functions
```
The javascript functions I created are:

1. function name ex( animate() )
.. what function does ex( animate() is used to move the elements in the info div across the screen)

```
function thankyou() {
    document.getElementById("TY").style.display = 'block';
    }
    Function thankyou() executes and blocks the style display:none to reveal a thank you div that was hidden when you click the link the schedule a repair.
