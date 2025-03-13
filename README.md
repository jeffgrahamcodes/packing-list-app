# Packing List App

## Overview

The **Packing List App** is a simple React application that helps users create and manage a list of items for a trip. Users can add items, mark them as packed, sort the list, and clear it when necessary.

## Features

- Add items with a description and quantity
- Mark items as packed/unpacked
- Delete individual items
- Sort items by input order, description, or packing status
- Clear the entire list with confirmation

## Technologies Used

- React (`useState` for state management)
- UUID for unique item IDs
- HTML & CSS for basic styling

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/packing-list-app.git
   cd packing-list-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```

## Components

### `App`

- Manages the overall application state and renders child components.

### `Logo`

- Displays the application title.

### `Form`

- Allows users to add new items to the list.

### `PackingList`

- Displays all items and provides sorting and clearing functionality.

### `Item`

- Represents a single item in the list with toggle and delete options.

### `Stats`

- Displays statistics on packed vs. unpacked items.

## Usage

1. Enter an item description and select a quantity in the form.
2. Click **"Add"** to add the item to the packing list.
3. Click on an item's checkbox to mark it as packed/unpacked.
4. Use the dropdown to sort items.
5. Click the **❌** button to delete an item.
6. Click **"Clear List"** to remove all items after confirmation.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Author

Created by [Your Name]. Feel free to contribute or provide feedback!
