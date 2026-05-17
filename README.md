# 🎨 AI Image Generation Workflow using n8n

An automated **Text-to-Image AI Generation Workflow** built using **n8n**.  
This project takes a text prompt as input and generates AI-powered images using an Image Generation API such as **Stable Diffusion / SDXL**.

It demonstrates workflow automation, API integration, and AI-powered content generation in a scalable and reusable way.

---

## 🚀 Features

- 📝 Text Prompt → AI Image Generation
- ⚡ Fully Automated n8n Workflow
- 🔗 API-based AI Integration
- 🎯 Easy Prompt Customization
- ♻️ Reusable & Scalable Architecture
- 📦 JSON Workflow Support
- 🌐 Real-time API Response Handling

---

## 🛠️ Tech Stack

- **n8n**
- **Stable Diffusion / SDXL API**
- **HTTP Request Nodes**
- **JSON Data Handling**
- **Webhook Automation**

---

## 📌 Workflow Overview

The workflow follows these steps:

1. User provides a text prompt
2. n8n workflow captures the input
3. Prompt is sent to the AI Image Generation API
4. AI model generates an image
5. Output image URL / binary response is returned
6. Generated image can be stored, downloaded, or shared

---

## ⚙️ How It Works

### 🔹 Step 1: Input Prompt
The workflow starts by receiving a custom text prompt from the user.

Example:
```bash
"A futuristic cyberpunk city at night"
```

### 🔹 Step 2: API Request
n8n sends the prompt to an AI Image Generation API using HTTP Request nodes.

### 🔹 Step 3: Image Generation
The AI model processes the prompt and creates a high-quality image.

### 🔹 Step 4: Output Response
The generated image is returned as:
- Image URL
- Binary File
- JSON Response

---

## 📂 Project Structure

```bash
Image_Generation/
│
├── workflow.json
├── README.md
└── assets/
```

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2️⃣ Import Workflow into n8n

- Open n8n
- Click **Import Workflow**
- Upload the `workflow.json` file

### 3️⃣ Configure API Keys

Add your:
- Stable Diffusion API Key
- Hugging Face Token
- Or any SDXL-compatible API credentials

### 4️⃣ Run the Workflow

Execute the workflow and generate AI-powered images instantly.

---

## 📸 Use Cases

- AI Art Generation
- Content Creation
- Thumbnail Generation
- Social Media Assets
- Creative Design Automation
- Prompt Engineering Experiments

---

## 🌟 Future Improvements

- Multiple Image Variations
- Style Selection
- Negative Prompt Support
- Image Upscaling
- AI Image Editing
- Prompt History Storage

---

## 👨‍💻 Author

**Parshvi Goyal**

- GitHub: https://github.com/parshvigoyal

---

## 🔗 Repository Link

```bash
https://github.com/parshvigoyal/Image_Generation
```

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
