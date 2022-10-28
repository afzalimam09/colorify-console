# Colorify-Afzal

A npm library to colorify your browser console logs build with typescript

# Installation

Run the command below to install the package inside your project

`npm i colorify-b-console`

# Import

`import {Log} from 'colorify-b-console'`

# Use

After importing the library in your file, you have three functions to colorify your logs. All these functions accepts a string

- `Log.success();` -> To give green color
- `Log.danger();` -> To give red color
- `Log.info();` -> To give yellow background color with black text color

For example:-

```
Log.success("Congratulations!"); // Print 'Congratulations!' in green color
Log.danger("Wrong"); // Print 'Wrong' in red color
Log.info("Info"); // Print 'Info' in black text color with yellow background color
```
