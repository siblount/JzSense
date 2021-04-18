# JzSense

JzSense is a JS file to assist developers with their DzScripts by utilizing powerful source code editors’ (such as Visual Studio Code) autocompletion, documentation, and suggestion functionalities.
JzSense contents is ported directly from the [DAZ Documentation website] and inherits the [Attribution 3.0 Unported (CC BY 3.0) License]
# Me
I DO NOT WORK FOR DAZ PRODUCTIONS AND THIS SCRIPT WAS NOT SUPPORTED BY OR ENDORSED BY ANYONE AT DAZ PRODUCTIONS INC.

If I made your life wonderful, and if you are feeling generious enough to donate to help me out a bit (or a lot)... 😏👉: 🌟 https://www.buymeacoffee.com/therealsoll 🌟
## Latest Update: 4/10/2021 ##
- Added missing documentation for properties.
- Static and non-static methods now have improved documentation.
- Renamed file to JzSense
- Fixed methods reporting wrong return type.
- Fixed constructors w/ default values.
# ⚠ Heads up ⚠ 
##### The current version of JzSense is still a Work-In-Progress project. 
- The current version does not include `String`, `Number`, `Boolean`, `Object`, `Date`, `Function`, and `JSON`, and others later explained.
- JzSense only includes information directly from the [Daz Documentation website]. **There are more methods, properties, enums, signals available not included in here.**
- JzSense comes with billions of errors. This is perfectly fine. If it bothers you, you may need to disable JS vailidation errors.

# How to use 
###### ⚠  The following instructions is for Visual Studio Code  ⚠
1.  Download the `JzSense.js` script and import it into your workspace.
2.  If you haven't made a `.dsa` DzScript (ASCII) script yet, go ahead and do so.
3.  After creating a `.dsa ` file, go to the bottom-right of the screen where you see the current language. At default, you will see `Plain Text` . Click on it and a Language Dialog will pop up.
4.  Select "Configure File Association for `.dsa" and then select JavaScript as your mode.

If you open a folder/workspace, make sure that the file is in your working directory/workspace. 

If you have created a new file (or opened a file) rather than a folder or workspace, you need to import the script using syntax like: `import * as _ from "./JzSense.js"`
##### Optional
###### Disable JavaScript validation errors.
5.  Go to File -> Preferences -> Settings. In the User tab (or Workspace) select TypeScript (TypeScript is the interpreter for JavaScript & TypeScript for VS Code). Search for `JavaScript > Validate: Enable` and disable JavaScript validation.


## Missing Classes
All missing classes are EMCAScript classes which can not be added to this (or atleast I think so) 🤷‍♂️
- `Array`
- `Boolean`
- `Date`
- `Error`
- `EvalError`
- `Function`
- `JSON`
- `Math`
- `NativeError`
- `Number`
- `URIError`
- All classes not documented such as DzShape (`shape_dz`).

# JzSense - How to use, setup, and tips video
Click on image to be redirected to youtube video.

[![JzSense - Overview Vid](https://img.youtube.com/vi/8ylc8F0a_jo/0.jpg)](https://www.youtube.com/watch?v=8ylc8F0a_jo)


There may be other things missing. If you found something thats missing and it's not mentioned in this post, please post a new issue describing what is missing and where it can be found.
## Planned Updates
- Fix some void functions w/ wrong return type (should be void; instead got neighbor return type) ✅
   - Update functions with (currently) void return type when it should return their class type. ❔
- Fix overloaded methods not showing. ✅
- Update JSDOC for classes. 
- Arrays will no longer return "any[]" (this has to be done manually afaik for 333 instances ._.)


   [Daz Documentation website]: <http://docs.daz3d.com/doku.php/public/software/dazstudio/4/referenceguide/scripting/start>
   [Attribution 3.0 Unported (CC BY 3.0) License]: <https://creativecommons.org/licenses/by/3.0/>
