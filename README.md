# CSCE 3444 - Project X (ShelfLife)

## Overview

ShelfLife is a PyQt-based desktop application for organizing and tracking personal book libraries. Easily search, add, and manage your book collection with intuitive features.


## Features

- User Authentication
- Book Search via ISBN, title, barcode scanning
- Collection Management
  - Add books 
  - Set book status (Read, Unread, In Progress)
  - Organized collection view


## Prerequisites

- Python 3.8+
- PyQt5
- Requests library
- bcrypt
- opencv-python
- pyzbar



## Usage

Run the application:
```bash
python ShelfLife/ui.py
```


### Key Interactions
- Login with credentials
- Search books by ISBN, title, or scan book's barcode
- Add books to collection
- Set book status


## Project Structure

```
ShelfLife/
│
├── ui.py                 # Main application entry point
├── login_page.py         # User authentication
├── book_search_page.py   # Book search functionality
├── collection_page.py    # Collection management
├── book.py               # Book data model
├── user.py               # User data model
├── collection.py         # Collection logic
├── scanner.py            # Book scanning
├── storage.py            # Data storage handling
│
└── images/               # Application assets
```
