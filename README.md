# MCQ Generator
Live : https://mcqgenerator-j9hpbiuj6ps6z72nobpuwz.streamlit.app/
This is a Streamlit application that generates multiple-choice questions (MCQs) based on a given text or PDF file. The application uses the LangChain library to interact with the OpenAI API and generate the quiz questions.

## Features

- **File Upload**: Upload a PDF or text file with content for MCQ generation.  
- **MCQ Count**: Choose the number of MCQs (3 to 50).  
- **Subject Input**: Specify the subject for the MCQs.  
- **Complexity Level**: Set the difficulty, with "Simple" as the default.  
- **Generate MCQs**: Create MCQs based on the uploaded file and inputs.  
- **View MCQs**: Display questions, options, and answers in a table format.  

## Installation

1. **Clone the Repository:**

   git clone https://github.com/UttkarrshhPal/mcq_generator
   cd mcq_generator

2. **Install the Required Packages:**

   pip install -r requirements.txt

4. **Set Up Environment Variables:**

   Create a `.env` file in the root directory and add your OpenAI API key:

   OPENAI_API_KEY=your-openai-api-key

5. **Run the Application:**
6. 
   streamlit run app.py

## Usage

1. **Upload a File:** Use the file uploader to upload a PDF or TXT file.
2. **Set Parameters:** Enter the number of MCQs, subject, and tone of the questions.
3. **Generate MCQs:** Click on "Create MCQs" to generate the quiz.
4. **View Results:** The generated MCQs will be displayed in a table format.

## Project Structure

- `app.py`: Main entry point for the Streamlit application.
- `src/`: Contains utility functions and additional logic for MCQ generation.
- `response.json`: Template JSON file used to format the quiz output.
