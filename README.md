# rn-roll-picker

A cross-platform (iOS&amp;Android), selector/picker component for React Native.

<br>Demo
------
<br>![](https://github.com/yjy5264/rn-roll-picker/raw/master/image/picker.gif)
<br>Install
------
```javascript
npm install rn-roll-picker --save
```
<br>Props
------
```javascript
data = {[{a: 'bbb'}]} // json type array
name = 'a' // json name with {a: 'bbb'}
onRowChange = {index => {}} // when row changed, return the index
```
<br>Function
------
```javascript
ref.setDataSource(data) // reset data with json type array
```
<br>Usage
------
```javascript
import Picker from 'rn-roll-picker'

<Picker 
    data = {[{a: 'bbb'}]}
    ref = '_Picker'
    name = 'a'
    onRowChange = {index => {}}
/>

this.refs._Picker.setDataSource(data); 
```
