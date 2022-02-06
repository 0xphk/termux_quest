## termux 'extra-keys' based keyboard for oculus quest (qwertz)
#### see documentation: https://wiki.termux.com/wiki/Touch_Keyboard

##### trying to match most physical keys, some optional keys replaced
___
**installation**

* make directory ```.termux``` in termux home
* copy files to ```/data/data/com.termux/files/home/.termux/```
* ```colors.properties``` is optional, adjust to your preference
  
  (uses manjaro green '#1aab9b' as terminal foreground color)
___
**long press popup keys**
___
* long press ```ESC``` for ```CTRL + d``` (end session)
* long press ```TAB``` for ```ALT```
* long press ```CTRL``` for ```SHIFT```
* long press ```SPACE``` for ```DRAWER``` (open termux sessions)
* long press ```UP``` for ```PGUP```
* long press ```DOWN``` for ```PGDN```
* long press ```LEFT``` for ```HOME```
* long press ```RIGHT``` for ```END```
* long press ```M◂``` for ```#CMD``` (see below)
___
**helpful bash shortcuts using macros**
___
| modifier | action |
|--:|:--|
|```UPPER``` | transform word in front of cursor to UPPER case (ALT + u) |
|```LOWER``` | transform word in front of cursor to lower case (ALT + l) |
| ```#CMD``` | comment current line(command) and start new line (ALT + #) |
|  ```ARG``` | yank last argument (CTRL + SHIFT + y) |
|   ```C◂``` | backward move one word |
|   ```C▸``` | forward move one word |
|   ```M◂``` | backward delete word |


