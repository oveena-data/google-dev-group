# Build With AI 2025

![image](https://github.com/user-attachments/assets/2a7d1007-89bb-46e6-aa91-f0ecde5a0807)


## CareerMatch AI - A Job Seeker Assistant App
A real-time resume analysis app deployed on Google Cloud Run for intelligent job recommendations and resume auditing.

---

## How to Build:

1. Getting Started:
- The application deployed to Google Cloud Run uses Gradio for the front end interface which handles the interaction with Vertex AI.
- Features include resume analysis, similarity scoring, and personalized job recommendations.
![image](https://github.com/user-attachments/assets/f7df5d5f-de34-49de-b17a-47eb1c8a01ab)

2. Explored Vertex AI in Google Cloud Console

![image](https://github.com/user-attachments/assets/aa4e6722-48ed-48cd-bfb1-76cfef2e9b4c)

3. Prompting Gemini 2.0
   -  Selected the gemini-2.0-flash-lite-001 model.
   -  Adjusted advanced prompt settings to configure model performance (Temperature, Output Token Limit and Top P, specifically)
   -  Safety filters to prevent generation of harmful content.
   
4. Saved the prompt
![image](https://github.com/user-attachments/assets/b323b109-47d4-4430-ba5c-ae37f281ffd7)

5. One click deployment of prompt as a web application to Google Cloud Run

- When we add a prompt to Vertex AI, it automatically generates a code snippet that can be used to call the model programmatically. We can also deploy the prompt as a web application directly from within Vertex AI.
- Vertex AI uses gradio to create a web application for the prompt and deploy it to Google Cloud Run. Click on Deploy as app to deploy the application to Google Cloud Run.

<img width="1120" alt="Screenshot 2025-05-07 191256" src="https://github.com/user-attachments/assets/494a1e88-8bc8-454a-88ed-8f40687a8d7b" />

6. Deploy a python Job Seeker Assistant App on Cloud Run with Gemini and Streamlit from scratch
![image](https://github.com/user-attachments/assets/a55e721d-5a6d-4cac-9e0e-ce854460acd7)

7. Analysed code to deploy.
![image](https://github.com/user-attachments/assets/96a30812-a27c-4336-9a32-1b99bae0ae78)

8. Use Cloud Shell Machine to clone code into the cloud shell environment.

![image](https://github.com/user-attachments/assets/fc9c222c-ee6e-4efc-8ba5-255cf64f6530)

![image](https://github.com/user-attachments/assets/802839ed-4d63-41d5-a9c5-3b93be455f56)

- The process will enable Cloud Run APIs on the project, I have selected `us-centrall` for the region.

9. The process will build a Docker image for the application

- This is then uploaded into Artifact Registry and deployed on GCR service.

10. Success!

![image](https://github.com/user-attachments/assets/40096092-685a-4847-867a-055d8ef5d578)

11. Upload a Sample Resume and job details

- The application I submitted provided a 75% match score, indicating that the resume aligns well with the job requiremnets.
![image](https://github.com/user-attachments/assets/69e5d89f-215a-4b7f-951d-4fa0c99201bd)

- It also suggests improvements to the resume, such as adding more details about past experiences and skills.
- If the match is above 50%, the application will automatically generate a cover letter for the job posting, which can be downloaded by clicking `Download Cover Letter` button.

![image](https://github.com/user-attachments/assets/d7c47f12-ae61-4f6d-a2b3-d3534d218d91)

### Key Takeaways:
- Particiapted in hands-on workshop to build and deploy the app using Streamlit and Google Cloud Run.
- Fresh insights into how Google Gemini is reshaping career search experience in Australia.


  






