<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/a3fefe1e-a5c0-4e58-9e99-36d3994db05a" /># Address book
 Aplikasi buku alamat sederhana untuk menyimpan dan mengelola informasi kontak.
# Link
 - Url Deployment:
 - Repisitory
# Features
 - Add, edit, and delete contacts
 - Search contacts by name or email
# Tech Stack
 - HTML 
 - CSS
 - JavaScript
# Flowchart
flowchart TD
    A[Start] --> B[Display Contact List]
    B --> C{User Action}
    C -->|Add Contact| D[Show Add Contact Form]
    C -->|Edit Contact| E[Show Edit Contact Form]
    C -->|Delete Contact| F[Confirm Deletion]
    D --> G[Save New Contact]
    E --> H[Update Contact]
    F --> I[Remove Contact]
    G --> B
    H --> B
    I --> B
    B --> J[End]
