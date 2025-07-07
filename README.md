Project: Sign Up & Login System with Email Confirmation
Description: Developed a secure user authentication system using Django that enables user registration with email verification to ensure only valid users can activate their accounts and log in. The system includes token-based email confirmation for account activation.
My Responsibilities:
Implemented user registration with Django’s built-in UserCreationForm customized to include email validation.
Configured SMTP backend using Gmail to send automated account activation emails with unique, time-sensitive tokens.
Created secure token generator by extending Django’s PasswordResetTokenGenerator for email confirmation workflow.
Developed activation views to handle token verification and activate user accounts upon confirmation.
Designed and developed responsive HTML templates for signup forms and email content.
Ensured security best practices including CSRF protection, token expiration, and form validation.
Technologies used:
Django, Python, SQLite, SMTP (Gmail), HTML/CSS, Bootstrap (optional), Git
