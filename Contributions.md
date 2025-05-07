# CareerMatch AI - A Job Seeker Assistant App
A real-time resume analysis app deployed on Google Cloud Run for intelligent job recommendations and resume auditing.

---

### Key Takeaways:
- Particiapted in hands-on workshop to build and deploy the app using Streamlit and Google Cloud Run.
- Fresh insights into how Google Gemini is reshaping career search experience in Australia.

# Key Activities
1. Getting Started:
- The application deployed to Google Cloud Run uses Gradio for the front end interface which handles the interaction with Vertex AI.
- Features include resume analysis, similarity scoring, and personalized job recommendations.
![image](https://github.com/user-attachments/assets/f7df5d5f-de34-49de-b17a-47eb1c8a01ab)

2. Explored Vertex AI in Google Cloud Console
![image](https://github.com/user-attachments/assets/aa4e6722-48ed-48cd-bfb1-76cfef2e9b4c)

3. Prompting Gemini 2.0
   -  Selected the gemini-2.0-flash-lite-001 model. Then, paste the following prompt in the Systems Instructions box:
''' You are a job seeker assistant. Your task is to analyze the resume and job details provided and give a score from 0 to 10 on how well the resume matches the job.
The score should be based on the following criteria:
1. Key skills that match.
2. Missing skills or qualifications.
3. Suggestions for improving the resume or get better qualifications to better match the job.
The score should be a number between 0 and 10, where 0 means little to no match and 10 means a perfect match.

Any questions irrelevant to matching the resume and job details should be replied to with - Sorry, I cannot help you with that, I am a job seeker assistant and I can only help you with matching resumes and job details.


