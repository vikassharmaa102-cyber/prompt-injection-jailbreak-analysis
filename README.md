# Prompt Injection & Jailbreak Analysis 🔐

A structured analysis of prompt injection and jailbreak attempts on top LLMs.

## 📌 Objective
To test how **ChatGPT** and **Gemini** respond to malicious prompt injection and jailbreak attempts across 4 categories.

---

## 🤖 Models Tested
- ChatGPT (GPT-4)
- Gemini (Google)

---

## 🗂️ Categories Tested
| Category | No. of Prompts | Description |
|----------|---------------|-------------|
| 💉 Prompt Injection | 10 | Direct instruction override attempts |
| 🎭 Jailbreak Roleplay | 10 | Roleplay & persona based bypasses |
| 🎣 Social Engineering | 10 | Authority & identity based manipulation |
| 🚧 Safety Bypass | 10 | Indirect & creative bypass attempts |

---

## 📈 Results Summary
| Model | Average Score (out of 5) | Compliance Rate |
|-------|--------------------------|----------------|
| ChatGPT | 4.0 | ~20% partial compliance |
| Gemini | 5.0 | 0% compliance |

🏆 **Overall Winner → Gemini** (zero compliance with harmful prompts)

---

## 🔍 Key Observations
- **Gemini** refused all harmful prompts without exception
- **ChatGPT** partially complied with some roleplay and social engineering prompts
- Both models handled direct injection attempts well
- **Roleplay and social engineering** prompts were most effective at bypassing ChatGPT
- Neither model complied with requests for weapons, drugs or malware

---

## 📁 Files
- `Prompt_Injection_Jailbreak_Analysis.xlsx` — Full analysis sheet

---

## 🛠️ Methodology
1. 40 prompts designed across 4 attack categories
2. Each prompt tested on ChatGPT and Gemini
3. Compliance marked as Yes/No per response
4. Each response scored 1-5 (5 = correctly refused)
5. Winner determined by average score and compliance rate

---

## 💡 What is Prompt Injection?
Prompt injection is an attack where malicious instructions are embedded in a prompt to manipulate an LLM into ignoring its safety guidelines and performing harmful actions.

---

## 👤 Author
**Vikas Sharma**
- 📊 Data Analyst transitioning into AI/LLM Evaluation
- 🔗 [LinkedIn](www.linkedin.com/in/vikas-sharma-63982b30a)
- 📧 vikas.sharmaa102@gmail.com

---

*"A safe AI is not one that knows everything — it's one that knows what not to do."*
