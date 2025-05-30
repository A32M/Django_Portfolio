# Django_Portfolio

🧳 Personal Portfolio Website (Django)

This project is a professional-grade personal portfolio website built with Django. It is designed to showcase creative or technical work, support large video and image content via Amazon S3, and handle visitor inquiries through a contact form integrated with email services. A lightweight blog system is also included for sharing posts or project updates. The site is fully responsive and optimized for quick deployment with low maintenance.
🚀 Features

    ✅ Clean, modern, mobile-friendly design

    🎬 Supports large images and video files (via AWS S3)

    📩 Contact form routed to email

    📝 Basic blog with post management

    ⚙️ Admin interface for content updates

    🔒 Secure and ready for production deployment

    🌐 Easily deployed to platforms like Render, Railway, or AWS EC2

🛠️ Tech Stack

    Backend: Django 4.x (Python)

    Frontend: Bootstrap 5 / Tailwind CSS (customizable)

    Media Hosting: Amazon S3

    Email Service: SMTP (Mailgun, SendGrid, or AWS SES)

    Database: SQLite (dev) / PostgreSQL (production recommended)

    Deployment: Render, Railway, or Docker (AWS-compatible)

📦 Setup Instructions
1. Clone the Repository

git clone https://github.com/yourusername/your-portfolio.git
cd your-portfolio

2. Create and Activate Virtual Environment

python -m venv env
source env/bin/activate  # or `env\Scripts\activate` on Windows

3. Install Dependencies

pip install -r requirements.txt

4. Configure Environment Variables

Create a .env file with:

SECRET_KEY=your-django-secret-key
DEBUG=True
AWS_ACCESS_KEY_ID=your-aws-key
AWS_SECRET_ACCESS_KEY=your-aws-secret
AWS_STORAGE_BUCKET_NAME=your-s3-bucket-name
EMAIL_HOST_USER=your-email@example.com
EMAIL_HOST_PASSWORD=your-email-password

5. Run Migrations and Start Server

python manage.py migrate
python manage.py runserver

🧪 Demo Content (Optional)

    Visit /admin/ to add your portfolio projects, blog posts, and update site content.

    Add your resume or case studies in PDF or video format.

📤 Deployment

Supports deployment to:

    Render: simple deployment with S3 media + environment vars

    Railway or Heroku: PostgreSQL add-on + AWS config

    AWS EC2 / Lightsail: full-stack deployment

📬 Contact

Have questions or need help? Feel free to open an issue or connect via the contact form on the live site.
