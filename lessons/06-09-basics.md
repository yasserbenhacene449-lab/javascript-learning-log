# JavaScript Basics (Lessons 6-9): What I Learned

**Date:** 2026-11-08
**Source:** Elzero Web School, "Learn JavaScript In Arabic 2021" (#006 to #009)
**Tools:** VS Code, Google Chrome DevTools

## Lesson 6: Comments and Bad Practices

```javascript
// Single line comment

/*
  Multi-line
  comment
*/
```

- `//` comments one line, `/* ... */` comments multiple lines.
- Comments explain the code and can temporarily disable code.
- `window.onload = function () {...}` waits for the page to load before running code.

## Lesson 7: Output to Screen

Three ways to output:

```javascript
window.alert("Hello From JS File");
document.write("<h1>Hello <span>Page</span></h1>");
console.log("Hello From Js File");
```

| Method | Where it shows |
|--------|----------------|
| `window.alert()` | Popup dialog in the browser |
| `document.write()` | Writes directly into the page (HTML tags work) |
| `console.log()` | Browser developer console |

- `document.createElement("tag")` creates an HTML element in memory (it is not displayed until added to the page).

## Lesson 8: Console Methods and Styling

```javascript
console.log("Log");
console.error("Error");
console.table(["Osama", "Ahmed", "Sayed"]);
console.log("Hello From %cJS %cFile", "color: red; font-size: 40px", "color: blue; font-size: 40px");
```

- `log` shows a normal message, `error` shows a red error, `table` shows an array as a table.
- The `%c` directive styles console text with CSS passed as extra arguments.
- Web APIs (like `console` and `document`) are provided by the browser, not by JavaScript itself.

## Lesson 9: What Is ECMAScript?

- ECMAScript (ES) is the official standard specification that JavaScript follows.
- ES6 (ES2015) introduced major features: `let`, `const`, arrow functions, classes, template literals, and more.
- Browsers implement the standard, so newer features may differ in support.

## My practice

```javascript
//window.alert("HELLO FROM JS COURSE");
document.write("good morning");
document.createElement("good");
console.log("hello from js ");
console.table(["yasser", "good", "job"]);
```

## Key takeaways

- Use comments to document code and disable lines while testing.
- `console.log()` is the best tool for debugging.
- `document.write()` and `alert()` are useful for learning but rarely used in real projects.
- ECMAScript is the standard, JavaScript is its implementation.
- <img width="1920" height="1080" alt="Screenshot 2026-11-08 162154" src="https://github.com/user-attachments/assets/b8486ada-b9a5-468a-b961-1ea6c49a6781" />
