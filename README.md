
# ToDo App

A simple ToDo application built with Kotlin and Jetpack Compose.  
This app lets you manage tasks easily — add, edit, mark as done, and delete.



 Features
- Add tasks with a title  
- Mark tasks as done using a checkbox  
- Edit tasks to update details  
- Delete tasks permanently  
- Room database for local storage  
- Jetpack Compose UI with Material 3 design  

---

Tech Stack
- Kotlin  
- Jetpack Compose  
- Room Database  
- MVVM Architecture  



 Project Structure

com.example.todoapp
│
├── data
│   ├── TaskItem.kt        # Entity
│   ├── TaskDao.kt         # DAO
│   └── TaskDatabase.kt    # Room Database
│




├── viewmodel
│   └── TaskViewModel.kt   # ViewModel
│





├── ui
│   ├── ToDoListScreen.kt  # Main screen
│   └── ToDoItem.kt        # Single task card
│





└── MainActivity.kt        # Entry point




 How to Run
1. Clone the repo  
2. Open in Android Studio  
3. Sync Gradle  
4. Run on emulator or device  



Future Improvements
- Add due dates and reminders  
- Support categories/tags  
- Dark mode toggle  
- Cloud sync with Firebase  


