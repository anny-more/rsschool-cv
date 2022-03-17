# Anna Grankina
## Junior Software developer (JavaScript/Front-end)

----------------------------------------------------

### Contacts:
* *location:* Russia, Rostov-on-Don
* *phone-number:* +7-988-990-2868
* *email:* anxxxen@ya.ru
* *git-hub:* [anny-more](https://github.com/anny-more/)

----------------------------------------------------

### About me

A wonderful things happens around. A websites became not just informational resource but more bigger. They are translator to beautifully interactive world, i mean World wide web.And I got caught.

I`m learning to create this wonderful Windows to magic interactive World. And soon it will be the windows on yours screens.

I like tasks that makes me sweat. More interesting thing that I does was a algorithmic task with reverse polish entry, or decode Morse's alphabet. The biggest exciting was,then I make the little pictures works, like play/pause video, skip images and etc...

### Skills

* HTML 
* CSS
* JavaScript 
* Git, Git-hub
* VSCode

### Code example

_This is IP-converter_


    export const ipToInt = (string) => {
      const newString = string.split('.');
      return newString.reduce(((acc, newStr, index, newString) => {
        return acc + Number(newStr) * 256 ** Math.abs(index - 3);
      }), 0);
    };

    export const intToIp = (number) => {
      const array = chunk(number.toString(2).padStart(32, 0), 8);
      const results = array.map((arr) => parseInt(arr.join(''), 2));
      return results.join('.');
    };


### Education

| years       | place (platform)|
| :---------- | --------------------------------------: |
| 2003 - 2009   |   Saratov state university, faculty mechanics and mathematics 
| 2021        |   Courses on Hexlet.io, Front-end developer |
| now         |   Courses JavaScript/Front-end in RS School |

### Language

_English level - A2_
