# JS CheatSheet
**Typeof <value>**  - type of data \

## Integer
**Math.ceil(value)** – highes closest integer \
**Math.floor(value)** – smalles closest integer \
**Math.round(value)** – round number \

**Number.isInteger(value)** – boolean if number is integer \

## String
**text.trim()** – remove whitespaces start and end \
**text.slice(number,number)** – remove character from slice (number – position of the character in string) \
**text.replace(searchValue,newValue)** – replace/delete text in string \
**text.split(value)** – split string into an array by the value separator. \

## Array
**Array.push(values)** – add items into the array (at the end) \
**Array.pop()** – deletes the last item in the array \
**Array.(un)shift()** - – (adds)deletes the first item in the array \
**Array.includes(value)** – boolean check whether the array includes the value (can have second argument, number to start the search from that position) \
**Array.filter(function)** – filter array by some function (word.filter(word=> word.length>6) ), returns an array of found objects \
**Array.find(function)** – same like filter but returns only the found object (not the array) \
**Array.map(function)** – create new array with the results of function \
**Array.some(function)** – Does the function apply at least to one object? (is at least one person older than 18). returns true/false \
**Array.every(function)** – Does the function apply to every object in the array? (is everyone older than 18). returns true/false \
**Array.findIndex(function)** – returns the index of the first item in array that matches the function \
**Array.slice(value1,value2)** – deletes and item from the array. Value1 is the postion where to start and value2 is how many object to delete (by saving this into a new array it will give just the deleted items, while the current array with stay without those items) \
**array.splice(indexToStart, numberOfIndices, 'stringToAdd');** \








