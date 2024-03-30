User and Admin Dashboards:
Create separate interfaces for administrators and users.
Admin Dashboard manages users, job listings, and analytics.
User Dashboard provides personalized job recommendations and displays search history.
Job Matching Algorithm:
Utilize NLP and machine learning.
Extract relevant information from job descriptions and user profiles.
Match job seekers with suitable opportunities.
Real-time Market Adaptability:
Monitor job market trends.
Adjust recommendation algorithms dynamically.
Stay relevant to changing dynamics.
Hiring Options:
Enable job posting, application management, and interview scheduling.
Streamline the hiring process for employers.
Security and Compliance:
Implement robust data security measures.
Ensure regulatory compliance for user privacy.
Regularly audit security practices. 🚀

#  Software Desgin
![1](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/bc125ea4-6043-4bc6-9f55-2df55c6f41b0)
<br>Architectural Design of the Project <br>

![2](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/f59183c5-2a29-4b08-8613-1439b33f110f)

![3](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/1a42c7cd-4d43-4687-a5b6-f5591dd27a4c)

#  Requirements 
##  Requirements

###  Hardware Requirements

- Webcam Enabled Device
- PC or Laptop
- Wifi Connection


###  Software Requirements

- Python Environment
- VS Code or PyCharm
- Xampp
- MySQL
- SMTP 
- ReactJS Environment
- Firebase
- WebRTC
- Socket
- Browser

##  Methodology
The methodology followed in this research involves the following steps: 
1. <b>Data Collection:</b> The first step was to collect data. For this, we have collected resumes from our classmates. We collected around 50 resumes. The collected data was stored in a database for further processing.
2. <b>Preprocessing:</b> The next step was to preprocess the collected data to extract useful information from it. The resumes were parsed to extract the candidate's name, contact details, education, work experience, skills, and certifications. 
3. <b>Feature Extraction:</b> The extracted data was then used to extract relevant features for each job posting and candidate. This was done using Natural Language Processing (NLP) techniques such as Named Entity Recognition (NER), Part-of-Speech (POS) tagging, and Sentiment Analysis. The features extracted for the job postings included the required skills, experience, and job description. The features extracted from the candidate's resume included the candidate's skills, experience, education, and certifications.
4. <b>Score Calculation:</b> Based on the extracted features, a score was calculated for each candidate. This was done using predefined criteria such as matching skills, years of experience, and education level. If the candidate's score exceeded a predefined threshold, the candidate was considered for the next stage. 
5. <b>Interview Scheduling:</b> An email was automatically sent to the candidate using the Smtplib library of Python. The email has the link and invitation to the virtual interview on the video conferencing platform. The interview schedule was automatically generated based on the candidate's availability and the availability of the interviewer. An admin can also manage interviews.
6. <b>Interview Taking:</b> The interview was conducted using the video conferencing platform, which Uses webRTC and Socket.io for API calls and establishing connections between peers and the interviewer could use the code editor to evaluate the candidate's programming skills in real time. For authentication, we are using Google OAuth. The code editor is made using the express framework and JDoodle API. Any code editor API can be used. One can also make its own code editor but that is out of the scope of this research paper, hence we have used already available options.
![4](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/2d6dc140-1592-4e7b-8108-9351cee1725a)
![5](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/d1be8c29-4366-41ea-8a7e-2d886eb30b88)
#  Components
1. [<b>Job Posting Website</b>](https://github.com/akshatprogrammer/jobDescription-BAAM)
2. [<b>BAAM Resume Parser</b>](https://github.com/akshatprogrammer/Resume-Analyser-Using-NLP)
3. [<b>BAAM Video Conferencing App</b>](https://github.com/akshatprogrammer/VideoConferencing)

# Some Views how actually looks 

![6](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/7964a633-942e-4dfe-9cc9-3251e9298b66)
![7](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/d6942cbe-bc18-47eb-8d70-c10c9fd2a220)
![8](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/35d8522b-bdd2-4b53-a51e-54e70ac0e941)
![9](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/8d9393c0-c9d7-4bd6-91f8-9e25eadd332c)
![10](https://github.com/akshatprogrammer/ML-Recruitment-System/assets/67745418/7e609af8-be07-4fa3-885a-8c69b67e26af)


