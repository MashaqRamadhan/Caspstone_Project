# Caspstone_Project

1.) Title Project: Insight Extraction on Diabetes Dataset using IBM Granite LLM

2.) Project Overview:
    This project demonstrates the use of a large language model (LLM)—specifically IBM Granite 3.3 8B Instruct—via the Replicate API, to       analyze a medical dataset of diabetic patients. By integrating LangChain's Pandas Agent, the model is used to answer analytical            queries and visualize results without the need to write direct Python code.
    The analysis explores average values and comparisons between diabetic and non-diabetic patients, providing insights about age, glucose     levels, and BMI. The approach leverages AI to empower non-technical users to explore data intuitively.

3.) Raw Dataset Link: diabetes.csv, 768 rows, 9 columns, Fields: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome

4.) Insight & Findings: Average Age (diabetic patients): ~37.07 years, Average Glucose (diabetic patients): ~141.26,
    BMI Comparison: Diabetic patients have higher average BMI than non-diabetic,
    Visualized via bar chart using the Outcome field (1 = diabetic)

5.) AI-Supported Explanation: 
    IBM Granite model was used through the LangChain create_pandas_dataframe_agent feature, which allows users to ask natural language         questions directly against a pandas dataframe.
    Example prompts executed:
    "What is the average age of patients who have diabetes?",
    "What is the average Glucose level of patients with diabetes?",
    "Please make a bar chart comparing average BMI of diabetic vs non-diabetic patients using the 'Outcome' column",
