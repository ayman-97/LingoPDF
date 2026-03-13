# 🎓 LingoPDF - AI-Powered PDF Translator & Reader

An intelligent, single-page web application designed to help students and researchers translate and understand academic PDF documents using the Groq Llama 3 API.

## ✨ Features Implemented

*   **Split-Screen Interface:** A modern, dark-themed layout allowing users to view the PDF and the AI translation side-by-side.
*   **Interactive PDF Rendering:** Native rendering using `pdf.js` with a transparent text layer that allows users to highlight text directly.
*   **Contextual Translation Selection:** Specify the academic domain (Medical, Engineering, Legal, etc.) for accurate terminology.
*   **AI Translation & Explanation:** Integration with Groq's high-speed API (`llama-3.3-70b-versatile`) for Arabic translations and conceptual breakdown.

## ⚙️ Configuration

To protect your API Key, this project uses a `config.js` file which is **ignored by Git**.

1. Copy `config.example.js` and rename it to `config.js`.
2. Open `config.js` and replace `'YOUR_GROQ_API_KEY_HERE'` with your actual [Groq API Key](https://console.groq.com/keys).
3. Save the file. The app will now load your key automatically.

## 🚀 How to Run Locally

### Using Python (Easiest)
1. Open your terminal and navigate to the project directory.
2. Run the simple server:
   ```bash
   python -m http.server 8080
   ```
3. Open **[http://localhost:8080](http://localhost:8080)** in your browser.

### Using VS Code
1. Install the **Live Server** extension.
2. Right-click `index.html` and select **Open with Live Server**.

## 🛠️ Requirements
- An active internet connection (to fetch `pdf.js` from CDN and connect to Groq API).
- A **Groq API Key** (already configured in the code for immediate use).

## 👨‍💻 Developed By
**Aymen N. Hamad**
