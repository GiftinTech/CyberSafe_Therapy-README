# CyberSafe AI Therapist

## 🔗 Live Demo

Experience CyberSafe live on Netlify: [https://ai-cybersafe-therapy.netlify.app](https://ai-cybersafe-therapy.netlify.app)

---

## 🚀 Project Overview

**CyberSafe** is an empathetic and intelligent AI therapist designed to support teens and young adults in navigating the complexities of digital life safely, while also promoting their general well-being. Powered by the advanced **Google Gemini 1.5 Flash** model, CyberSafe provides confidential, non-judgmental advice on crucial topics like online safety, privacy, cyberbullying, healthy screen time, and broader mental wellness.

### ✨ Key Features

- **Intelligent & Empathetic Support:** We provide a safe, non-judgmental space, offering conversational guidance on digital safety and general well-being.
- **Comprehensive Guidance & Resources:** Get practical advice on online risks like cyberbullying and privacy, with tailored resources provided dynamically as you need them.
- **Seamless Multi-Language Adaptation:** Our system understands and responds in your language, including specific English dialects and Nigerian Pidgin, ensuring a truly inclusive experience.
- **Prioritised User Privacy & Safety:** Your anonymity is guaranteed with chat history saved locally, and we have a clear protocol to redirect you to human-led crisis support if ever necessary.
- **Optimised User Experience:** Enjoy smooth interaction across all your devices thanks to our responsive design.
- **100% Anonymity & Confidentiality:** Users are assured that their interactions are completely private and secure, with conversation history stored only locally in their browser's `localStorage`.

---

## 💻 Technologies Used

- **Google Gemini 1.5 Flash:** The core large language model driving CyberSafe's intelligent and empathetic responses.
- **TypeScript:** Enhances code quality, maintainability, and scalability with static typing.
- **Vite:** Provides an incredibly fast development environment and optimized build process for a modern web application.
- **Tailwind CSS:** For rapid and efficient utility-first CSS styling, ensuring a clean and responsive design.
- **HTML & CSS:** Fundamental technologies for structuring and styling the user interface.
- **Marked.js:** A robust library used for efficiently parsing and rendering Markdown content, ensuring AI responses are well-formatted.

---

## 🛠️ Setup & Local Development

Follow these steps to get CyberSafe running on your local machine.

1.  **Clone the Repository:**

    ```bash
    git clone YOUR_GITHUB_REPO_LINK_HERE # Replace with your actual repo link
    cd cybersafe_therapy
    ```

2.  **Install Dependencies:**

    ```bash
    npm install
    ```

    This will install all necessary project dependencies, including `marked` and `@types/marked`.

3.  **Set Up Environment Variables:**
    Create a `.env` file in the root of your project (`cybersafe_therapy/`) and add your Google Gemini API Key:

    ```
    VITE_GEMINI_API_KEY=your_google_gemini_api_key_here
    ```

    You can obtain a Gemini API key from the [Google AI Studio](https://aistudio.google.com/app/apikey).

4.  **Run the Development Server:**

    ```bash
    npm run dev
    ```

    This will start the development server, usually at `http://localhost:5173`.

5.  **Build for Production (Optional):**
    To create a production-ready build:
    ```bash
    npm run build
    ```
    The compiled files will be located in the `dist` directory.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please feel free to:

1.  **Fork** the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'feat: Add new feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a **Pull Request**.

---

## ℹ️ About the Developer

CyberSafe was passionately built by **GiftinTech (Gift Egbonyi)**, a dedicated **AI Frontend Developer**. GiftinTech is always happy to connect, collaborate, and discuss exciting projects with fellow enthusiasts and professionals!

You can find more about their work and connect through:

- **Linktree:** [https://linktr.ee/GiftinTech](https://linktr.ee/GiftinTech)
- **LinkedIn:** [https://www.linkedin.com/in/gift-egbonyi](https://www.linkedin.com/in/gift-egbonyi)
- **Portfolio:** [https://giftegbonyi.vercel.app/](https://giftegbonyi.vercel.app/)

---

[![License: Custom](https://img.shields.io/badge/license-custom-blue.svg)](LICENSE)

---
