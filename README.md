# Dual-Pulse-AI - Autonomous Voice-Agent

A highly responsive, browser-native AI Cognitive Agent utilizing a futuristic dark-mode glassmorphic user interface. The platform securely establishes a direct, streaming connection to state-of-the-art LLMs while handling complex voice integration and conversational workflows completely inside the client environment.

## 🔗 Project Links
- **Live Hosted Application:** https://dual-pulse-ai.netlify.app/
- **GitHub Repository:** https://github.com/Abhiram569/Dual-Pulse-AI

---

## 🛠️ Core Implemented Features
*   **Dual Input Support:** Features a unified control area that gracefully accepts both manual keyboard text entry and interactive microphone capture.
*   **Speech-to-Text (STT) Conversion:** Integrates browser-native Web Speech API interfaces to capture raw user voice audio and cleanly convert it into text inputs before routing the prompt payload to the AI model.
*   **Dual Output Pipeline:** Renders high-fidelity, markdown-parsed response text dynamically on the UI console layout while simultaneously using a Text-to-Speech engine to read the answers aloud.
*   **Chronological Conversation Logging:** Includes a dedicated transcript exporter utility that logs the full session history and downloads a structured `.txt` file formatted with synchronized timestamps.

---

## 🚀 Creative Extension Features (Bonus Marks)
*   **Fluid "Barge-In" Interruptions:** Simulates natural, human-like conversations. Typing into the box or triggering the microphone while the agent is midway through a spoken response instantly cancels the speech synthesis loop (`speechSynthesis.cancel()`) to prioritize your new instruction.
*   **Dynamic Structural Sentiment Mood Shifts:** Parses structural keyword metrics inside incoming text strings to fluidly morph accent lighting, neon glow rings, and system tags across 6 interactive mood states (*Calm, Technical, Excited, Caution, Friendly, Thinking*).
*   **Context-Aware Smart Action Tags:** Evaluates markdown code blocks and hyperlinks to display immediate interactive button modules (*"Copy Code", "Extract Links", "Save Summary"*) inside the individual message panels.
*   **Audio Frequency Canvas Visualizer:** Combines live Web Audio API nodes with an HTML5 `<canvas>` stream to render reactive audio frequency waves during speech processing slots.
*   **Cross-Device Mobile Optimization:** Tailored layout boundaries with strict viewport scale-locking parameters stop mobile smartphone screens from executing broken automatic input-focus zooming bugs, paired with a mobile-resilient speech loop handler.
