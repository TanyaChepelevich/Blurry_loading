### Blurry Loading

Implementing Bblurry loading effect by using JavaScript [Timing Events](https://www.w3schools.com/js/js_timing.asp)

and a StackOverflow post [Javascript / jQuery - map a range of numbers to another range of numbers](https://stackoverflow.com/questions/10756313/javascript-jquery-map-a-range-of-numbers-to-another-range-of-numbers)

```
function scale (number, inMin, inMax, outMin, outMax) {
    return (number - inMin) * (outMax - outMin) / (inMax - inMin) + outMin;
}
```
