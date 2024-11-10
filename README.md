This project is an automated system for analyzing resumes and job vacancies using artificial intelligence. It extracts text from PDF resumes, analyzes job descriptions to identify key requirements and responsibilities, and compares resumes against these requirements to assess candidate suitability. If the candidate passes the first stage, the system generates tasks for the second stage of the interview. Responses to the tasks are evaluated, and the results are stored for further use. The project provides a user-friendly web interface, allowing users to upload documents, receive analysis results, and download reports in CSV format.

Key Features:

Extracts text from PDF resumes.
Analyzes job descriptions to identify key requirements and responsibilities.
Compares resumes with job requirements to determine suitability.
Generates tasks for the second stage of the interview.
Evaluates task performance and saves results in CSV.
Technologies Used:

OpenAI GPT-3.5 for text analysis and task generation.
PyPDF2 for extracting text from PDF files.
Gradio for creating the web interface.
Pandas for processing and saving data in CSV format.
