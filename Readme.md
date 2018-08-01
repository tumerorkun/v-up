# V-UP


### install

local
```javascript
npm i @tumerorkun/v-up
```
or

global
```javascript
npm i -g @tumerorkun/v-up
```
### usage

in your packages.json you can ad a script

```json
"scripts": {
  "patch-up": "v-up patch",
  "minor-up": "v-up minor",
  "major-up": "v-up major",
}
```
then you can
```
npm run patch-up
or
npm run minor-up
or
npm run major-up
```

with global installation you can use it in the terminal directly (pwd should project folder)
```
$ v-up patch
```
