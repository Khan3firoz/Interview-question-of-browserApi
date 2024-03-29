﻿# Interview-question-of-browserApi

1. **what is localStorage and sessionStorage? what is the diffrence in between and its methood:**

In both localStorage and sessionStorage, you can store data as key-value pairs. The main difference between them is their lifetime and scope:

**localStorage:**
Lifetime: Data persists even after the browser is closed and is not automatically cleared.
Scope: Data is available across all tabs and windows within the same origin (domain).
Use Cases: Storing user preferences, caching data for offline use, etc.

**sessionStorage:**
Lifetime: Data persists only for the duration of the page session. It is cleared when the page session ends, typically when the browser is closed.
Scope: Data is specific to the current tab or window and is not shared with other tabs or windows.
Use Cases: Storing temporary data, such as a shopping cart for an e-commerce website, that should not persist across page reloads or browser sessions.

**Note:** In both localStorage and sessionStorage, you can store data as strings. This means you can store simple data types like strings, numbers, and booleans directly. However, if you want to store more complex data types like arrays or objects, you'll need to convert them to strings using JSON.stringify() before storing and then parse them back to their original format using JSON.parse() when retrieving.
