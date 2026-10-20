# Student Marks Queue Management System

A student marks manager built with HTML, CSS, and JavaScript to demonstrate a **Queue** data structure.

## How the queue is implemented
The queue is stored in the JavaScript array `studentQueue`:
- **Enqueue:** `studentQueue.push(student)` adds a student at the rear.
- **Dequeue:** `studentQueue.shift()` removes the student at the front.
- **FIFO:** First In, First Out—the earliest student added is the first removed.
- Search checks the queue without changing its order. Statistics calculate class average, highest mark, and pass rate.

## Features
Add students; validate marks from 0 to 100; assign grades; calculate statistics; search by ID/name; dequeue the first student; export CSV; save records in the current browser with localStorage; and load sample records.

## Run locally
Keep `index.html`, `styles.css`, and `script.js` in the same folder, then open `index.html` in a browser.

## Deploy using GitHub Pages
1. Upload these files and this README to the repository root.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/(root)`, then click **Save**.
4. Wait for the published website URL to appear.

## Limitation
This is a front-end educational demo. `localStorage` only saves data in the same browser and device; it is not a shared database.
