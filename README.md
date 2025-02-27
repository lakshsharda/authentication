# Animated Login and Registration Page

This project is an animated authentication system built with TypeScript, React, and Tailwind CSS. It features smooth UI transitions, responsive design, and user authentication stored in local storage.

## 🚀 Live Demo

🔗 [Live URL](https://authentication-tau-three.vercel.app/dashboard)

## 📌 Features

- **Login Page**: Animated login form with email validation.
- **Registration Page**: Smooth animations and input validation.
- **Normal Page**: Simple static page after login/registration.
- **Email Validation**: Only emails ending with `@gmail.com` are allowed.
- **Password Handling**: Passwords are masked for security.
- **Responsive Design**: Fully mobile-friendly UI.
- **Error Handling**: Displays appropriate messages for invalid inputs.
- **Form Submission**: Simulated submission process with local storage.
- **No Page Reloads**: Implemented using React state management.
- **Modern UI**: Styled using Tailwind CSS.

## 🎯 Bonus Features

- **Dark Mode Support** 🌙
- **Password Strength Validation** 🔐
- **Smooth Page Transitions** using GSAP
- **Creative UI Enhancements**

## 🛠️ Installation & Setup

```sh
# Clone the repository
git clone https://github.com/lakshsharda/authentication.git

# Navigate to the project folder
cd authentication

# Install dependencies
npm install

# Run the development server
npm run dev
```

The application will be available at `http://localhost:5173/` by default.

## 🏗️ Project Structure

```
📦 authentication
├── 📂 src
│   ├── 📂 components  # Reusable UI components
│   ├── 📂 pages       # Login, Register, and Dashboard pages
│   ├── 📂 utils       # Utility functions (e.g., validation)
│   ├── 📜 App.tsx     # Main App component
│   ├── 📜 index.tsx   # React entry point
│   ├── 📜 styles.css  # Global styles
├── 📜 package.json    # Dependencies & scripts
├── 📜 README.md       # Project documentation
└── ...
```

## 📜 Usage

1. **Register a new user** with a valid `@gmail.com` email.
2. **Login using the registered credentials**.
3. **Access the dashboard** after successful authentication.

## 🛡️ Technologies Used

- **React (TypeScript)** ⚛️
- **Tailwind CSS** 🎨
- **GSAP (for animations)** ✨
- **Local Storage (for user data storage)** 🗄️

## 📌 Future Improvements

- Integration with an actual backend (SQL database)
- Enhanced UI with more animations
- Multi-theme support

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Developed with ❤️ by [Laksh Sharda](https://github.com/lakshsharda)

