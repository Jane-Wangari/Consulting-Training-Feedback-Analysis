# EDAS Consulting-Training-Feedback-Analysis
Insights from a google form response for trainees who took part in a CV and Interview training offered by EDAS Consulting.

# OVERVIEW
EDAS Consulting is a Consulting firm that offers Human Resources services such as Training, Human Resource Consultancy, Advisory and all Labour Relations services related to aspects of employment. Data to gauge feedback from the trainer’s experience during the training was collected between 28/08/2023 at 9.12.20 am and 31/08/2023 at 10.06.01 p.m following a training conducted by two of the firm trainers on the following topics; 

a)	CV writing and Cover Letter writing. 
b)	Interview Preparation and Personal goals.

# OBJECTIVES
After sharing a Google response form to the trainees 47 responses were received. Several questions were outlined in the response form to answer the intended objectives on how effective the training program was. The following were the objectives to help gauge different aspects of the training, provide actionable insights and related recommendations:

## A: OVERALL EVALUTION:
I)	Assessing the Clarity of the training objectives as outlined in the training Curriculum. Evaluating the responses to understand if the trainees understood of what the training aimed to achieve by determining whether the training objectives provided were clearly defined and communicated effectively to the trainees.

II)	Evaluating the responses to gauge the level of participation and interaction during the training sessions through identifying the extent to which they were engaged in activities, questions and discussions.

III)	To assess whether the trainees found the content provide applicable to career needs and whether they met the trainees’ expectations.

IV)	Determining to what extent the training would be beneficial to the trainees in their job search and career advancement based on the knowledge and skills gained.

V)	Measuring to what extent the training objectives were met – Assessing trainees’ perception of their own progress to achieve the targeted learning outcomes.

VI)	Pinpointing Major suggestions, feedback, trainees’ overall satisfaction according to expectations and recommendations as provided by the trainees to enhance future training sessions.

VII)	Evaluating trainers on their mode of delivery, engagement and effectiveness in meeting the needs of the trainees.

# DATA SOURCING
The data set used for this Analysis was sourced from a Google response form shared among the trainees. The responses were taken between 28/08/2023 at 9.12.20 am and 31/08/2023 at 10.06.01 p.m. The dataset had 47 rows and 27 columns.
# DATA CLEANING
Tools used for data cleaning and preparation:
### 1.	Microsoft Excel
In MS Excel, I checked the data for misspellings, duplicates and Null values. 
Deleted the Timestamp column because it was irrelevant in this analysis.
Separated the data into two csv files; one including the overall training evaluation feedback and the other the feedback based on the trainers.
On the Trainers evaluation Sheet, combined the responses from the two trainers to share common columns.

### 2.	Microsoft Power BI
Loaded the datasets from both csv files into Microsoft Power BI and transformed the data in the power query
#### a)	Overall Evaluation dataset
Renamed the columns as follows;
1.	Indicate your level of agreement with the following statements [The objectives of the training were clearly defined] -Objectives Clearly defined
2.	Indicate your level of agreement with the following statements [Participation and interaction were encouraged] -Participation & Interaction.
3.	Indicate your level of agreement with the following statements [The topics covered were relevant to me] -Topic Relevance
4.	Indicate your level of agreement with the following statements [The content was organized and easy to follow] -Content Organization
5.	Indicate your level of agreement with the following statements [This training experience will be useful in my job search/settling] – Usefulness in Job Search
6.	Indicate your level of agreement with the following statements [The training objectives were met] – Training Objectives met
7.	What did you like most about the training? -Outstanding things
8.	What aspects of the training could be improved? - Improvements
9.	What other trainings would you like to have in the future? – Future trainings
10.	Any other comment (optional) -Other Comments

#### b)	Trainers Evaluation dataset
1.	Trainer being evaluated -Trainer
2.	Indicate your level of agreement with the following statements [Instructor was an effective trainer] -Effectiveness
3.	Indicate your level of agreement with the following statements [Presentations were clear and organized] -Clarity and Organization
4.	Indicate your level of agreement with the following statements [Instructor stimulated student interest] – Simulating Interests
5.	Indicate your level of agreement with the following statements [Instructor effectively used time during class periods] -Time effectiveness
6.	Indicate your level of agreement with the following statements [The trainer was knowledgeable about the topic] - Knowledgeable
7.	Indicate your level of agreement with the following statements [The trainer was well prepared] - Prepared
8.	Indicate your level of agreement with the following statements [It was easy was it to remain engaged throughout each part of training] – Learner’s Engagement
- On the Trainer column replace Silas Magawi (CV writing & Cover Letter Writing) and Paula Rogito (Interview Preparation & Setting personal goals) with Silas and Paul respectively.

# ANALYSIS
#### a)	Overall Evaluation dataset
- Create a measure of Total Responses.
- Create a number card to show Total Responses.
- Create a column clustered bar chart to show clarity of the training objectives as outlined in the training curriculum out of the total responses.
- Create a clustered bar chart to show the trainees response on how they were encouraged to participate and interact during the training.
- Create a column bar chart to show trainees response on the effectiveness of implementation of the training objectives.
- Create a column bar chart to show trainees evaluation on the relevance of the topics offered during the training.
- Create a column clustered bar chart to analyze the trainee’s evaluation based on the organization of the training content.
- Create a Word Cloud chart to show any aspects improvements that could be improved to make it more effective.
- Create a Word Cloud chart to show any future trainings the trainees would like to be part of.
- Create a Word Cloud chart to show other comments from the trainees.

#### c)	Trainers Evaluation dataset
- Create a measure of Total Responses
- Create a slicer for the trainers.
- Create a pie chart to analyze the preparedness of the trainers.
- Create a clustered bar chart to analyze effectiveness of the trainers in simulating the interests and engaging learners.
- Create a clustered column bar chart to analyze the trainer’s effectiveness and their ability to utilize time effectively.
- Create a donut chart to analyze feedback responses of the trainer’s knowledge of the training content.
- Create a clustered bar chart to analyze the clarity and organization of the trainers’ presentations during the training.

# VISUALIZATION, ANALYSIS AND RECOMMENDATIONS
## 1.	Objectives Clearly defined;
![Screenshot 2023-09-15 125104]
