# 📝 To-Do List App

Welcome to the **To-Do List App**! This is a simple JavaScript-based application that allows you to manage your daily tasks right from the console. Add tasks, list them, delete specific tasks, and quit the app when you're done.

## 🚀 Features

- **Add New Tasks**: Easily add new tasks to your to-do list.
- **List All Tasks**: View all your tasks in a neat and organized manner.
- **Delete Tasks**: Remove tasks by specifying their index.
- **Quit App**: Exit the application gracefully.

## 📋 How to Use

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/todo-list-app.git
    cd todo-list-app
    ```

2. **Install Dependencies**

    ```bash
    npm install
    ```

3. **Run the Application**

    ```bash
    npm start
    ```

4. **Interact with the App**

    - Type `"new"` to add a new to-do item.
    - Type `"list"` to list all to-do items.
    - Type `"delete"` to remove a specific to-do item by index.
    - Type `"quit"` or `"q"` to quit the application.

## 📜 Example Usage

```bash
> npm start
What would you like to do?
> new
Ok, what is the new To-Do?
> Collect Chicken Eggs added to the list

What would you like to do?
> list
*****************
0: Collect Chicken Eggs
1: Clean Litter Box
*****************

What would you like to do?
> delete
Ok, enter an index to delete:
> 0
Ok, deleted Collect Chicken Eggs

What would you like to do?
> quit
OK, Quit the APP!
