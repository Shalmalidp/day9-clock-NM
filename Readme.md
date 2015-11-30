### NORMAL MODE CLOCK 

created a simple digital Clock

```
window.setInterval(function(){
var time = new Date();
var hours=time.getHours();
var minutes = time.getMinutes();
var seconds = time.getSeconds();
//var textNode;
var hours     =(hours <10) ? "0" + hours : hours;
var digit_min = (minutes <10) ? "0"+ minutes : minutes;
var digit_sec = (seconds < 10) ? "0" + seconds : seconds;
var currenttime = (hours + ":" +digit_min +":" + digit_sec);
//var textNode= document.createTextNode(currenttime);
$('.clock-body').text(currenttime);
},1000);
```

>A link to my Project : http://shalmalidp.github.io/day9-clock-NM/
