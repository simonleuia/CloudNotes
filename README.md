# CloudNote

This project was developed as part of Assignment 2.

CloudNote is a collaborative note-taking app built with React Native (Expo) and Supabase.
The app allows multiple users to create, view, edit, and delete shared notes.

---

## GitHub Repository

Project source code:
https://github.com/simonleuia/CloudNotes

---

## Features

* User authentication (sign up, login, logout)
* Persistent login (session is remembered)
* Create notes
* View all notes from all users
* Edit notes
* Delete notes with confirmation
* Input validation (no empty fields)
* Success and error messages

---

## Requirements checklist

### Authentication

* [x] Sign-up (email + password)
* [x] Email template customized in Supabase
* [x] Login / Logout implemented
* [x] Session persistence (user stays logged in)

---

### Database

* [x] Only authenticated users can access the database (RLS)
* [x] Create note (title, content, creator, updated time)
* [x] Read all notes (shared across users)
* [x] Update existing notes
* [x] Delete notes with confirmation

---

### Validation

* [x] No empty fields (notes, email, password)
* [x] User receives feedback (success/error messages)

---

## Video

A demonstration video (3–5 minutes) is included showing:

* User sign up and login
* Creating a note
* Editing a note
* Deleting a note
* Data updating in Supabase database
* Session persistence (user stays logged in after restart)

---

## Technologies used

* React Native (Expo)
* Supabase (Authentication + Database)

---

## Notes

* The app was tested using an Android emulator
* All data is stored in Supabase
* Multiple users can collaborate on shared notes
