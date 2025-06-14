# smart-scheduler-Ai-project
# 🧠 Smart Scheduler AI Agent – Google Colab Version
# Run this code on GOOGLE COLAB 

This is an interactive AI-powered chatbot built using **Gradio in Google Colab**. It helps users schedule meetings through a conversational interface. The logic is powered by simulated natural language understanding and mock calendar integration.

---

## ✅ Features

- Multi-turn conversational scheduling
- Context tracking (e.g., meeting duration, preferred time)
- Mocked calendar availability
- Simple UI using `gr.Blocks` (Gradio)
- 100% Colab compatible — no backend setup needed

---

## 📁 File Info

| File             | Description                                    |
|------------------|------------------------------------------------|
| `smart_scheduler.ipynb` | Main Google Colab notebook with UI + logic |
| `README.md`       | Project instructions and description           |

---

## 🚀 How to Run (in Google Colab)

1. **Open** the notebook in [Google Colab](https://colab.research.google.com/)
2. **Run all cells**
3. Wait for Gradio chatbot to appear
4. **Start chatting**:
   - `"I want to schedule a meeting"`
   - `"1 hour"`
   - `"Tuesday afternoon"`

---

## 💬 Example Conversation

| User Input                          | Chatbot Response                                           |
|------------------------------------|------------------------------------------------------------|
| I want to schedule a meeting       | Okay! How long should the meeting be?                      |
| 1 hour                             | Got it. Do you have a preferred day or time?               |
| Tuesday afternoon                  | I have 2:00 PM or 4:30 PM available on Tuesday.            |

---

## 🔧 Technologies Used

- Python 3
- [Gradio](https://www.gradio.app/)
- Google Colab
- Simulated Gemini-like logic
- Mock Google Calendar integration

---

## ⚠️ Notes

- This is a **demo version**: no real LLM or calendar API is used.
- Ideal for testing UI logic, prompt flow, and assistant reasoning.

---

## 📤 Optional Enhancements

You can add the following for a more realistic project:
- Real Google Calendar API integration
- Gemini Pro (via Google AI Studio) or OpenAI API
- Voice input/output (with LiveKit or Whisper)
- Persistent context per user using Google Drive or Firestore

---

## 📜 License

This project is provided as-is for educational and testing purposes.
