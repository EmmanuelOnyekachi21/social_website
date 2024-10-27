# Social Website - Image Bookmarking and Sharing Platform

This project is a social website that allows users to bookmark and share images.

It is built using Django, JavaScript, and various third-party packages. The key features include authentication, social login, image management, and user interaction through a follow system.

## Features

1. **User Authentication**
    - Implemented using Django's authentication.
    - Supports custom profile models to extend the default user model.
    - Utilizes the Django messages framework to display notifications.

2. **Custom Authentication**
    - A custom authentication backend has been created.
    - Social authentication with Google is enabled using Python Social Auth.
3. **Development Server**
   - HTTPS support through `django-extensions` for secure development.

4. **Image Management**
   - Easy-thumbnails is used to generate image thumbnails.
   - Many-to-many relationships are utilized to allow multiple users to bookmark the same image.

5. **JavaScript Bookmarklet**
   - Built using JavaScript and Django to allow users to bookmark images from other websites.

6. **Asynchronous HTTP Requests**
   - The Fetch API and Django are used to add asynchronous requests for a more responsive experience.

7. **Infinite Scroll Pagination**
   - Users can scroll infinitely to load more images dynamically.

8. **User Follow System**
   - A system that enables users to follow other users.
   - User activity streams are implemented for updates.

9. **QuerySet Optimization**
   - QuerySets are optimized for better performance.

10. **Django Signals**
    - Signals are used for decoupled event handling within the app.

11. **Debugging and Optimization**
    - `django-debug-toolbar` is employed to obtain relevant debug information.
    - Redis is used for counting image views and building an image ranking system.

## Prerequisites

- Python 3.x
- Django
- Redis
- Django extensions (`django-extensions`)
- Easy-thumbnails
- Python Social Auth
- Django Debug Toolbar
