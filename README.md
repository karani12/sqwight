# sqwight



## Simple  Database Engine (C)
 This project implements a basic B-tree storage engine for a simple database. It allows you to store and retrieve data with integer IDs, usernames, and email addresses.

### Features
- Stores data in a persistent B-tree structure on disk.
- Supports inserting and selecting rows.
- Uses a pager module for efficient data management.
- Provides limited meta-commands for introspection.
### Getting Started
Clone the repository:
```git clone https://github.com/your-username/simple-btree-db.git```
Build the project:
```bash make```
Run the database:

```./db <database_filename>```
**Interact with the database:**

Enter .exit to quit.
Usage
Insert a row:
insert 1 JohnDoe johndoe@example.com
Select all rows:
select
View B-tree structure:
.btree
View database constants:
.constants
API
The project includes header files for potential integration into other C projects. However, the API is not yet fully documented.

## Limitations
Currently only supports single-threaded access.
The select functionality is not yet implemented (work in progress).
Limited error handling and data validation.
Contribution
We welcome contributions to improve this project. Feel free to fork the repository and submit pull requests.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Author
Karani
I hope this readme provides a good overview of your project. Please let me know if you have any questions or suggestions.
