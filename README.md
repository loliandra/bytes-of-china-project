# Build A Menu For Bytes Of China 🍜

## Project Overview

This project focuses on designing a relational database schema for a restaurant called **Bytes of China**.

The restaurant has recently moved to a new location on a busy street in Chinatown and needs a structured database to display its menu and customer reviews on its new website.

As a database designer, the main objective of this project is to model real-world restaurant data and implement a working SQL solution that supports menu organization, pricing, and customer feedback.
<img width="800" height="2500" alt="Bytes_of_China-single-column" src="https://github.com/user-attachments/assets/db4d2253-f39d-4ab8-b60e-75b5c3af134e" />

---

## Restaurant Information

* **Name:** Bytes of China
* **Cuisine:** Delectable Chinese cuisine
* **Address:** 2020 Busy Street, Chinatown, MA 02139
* **Telephone:** 617-555-1212
* **Hours:**

  * Mon – Fri: 9:00 am – 9:00 pm
  * Weekends: 10:00 am – 11:00 pm
* **Rating:** 3.9 out of 200 reviews

---

## Business Requirements

The restaurant website includes two main pages:

### 🍽 Menu Page

The menu is organized into multiple categories:

* Appetizers
* Soup
* Chicken
* Beef
* Veal
* Vegetarian
* Rice and Noodles
* Luncheon Specials
* House Specials

Each category contains dishes with:

* Dish code
* Dish name
* Price
* Description
* Hot & spicy indicator (marked with an asterisk *)

Some categories such as **Luncheon Specials** have:

* A shared fixed price
* Additional serving information
* Time-based availability

---

### ⭐ Reviews Page

The website also displays customer reviews including:

* Rating
* Review text
* Review date

Example feedback includes experiences related to service quality, food taste, and overall dining satisfaction.

---

## Database Design Goals

This project demonstrates the following database design tasks:

* Creating relational tables
* Defining primary and foreign keys
* Designing many-to-many relationships
* Inserting sample restaurant data
* Writing analytical SQL queries

---

## Main Tables

* `restaurant`
* `address`
* `category`
* `dish`
* `categories_dishes`
* `review`

---

## Example Queries Implemented

* Retrieve full menu with categories and prices
* Find spicy dishes
* Identify dishes that appear in multiple categories
* Get highest rated customer review
* Perform joins between restaurant and address tables

---

## Technologies Used

* SQL
* Relational Database Design
* Git & GitHub

---

## Purpose

This project is part of a learning portfolio focused on practicing real-world SQL schema design and query writing for entry-level database or backend developer roles.
