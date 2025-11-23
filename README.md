<p align="center">
  <img src="assets/banner.png" width="100%">
</p>

# GemmaX_ChatCore
A multimodal AI chat system built using **Gemma 3 models**, supporting:
- Text chat  
- Vision analysis  
- Local JAX inference  
- Function calling
  
## 1. Project Features
- **Cloud inference** using Google GenAI SDK  
- **Image + text multimodal inference**  
- **Local Gemma inference** using KerasHub + JAX  
- **Multi-turn chat** with conversation history  
- **Function calling** (datetime, currency converter)  
- **Formatted response display**  

---

## 2. Folder Structure

```
GemmaX-ChatCore/
│
├── GemmaX_ChatCore.ipynb      # Main notebook
├── assets/                    # Image files for multimodal demos
└── README.md
```

---

## 3. API Key Setup
Insert your own key inside the notebook:
```python
client = genai.Client(api_key="YOUR_API_KEY_HERE")
```
---
## 4. Usage
- **Open the notebook**
- **Run the setup cells**
- **Choose cloud or local inference**
- **Test multimodal image analysis**
- **Run the chat system**
- **Try the function-calling examples**


---
## 5. Notes

- **This project demonstrates a full multimodal pipeline using Gemma 3.**
- **Identical versions of this project are maintained on two GitHub profiles for portfolio visibility.**

---
## 6. Authors
- **Jibitesh Kumar Mishra**
- **Ankita Singh**
