# Contacts API

This is the requirement documentation for the Contacts API. This API allows users to manage contacts, categorize them, and perform CRUD operations.

## Functionality

- Users should be able to add new contacts with information such as name, phone number, email address, etc.

## Functional Requirements

- Contact Registration
- Contacts Viewing
- Contacts Updating
- Contacts Deletion

## Authentication and Authorization Requirements

- User Authentication
- Access Authorization to Operations
- User Creation

## Business Rules

- Users must be registered with a name and email.
- The email must be a unique key.
- Contacts must contain at least one name and one contact method (phone number, email address, etc.).
- Only authenticated users can perform create, update, and delete operations on contacts.
- Authorization is based on user roles, such as administrator and regular user.
- All API data must be stored securely and protected against unauthorized access.
- User inputs must be validated to prevent the insertion of incorrect or malicious data.
