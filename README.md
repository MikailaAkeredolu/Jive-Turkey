
## Creating a Simple Book Store API 
- Your screen must be shared throughout this exam in your individual breakout room

### User stories - Create a backend API for a Book store:
- Endpoint needed to create a book and ensure it has a category
- Endpoint needed to get a single book 
- Endpoint needed to get all books and to search for books by name or by sku
- Endpoint needed to update a book
- Endpoint needed to delete a book
- Endpoint needed to get all of the books that belong to a category such as: "comic books or text books"
- Endpoint needed to create a category
- Endpoint needed to get all categories 
- Endpoint needed to edit a category

### Backend Requirments describing each Book and Category:
A Category must have the following:
- A unique way to **identify** the category and the **name** of the category. eg: "comic books or text books"

A Book **must** have the following:
- A unique way to **identify** the book in our system, a **name**, a **sku**, a **description**, a **price**, an **image**, and finally **stock** to know how many we have available.

- A book **must** belong to a category. For example: The Head First Java book belongs under the Text Books category

### API Requirments:
- API must have a database such as MYSQL
- All POJO's **must have** controllers, repositories and service layers
- Appropriate status codes should be displayed for each type of request
- API must have LOGS to log activities to the console

### Exception Handling:
- Ensure that you throw exceptions for the following reason below:
- A book cannot be found by category - display and log the error as ``` No books exist with a category id of:  3 ```

- **Extra credit:** Ensure that all activities logged are saved to a file !!!

### Submit your repo to me via DM by 1pm sharp. No Extensions for anyone!

- We will have a 1-1 code review via zoom (breakout room) later. It will be graded.
- Have your sample JSON test Payload for postman available to use during code review.
- Make repo private and do not push any new code until I review it else get an incomplete.

