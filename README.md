# First-Project
# Kelvins __> Farenheit

//Variables that show what each one are and they are each somehow connected

//weather today in kelvin
const kelvin = 300
//celsius 
let celsius = kelvin - 273

var fahrenheit = celsius * 1.8 + 32
//rounds the tempature downwards
var fahrenheit = Math.floor(fahrenheit)

console.log('The Tempature is ' + fahrenheit + ' degrees Fahrenheit')
