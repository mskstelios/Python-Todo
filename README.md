
</head>

<body>

  <h1>To-Do List Application</h1>

  <p>This is a simple To-Do List application built using PyQt5 in Python. It allows users to create, manage, and save To-Do lists with tasks. Lists can be created, tasks can be added, deleted, and the entire list can be saved to a text file. Additionally, users can open and edit existing To-Do lists.</p>

  <h2>Requirements</h2>
  <ul>
    <li>Python 3.x</li>
    <li>PyQt5</li>
  </ul>

  <h2>How to Use</h2>

  <h3>1. Create a New To-Do List</h3>
  <ul>
    <li>Click on the "Create New List" button.</li>
    <li>Enter a name for the new list in the provided text field.</li>
    <li>Click the "Create" button to open the new To-Do list window.</li>
  </ul>

  <h3>2. Add Tasks to the To-Do List</h3>
  <ul>
    <li>In the To-Do list window, enter a task in the text field provided.</li>
    <li>Click the "Create Task" button to add the task to the list.</li>
  </ul>

  <h3>3. Delete Tasks</h3>
  <ul>
    <li>Select a task by checking the checkbox next to it.</li>
    <li>Click the "Delete Task" button to remove the selected task from the list.</li>
  </ul>

  <h3>4. Save To-Do List</h3>
  <ul>
    <li>Click the "Save List" button to save the entire To-Do list to a text file.</li>
    <li>The file will be saved in the same directory as the application with the name provided for the list.</li>
  </ul>

  <h3>5. Open Existing To-Do List</h3>
  <ul>
    <li>Click on the "Open List" button.</li>
    <li>Choose a saved To-Do list from the available radio buttons.</li>
    <li>Click the "Open" button to view and edit the selected list.</li>
  </ul>

  <h3>6. Return to Main Menu</h3>
  <ul>
    <li>Click the "Return Main Menu" button to go back to the main menu.</li>
  </ul>

  <h2>Implementation Details</h2>

  <p>The application uses PyQt5 for the graphical user interface. The main functionalities are divided into the following components:</p>

  <ul>
    <li><strong>List Creation</strong>: Function <code>creation_list()</code> is responsible for creating a new To-Do list window. Users can add tasks, delete tasks, save the list, and return to the main menu.</li>
    <li><strong>Opening Existing Lists</strong>: Function <code>opening()</code> allows users to open an existing list using Notepad.</li>
    <li><strong>Main Menu</strong>: The main menu includes options to create a new list, open an existing list, and view saved lists.</li>
  </ul>

  <h2>How to Run</h2>

  <ol>
    <li>Install Python 3.x on your machine.</li>
    <li>Install PyQt5 by running the following command in your terminal or command prompt:
      <pre>pip install PyQt5</pre>
    </li>
    <li>Save the provided Python script to a file with a <code>.py</code> extension.</li>
    <li>Run the script using the following command:
      <pre>python todo_gui.py</pre>
    </li>
  </ol>

  <p>Feel free to customize, extend, or modify this application according to your needs. Happy organizing!</p>

</body>

</html>
