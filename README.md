# lead-tracker
**This is a Chrome extension**

You can use this extension to enhance your performance for sales
This project covers some of the interesting topics of web development, which are listed below:
- const
- addEventListener()
- innerHTML
- input.value
- function parameters
- template strings
- localStorage
- The JSON Object
- Object in array ( specifically, using this, I grab the current tab's URL)

  **N.B.**_ In this Chrome extension project, files in the extension folder are all packaged together.
  
  project/
  ├─ index.html
  ├─ index.js
  ├─ index.css
  ├─ manifest.json
  
- When the extension runs, Chrome can directly access local files in the extension folder using relative paths, because the browser treats them as part of the extension bundle.

- This is different from a normal website, where the browser cannot access a local .json file due to security (CORS).
