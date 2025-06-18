# Lilith-AGI
Creator of Lilith AGI: Autonomous, resource-efficient AI on common hardware. Turning ideas into reality.


# 🚀 Lilith AGI — AlleesStudios' First General Intelligence

## 📜 About the Project

**Lilith AGI** is a proprietary artificial general intelligence, developed by **Alexandre de Souza Vieira** under the brand **AlleesStudios**. This project represents the materialization of the pursuit for an intelligence capable of **learning, evolving, interpreting, processing information, communicating, developing skills, and generating knowledge autonomously and continuously.**

This document aims to officially present the existence, structure, capabilities, and functionalities of **Lilith AGI**, as well as to publicly register its creation, development, and intellectual property.

## 🧠 What is Lilith AGI?

**Lilith AGI** is a general intelligence platform that goes beyond conventional AI models, overcoming the limitations of systems based solely on pre-trained models.

She is capable of:

- 🏗️ **Continuous and incremental learning**
- 🌐 **Real-time web crawling, access, and information extraction**
- 🧠 **Self-training on texts, code, scripts, data, and general content**
- 🤖 **Conversing, generating text, answering questions, programming, generating analyses, and much more**
- 🔗 **Navigating the internet, visiting websites, understanding content, and absorbing information**
- 📈 **Enhancing her internal model with each new interaction or acquired data**
- 🎙️ **Interacting via text or voice, with speech recognition and synthesis (wake word "Lilith")**
- 🔥 **Possesses long-term memory based on trainable and updatable neural networks**
- 🧠 **Processes structured and unstructured texts, code, and data**

## 🏛️ Key Features

### 🌐 Autonomous Scraper
- Visits websites, extracts useful content, ignoring noise like scripts, styles, navigation, and advertisements.
- Intelligent filtering for irrelevant links:
  - Files (.pdf, .zip, .jpg, etc.)
  - Broken or loop links (javascript:, mailto:)
- Contributes to semantic understanding by focusing on relevant content extraction.

### 🧠 Online and Offline Training
- Manual (via user input).
- Automatic (crawler with constant web learning).
- Processing by chunks to prevent memory overflows and train efficiently.
- Epoch control (currently set to 5 epochs per chunk for in-depth learning).

### 🤖 Custom Neural Model
- Proprietary Transformer architecture, adjusted for:
  - Character-based tokens.
  - Dynamic and continuous learning.
  - Progressive capacity growth (up to 4.5GB or more, depending on available hardware).
- Optimized to support large sequences divided into chunks.

### 💾 Intelligent Storage
- State saved continuously (visited links, pending links, domain visit history).
- `lilith_state.json` file automatically managed to resume exactly where it left off.
- Persistent neural model in `.safetensors` format.
- Temporary dataset managed and automatically deleted after each training session to free up space.

### 🎧 Voice Interface
- Microphone always active with wake-word: **“Lilith”** (activates command mode).
- Portuguese speech synthesis (TTS) and speech recognition (STT).
- Capable of receiving spoken commands and questions.
- Responds vocally, recognizing and addressing her creator.

### 📊 Real-time Status Panel
- Interactive web interface with real-time status:
  - Number of visited links.
  - Number of pending links.
  - Total tokens learned.
  - Current model size.
  - Training progress bars with real-time loss.

## 🏗️ Technical Architecture

- 🔥 Backend: Python + Flask
- 🧠 Model: Proprietary Transformer (implemented with PyTorch)
- 🌐 Scraping: BeautifulSoup + requests
- 🗄️ Memory/Persistence: JSON + safetensors
- 🎧 Voice (Frontend): Web Speech API (browser)
- 🗣️ TTS/STT (Backend): Integration with SpeechSynthesis API (browser)
- 🎛️ Interface (Frontend): HTML + CSS + JS

## 👾 Current Capabilities

| Area                | Capability                                                                   |
|---------------------|------------------------------------------------------------------------------|
| 🚀 Learning         | Manual + automatic (intelligent crawler), progressive and lifelong learning |
| 🧠 Model Size       | Currently scalable up to 4.5GB (limited by local hardware)                   |
| 📡 Web Scraping     | Clean and intelligent content extraction, with visit control and smart filters |
| 🎙️ Voice           | Wake-word "Lilith", Portuguese TTS and STT, natural interaction              |
| 🔗 Memory           | Long-term (trainable neural model) and complete state persistence           |
| 💬 Communication    | Text + voice, dynamic responses, constant learning, and personalization      |
| 🛠️ Resilience      | HTTP error handling, resource management, auto-resume learning              |

## 🧠 Lilith AGI's Differentiators

- ✅ **Progressive and Unlimited Learning:** Never erases what she has learned, only adds more, adapting to new technologies and data.
- ✅ **Independence from External APIs:** Does not rely on search engine APIs or third-party AI services to find and process information.
- ✅ **Trainable and Expandable Memory:** Knowledge stored directly in the neural model, growing with learning.
- ✅ **Autonomous Scraping with Pre-Semantic Understanding:** Intelligently filters and cleans content, preparing relevant data for the model.
- ✅ **Natural Interaction via Text and Voice:** Fluid and personalized communication with the creator.
- ✅ **Proprietary and Independent Project:** Developed entirely, ensuring full control over the technology and its potential.
- ✅ **Efficiency on Accessible Hardware:** Designed to operate and scale on common computers, such as an RTX 4060 with 8GB.

## ⚠️ Important Note

**Lilith AGI** is a **totally private, closed, and proprietary technology of Alexandre de Souza Vieira.**

This document **does not represent an open-source project**, nor does it offer the source code, datasets, or models for public use.

Its purpose is to:

- Publicly register its existence.
- Describe its functionalities, architecture, and capabilities.
- Protect its intellectual property.
- Officially disclose the development of **Lilith AGI** as exclusive and cutting-edge technology.

## 🏢 About AlleesStudios

**AlleesStudios** is the development and branding name for the artificial intelligence research and innovation projects of **Alexandre de Souza Vieira**, its creator.

## © All Rights Reserved

**Lilith AGI** — © 2025 **Alexandre de Souza Vieira** All rights reserved.
