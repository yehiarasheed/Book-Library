# Book Library
## Project Description
The Book Library project is a simulation of a Book Library System, essentially managing an inventory of books stored in an Excel file. The inventory contains information such as the book's name, quantity, price, and ISBN. The program provides a user interface where users can perform the following actions:

- **Query a Book**: Enter the book’s name to retrieve its details.
- **Buy a Book**: Enter the book’s name and the quantity to purchase provided that the library has the needed book in sufficient quantity.
- **Exit**: Exit the program.
<img src = "https://github.com/yehiarasheed/Book-Library/assets/157399068/db49424e-e782-4ccc-9704-11960840450d" />
You’ll find two versions of the Books Inventory in the `Additional Files` folder:

Original Inventory File: This is the initial inventory.
Validation Inventory File: This version includes additional validations.
As well as the original task requirements.

>[!NOTE]
>Extra validations were added for when a book is found by name in the Inventory but is listed with a quantity of Zero **(Inventory Update Mistake)** at the start of the program before Querying or Purchasing a book.

## How to Install

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yehiarasheed/Book-Library.git
   cd Book-Library
   ```

2. **Install UiPath Studio:**
   Download and install UiPath Studio from the [official UiPath website](https://www.uipath.com).

3. **Open the Project in UiPath Studio:**
   - Launch UiPath Studio.
   - Click on `Open` in the Start tab.
   - Navigate to the cloned repository folder and open the `.xaml` file.

## Dependencies

This project requires the following dependencies:

- **Microsoft Excel**: Required for handling Excel files.
- **UiPath.Excel.Activities**: For interacting with Excel files.
- **UiPath.System.Activities**: For general automation tasks.
- **UiPath.WebAPI.Activities**: For making HTTP requests (if applicable).

These dependencies can be managed through UiPath Studio's Package Manager. Make sure all required packages are installed and up to date.

---


