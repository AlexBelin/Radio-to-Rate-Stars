# Radio-to-Rate-Stars

The first script beacon is the library  
The second one is the use case  

Exemple:  
**HTML**:  
&lt;div class="sc-formfield-input-wrapper radios-to-ratestars"&gt;  
&nbsp;&nbsp;&nbsp;&nbsp;radio1  
&nbsp;&nbsp;&nbsp;&nbsp;radio2  
&nbsp;&nbsp;&nbsp;&nbsp;radio3  
&nbsp;&nbsp;&nbsp;&nbsp;etc.  
&lt;/div&gt;  

&lt;div class="sc-formfield-input-wrapper radios-to-ratestars"&gt;  
&nbsp;&nbsp;&nbsp;&nbsp;radio1  
&nbsp;&nbsp;&nbsp;&nbsp;radio2  
&nbsp;&nbsp;&nbsp;&nbsp;radio3  
&nbsp;&nbsp;&nbsp;&nbsp;radio4  
&nbsp;&nbsp;&nbsp;&nbsp;radio5  
&nbsp;&nbsp;&nbsp;&nbsp;etc.  
&lt;/div&gt;

**JS**:  
var radiosStars = new radioToStars({'target': '.radios-to-ratestars', 'gap': '4px', 'dim': '32px', 'starOn': 'star_on.png', 'starOff': 'star_off.png'});  
radiosStars.init();

**configuration**  
target => class the radios wrappers to target  
gap => make the stars spaced  
dim => stars size  
starOn => image of the selected stars  
starOff => image of the unselected stars

**Pay attention**  
Each radio group wrapper must have an id  
Each id must be targeted by a separate js instance
