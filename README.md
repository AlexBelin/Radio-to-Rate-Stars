# Radio-to-Rate-Stars

The first script beacon is the library  
The second one is the use case  

Exemple:  
HTML:  
&lt;div class="sc-formfield-input-wrapper" id="wrapper2"&gt;  
  radio1  
  radio2  
  radio3  
  etc.  
&lt;/div&gt;

JS:  
var radiosStars = new radioToStars({'target': 'wrapper2', 'gap': '10px', 'dim': '32px', 'starOn': 'star_on.png', 'starOff': 'star_off.png'});

target => id of the radios wrapper  
gap => make the stars spaced  
dim => size of the stars  
starOn => image of the selected stars  
starOff => image of the unselected stars
