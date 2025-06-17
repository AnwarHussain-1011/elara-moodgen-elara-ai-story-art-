# elara-moodgen-elara-ai-story-art-
Elara: Mood-Based Story and Image Generator using LLM and Stable Diffusion.

# 🌌 Elara: Mood-Based Story and Image Generator using LLM and Stable Diffusion

Elara is a multimodal generative AI system that combines the power of large language models and text-to-image diffusion models to create immersive storytelling experiences. With just a short prompt and a mood selection, Elara generates both a short story and a matching image—bringing creativity to life in both words and visuals.

---

## ✨ Demo Output

> **Prompt:** *"A robot exploring an abandoned city"*  
> **Mood:** *Sci-Fi*  
> 📝 **Story:**  
> *In a forgotten metropolis under twin moons, the robot wandered alone.  
> Each building whispered tales of vanished humans.  
> It paused beside a rusted playground, scanning for signs of life.  
> Only silence answered, echoing in steel and shadow.  
> Still, it marched on—hope flickering in its synthetic heart.*

> 🖼️ **Image:** (Generated using Stable Diffusion)

---

## 🚀 Features

- 🎭 **Mood-based story generation** using LLaMA3 70B via Groq API
- 🎨 **Image synthesis** from user prompt using Stable Diffusion v1.5
- 🧠 Powered by multimodal AI: LLM + Diffusion
- 🖥️ Interactive frontend built with Gradio
- 🔐 Secure API key management in Google Colab

---

## 🧰 Tools & Technologies

| Component              | Technology Used                                     |
|------------------------|-----------------------------------------------------|
| Language Model         | [LLaMA3 70B](https://console.groq.com/) via Groq API|
| Image Generation       | [Stable Diffusion v1.5](https://huggingface.co/runwayml/stable-diffusion-v1-5) using 🤗 Diffusers |
| Frontend UI            | [Gradio](https://www.gradio.app/) (Python)          |
| Platform               | Google Colab (for prototyping and testing)          |
| API Key Handling       | `google.colab.userdata`                             |
| Programming Language   | Python 3.11                                          |

---

## 🛠️ System Workflow

```text
User Prompt + Mood 
         │
         ▼
     [LLM: LLaMA3]
     Story Generation
         │
         ├─────────────┐
         ▼             ▼
 Story Output     [Stable Diffusion]
                    Image Generation
                         │
                         ▼
               📺 Gradio UI (Side-by-Side View)
---
## 🎮 How It Works

Prompt Input: User enters a short phrase (e.g., "a cat flying a spaceship").

Mood Selection: Choose from Fantasy, Funny, Sad, Sci-Fi, Adventure, or Romantic.

Story Generation: LLaMA3 via Groq API creates a 4–6 line story matching the mood.

Image Generation: Stable Diffusion v1.5 synthesizes an image from the prompt.

Result Display: Story and image are shown side by side in the Gradio web app.

---


### 📦 Installation & Usage:

📌 Note: This project is built and tested in Google Colab.

🔹 Open in Google Colab

🔹 Or Clone Locally
bash

git clone https://github.com/your-username/elara-moodgen.git
cd elara-moodgen
pip install -r requirements.txt
python app.py

⚠️ Before running, add your API keys securely (Groq and HuggingFace).



📈 System Architecture & Functions
Function	Description
Prompt Input	User types a short creative idea
Mood Selection	Mood dropdown (Fantasy, Sad, Funny, Sci-Fi, etc.)
Story Generator	LLaMA3 (Groq API) generates a story based on mood
Image Generator	Stable Diffusion (Hugging Face) creates image from the same prompt
UI Display	Real-time display via Gradio Blocks UI

🧪 Development & Testing
🧪 Tested various creative prompts and moods

🐛 Debugged latency issues using Google Colab GPU runtime

🎛️ Tuned Stable Diffusion parameters: guidance scale, inference steps

🧼 UI optimized for clean layout and real-time display

📚 References
	Groq API: https://console.groq.com/
	Hugging Face Diffusers: https://huggingface.co/docs/diffusers
	Stable Diffusion v1.5: https://huggingface.co/runwayml/stable-diffusion-v1-5
	Gradio: https://www.gradio.app/



📍 Project Status
✅ MVP Completed
✅ Integrated LLM and Diffusion
✅ Working Gradio UI
🧩 Future Improvements:

 Add image-to-story mode

 Extend moods or allow custom tone

 Deploy as standalone web app (Streamlit, HuggingFace Spaces)

📬 Contact
Anwar Hussain Sofi
Generative AI Research | Softech computing Lab, NTOU
📧 Email: [sofianwar2001@gmail.com]
🔗 GitHub: [github.com/Anwar1011/elara-moodgen]

📝 License
This project is licensed under the MIT License.



