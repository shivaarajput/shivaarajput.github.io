# 🚀 Shivam Kumar - Modern Portfolio

A high-performance, dynamic portfolio website built for Software Engineers. It features a stunning dark mode design, particle animations, and a fully functional Admin Dashboard powered by Firebase.

**Live Site:** [https://shivaarajput.github.io/](https://shivaarajput.github.io/)

## ✨ Features

* **Dynamic Content:** All data (Skills, Projects, Experience) is fetched from Firestore. No need to edit HTML to update your resume.
* **Admin Dashboard:** A password-protected GUI (`/admin.html`) to add/edit/delete content without touching code.
* **Modern UI/UX:**

  * Dark/Light Mode toggle
  * Soft Particle Network background (Canvas API)
  * Glassmorphism navigation
  * Fully Responsive (Mobile First)
* **SEO Optimized:** Meta tags, semantic HTML, and fast loading speeds (Tailwind CSS via CDN)
* **Custom 404:** Interactive "Lost in Space" error page

## 🛠️ Tech Stack

* **Frontend:** HTML5, JavaScript (ES6+), Tailwind CSS
* **Backend (BaaS):** Firebase (Auth & Firestore)
* **Hosting:** GitHub Pages

## 📂 Project Structure

```
.
├── assets\images
├── index.html       # Main Portfolio (The Viewer)
├── links.html       # Social Links
├── admin.html       # Admin Dashboard (The Controller)
├── 404.html         # Custom Error Page
└── README.md        # Documentation
└── LICENSE.md        # License
```

## ⚙️ Setup & Configuration

### 1. Firebase Setup

To make the Admin Panel work, you need your own Firebase project.

1. Create a project at Firebase Console.
2. Enable Authentication (Email/Password & Anonymous).
3. Enable Firestore Database.
4. Copy your `firebaseConfig` object.
5. Update `index.html` and `admin.html` with your config keys.

### 2. Admin Access

1. Navigate to `your-site.github.io/admin.html`
2. Login with the credentials you created in Firebase Auth
3. Use the GUI Dashboard to add Skills, Projects, and Timeline entries
4. Click **Save Configuration** to push changes live instantly

## 🎨 Customization

* **Icons:** Uses FontAwesome 6. You can use any class like `fab fa-react` or `fas fa-code`.
* **Colors:** Powered by Tailwind. The primary theme color is Teal-600 (#0d9488). You can change this in the `tailwind.config` script tag in the HTML head.

## 📝 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this project with proper attribution.

---

**Designed & Developed by Shivam Kumar**
