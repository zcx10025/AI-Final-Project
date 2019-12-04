# Project Description
   In my project, I will use a data set of resumes to train a model that can be used for automated recruitment. At the same time, I will also extract some of the most common words from these resumes to find out the main interests of these job seekers. I know that a lot of people have researched this data set and got a lot of interesting results. So I will do something different. For my problem, I will mainly use deep learning algorithms. Of course I will also use some conventional machine learning algorithms to compare. The reason why deep learning is chosen for NLP is that deep learning has three advantages in dealing with NLP problems compared to traditional machine learning algorithms. The first is its ability to express. With deep learning, data in different formats such as text and images can be represented as real-value vectors. This allows us to perform information processing across multiple modes. The second is its trainability. Deep learning allows us to perform end-to-end training to solve problems quickly and with high quality. Because the information entered in the neural network is uniformly "encoded". The third is its scalability. Deep learning can predict untrained data very well. 

# Data set 
   I find this data set on “kaggle”, which is available here. I will use the one called “Sheet_2.csv”. The data set I use contains 125 rows and three columns. First column is the ID of the resumes, from 1 to 125. Second column “class” is the label, and third column is the resume. The resumes are queried from “Indeed.com” with keyword “data scientist”, location “Vermont”. In “class” column, there are two types of value which are “flagged” and “not flagged”. If a resume is “not flagged”, it means that the applicant can submit a modified resume version at a later date. If it is “flagged”, it means that the applicant is invited to interview.
