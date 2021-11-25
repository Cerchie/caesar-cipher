# caesar-cipher

this function encodes a string you input by your selected Caesar shift 

To use: 

`git clone https://github.com/Cerchie/caesar-cipher.git && cd caesar-cipher && node index.js`

If you want to output an encoded string to the terminal you'll need to add a `console.log` that calls the function at the bottom, like so:

`console.log(caesarShift('hello', 6)`

then run `node index.js` 

Limitations:

You've got to use a `shiftDegree` between 26 and -26, and your `inputText` must be a string.

PS-- this is a resource that I used: https://stackoverflow.com/questions/5788741/remove-commas-from-the-string-using-javascript
Otherwise, I just used MDN for loop syntax -- I can never remember whether it's `,` or `;` off the top of my head. ;)
