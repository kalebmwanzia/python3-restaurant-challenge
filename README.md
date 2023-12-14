# python3-restaurant-challenge

This is a simple restaurant review system implemented in Python. The system includes classes for Customer, Restaurant, and Review, allowing users to manage customers, restaurants, and their reviews.

## Customer Class

### Properties

- given_name: First name of the customer.
- family_name: Last name of the customer.

### Methods

- full_name(): Returns the full name of the customer.
- all(): Returns a list of all customers.
- restaurants(): Returns a list of restaurants reviewed by the customer.
- add_review(restaurant, rating): Adds a new review for a restaurant.

### Class Methods

- find_by_name(name): Finds a customer by their full name.
- find_all_by_given_name(name): Finds all customers with a given first name.

## Restaurant Class

### Properties

- name: Name of the restaurant.

### Methods

- reviews(): Returns a list of all reviews for the restaurant.
- customers(): Returns a unique list of customers who have reviewed the restaurant.
- average_star_rating(): Calculates the average star rating based on reviews.

## Review Class

### Properties

- rating: Rating given in the review.

### Methods

- all(): Returns a list of all reviews.
- customer(): Returns the customer object for the review.
- restaurant(): Returns the restaurant object for the review.

## Usage

1. Create instances of Customer, Restaurant, and Review classes.
2. Interact with the methods provided by each class to manage customers, restaurants, and reviews.