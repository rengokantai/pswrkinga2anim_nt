# pswrkinga2anim_nt
##2. Understanding Animation Basics
###2 Angular Animation Structure
```
import { Component,trigger,state,style,transition,animate,keyframes} from '@angular/core';
```

####01:41 syntax
```
<div [@triggerName]></div>
```


##3. Digging Deeper into Angular Animation
###1 Animation Timing
####01:00
delay animation
```
'0.5s 1000ms ease-in`  //delay 1s
```

##2 Multi-step Animations
```
transition('void=>*',[animate(1000,keyframes([
  style({opacity:0,offset:0}),
   style({opacity:1,offset:0.3}),
    style({opacity:0.3,offset:1})
]))
])
```
