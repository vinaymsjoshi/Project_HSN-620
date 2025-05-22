# Project_HSN-620
# Multi Dimensional Hiring Decision Analysis Model: 
Our model proposes a solution to the latest hiring problems where mis-information and fake certificates make it tough for recruiters to choose genuine candidates across a
large sample of candidates. It uses advanced techniques to give scores to each candidate based on their interview and transcript in accordance with the requirements.
Traditional hiring methods rely heavily on resumes, technical interviews, and gut feelings — often missing critical insights into a candidate’s emotional intelligence,
communication style, and real-time interaction behavior. This leads to:
❑ Poor cultural fit
❑ Weak communication alignment
❑ Underperformance despite technical competence
Comprehensive hiring model integrating:
❑ Emotional Analysis (via facial expressions, gaze tracking, and emotional fluctuations)
❑ Communication Analysis (including speech pace, confidence, eye contact, hesitation, and conciseness)
❑ Transcript Analysis (using NLP to evaluate role-fit, technical depth, emotional tone, and language clarity)

- **Emotional Score**:  It is a weighted average of scores of different emotional indexes like happiness score, Sadness score, fear score, neutralty score, etc
- **Overall Candidate Score**: Speech Speed Distribution, Confidence Score, Hesitation Score, Conciseness Score are the indexes used here in weighted form.
- **Wordcloud**: This is an AI generated image comprising of all the major keywords used in the transcript with its size showing the weightage. This is created for each of the candidate.
- **NER and Skill Extraction**: Sentiment Analysis through text processing of raw transcript data is done to extract NAmed Enttity Recognition and major skill expertise of each of the candidate
- **Communication Skill Score**: The main objective is to measure communication effectiveness using behavioral indicators like confidence, speech, eye movement, and hesitation.

The scores obtained in each of the metrics are very much dependent upon the weights we put in each subpart, that depends on how much that metrics essence is needed in the job
role for which the hiring is being made. Also, a cumulative score combing the four above metrics is also based on role, thereby creating a formula to get the final score according to the role fit.

Instead of keeping a threshold based on value we can keep it on the basis of requirement for the company and industry standards.


## Repository Structure
The project is organized as follows:
- **`README.md`**: This file, providing an overview of the project.
- **`Statement`**: This file provides an overview of each member's contribution.
- **`Data Folder`**: Contains the dataset or a link to it. 
- **Code**: Jupyter Notebooks.
- **`Slides Folder`**:
  - **Presentation Source File**: The source file for the presentation (PowerPoint).
  - **Presentation PDF**: The final PDF version of the presentation slides.

## License
This project is licensed under the MIT License.
