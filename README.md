# TypeScript Conversion of JavaScript Code

This repository contains a JavaScript code snippet that has been transformed into TypeScript. The original
JavaScript code was converted to TypeScript to take advantage of static typing and other TypeScript features.


## Code Transformation Steps

To convert the JavaScript code into TypeScript, the following steps were followed:

1. The file extension was changed from `.js` to `.ts` to indicate that it is now a TypeScript file.
2. Type annotations were added to variables and functions. TypeScript allows specifying types for variables, 
   parameters, and return values. Type annotations were added to the code wherever applicable.
3. The TypeScript compiler (`tsc`) was installed globally using npm. The npm command used for installation 
   is: `npm install -g typescript`.
4. The TypeScript code was then compiled into JavaScript using the TypeScript compiler (`tsc`). The             
   command used for compilation is: `tsc script.ts`. This generated a JavaScript file (`script.js`)
   based on the TypeScript code.
5. The generated JavaScript file (`script.js`) was referenced in the HTML file using the `<script>` tag.   


## Running the Transformed Code

To run the converted TypeScript code, please follow these steps:

1. Clone or download this repository to your local machine.
2. Make sure you have TypeScript and a web browser installed on your machine.
3. Open the terminal or command line and navigate to the directory where you have saved the TypeScript file.
4. Run the following command to compile the TypeScript code into JavaScript: tsc script.ts.
5. Open the HTML file (index.html) in a web browser.
6. You should now see the transformed TypeScript code in action.
