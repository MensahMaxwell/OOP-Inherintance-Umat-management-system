# Inheritance: UMaT Management System

## Project Description
This repository contains a simple object-oriented Python implementation designed to manage different types of people on the UMaT campus using the principle of **inheritance**[cite: 1]. 

All people in the system share common attributes (`name`, `age`), while specific roles inherit these properties and introduce their own unique functionalities and behaviors[cite: 1].

## Requirements Implemented
1. **Parent Class (`Person`):** 
   * Base attributes: `name`, `age`[cite: 1].
   * Base method: `display_info()`[cite: 1].
2. **Child Classes:**
   * `Student`: Inherits from `Person`, adds `student_id`, and tracks enrolled courses[cite: 1].
   * `Lecturer`: Inherits from `Person`, adds `employee_id`, and tracks teaching courses[cite: 1].
3. **Advanced OOP Concepts:**
   * Used `super().__init__()` to properly initialize inherited parent attributes[cite: 1].
   * Overrode the `display_info()` method in the child classes to display unique IDs while using `super().display_info()` to maintain parent output[cite: 1].
  
  Programmer: Mensah Maxwell
