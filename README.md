# RGB-Button-
in this code talking  about  how create simple web interface with color full button 
ඉතාමත් සරල විදිහට හදපු code එකක් තමයි මෙ තියෙන්නෙ මම මෙතනින් කියලදෙන්න උත්සහ කරේ වර්නවත් බටන් කිහිපයක් යොදාගෙන nodemcu එකෙන් LED කිහිපයක් වැඩ කරන විදිහ ගැන 

පහත තියෙන කේතයන් ටික තමයි මම මෙතනට එකතු කරේ 
මේ කේත දිහා අවදානයෙන් බැලුවොත් ඔයාට තෙරුම් ගන්න පුලුවන් වේවී කොහොමද මේව වැඩ කරන්නෙ කියල.
මේවා ගැන එකින් එක කියල දෙන්න තරම් කාලයක් මම කරන රැකියාව අනුව නෑ ඒ පිලිබදව මම බෙහෙවින් කනගටු වෙනවා 


<!DOCTYPE html><html lang=\"en\"><head><meta name=\"viewport\" content=\"width=device-width, initial-scale=1, user-scalable=no\"/><title>{v}</title>


<style>
  .c{text-align: center;} 
  div,input{padding:5px;font-size:1em;} 
  input{width:90%;} 
  body{text-align: center;font-family:verdana;} 
  button{border:0;border-radius:0.6rem;background-color:#1fb3ec;color:#fdd;line-height:2.4rem;font-size:1.2rem;width:100%;} 
  .q{float: right;width: 64px;text-align: right;} 
  
  .button2 {background-color: #008CBA;} 
.button3 {background-color: #f44336;} 
.button4 {background-color: #e7e7e7; color: black;} 
.button5 {background-color: #555555;} 
  .button6 {background-color: #4CAF50;} 
  
</style>




</head><body><div style='text-align:left;display:inline-block;min-width:260px;'>

<form action=\"/cmd1\" method=\"get\"><button class=\"button3\">Red</button></form><br/> 
<form action=\"/cmd2\" method=\"get\"><button class=\"button6\">Green</button></form><br/> 
<form action=\"/cmd3\" method=\"get\"><button class=\"button2\">Blue</button></form><br/> 
<form action=\"/cmd4\" method=\"get\"><button class=\"button4\">Off</button></form><br/> 


