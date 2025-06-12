# QuickContact

QuickContact is a simple, responsive contact form web application that allows users to send messages directly from the website. It features a clean UI, form validation, and a success message upon submission.

---

## Features

- Responsive contact form
- Fields for Name, Email, and Message
- Form validation (required fields)
- Success message after form submission
- Custom favicon and styling
- Easy integration with backend/email services

---

## Project Structure

```
QuickContact/
│
├── assets/
│   └── images/
│       └── msg_favicon.png
├── index.html
├── styles.css
├── script.js
└── README.md
```

---

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/YOUR-USERNAME/QuickContact.git
cd QuickContact
```

### 2. Open the Project

Open the folder in [Visual Studio Code](https://code.visualstudio.com/) or your preferred editor.

### 3. Run Locally

Just open `index.html` in your browser. No server setup is required for the basic form.

---

## Usage

1. Fill in your **Name**, **Email**, and **Message**.
2. Click **Submit**.
3. A success message will appear if the form is submitted successfully.

---

## Customization

- **Favicon:** Replace `assets/images/msg_favicon.png` with your own icon if desired.
- **Styling:** Edit `styles.css` to change the look and feel.
- **Form Handling:**  
  - The form uses a hidden `access_key` for integration with backend/email services.
  - To connect to your own backend, update the form action or modify `script.js` as needed.

---

## File Details

- **index.html**  
  Main HTML file containing the contact form and success message.

- **styles.css**  
  Stylesheet for layout and design.

- **script.js**  
  Handles form submission and success message display.

- **assets/images/msg_favicon.png**  
  Favicon for the website.

---

## Deployment

You can deploy this project on any static hosting service (GitHub Pages, Netlify, Vercel, etc.).

---

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, open an issue or contact the repository owner.
