# To-Do List

A simple and interactive **To-Do List web application** built using HTML, CSS, and JavaScript. The application allows users to add tasks dynamically and delete tasks from the list.

**GitHub:** https://github.com/MSIVAPAPARAO13/To-Do-List

## Features

* Add new tasks
* Dynamically display tasks in an unordered list
* Delete individual tasks
* Clear the input field after adding a task
* DOM manipulation using JavaScript
* Event delegation for task deletion
* Simple and lightweight frontend implementation

## Tech Stack

* HTML5
* CSS3
* JavaScript
* DOM Manipulation
* Event Listeners

## Project Structure

```text
To-Do-List/
│
├── Todo list.html
├── Todo list.css
└── Todo list.js
```

## How It Works

### Add Task

Enter a task in the input field and click **Add Task**.

JavaScript dynamically:

1. Creates a new `<li>` element.
2. Inserts the entered task.
3. Creates a Delete button.
4. Attaches the Delete button to the task.
5. Adds the task to the `<ul>`.
6. Clears the input field.

### Delete Task

The application uses an event listener on the `<ul>` element.

When a Delete button is clicked:

```javascript
let listitem = event.target.parentElement;
listitem.remove();
```

The corresponding task is removed from the DOM.

## Example

Initial tasks:

```text
Eat       [delete]
Sleep     [delete]
```

After entering:

```text
Study JavaScript
```

the list becomes:

```text
Eat
Sleep
Study JavaScript
```

Each task has its own Delete button.

## Running the Project

Clone the repository:

```bash
git clone https://github.com/MSIVAPAPARAO13/To-Do-List.git
```

Open the project folder and launch:

```text
Todo list.html
```

in a web browser.

No backend or external dependencies are required.

## Key JavaScript Concepts Demonstrated

* `querySelector()`
* `addEventListener()`
* `createElement()`
* `appendChild()`
* `classList.add()`
* DOM element removal
* Event delegation
* User input handling

## Author

**Siva Paparao Medisetti**

GitHub: https://github.com/MSIVAPAPARAO13
