# Radio-to-Rate-Stars

The first script beacon is the library  
The second one is the use case  

Exemple:  
**HTML**:  
&lt;div class="sc-formfield-input-wrapper" id="wrapper2"&gt;  
&nbsp;&nbsp;&nbsp;&nbsp;radio1  
&nbsp;&nbsp;&nbsp;&nbsp;radio2  
&nbsp;&nbsp;&nbsp;&nbsp;radio3  
&nbsp;&nbsp;&nbsp;&nbsp;etc.  
&lt;/div&gt;

**JS**:  
var radiosStars = new radioToStars({'target': 'wrapper2', 'gap': '10px', 'dim': '32px', 'starOn': 'star_on.png', 'starOff': 'star_off.png'});  
radiosStars.init();

target => id of the radios wrapper  
gap => make the stars spaced  
dim => size of the stars  
starOn => image of the selected stars  
starOff => image of the unselected stars
