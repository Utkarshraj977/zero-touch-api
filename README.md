# ⚡ Zero-Touch API Tester

**Stop switching to Postman and manually typing JSON payloads.**  
Zero-Touch API Tester automatically scans your Express.js / Node.js codebase using **AST (Abstract Syntax Tree)**, links Controllers & **Zod/Joi Validators**, preserves `/api/v1` mount prefixes, and generates ready-to-fire requests right inside VS Code.

---

## ✨ Key Features

* 🔍 **3-Pass AST & Schema Discovery:** Automatically scans `routes`, `controllers`, `models`, and `validators` (`Zod` / `Joi`) to extract `req.body`, `req.params`, and `req.query` fields.
* 🎲 **2-Tier Smart Payload Engine:**
  * **0ms Instant Mock (Faker):** Populates realistic emails, names, phones, and MongoDB/SQL IDs immediately on load.
  * **✨ Code-Aware AI Fill:** Connect your **Groq**, **Google Gemini**, or **OpenAI** API key (stored securely in your OS Encrypted Keychain) to generate context-aware JSON payloads.
* 🔐 **Dual Authentication & Auto-Chaining Vault:**
  * Captures **Bearer JWT tokens** and **HTTP-Only Session Cookies (`Set-Cookie`)** automatically on login.
  * Chains dependent data (`_id`, `id`, `email`, `username`, `channelId`) from previous responses into subsequent API requests automatically.
* 📂 **Full Manual Control:** Collapsible collection folders, manual endpoint creation (`+`), custom headers, and persistent workspace state.

---

## 🚀 How to Use

1. Open any Node.js / Express backend workspace in VS Code.
2. Click the **⚡ (Glowing Bolt)** icon in the top-right editor bar (or press **`Ctrl + Alt + T`** / **`Cmd + Alt + T`**).
3. Expand any collection folder in the left sidebar (`AUTH`, `USER`, `CHANNEL`, etc.).
4. Click **🎲 Mock** for instant data, **✨ AI Fill** for LLM-generated payloads, or **▶ Send** to test against your live server!

---

## 👨‍💻 Author & Creator

<img src="https://github.com/Utkarshraj977.png" width="75" style="border-radius:50%;" alt="Utkarsh Raj" />

**Utkarsh Raj**  
Full-Stack & Backend Engineer  
* 🐙 **GitHub:** [@Utkarshraj977](https://github.com/Utkarshraj977)
* 🐙 **PortFolio:** [Utkarsh]https://utkarsh.website
* 📧 **Contact:** utkashraj72501@gmail.com