# ToDo-List-HTML-CSS-Javascript-
This project is a basic To-Do List web application that allows users to add tasks, mark them as completed, and delete them. 
The application is built using HTML for structure, CSS for styling, and JavaScript for functionality.

## HTML (index.html)
Structure :
<!DOCTYPE html>: Declares the document type and version of HTML.
<html lang="en">: Specifies the language of the document.
<head>: Contains meta information and links to external resources.
<meta charset="UTF-8">: Sets the character encoding.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Configures the viewport for responsive design.
<title>List ToDo</title>: Sets the title of the web page.
<style>: Contains the CSS styles for the page.
<body>: Contains the content of the web page.
<div class="container">: Main container for the application.
<div class="form">: Input form for adding tasks.
<input type="text" class="input" />: Text input for task entry.
<input type="submit" class="add" value="Add Task" />: Submit button for adding tasks.
<div class="tasks"></div>: Container for displaying tasks.
<script src="main.js"></script>: Links to the external JavaScript file.
**CSS (styles.css) **
Styles :
Styles are defined for the overall layout, form, input fields, buttons, and task display.
The application uses flexbox for layout and styling to create a clean and responsive design.
Different styles are applied for task elements, highlighting completed tasks and providing visual cues for user interactions.
## JavaScript (main.js)
Functionality
Variables are declared for the input field, submit button, and tasks container.
An empty array (arrayOfTasks) is used to store task data.
On page load, the application checks for tasks in local storage and retrieves them if available.
Event listeners are added to handle adding tasks, marking them as completed, and deleting tasks.
Functions are defined for adding tasks to the array, updating the page, and managing local storage.
The application dynamically updates the page content based on user interactions.
Local Storage
Task data is stored and retrieved from local storage to maintain tasks even after a page reload.
Feel free to customize this README to provide more details or context specific to your project!
