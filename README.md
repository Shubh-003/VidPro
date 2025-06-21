# 🎥 **AI-Powered Video Processor**

An intelligent Streamlit app that analyzes videos to extract **textual and visual information**, then generates structured **Word reports** and **Draw.io diagrams** using **Gemini AI models**. Ideal for summarizing educational, training, or technical videos into meaningful documentation.

---

## ✨ **Features**

- 📼 Upload videos (MP4 format)
- 🧠 Extract:
  - Textual narration and spoken content
  - Visual insights and scene analysis
- 📝 Generate:
  - Structured **Word document** reports using `gemini-1.5-pro-latest`
- 🔄 Auto-create **Draw.io diagrams** using `gemini-1.5-flash-002`
- 📥 Download generated files (Word, Draw.io XML)
- 🎛️ Simple and clean **Streamlit UI**

---

## 🧰 **Tech Stack**

| Component        | Technology / Tool               |
|------------------|----------------------------------|
| UI               | Streamlit                        |
| AI Models        | Google Gemini (Pro + Flash)      |
| Text Extraction  | Gemini + Transcription (optional Whisper/ASR) |
| Visual Processing| Gemini-based scene understanding |
| Report Output    | python-docx                      |
| Diagram Output   | Draw.io (XML)                    |
| Deployment       | Streamlit Cloud / Local          |

---


---

## 🚀 **Getting Started**

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/video-processor.git
cd video-processor
```
### 2️⃣ Create virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate
```
### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the app
```bash
streamlit run app.py
```
## Sample Output
<img src="output.jpg" alt="output-img" />



## 💡 Future Improvements
- 🎙️ Add speech-to-text transcription using Whisper
- 📌 Scene timeline with timestamps
- 🔎 OCR from video frames (for text on-screen)
- 🔁 Export diagrams directly as PNG/SVG
- 🧠 Use vision models like Gemini Flash for better scene detection

