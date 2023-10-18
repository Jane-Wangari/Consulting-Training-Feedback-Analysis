# EDAS Consulting-Training-Feedback-Analysis
Insights from a google form response for trainees who took part in a CV and Interview training offered by EDAS Consulting.

![Screenshot 2023-09-20 114832](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/24ea861e-940a-4910-a288-18f6854fb522)
![Screenshot 2023-09-20 114809](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/ce3d9b74-734c-4fa9-adee-7032032de9fe)
![Screenshot 2023-09-20 114617](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/eb7fcf59-250e-4941-9a2e-120b90dc0476)

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
![Screenshot 2023-09-15 125104](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/bbf764bb-8985-400d-b849-750cf2275500)

From the analysis and findings, majority of respondents strongly agree that the objectives of 
the training were clearly defined. With a high level of respondents agreeing to this, it is a 
strong indicator that the outlined training objectives were effectively communicated and 
understood by the trainees.

However, from the analysis there was a strong disagreement that cannot be dismissed as it 
indicates that at least one respondent perceived a lack of clarity in the outlined objectives. 
This feedback can be considered in addressing potential issues and improvements to ensure 
the objectives are well understood and aligned to the expected outcomes.
Overall, according to the analysis of the responses the training objectives were effectively 
communicated and the trainees perceived them to be clear. Efforts should be made to
maintain and enhance clarity to accommodate different perspectives.

## 2. Participation and Interaction
![Screenshot 2023-09-15 141428](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/67cdcc99-2955-4c53-b73e-7b5e3ae3ce89)

From the analysis, there was a high level of satisfaction among the trainees regarding how 
they were encouraged to participate and interact during the training. The high strong 
agreement response indicates many of the trainees resonate well with the participation and 
interaction. The strong disagreement indicates that despite majority positive perceptions,
there may be individuals who found the encouragement to interact and participate during the
training not effective enough. More feedback and further analysis would be necessary to 
understand the reasons behind such dissenting views. On the other hand, the neutral response 
may be used to identify areas of improvement.

## 3. Evaluation on implementation of Training Objectives.
![Screenshot 2023-09-15 141521](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/7ec15640-cb69-4931-bed8-099e52442d5b)

The analysis reveals that the trainee was impactful to the trainees with a majority strongly 
agreeing to the effective implementation of the training objectives. This shows that the 
strategies employed in delivering and executing the training objectives were well received 
and successful in achieving expected outcomes. However, a minor dissenting opinion on 
strongly disagreeing and a neutral feedback on the implementation of the training objectives 
indicate a strong need for ongoing feedback and potential improvements to meet the diverse 
need of all trainees.

## 4. Evaluation of Topics relevance
![Screenshot 2023-09-15 141617](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/c8eab5ad-b8be-4f88-927c-77649d318169)

The analysis on the relevance of topics undertaken during the training reveals a great 
consensus among the trainees which is a collective agreement that the content aligned with 
the trainees needs and expectations. A single dissenting view, suggests that at least one of the 
trainees found that the topics were less relevant to their expectation which calls for periodic 
evaluation and adjustment of the training topics to ensure the cater for all trainees.

## 5. Evaluation on the Organization of the training content
![Screenshot 2023-09-15 141734](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/4b2a3391-b196-430f-8416-9bf69040ea62)

The analysis reveals a compelling consensus among the trainees with majority strongly 
agreeing which is a overwhelming positive feedback that indicates that the training was 
successful in delivering content that is logically arranged and thoughtfully structured to meet 
the trainees needs. A single strongly disagreeing suggests that there was at least one trainee 
who did not find the training content organization suitable for their needs. This perspective 
should be used for continuous improvement.

## 6. Trainer well prepared
![Screenshot 2023-09-15 152337](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/f88b2a2c-96f1-45ff-960a-99ee09043dcc)

From the analysis, out of all the responses made to evaluate the trainers 77% of the trainees 
strongly agreed that the trainers were well prepared, 22% agreed the trainers were prepared 
while 1% were neutral. For individual trainers the responses were as follows;

- Paul: Strongly Agree -81%, Agree -19%
- Silas: Strongly Agree -72%, Agree -26%, Neutral -1%
  
To maximize on the effectiveness of the training the trainers need to be well prepared while 
ensuring consistency in their preparedness at all times. Regular feedback need to be taken to 
capture the needs of the trainees.

## 7. Trainer simulates interests and engages learners
![Screenshot 2023-09-15 152832](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/e3ca29ed-d248-44e0-bcda-055214288c45)

From the analysis, the trainees were in agreement that the trainers simulated their interests in
what they were being trained on and they also felt engaged in the training throughout. 
However, there is a neutral response which indicates need for improvements to meet trainees 
expectations.

## 8. Trainer Effective and utilized time effectively
![Screenshot 2023-09-15 154520](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/30f5b680-477c-4e86-830e-f7cc1df51c9f)

From the analysis, most of the trainers agree that the trainers were effective and they utilized 
time effectively which is positive feedback to trainers. However, one neutral response 
indicates a contrary review based on experiences during the training which should be used to 
assess on the effectiveness and time utilization of the trainer for improvements.

## 9. The trainer was Knowledgeable
![Screenshot 2023-09-15 155550](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/678d71d6-1fe6-43fd-9821-378f6db2620d)

According to the analysis, there is a notably positive perception for the trainers to deliver 
based on their knowledge. The collective agreement signifies that the trainers are well 
endorsed for their competence and qualifications. To maximize on this, it is necessary to 
engage the trainees in ways they can better transfer their knowledge to ensure the training 
meets their expectations.

## 10. Trainer had clear and organized presentations
![Screenshot 2023-09-15 161103](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/d6ba4a8f-d0e4-44ec-8222-a0aca7ebe02e)

According to the analysis, the clarity and organization of the trainer’s presentation reveals a 
positive experience among the trainees. A high-level agreement indicates that the trainers
were prepared to deliver by sharing clear and organized presentations. However, the neutral 
and strong disagreement responses indicate a need for improvement and adjustment to meet 
all trainers needs. Also, to ensure the effectiveness of the training by ensuring it meets the 
expectations of the trainees while achieving the goal of the consultancy.

## 11. Open ended questions analysis
![Screenshot 2023-09-15 164343](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/9e7f6289-b6ba-4611-bb6c-6642de1a7d9d)
![Screenshot 2023-09-15 164439](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/bac2f9d6-46e1-4008-82dc-990e791f8584)
![Screenshot 2023-09-15 164508](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/26b57abd-829d-4c15-9d3c-6d14738b89cd)
![Screenshot 2023-09-15 164611](https://github.com/Jane-Wangari/Consulting-Training-Feedback-Analysis/assets/110452335/17e55034-c26e-4605-9288-67fe52870cb7)

Based on feedback about Outstanding things from the training; enough preparedness, 
interaction, knowledgeable, having feedback, flexibility, discussion and presentation which 
indicates the training was impactful.


Based on feedback about Future Trainings the following were recommended; CV writing
samples, cover letter training and project management.


Based on feedback on future improvements to the training the following were proposed;
Improve on presentation, internet, interview, communication and management.


Based on feedback on other comments from the trainees the following stood out; Thanks, 
appreciate, productive, interview sessions, interview training and mentorship. This was good 
feedback indicating trainees’ satisfaction and their need for other related trainings

