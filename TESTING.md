# Valladolid Snooker Club - Testing

![screenshot of site on amiresponsive](documentation/amiresponsive-snooker-img.png)

### Live website

You can visit the website [here](https://jonathandussot.github.io/valladolid-snooker-club/)

## W3C Validator

I used the W3C Validator to validate the HTML and CSS code of the following pages below:

[index.html](index.html)
![screenshot of index.html being validated](documentation/index-w3c.png)
[booking.html](bookings.html)
![screenshot of bookings.html being validated](documentation/bookings-w3c.png)
[kidsclub.html](kidsclub.html)
![screenshot of kidsclub.html being validated](documentation/kidsclub-w3c.png)
[style.css](assets/css/style.css)
![screenshot of style.css being validated](documentation/styles-w3c.png)

## Wave

## Lighthouse

## Manual Testing

### Testing User Stories

### Full Testing

## Bugs

- Media video on kidsclub.html wouldn't let me make it narrower.  Upon inspecting the code using Google DevTools, I discovered it was due to a line on css:269 which had it set to 100%. This was corrected and fixed in order to modify size and change structure for larger screens.

- The kid-snooker image on kidsclub.html originally wouldn't allow me to increase the width for screens 768px and larger.  I found it was because of a rule in which I had set a max-width of 450px. This was modified and fixed.