# Django Blog Application

A simple blog application built with Django that allows users to create, read, update, and delete blog posts with image uploads.

## Features

- Create new blog posts with title, author, content, and optional image
- View all blog posts on the homepage
- Read individual blog posts in detail
- Edit existing blog posts
- Delete blog posts with confirmation
- Image upload functionality for blog posts

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/swetha-vjec/BLOG-1.git
   cd BLOG-1
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`

4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

5. Apply migrations:
   ```
   python manage.py migrate
   ```

6. (Optional) Create a superuser for admin access:
   ```
   python manage.py createsuperuser
   ```

7. Run the development server:
   ```
   python manage.py runserver
   ```

8. Open your browser and go to `http://127.0.0.1:8000/`

## Usage

- Visit the homepage to see all blog posts
- Click "New Post" to create a new blog post
- Click on a post title to read the full post
- Use the "Edit" button to modify a post
- Use the "Delete" button to remove a post

## Project Structure

- `blogproject/` - Main Django project settings
- `blog/` - Blog app containing models, views, templates, and URLs
- `media/` - Directory for uploaded images (created automatically)
- `static/` - Static files (CSS, JS, images)
- `templates/` - HTML templates

## Technologies Used

- Django 6.0
- Pillow (for image processing)
- SQLite (default database)

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).