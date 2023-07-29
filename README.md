# AWS_SageMaker_Udemy_Course
Projects and Notebooks from Udemy Course [2023 Become AWS SageMaker ML Engineer in 30 Days + ChatGPT" By Ryan Ahmed](https://www.udemy.com/course/become-an-aws-machine-learning-engineer-in-30-days-new-2022/)

# Table of contents

- [00. Overview](#abstract-overview)
- [01. Section 1: AWS Essentials & Machine Learning](#sec1)
- [02. Section 2: Data Labeling and Data Wrangling](#sec2)
- [03. Section 3: Exploratory Data Analysis and Visualization](#sec3)
- [04. Section 4: Machine Learning Regression ](#sec4)
- [05. Section 5: Hyperparameters Optimization ](#sec5)
- [06. Section 6: Machine Learning Classification and Beyond ](#sec6)
- [07. Section 7: Prototyping AI/ML Models with AutoGluon ](#sec7)
- [08. Section 8: Machine Learning Workflow Automation with AWS Lambda ](#sec8)
- [09. Learning Outcomes](#sec9)


# Course Overview <a name="abstract-overview"></a>
The course extends beyond theory, providing hands-on opportunities to work with real-world datasets and cutting-edge technologies. 
We begin with a deep dive into exploratory data analysis and visualization using Pandas, Seaborn, and Matplotlib. I analyzed corporate employee information, performed statistical analysis, and mastered the art of data visualization. Embracing the potential of Amazon SageMaker Data Wrangler, I prepared, cleaned, and visualized data with ease, and explored feature engineering strategies and tools to enhance model performance.

In the realm of Machine Learning regression, we delved into simple and multiple linear regression, learning to build and deploy models using SageMaker Linear Learner algorithm and XG-Boost algorithm. Hyperparameter optimization strategies, such as grid search, randomized search, and Bayesian optimization, were explored. Moving into Machine Learning classification, we trained and compared various classifiers, including Logistic Regression, Support Vector Machine, K-Nearest Neighbors, and Random Forest Classifier.

The course also introduced prototyping of AI/ML models with AutoGluon, minimizing the need for extensive code writing. With Amazon SageMaker Autopilot and SageMaker Canvas, we also explored streamlined model training without writing code. The journey culminates with machine learning workflow automation using AWS Lambda, where we define, invoke, and monitor Lambda functions. Embracing the power of Boto3 SDK, we test Lambda functions and understand synchronous and asynchronous invocations.

By the end of this comprehensive course, I have acquired the skills, knowledge, and hands-on expertise to become an AWS SageMaker ML Engineer.





# Section 1 (Days 1 – 3): AWS Essentials & Machine Learning <a name="sec1"></a>

At the beginning, we got a solid foundation by diving into key AWS services like Simple Storage Service (S3), Elastic Compute Cloud (EC2), Identity and Access Management (IAM), and CloudWatch. Understanding these services was crucial for navigating the AWS world.

We also learned about the perks of cloud computing and the differences between regions and availability zones. Plus, we discovered what the AWS Free Tier Package has to offer, allowing us to explore AWS without spending a fortune.

Setting up our own AWS account, enabling Multi-Factor Authentication (MFA), and confidently using the AWS Management Console was a huge accomplishment.

On top of that, we grasped the fundamentals of Machine Learning! Being able to differentiate between Artificial Intelligence (AI), Machine Learning (ML), Data Science (DS), and Deep Learning (DL) was mind-blowing. And who would have thought that supervised, unsupervised, and reinforcement learning would be so interesting?

### Section 2 (Days 4 – 5): Data Labeling and Data Wrangling <a name="sec2"></a>

In this section, we got hands-on with data labeling and data wrangling using Amazon SageMaker GroundTruth. Labeling images and text was both fun and valuable for real-world applications.

Dealing with data sources, types, and distinguishing good and bad data was an essential skill that we can use in any ML project. And let's not forget the Json Lines formats and Manifest Files - they were a bit tricky at first, but we got the hang of them!

By defining image classification labeling jobs in SageMaker, we unleashed the true power of ML. Plus, learning about auto-labeling workflows and the differences between SageMaker GroundTruth and GroundTruth Plus opened up new possibilities for us.

### Section 3 (Days 6 – 10): Exploratory Data Analysis and Visualization <a name="sec3"></a>

Now it's time to dive into data analysis with Pandas! Analyzing corporate employee information in Jupyter Notebooks within AWS SageMaker Studio was like solving a puzzle.

Working with Pandas Dataframes, reading CSV data, and performing statistical analysis gave us the confidence to handle real-world datasets. It was amazing to manipulate Dataframes, select specific columns, and add/delete columns like a pro.

Visualizing data using Seaborn and Matplotlib was an eye-opener. We created a variety of plots, from line plots to histograms, and even scatter plots. The power of Amazon SageMaker Data Wrangler was unleashed, and we learned valuable feature engineering strategies and tools.

### Section 4 (Days 11 – 18): Machine Learning Regression <a name="sec4"></a>

Building our very first simple linear regression model in Scikit-Learn was a proud moment. But it didn't stop there - we explored all available built-in algorithms in SageMaker, and deploying our regression model using SageMaker Linear Learner algorithm made us feel like true ML engineers.

Understanding regression algorithms' KPIs like MAE, MSE, RMSE, MPE, R2, and adjusted R2 allowed us to evaluate our model's performance effectively. And launching training jobs and deploying endpoints without writing code was super cool!

### Section 5 (Days 19 – 20): Hyperparameters Optimization <a name="sec5"></a>

Fine-tuning our models with hyperparameters optimization strategies was a game-changer. We got to experiment with grid search, randomized search, and Bayesian optimization, making our models even better.

Understanding the bias-variance trade-off and L1 and L2 regularization techniques gave us the confidence to handle complex ML problems. Plus, performing hyperparameters optimization using Scikit-Learn library and SageMaker SDK made our models shine!

### Section 6 (Days 21 – 24): Machine Learning Classification and Beyond <a name="sec6"></a>

Now it's time to tackle classification models! Logistic Regression, Support Vector Machine, K-Nearest Neighbors, and Random Forest Classifier became our new challenges.

Diving into classifier models' KPIs like accuracy, precision, recall, F1-score, ROC, and AUC helped us understand the strengths of different models. And training XG-Boost and Linear Learner algorithms in SageMaker opened new possibilities.

And the bonus materials on leveraging ChatGPT and generative AI models as a programmer were a fantastic way to unleash our creativity.

### Section 7 (Days 25 – 28): Prototyping AI/ML Models with AutoGluon <a name="sec7"></a>

Enter AutoGluon! Prototyping AI/ML models using just a few lines of code was incredible. We leveraged AutoGluon to train multiple regression and classification models, giving us a taste of the power of automation.

Exploring Amazon SageMaker Autopilot and SageMaker Canvas allowed us to train multiple models without writing any code - it was like magic!

### Section 8 (Days 29 – 30): Machine Learning Workflow Automation with AWS Lambda <a name="sec8"></a>

The final section was all about AWS Lambda and its role in ML workflow automation. Defining and invoking lambda functions in AWS was empowering - we felt like ML automation masters.

We understood the anatomy of Lambda functions, configured test events, and monitored Lambda invocations in CloudWatch. Defining Lambda functions using Boto3 SDK and testing them using Eventbridge (CloudWatch Events) gave us hands-on experience.

## What I've Learned <a name="sec9"></a>

Throughout this course, I've gained valuable skills and knowledge, including:

- Building, Training, Testing, and Deploying Machine Learning Models in AWS
- Leveraging ChatGPT and GPT-4 to Automate Coding Tasks, Perform Code Debugging, Write Documentation, and Add New Features to My Code
- Defining and Performing Image and Text Labeling Jobs Using AWS SageMaker GroundTruth
- Preparing, Cleaning, and Visualizing Data Using AWS SageMaker Data Wrangler without Writing any Code
- Optimizing ML Model Hyperparameters using GridSearch, Bayesian & Random Search Optimization Techniques
- Mastering Key AWS Services such as Simple Storage Service (S3), Elastic Compute Cloud (EC2), Identity and Access Management (IAM), and CloudWatch

