# Hi, I'm Andrew 👋

<a href="https://andrewpang.dev/"><img src="https://andrewpang.dev/favicon.svg?v=9" width="16" height="16" align="absmiddle" alt="Andrew Pang portfolio" />&nbsp; Portfolio</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://www.linkedin.com/in/andrew-pang-hw/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" width="16" height="16" align="absmiddle" alt="LinkedIn" />&nbsp; LinkedIn</a>

**Role** — Singapore-based AI Engineer at **Adactive Asia**, building production-facing AI systems for real-world environments.  
**Focus** — Multilingual conversational AI, grounded retrieval, computer vision, and intelligent CMS products.  
**Delivery** — End-to-end application development, QA, observability, infrastructure, and deployment.

---

## 💻 Tech Stack

### Languages

![Languages](https://go-skill-icons.vercel.app/api/icons?i=python,javascript,html,css&titles=true&theme=dark)

### Application Development

![Application Development](https://go-skill-icons.vercel.app/api/icons?i=react,redux,nodejs,expressjs,flask,antdesign,socketio&titles=true&theme=dark&perline=6)

### AI, Data & Cloud

![AI, Data and Cloud](https://go-skill-icons.vercel.app/api/icons?i=chatgpt,azure,aws,mongodb,sqlite,pandas,numpy&titles=true&theme=dark&perline=6)

### Engineering & Operations

![Engineering and Operations](https://go-skill-icons.vercel.app/api/icons?i=docker,linux,nginx,systemd,git,github,gitlab,postman,selenium,vscode,pytest&titles=true&theme=dark&perline=6)

---

## 💼 Selected Work at Adactive Asia

> The source repositories are private and my contributions were made through my work GitHub account, so their activity is not reflected on this profile. Proprietary implementation details are omitted.

### 🗣️ [PDD Multilingual Kiosk Chatbot](https://andrewpang.dev/projects/pdd-chatbot)

Production conversational AI for public kiosks in a noisy, multilingual environment.

- Improved the end-to-end speech pipeline across language detection, transcription, translation, response generation, and TTS.
- Added Azure Speech and OpenAI Whisper fallback paths, strengthened session isolation, and reduced startup latency.
- Built grounded retrieval and deterministic fast paths for reliable answers from approved CMS data.
- Expanded multilingual and failure-mode QA, observability, deployment tooling, and production hardening.
- Raised tested linguistic accuracy from roughly **40% to over 90%**.

### 💬 [CMS Analytics Chatbot](https://andrewpang.dev/projects/cms-chatbot)

A closed-loop AI assistant embedded in AdSign CMS and grounded in approved, client-managed information.

- Built the first working chatbot prototype inside the existing proprietary CMS.
- Developed React interface components and integrated backend retrieval logic.
- Constrained responses to approved CMS data instead of open-web knowledge.
- Designed clear loading, empty-data, partial-response, and recoverable-failure states.
- Stress-tested edge cases, response latency, and heavier usage paths for production handoff.

### 🏷️ AdSign Smart Tags

An AI-powered CMS workflow that analyzes media and context to recommend relevant, reusable tags.

- Built a media-first tagging service for images and video, with CMS catalogue-aware suggestions and deterministic normalization.
- Integrated the React CMS through a server-side API proxy, keeping credentials out of the browser.
- Designed an authenticated asynchronous Flask API and worker with job polling, idempotency, readiness checks, and bounded processing.
- Added video-frame extraction and preview workflows, staged tag review, and clear handling of existing versus newly suggested tags.
- Hardened media validation, URL fetching, resource limits, queue behavior, and single-host AWS deployment.

---

## 🌱 Current Focus

- **Production AI** — reliable systems that work beyond controlled demos
- **Multimodal workflows** — speech, text, images, video, and spatial data
- **End-to-end delivery** — AI services, product interfaces, QA, observability, and deployment

---

💬 *Building practical AI systems that work beyond the demo.*  
📫 Reach me on [LinkedIn](https://www.linkedin.com/in/andrew-pang-hw/)
