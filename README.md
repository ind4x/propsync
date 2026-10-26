# PropSync CRM - Suite Métier Immobilière & Déploiement Autonome

PropSync is a high-craft commercial showcase and product portal for an enterprise-grade
real estate CRM designed for sovereign on-premise and private cloud deployment.

The platform eliminates recurring monthly SaaS subscriptions by delivering a perpetual-license,
self-hosted solution that guarantees total client data ownership, confidential transaction records,
and zero vendor lock-in.

---

## Key Features

- **Sovereign On-Premise Architecture:** Direct deployment onto client VPS or private bare-metal infrastructure via pre-packaged Docker Compose recipes.
- **Smart Real Estate Matching:** Algorithmic pairing between client acquisition criteria, budgets, and active property mandates.
- **Automated Contract & PDF Generation:** One-click compilation of lease agreements, sales mandates, and property inspection records.
- **Sovereign AI Integration:** Flexible native integration with modern LLM engines (Gemini, Groq, OpenAI) using the client's own API keys.
- **Integrated Lead Routing:** Automated inquiry capture and lead routing powered by direct asynchronous FormSubmit endpoints.

---

## Technical Architecture

```text
+---------------------------------------------------------------+
|                    PropSync Public Showcase                   |
|   index.html (Single-Page Responsive Production Portal)        |
+---------------------------------------------------------------+
            |                                       |
            v                                       v
+-------------------------------+       +-------------------------------+
|   UI/UX Design Engineering    |       |     Direct Lead Dispatch      |
|  - Plus Jakarta Sans + Mono   |       |  - Asynchronous FormSubmit    |
|  - Ambient Glow Lighting      |       |  - Direct Ingestion to Mail   |
|  - Responsive Glassmorphism   |       |  - Lead Modal Dialogs         |
+-------------------------------+       +-------------------------------+
                                    |
                                    v
+---------------------------------------------------------------+
|               Connected Enterprise Stack (Core)               |
|   - Backend: Spring Boot 3 / PostgreSQL (Enterprise Edition)  |
|   - Frontend: Angular 19 Dashboard (Tailwind CSS)             |
|   - Infrastructure: Docker Compose Multi-Service Recipe       |
+---------------------------------------------------------------+
```

---

## Deployment & Local Preview

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Any lightweight HTTP server (Python `http.server`, Node.js `serve`, or Nginx)

### Running Locally
From the repository root:

```bash
# Using Python built-in server
python3 -m http.server 8080
```

Open `http://localhost:8080` to interact with the responsive landing page, explore pricing tiers, and test lead capture modals.

---

## Technology Stack

- **Frontend:** Semantic HTML5, Vanilla JavaScript (ES6+), Modern CSS3 (CSS Variables, Flexbox, CSS Grid)
- **Design Typography:** Plus Jakarta Sans, JetBrains Mono
- **Asset Formats:** Scalable Vector Graphics (SVG)
- **Lead Transport:** FormSubmit REST API

---

## Author

- **Author:** Youssef Fellah ([ind4x_](https://github.com/ind4x))
- **Institution:** Mundiapolis University, Engineering Cycle
