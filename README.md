# Food Menu RecyclerView App

A simple Android application built using **Kotlin** and **RecyclerView** that displays a list of food items with images and names.

This project demonstrates:

* RecyclerView implementation
* Custom Adapter creation
* Model class usage
* Image and text binding
* Linear Layout Manager setup
* Basic Android UI design

---

# Features

* Display food items in a vertical scrolling list
* Show food images with names
* Clean and beginner-friendly code structure
* Uses custom RecyclerView Adapter
* Built using Kotlin and Android Studio

---

# Technologies Used

* Kotlin
* Android Studio
* RecyclerView
* XML Layouts
* Gradle

---

# Project Structure

```bash
MyAssignment/
│
├── app/
│   ├── src/main/java/com/example/myassignment/
│   │   ├── MainActivity.kt
│   │   ├── adapters/
│   │   │   └── FoodAdapter.kt
│   │   ├── models/
│   │   │   └── FoodModel.kt
│   │
│   ├── src/main/res/
│   │   ├── drawable/
│   │   ├── layout/
│   │   └── values/
│
├── gradle/
├── build.gradle.kts
└── README.md
```

---

# How It Works

## 1. MainActivity

`MainActivity.kt` initializes the RecyclerView and creates a list of food items.

Example:

```kotlin
arrlist.add(FoodModel(R.drawable.cheese, "Cheese Burger"))
arrlist.add(FoodModel(R.drawable.fettuccine, "Fettuccine Alfredo Pasta"))
arrlist.add(FoodModel(R.drawable.fries, "French Fries"))
```

The RecyclerView is connected with:

* Adapter
* LayoutManager
* Data List

---

## 2. FoodModel

`FoodModel.kt` is a data class used to store:

* Food Image
* Food Name

```kotlin
data class FoodModel(
    val images1: Int,
    val text: String
)
```

---

## 3. FoodAdapter

`FoodAdapter.kt` connects the data with RecyclerView items.

Responsibilities:

* Inflate item layout
* Bind image and text
* Manage list size

Important methods:

```kotlin
override fun onCreateViewHolder()
override fun onBindViewHolder()
override fun getItemCount()
```

---

# UI Components

The app uses:

* RecyclerView
* ImageView
* TextView
* LinearLayoutManager

Each food item contains:

* Food image
* Food title

---

# Screens Included

The application displays:

1. Cheese Burger
2. Fettuccine Alfredo Pasta
3. French Fries

---

# Setup Instructions

## Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

## Open in Android Studio

1. Open Android Studio
2. Click on **Open Project**
3. Select the project folder
4. Sync Gradle files
5. Run the application

---

# Requirements

* Android Studio
* Kotlin Support
* Android SDK
* Gradle

---

# Learning Objectives

This project helps beginners understand:

* RecyclerView basics
* Adapter pattern
* Model classes
* Android layouts
* Kotlin Android development

---

# Future Improvements

Possible future enhancements:

* Add click listeners
* Add food prices
* Add detailed food screens
* Connect with Firebase or API
* Add animations
* Add search functionality

---

