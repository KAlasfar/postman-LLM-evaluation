#  Postman LLM Evaluation Project

**Name:** Khadijah AlAsfar  
**Tools Used:** Postman, JavaScript test scripts, REST APIs  

---
This repository contains my Postman project for automated evaluation of LLM (Large Language Model) responses using Postman + API integration.

The project includes:
- A full Postman Collection with test scripts
- An Environment file containing variables used for API calls
- Automated evaluation logic using a separate judge LLM
- Multiple test prompts (bonus requirement)
- A demonstration video showing the testing process

---

## Project Structure

postman-LLM-evaluation/
│
├── LLM_Eval_Environment.json       # Environment variables (API keys, evaluation)
├── LLM_Evaluation_Collection.json  # Full collection with requests + scripts
│
└── demo.mp4                        # Demo video showing the evaluation running in Postman

---

##  How to Run the Project

1. Open **Postman**
2. Click **File → Import**
3. Import both files:
   - `LLM_Evaluation_Collection.json`
   - `LLM_Eval_Environment.json`
4. From the top right, select the imported **Environment**
5. Open the collection and click **Run Collection**
6. View:
   - LLM response generation
   - Judge model evaluation
   - Pass/Fail status for each test

---

##  Demonstration Video

The video file (`demo.mp4`) is included in this repository.  
Click it to watch the demonstration.

---

##  Features Implemented

- Correct API setup & authentication
- Automated evaluation using an external judge model
- Multiple prompts (bonus)
- Response validation logic
- Error handling
- Clean and organized project structure

---

##  Notes

- API keys inside the Environment file should be replaced with valid ones before running.
- The project demonstrates automation and evaluation logic inside Postman test scripts.
