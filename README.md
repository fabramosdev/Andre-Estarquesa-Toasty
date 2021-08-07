<div align="center" id="top"> 
  <img src="./.github/estarquesa-toasty.png" alt="QToasty - André Estarquesa Toasty" />

  &#xa0;

  <!-- <a href="https://qtoasty.netlify.app">Demo</a> -->
</div>

<h1 align="center">Andre Estarquesa QToasty</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/fabramosdev/Andre-Estarquesa-Toasty?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/fabramosdev/Andre-Estarquesa-Toasty?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/fabramosdev/Andre-Estarquesa-Toasty?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/fabramosdev/Andre-Estarquesa-Toasty?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/fabramosdev/Andre-Estarquesa-Toasty?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/fabramosdev/Andre-Estarquesa-Toasty?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/fabramosdev/Andre-Estarquesa-Toasty?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  QToasty 🚀 Under construction...  🚧
</h4> 

<hr> -->

## :dart: About ##

[PT-BR]
O Clássico toasty do Mortal Kombat numa versão André Estarquesa, a felina do povão!

[EN-US]
The classic toasty Mortal Kombat in a version of André Estarquesa, the feline of the populace!

OBS: Este é um fork do projeto original de [Raphael Quintão](https://github.com/raphaelquintao/QToasty)

```bash
# Clone this project
$ git clone https://github.com/fabramosdev/Andre-Estarquesa-Toasty

```

## Usage

#### Adding QToasty.js to you website

```html
<head>
    <script src="https://raw.githubusercontent.com/fabramosdev/Andre-Estarquesa-Toasty/master/qtoasty.js" type="text/javascript"></script>
    // or
    <script src="https://fabramosdev.github.io/Andre-Estarquesa-Toasty/qtoasty.js" type="text/javascript"></script>
</head>
```
#### For the key code version
```html
<script type="text/javascript">
    var toasty = new QToasty(params = {
        'domElement': document.body, // HTMLElement to show bind events.
        'sound': true, // Play sound
        'volume': 0.5, // Sound volume, 0 to 1
        'imageSize': 150, // Image Size. Default: 150
        'imageSrc': '', // User that if wanna change the default image, leave empty for default image.
        'keyCodes': [38, 38, 40, 40, 37, 39, 37, 39, 66, 65], // Key sequence to activate. Default: Konami Code.
        'slideInSpeed': 360, // Slide in speed.
        'slideOutSpeed': 360, // Slide out speed.
        'delayToSlideOut': 600, // Delay before slide out image.
        'easing': 'easeinout' // Easing function, linear, easein, easeout, easeinout, easeoutelastic. Default easeinout
    });
</script>
```
#### For the button version
```html
<script type="text/javascript">
    var toasty = new QToasty(params = {'keyCodes':[]});
    
    document.getElementById("toasty_btn").addEventListener("click", ev => {
        ev.preventDefault();
        toasty.trigger();
    });
</script>
```

#### For the page loaded version.
```html
<script>
    // --- Sound may not play due browser security policies ---
    var toasty = new QToasty(params = {'keyCodes':[]});
    
    setTimeout(()=>{
        toasty.trigger();
    }, 1500);
</script>
```

### Konami Code

| ↑ | ↑ | ↓ | ↓ | ← | → | ← | → | B | A |
|---|---|---|---|---|---|---|---|---|---|
|38|38|40|40|37|39|37|39|66|65|

### Key Codes

| Key | Code |
| --- |:----:|
backspace | 8
tab | 9
enter | 13
shift | 16
ctrl | 17
alt | 18
pause/break | 19
caps lock | 20
escape | 27
page up | 33
Space | 32
page down |34
end | 35
home | 36
arrow left | 37
arrow up | 38
arrow right | 39
arrow down | 40
print screen |44
insert | 45
delete | 46
0 | 48
1 | 49
2 | 50
3 | 51
4 | 52
5 | 53
6 | 54
7 | 55
8 | 56
9 | 57
a | 65
b | 66
c | 67
d | 68
e | 69
f | 70
g | 71
h | 72
i | 73
j | 74
k | 75
l | 76
m | 77
n | 78
o | 79
p | 80
q | 81
r | 82
s | 83
t | 84
u | 85
v | 86
w | 87
x | 88
y | 89
z | 90
left window key | 91
right window key | 92
select key | 93
numpad 0 | 96
numpad 1 | 97
numpad 2 | 98
numpad 3 | 99
numpad 4 | 100
numpad 5 | 101
numpad 6 | 102
numpad 7 | 103
numpad 8 | 104
numpad 9 | 105
multiply |106
add | 107
subtract | 109
decimal point | 110
divide | 111
f1 | 112
f2 | 113
f3 | 114
f4 | 115
f5 | 116
f6 | 117
f7 | 118
f8 | 119
f9 | 120
f10 | 121
f11 | 122
f12 | 123
num lock | 144
scroll lock | 145
semi-colon | 186
equal sign | 187
comma | 188
dash | 189
period | 190
forward slash | 191
open bracket | 219
back slash | 220
close braket | 221
single quote | 222

<br>


Made with :heart: by <a href="https://github.com/fabramosdev" target="_blank">Fabiano Ramos</a>

&#xa0;

<a href="#top">Back to top</a>
