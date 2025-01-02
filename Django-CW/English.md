# PYTHON BOOTCAMP

## 
Imagine you are tasked with creating a model for a project using the Django framework. The project should include a data model, templates, and views to display book information.

### 1. Setting up the Django Project:
- Create a Django project and add as many apps as needed to the project.

### 2. Creating the Data Model:
- Create a data model to store book information that includes the following fields:
  - `title`: A text field with a maximum length of 200 characters (book title).
  - `author`: A text field with a maximum length of 200 characters (author).
  - `published_date`: A date field for the publication date.
  - `isbn`: A text field with a maximum length of 13 characters (ISBN).

### 3. Creating Views:
- Create three views:
  1. A view to display a list of books (`book_list`) that fetches all the books in the database and sends them to the corresponding template.
  2. A view to display the details of each book (`book_detail`) based on the specific book `id`, fetches its details, and sends them to the template.
  3. **(Optional)** A view to create or edit a book (`book_create_update`) that allows saving a new book or updating existing information. If an `id` exists, it updates the book; otherwise, it creates a new one. 

### 4. Creating Templates:
- Create three templates:
  1. `book_list.html`: Displays a list of all books with links to their details.
  2. `book_detail.html`: Displays the details of a book, including title, author, publication date, and ISBN.
  3. **(Optional)**  `book_form.html`: Includes a form for entering or editing book information.

### 5. Customizing the Django Admin Panel:
- Add all project models to the admin panel.

#### For the Book model:
1. If the ISBN field is missing, display `-N/A-`.
2. Create a new column named "Book - Author" that combines the book title and author into one field.
3. Search Based on ISBN.

---

### 6. Adding Logical Delete:
- Add a Boolean field to allow soft deletion of books.

### 7. Adding an Image Field for Books:
- Add a field to store book images in the data model.

---

## Extra Task: Setting up Tailwind CSS

### 1. Setting up Tailwind CSS in a Django Project:
- Install Node.js (if not already installed).
- Install Tailwind CSS using NPM in the project.
- Create configuration files (`tailwind.config.js` and `postcss.config.js`).
- Update the Django project’s static file settings to use Tailwind.

### 2. Using Tailwind Classes in Templates:
- Design templates using Tailwind CSS classes.
- Improve the design of the book list (`book_list.html`) with responsive styling.

**Tip:**
- Refer to the official Tailwind CSS documentation for installation and configuration:  
  [https://tailwindcss.com/docs/installation](https://tailwindcss.com/docs/installation)

---

## Bonus Section:
- You can create the author model as a separate table with the following fields:
  - First Name
  - Last Name
  - Age
  - Number of authored books
- Add any additional information you want.

- #### For the Bonus Section (Author model):
1. Combine the first name and last name into a single column named "Full Name".
2. If the author’s age is not provided, display `-N/A-`.
3. When adding a new author, first name and last name should be on the same row.


## Completing the Task:
- Submit your task on GitHub.

**Good Luck!**
