# BookLibrary

# All of your book objects are going to be stored in an array, so add a function to the script (not the constructor) that can take user’s input and store the new book objects into an array.

# Write a function that loops through the array and displays each book on the page.

# It might help for now to manually add a few books to your array so you can see the display.

# Add a “NEW BOOK” button that brings up a form allowing users to input the details for the new book: author, title, number of pages, whether it’s been read and anything else you might want

# explore dialogs and modals for form https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog

# the submit input tries to send the data to a server by default. This is where event.preventDefault(); will come in handy  https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault

# Add a button on each book’s display to remove the book from the library.
# You will need to associate your DOM elements with the actual book objects in some way. One easy solution is giving them a data-attribute that corresponds to the index of the library array.

# Add a button on each book’s display to change its read status.
# To facilitate this you will want to create the function that toggles a book’s read status on your Book prototype instance.