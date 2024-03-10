## JavaScript Pseudocode:

### Add Item:

```

1. Start
2. Get references to the HTML input elements
3. Add an event listener to the "Add" button
4. When the "Add" button is clicked, prevent the default form submission
5. Create a new HTML div element to represent the to-buy item
6. Create HTML elements for item details (li, buttons)
7. Append the elements to the div
8. Append the div to the to-buy list
9. Clear input fields
10. End

```

### Mark as Completed, Edit, and Delete:

```

1. Start
2. Get references to the HTML elements representing the to-buy list
3. Add an event listener to the to-buy list
4. When a button within the list is clicked, identify the clicked button
5. If the clicked button is the delete button, remove the corresponding to-buy item
6. If the clicked button is the completed button, toggle the completed class on the to-buy item
7. If the clicked button is the edit button, remove the to-buy item(the line of the list), extract item details in add form, user could modify the data, and save as a new line record
8. End

```
