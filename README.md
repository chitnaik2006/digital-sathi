# digital-sathi
Digital Sathi is a Rajasthani-first web app that helps first-time computer users learn basic PC operations, keyboard shortcuts, and essential Office tools like Word, Excel, and PowerPoint. With simple visuals, bilingual content, and a Gemini-powered voice assistant, it makes digital learning easy and accessible for everyone.

Problem: Many adults struggle with basic PC use due to lack of simple, local-language guides.

Solution: A simple, step-by-step PC learning website in Rajasthani, with visuals and a voice assistant, helping beginners learn keyboard, Word, Excel, and tasks easily.

Tech Stack with Justification:

| Layer                    | Technology                        | Purpose                            | Justification                                                                                    |
| ------------------------ | --------------------------------- | ---------------------------------- | ------------------------------------------------------------------------------------------------ |
| Frontend               | HTML, CSS, JavaScript             | User Interface                     | Simple, fast, and widely supported. Great for multilingual support (Rajasthani, Hindi, English). |
| Framework (optional)     | React.js (optional upgrade)       | Dynamic UI                         | For better scalability and smoother voice assistant integration.                                 |
| Backend                  | Python (Flask or Django)          | Server Logic & API handling        | Easy to integrate AI (Gemini API), process requests, and manage lessons.                         |
| Database                 | MySQL                             | Store user data, lessons, progress | Reliable, structured, open-source relational DB ideal for educational data.                      |
| Voice Assistant API      | Google Gemini API                 | Real-time voice queries & help     | Adds interactivity and instant learning help in native languages.                                |
| Hosting                  | AWS / Render / PythonAnywhere     | Deployment                         | Scalable, secure, and affordable for web hosting.                                                |
