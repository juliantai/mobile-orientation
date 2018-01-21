# Mobile-Orientation
Detect Mobile Portrait/Landscape on resize.
## Install
```bash
npm install --save mobile-orientation
```
## Usage
```js
import { MobileOrientation } from 'mobile-orientation'

const orientation = new MobileOrientation()

console.log(orientation)
// { state: 'portrait' }
```