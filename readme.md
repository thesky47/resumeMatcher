How to Run the Code

To run the code for matching job descriptions with candidates' resumes based on similarity scores, follow these steps:

1. Prerequisites:

Ensure you have the following libraries installed:

transformers
pandas
torch
sklearn
You can install these libraries using pip:

Copy code
pip install transformers pandas torch scikit-learn
2. Data Preparation:

Prepare your data:

Create a CSV file containing job descriptions with the column 'job_description.'
Organize candidate CVs in a directory (e.g., 'test') where each CV is a PDF file.
3. Code Execution:

Replace the following placeholders in the code with your specific data:

'training_data.csv' with the path to your job descriptions CSV file.
'test' with the directory path containing candidate CVs (PDF files).
Modify the pre-trained model ('sentence-transformers/all-MiniLM-L6-v2') as needed.
Run the code by executing the Python script.

4. Output:

The code will generate a DataFrame with job titles and their top 5 matching candidates based on similarity scores. You can customize the output format as needed for your application.

5. Fine-tuning and Optimization:

Consider experimenting with different pre-trained models and tuning hyperparameters to improve the accuracy of matching. You can also implement feedback mechanisms to continuously enhance the matching process.

Feel free to reach out for further assistance or customization of the code to suit your specific requirements.