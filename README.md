# 🌍 AI-Powered Travel Itinerary Builder

An intelligent travel planning engine developed by **Harshal**, built with **LangChain** and **Google Gemini**. This application takes user preferences (City, Duration, Style, Interests) and generates a structured, day-wise itinerary with budget-saving advice.

## 🚀 Key Features
- **Dynamic Prompting:** Uses LangChain `PromptTemplate` to transform unstructured user interests into professional travel plans.
- **Strict Format Enforcement:** Automatically organizes output into "Morning," "Afternoon," and "Evening" blocks.
- **Smart Pacing:** Adjusts activity density based on the user's "Relaxed" or "Busy" travel style.
- **Budget Intelligence:** Provides one practical, location-specific money-saving tip for every day.

## 🛠️ Tech Stack
- **Language:** Python
- **Orchestration:** LangChain (LCEL)
- **Model:** Google Gemini 1.5 Flash (via `langchain-google-genai`)
- **Environment:** Google Colab

## 📂 Project Structure
- `AI_Travel_Planner.ipynb`: The main notebook containing the LangChain logic and LLM chain.
- `requirements.txt`: List of dependencies required to run the project.
- `.gitignore`: Ensures environment variables and junk files aren't tracked.

## ⚙️ Installation & Usage

1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/Codebro-hash/AI-Travel-Planner.git](https://github.com/Codebro-hash/AI-Travel-Planner.git)

2. **Install Requirements:**
```bash
pip install -r requirements.txt

3. **Set Up API Key:**
Get your key from Google AI Studio.
In Google Colab, add it to the Secrets (🔑 icon) with the name GEMINI_API_KEY.

4. **Run the Notebook:**
 Open AI_Travel_Planner.ipynb in Colab and run all cells.

🛡️ Security & Best Practices (.gitignore)
To maintain a professional and secure repository, this project includes a .gitignore file that prevents the following from being uploaded:
Sensitive Data: Environment variables and API keys (via .env).
Junk Files: Temporary system files and Python cache (__pycache__).
Notebook Checkpoints: Local Jupyter/Colab saving points.

📄 License
This project is open-source and available under the MIT License.
Permission: You are free to use, copy, and modify this software.
Requirement: The above copyright notice must be included in all copies.
Disclaimer: THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
