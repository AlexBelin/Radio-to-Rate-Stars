# Radio-to-Rate-Stars

The first script beacon is the library  
The second one is the use case  

Exemple:  
**HTML**:  
&lt;div class="sc-formfield-input-wrapper" id="wrapper1"&gt;  
&nbsp;&nbsp;&nbsp;&nbsp;radio1  
&nbsp;&nbsp;&nbsp;&nbsp;radio2  
&nbsp;&nbsp;&nbsp;&nbsp;radio3  
&nbsp;&nbsp;&nbsp;&nbsp;etc.  
&lt;/div&gt;  

&lt;div class="sc-formfield-input-wrapper" id="wrapper2"&gt;  
&nbsp;&nbsp;&nbsp;&nbsp;radio1  
&nbsp;&nbsp;&nbsp;&nbsp;radio2  
&nbsp;&nbsp;&nbsp;&nbsp;radio3  
&nbsp;&nbsp;&nbsp;&nbsp;radio4  
&nbsp;&nbsp;&nbsp;&nbsp;radio5  
&nbsp;&nbsp;&nbsp;&nbsp;etc.  
&lt;/div&gt;

**JS**:  
var radiosStars1 = new radioToStars({'target': 'wrapper1', 'gap': '10px', 'dim': '32px', 'starOn': 'star_on.png', 'starOff': 'star_off.png'});  
radiosStars1.init();
var radiosStars2 = new radioToStars({'target': 'wrapper2', 'gap': '10px', 'dim': '32px', 'starOn': 'star_on.png', 'starOff': 'star_off.png'});  
radiosStars2.init();

target => id of the radios wrapper  
gap => make the stars spaced  
dim => size of the stars  
starOn => image of the selected stars  
starOff => image of the unselected stars

**Pay attention**  
Each radio group wrapper must have an id  
Each id must be targeted by a separate instance
