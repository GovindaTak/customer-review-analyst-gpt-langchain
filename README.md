# customer-review-analyst-gpt-langchain
A LangChain-powered GenAI application for analyzing customer reviews using GPT-4o-mini. Automatically summarizes reviews, extracts sentiment, identifies key emotions, and generates structured email responses. Built using Python, LangChain, and OpenAI API.

```markdown
# 🧠 Customer Review Analyst – GenAI App using GPT-4o-mini + LangChain

This project demonstrates how to build an intelligent **review analysis system** using **LangChain**, **OpenAI GPT-4o-mini**, and **structured output parsers**. It processes customer reviews and produces meaningful summaries, identifies key sentiments and emotions, and generates personalized email responses automatically.

---

## 🎯 Objective

To analyze customer reviews using an LLM and return:
- Summary of the review (max 3 lines)
- Positives and negatives highlighted
- Overall sentiment (Positive/Negative/Neutral)
- 3 to 5 emotions extracted
- Personalized email response (thank you or apology)

---

## 🛠 Technologies Used

- Python 3.11+
- LangChain
- OpenAI GPT-4o-mini
- Pydantic
- Google Colab / Jupyter Notebook

---

## 🚀 Features

- ✅ Summarizes review in 3 lines
- ✅ Identifies and lists positives and negatives
- ✅ Predicts sentiment accurately
- ✅ Extracts emotional tone from reviews
- ✅ Auto-generates thank-you or apology emails
- ✅ Uses Pydantic for structured outputs
- ✅ Highly modular prompt-based design

---

## 🧾 How It Works

1. **User provides a review** as input
2. LangChain + OpenAI generates:
   - Structured summary
   - Positives/Negatives
   - Emotions
   - Email reply
3. Output is parsed with **PydanticOutputParser** into structured format

---

## 📁 Folder Structure

```

customer-review-analyst-gpt-langchain/
├── customer_review_analyst.ipynb     # Main notebook
├── README.md                         # This file

````

---

## 📸 Example Output

```text
Review: "The blender was noisy, struggled with hard food, and came late."

Summary: Customer is dissatisfied due to poor performance, noise, and late delivery.

Sentiment: Negative

Emotions: Frustration, Anger, Disappointment

Email:
Dear Customer, we sincerely apologize for the inconvenience... [full reply]
````

---

## 🧠 Skills Learned

✅ Prompt Engineering
✅ LangChain PromptTemplate and OutputParser
✅ LLM orchestration and structuring responses
✅ Pydantic-based response formatting
✅ Email generation logic based on tone/sentiment
✅ Building AI applications using GenAI best practices
✅ Error handling and improvements from model feedback

---

## 📌 Next Steps

* Add UI with Streamlit
* Support multi-language reviews
* Log all reviews to database
* Enable emotion tagging with emojis or categories

---

## 🙌 Author

**Govinda Tak**
Email: [govindatak19@gmail.com](mailto:govindatak19@gmail.com)
GitHub: [GovindaTak](https://github.com/GovindaTak)

---

## 📜 License

MIT License - free to use and modify with attribution.

```
