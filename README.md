
## Creating a Simple Book Store API 
- Your screen must be shared throughout this exam in your individual breakout room

### User stories - Create a backend API for a Book store:
- Endpoint needed to create a book and ensure it has a category
- Endpoint needed to get a single book 
- Endpoint needed to get all of the books in the book store
- Endpoint needed to update a book
- Endpoint needed to delete a book
- Endpoint needed to get all of the books that belong to a category such as: "comic books or tech books"
- Endpoint needed to create a category
- Endpoint needed to get a single category
- Endpoint needed to get all categories 
- Endpoint needed to update a category
- Endpoint needed to delete a category 
- Endpoint needed to search or find books by name
- Endpoint needed to search or find books by price

### Backend Requirments describing each Book and Category:
A Category must have the following:
- A unique way to **identify** the category and the **name** of the category. eg: "comic books or tech books"

A Book **must** have the following:
- A unique way to **identify** the book in our system, a **name**, a **sku**, a **description**, a **price**, an **image**, and finally **stock** to know how many we have available.

- A book **must** belong to a category.
`For example: The Head First Java book belongs in the Tech Books category`

### API Requirments:
- API must have a database such as MYSQL
- All POJO's **must have** controllers, repositories and service layers
- API must have LOGS to log activities by using the SLF4J logger

### Exception Handling:
- Ensure that you throw exceptions for the following reasons:
- A book cannot be found
- If one tries to create a Book but uses a bad or not properly formatted payload
- If one tries to create a Book but is mising a name, sku, price, stock or an image

- **Extra credit:** Ensure that all activities logged are saved to a file !!!

### Code Review

- We will have a 1-1 code review via zoom (breakout room) later. It will be graded.
- Have your sample JSON test Payload for postman available to use during code review.
- Make repo private and do not push any new code until I review it else get an incomplete.

