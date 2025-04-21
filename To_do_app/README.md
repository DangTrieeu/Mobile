# Author

**Student ID:** 22110080  

**Student Name:** Ly Dang Trieu

# 📅 React Native ToDo App

A simple task management application built with **React Native** and **Expo** that helps you add, sort, and delete tasks with due dates.

---

## 🚀 Main Features

- ✅ **Add new tasks** with a name and due date.  
- 🗑️ **Delete tasks** with a simple button press.  
- 📅 **Select due dates** using a user-friendly DatePicker.  
- 📋 **Sort task list** by:
  - 🔠 Task name  
  - 📆 Due date

---

## 🧠 Learning Objectives

This application helps students master the following concepts:

### 📌 Input Controls

- **`TextInput`**: Used to enter the task name.  
- **`Button`** / `TouchableOpacity`: Used to add a new task when pressed.  

➡️ Helps students understand how to handle **user input** in React Native.

---

### 📌 Menus

- Uses **`react-native-material-menu`** to display option menus.  
- The menu includes functions:
  - **Sort by name**
  - **Sort by date**

➡️ Students will practice **creating menus** and handling **selection events**.

---

### 📌 Pickers

- Uses **`@react-native-community/datetimepicker`** to select the due date for each task.  

➡️ Allows learners to get familiar with **common date picker components** in real-world applications.

---

## 🏗️ Technologies Used

- **React Native** (Expo)  
- **TypeScript**  
- **React Navigation**  
- **DateTimePicker**  
- **Material Menu**  
- **AntDesign Icons**

---

## 📦 Installation

🛠 Set up the development environment  
✅ Step 1: Install Java environment  
Requires Java 17 or higher.  

Download Java from:  
👉 https://www.oracle.com/in/java/technologies/downloads/archive/

After installation, configure the `JAVA_HOME` environment variable.

Check installation:

```bash
java -version
```

✅ Step 2: Configure `ANDROID_HOME` environment variable  
For Windows:  
```env
ANDROID_HOME=C:\Users\Username\AppData\Local\Android\Sdk
```

Update `Path`:

```makefile
C:\Users\Username\AppData\Local\Android\Sdk\platform-tools  
C:\Users\Username\AppData\Local\Android\Sdk\emulator
```

Reference: https://reactnative.dev/docs/environment-setup

Verify configuration:

```bash
adb --version
```

If the adb version info appears, the setup is successful.

---

```bash
# Install libraries
npm install --legacy-peer-deps

# Start the project
npm start
```