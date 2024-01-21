The Multilingual Wikipedia GUI is a graphical user interface application built using the Tkinter library in Python. The purpose of this project is to create an interactive tool that allows users to search and read Wikipedia articles in different languages easily.

Key Features:

Search Wikipedia:

Users can enter a search query in the provided entry field.
A dropdown combobox allows users to select the language in which they want to search for Wikipedia articles.
Language Support:

The application utilizes the googletrans library to provide a dictionary of language codes and names.
Users can choose from a list of available languages in the combobox.
Search and Display:

Upon clicking the "Search" button, the application retrieves the Wikipedia page for the specified query in the selected language.
The content of the Wikipedia page is displayed in a text area, allowing users to read the article.
Edit Mode:

Users can switch to an "Edit" mode, which enables them to modify the content in the text area.
Copy Content:

The "Copy" button allows users to copy the content of the text area to the clipboard using the pyperclip library.
Clear Functionality:

The "Clear" button resets the entry field and clears the content in the text area.
User Interface:

The application has an aesthetically pleasing user interface with labeled frames, entry fields, buttons, and a scrollable text area.
Colors are used to enhance visual appeal, and the layout is organized for user convenience.
Libraries Used:

Tkinter: For building the graphical user interface.
googletrans: For language translation and code retrieval.
wikipedia: For accessing Wikipedia content.
pyperclip: For copying text to the clipboard.
How to Use:

Enter a search query in the entry field.
Select the desired language from the dropdown combobox.
Click the "Search" button to fetch and display the Wikipedia article.
Optionally, switch to "Edit" mode, copy the content, or clear the interface.
Note:

Ensure that the required libraries (tkinter, googletrans, wikipedia, pyperclip) are installed before running the application.
This project serves as a practical example of creating a multilingual Wikipedia search tool with a user-friendly interface. Users can explore articles in various languages and perform basic text editing and copying operations.





