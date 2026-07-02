# Inheritance-UMaT-Management-System
Case Study Activity: UMaT Management System

# UMaT Management System

A simple Python case study demonstrating **Object-Oriented Programming (OOP)** concepts — specifically inheritance and method overriding — through a mock student/lecturer management system for UMaT (University of Mines and Technology).

# Overview

This project was built as part of a lab session case study activity. It models two types of people within a university system, `Student` and `Lecturer`, both of which inherit shared attributes and behavior from a common `Person` base class.

#  Class Structure

### `Person` (Base Class)
| Attribute | Description |
|---|---|
| `name` | Full name of the person |
| `age` | Age of the person |

**Methods:**
- `display_info()` — Prints the person's name and age.

### `Student` (inherits from `Person`)
Adds student-specific attributes on top of `Person`.

| Attribute | Description |
|---|---|
| `student_id` | Unique student identifier |
| `enroll_course` | Enrollment status (`True`/`False`) |

**Methods:**
- `display_info()` — Overrides the parent method to print full student details, including ID and enrollment status.

### `Lecturer` (inherits from `Person`)
Adds lecturer-specific attributes on top of `Person`.

| Attribute | Description |
|---|---|
| `employee_id` | Unique employee identifier |
| `teach_course` | Teaching status (`True`/`False`) |

**Methods:**
- `display_info()` — Inherited directly from `Person` (not overridden).
- `show_more_info()` — Prints additional lecturer-specific details.

## Author
Woode Adom Edwin 
EL1B, Electrical And Electronic Engineering  
University of Mines And Technology(UMaT),Tarkwa
