# Xpen
Daily expense note -- runing on web based

🔒 [Privacy Policy](Privacy.md) | 📕[Read the detail maunally](Xpen-webap-plan.mb)

<img width="1080" height="1080" alt="Xpen web app" src="https://github.com/user-attachments/assets/d787d788-1183-4dc0-9c94-8301fdc2a88d" />


(SaaS) idea for expense analysis and management. This project aims to help users track, analyze, and manage their expenses efficiently with a modern web interface.

## Features

- 🔒 Secure authentication (phone, onboarding, protected routes)
- 📊 Dashboard for visualizing expenses
- 🏦 Account and category management
- 🧾 OCR integration for receipt scanning
- ⚡ Fast, responsive UI built with React and Tailwind CSS
- ☁️ Firebase backend for real-time data and authentication

## Tech Stack

- **Frontend:** React, Tailwind CSS, Vite
- **Backend:** Firebase (Firestore, Authentication, Storage)
- **OCR:** Google Vision API (Node.js)
- **Deployment:** GitHub, Firebase Hosting

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm or yarn
- Firebase account and project

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Pon-Chaithawat/Xpen.git
   cd Xpen
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Set up Firebase:**
   - Copy `firebase-config.example.js` to `src/lib/firebase-config.js` and fill in your Firebase project details.
   - Follow the instructions in `FIREBASE_SETUP.md` for more details.

4. **Run the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

## Project Structure

```
Xpen/
  ├── src/
  │   ├── components/         # React components
  │   ├── contexts/           # React context providers
  │   ├── lib/                # Utility libraries (Firebase, OCR, etc.)
  │   └── App.jsx             # Main app entry
  ├── public/                 # Static assets
  ├── server/                 # Backend scripts (OCR, etc.)
  ├── FIREBASE_SETUP.md       # Firebase setup instructions
  └── ...
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.

---

**Xpen** — Expense analysis made simple. 

![Xpen Mobile Screenshot](Xpen-mobile.png) 
