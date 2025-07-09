<h1>🔐 Sign Up & Login System with Email Confirmation</h1>
<p>
A secure user authentication system built with <strong>Django</strong>, enabling <strong>user registration</strong>, <strong>login</strong>, and <strong>email-based account verification</strong>. Only users who confirm their email addresses through a token-based link are allowed to activate and access their accounts.
</p>
<hr>
<h2>✨ Features</h2>
<ul>
  <li>✅ User <strong>sign up</strong> and <strong>login</strong> with email confirmation</li>
  <li>🔒 <strong>Token-based</strong> account activation via email</li>
  <li>⏳ Time-sensitive and unique <strong>activation links</strong></li>
  <li>📩 Integration with <strong>Gmail SMTP</strong> for sending confirmation emails</li>
  <li>🛡️ Security best practices: CSRF protection, token expiry, input validation</li>
  <li>🎨 Clean, responsive frontend using <strong>HTML/CSS</strong> and optionally <strong>Bootstrap</strong></li>
</ul>
<hr>
<h2>🧠 My Responsibilities</h2>
<ul>
  <li>📥 <strong>User Registration</strong><br>
  Customized Django’s built-in <code>UserCreationForm</code> to include <strong>email validation</strong>.</li>

  <li>📤 <strong>Email Confirmation via Token</strong><br>
  Configured <strong>SMTP (Gmail)</strong> to send activation emails containing unique, time-sensitive tokens.</li>

  <li>🔐 <strong>Custom Token Generator</strong><br>
  Extended Django’s <code>PasswordResetTokenGenerator</code> to generate secure email activation tokens.</li>

  <li>🔄 <strong>Activation Workflow</strong><br>
  Created activation <strong>views</strong> to handle token validation and activate user accounts securely.</li>

  <li>🖼️ <strong>UI Design</strong><br>
  Designed <strong>responsive HTML templates</strong> for the signup form and email content.</li>

  <li>🧰 <strong>Security Implementation</strong><br>
  Ensured CSRF protection, form input validation, and proper token expiration handling.</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li><strong>Backend:</strong> Django (Python), SQLite</li>
  <li><strong>Frontend:</strong> HTML, CSS, <a href="https://getbootstrap.com/">Bootstrap</a> (optional)</li>
  <li><strong>Email:</strong> SMTP with Gmail</li>
  <li><strong>Version Control:</strong> Git</li>
</ul>

<hr>

<h2>📸 Screenshots (Optional)</h2>
<p><em>Add screenshots or a demo gif here to showcase signup, email, and activation screens.</em></p>

<hr>

<h2>🚀 Getting Started (Optional)</h2>

<pre>
<code>
# Clone the repository
git clone https://github.com/yourusername/signup-email-confirmation.git
cd signup-email-confirmation

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the server
python manage.py runserver
</code>
</pre>

<hr>

<h2>📫 Contact</h2>
<p>
<strong>Chandana Madasu</strong><br>
📧 chandanamadasu94@gmail.com<br>
🌐 <a href="https://www.linkedin.com/in/your-profile">LinkedIn</a>
</p>
