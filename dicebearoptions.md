# these look good

## icons

- scale: 110%
- radius:50
- bgtype: gradient linear
- bgcolors:80deea/81d4fa/ffab91/ffcc80
- bgrotation:0/360

### example with Patches
#### the thing
<img
  style="height:25%;width:25%;"
  src="https://api.dicebear.com/5.x/icons/svg?seed=Patches&scale=110&radius=50&backgroundColor=ffcc80,ffab91,80deea,81d4fa&backgroundType=gradientLinear"
  alt="avatar" >
#### http
https://api.dicebear.com/5.x/icons/svg?seed=Patches&scale=110&radius=50&backgroundColor=ffcc80,ffab91,80deea,81d4fa&backgroundType=gradientLinear

#### html
img
  src="https://api.dicebear.com/5.x/icons/svg?seed=Patches&scale=110&radius=50&backgroundColor=ffcc80,ffab91,80deea,81d4fa&backgroundType=gradientLinear"
  alt="avatar" / REMBER TO READD THE < AND THE >
  
#### js
- install with npm first --> npm install @dicebear/core @dicebear/collection --save
- then use -->
import { createAvatar } from '@dicebear/core';
import { icons } from '@dicebear/collection';

const avatar = createAvatar(icons, {
  "seed": "Patches",
  "scale": 110,
  "radius": 50,
  "backgroundColor": [
    "ffcc80",
    "ffab91",
    "80deea",
    "81d4fa"
  ],
  "backgroundType": [
    "gradientLinear"
  ]
});

const svg = avatar.toString();

#### cli
- install using npm first --> npm install --global dicebear
- then use -->
dicebear icons . \
  --seed 'Patches' \
  --scale 110 \
  --radius 50 \
  --backgroundColor 'ffcc80' 'ffab91' '80deea' '81d4fa' \
  --backgroundType 'gradientLinear'
  
  ## identicons
  
- scale: 70%
- radius:50
- bgtype: gradient linear
- bgcolors:ffbfdf/b6e3f4/c0aede/d1d4f9/ffd5dc
- bgrotation:0/360

### example with Patches
#### the thing
<img
style="height:25%;width:25%;"
  src="https://api.dicebear.com/5.x/identicon/svg?seed=Patches&scale=70&radius=50&backgroundType=gradientLinear&backgroundColor=ffdfbf,ffd5dc,d1d4f9,c0aede,b6e3f4"
  alt="avatar" />
#### http
https://api.dicebear.com/5.x/identicon/svg?seed=Patches&scale=70&radius=50&backgroundType=gradientLinear&backgroundColor=ffdfbf,ffd5dc,d1d4f9,c0aede,b6e3f4
#### html
img
  src="https://api.dicebear.com/5.x/identicon/svg?seed=Patches&scale=70&radius=50&backgroundType=gradientLinear&backgroundColor=ffdfbf,ffd5dc,d1d4f9,c0aede,b6e3f4"
  alt="avatar" / REMBER TO READD THE < AND THE >
  
#### js
- install with npm first --> npm install @dicebear/core @dicebear/collection --save
- then use -->
import { createAvatar } from '@dicebear/core';
import { identicon } from '@dicebear/collection';

const avatar = createAvatar(identicon, {
  "seed": "Patches",
  "scale": 70,
  "radius": 50,
  "backgroundType": [
    "gradientLinear"
  ],
  "backgroundColor": [
    "ffdfbf",
    "ffd5dc",
    "d1d4f9",
    "c0aede",
    "b6e3f4"
  ]
});

const svg = avatar.toString();

#### cli
- install using npm first --> npm install --global dicebear
- then use -->
dicebear identicon . \
  --seed 'Patches' \
  --scale 70 \
  --radius 50 \
  --backgroundType 'gradientLinear' \
  --backgroundColor 'ffdfbf' 'ffd5dc' 'd1d4f9' 'c0aede' 'b6e3f4'
  --fontfam sans serif
  

 ## initials
  
- scale:140%
- radius:50
- bgtype: gradient linear
- bgcolors:f4511e/fb8c00/ffb300/ffdfbf/00acc1/1e88e5/b6e3f4
- bgrotation:0/360
- fontfamily : sans serif

### example with Patches
#### the thing
<img style="height:25%;width:25%;" src="https://api.dicebear.com/5.x/initials/svg?seed=Patches&scale=140&radius=50&backgroundColor=ffb300,ffdfbf,f4511e,fb8c00,b6e3f4,1e88e5,00acc1&backgroundType=gradientLinear&fontFamily=sans-serif" alt="avatar" />

#### http

https://api.dicebear.com/5.x/initials/svg?seed=Patches&scale=140&radius=50&backgroundColor=ffb300,ffdfbf,f4511e,fb8c00,b6e3f4,1e88e5,00acc1&backgroundType=gradientLinear&fontFamily=sans-serif

#### html

img
  src="https://api.dicebear.com/5.x/initials/svg?seed=Patches&scale=140&radius=50&backgroundColor=ffb300,ffdfbf,f4511e,fb8c00,b6e3f4,1e88e5,00acc1&backgroundType=gradientLinear&fontFamily=sans-serif"
  alt="avatar" /
 REMBER TO READD THE < AND THE >
  
#### js
- install with npm first --> npm install @dicebear/core @dicebear/collection --save
- then use -->
import { createAvatar } from '@dicebear/core';
import { initials } from '@dicebear/collection';

const avatar = createAvatar(initials, {
  "seed": "Patches",
  "scale": 140,
  "radius": 50,
  "backgroundColor": [
    "ffb300",
    "ffdfbf",
    "f4511e",
    "fb8c00",
    "b6e3f4",
    "1e88e5",
    "00acc1"
  ],
  "backgroundType": [
    "gradientLinear"
  ],
  "fontFamily": [
    "sans-serif"
  ],
});

const svg = avatar.toString();

#### cli
- install using npm first --> npm install --global dicebear
- then use -->
dicebear initials . \
  --seed 'Patches' \
  --scale 140 \
  --radius 50 \
  --backgroundColor 'ffb300' 'ffdfbf' 'f4511e' 'fb8c00' 'b6e3f4' '1e88e5' '00acc1' \
  --backgroundType 'gradientLinear' \
  --fontFamily 'sans-serif' 
  
