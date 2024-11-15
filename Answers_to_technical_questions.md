# Answers to Technical Questions

## 1. How long did you spend on the coding test?

I spent approximately **5-6 hours** on the coding test. This includes setting up the project, implementing core features (task adding, searching, filtering), and styling the user interface to enhance the overall user experience.

## 2. What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.

One of the most useful features introduced in recent versions of **JavaScript (ES2021)** is the **logical assignment operators** (`&&=`, `||=`, `??=`). These operators provide a concise way to perform logical operations combined with assignment, reducing boilerplate code.

### Example Usage

```javascript
// Logical OR Assignment (||=)
let settings = { theme: 'light' };
settings.theme ||= 'dark';
console.log(settings.theme); // Output: 'light'

// Logical AND Assignment (&&=)
let isAuthenticated = true;
isAuthenticated &&= checkUserAuthentication();
console.log(isAuthenticated);

// Nullish Coalescing Assignment (??=)
let username = null;
username ??= 'Guest';
console.log(username); // Output: 'Guest'
 
