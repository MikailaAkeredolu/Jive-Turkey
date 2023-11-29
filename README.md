
# A Quick Backend Jab by Mikaila


Creating a Simple Book Store API - demo - https://www.betterworldbooks.com/

### User stories - Create a backend API for a fake Book store:
- Endpoint needed to get a single book via "/books/id"
- Endpoint needed to create a book via "/books/{categoryId}/books"
- Endpoint needed to get all of the books in the book store via "/books"
- Endpoint needed to update a book via "/books/{categoryId}/books"
- Endpoint needed to delete a book via "/books/id"
- Endpoint needed to get all of the books that belong to a category such as: "comic books" via /books/{categoryId}/books
- Endpoint needed to get a single category via "/category/id"
- Endpoint needed to create a category via "/category"
- Endpoint needed to get all categories via "/category"
- Endpoint needed to update a category via "/category/id"
- Endpoint needed to delete a category via "/category/id"
- Endpoint needed to search or find books by name using @RequestParam annotation

### Backend Requirments describing each Book and Category:
A Category must have the following:
- A unique way to identify the category and a name

A Book must have the following:
- A unique way to identify the book in our system, a **name**, a **sku**, a **description**, a **price**, an **image**, and finailly **stock** to know how many we have available.

- A book MUST belong to a category!!!
`For example: The Head First Java book belongs in the Text Book category`


### API Requirments - You must do the following:
- API must have a database of your choice
- API must have controllers, repositories and services
- API must have LOGS to log activities 

## Sample POST data for creating a book
```
 "name": "Core java",
 "sku": "tbk",
 "description": "the java text book",
 "image": "https://m.media-amazon.com/images/I/51dBjBGQFXS._SX218_BO1,204,203,200_QL40_FMwebp_.jpg",
 "price": 25.00,
 "stock": 200,
 "category_id": 2
```
## Sample Post data for creating a category
```
    {
        "name": "textbook"
    }
```
# Resourse to help with Join Types
https://www.callicoder.com/hibernate-spring-boot-jpa-one-to-many-mapping-example/


### Frontend Requirements
 - UI must be built with Angular AND Bootstrap
 - UI must display list of books as a table or a grid
 - When a user clicks on the image of the book, they should see more details about the book
 - If a user ends up on the details page and wants to go back to the home page, ensure they can easily do so.
 - UI should have a search box so a user can easily search for books by typing the name of the book in the search box
 - UI should display the categoriesof books available and upon clicking should display only books in that category

### Code Review

- We will have a 1-1 code review via zoom (breakout room) on due date.
- Have your sample JSON test Payload for postman available to use during code review


# Demo UI of the assessment - make it your own

![Screen Shot 2020-11-30 at 5 24 54 PM (2)](https://user-images.githubusercontent.com/10773482/124328156-1839a200-db57-11eb-8450-6054e941f397.png)

