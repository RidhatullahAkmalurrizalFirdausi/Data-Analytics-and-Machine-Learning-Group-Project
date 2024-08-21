## Introduction
We believe that the management of Human Resources (HR) plays a big factor in running a company. Promotion management is one of the important activities in a company.
With promotions, employees will work well and be responsible for their roles. It is possible for companies to experience difficulties in determining which employees will be promoted
because there is no standard value in determining deserving employees to be promoted. As executives, we are going to visualize and analyze the data referring to employees in order to
train a classification algorithm to predict which employees will be promoted and what kind of features are for their promotions and long-term dedication to the company. We will be using
HR analytics data set, which consists of a dependent variable, the promotion status, and independent variables such as the key performance indicator, training score, length of service,
age, colleague evaluation, education background, department, etc. HR management activities such as promotion management, job evaluation and personnel review, education, and training, contribute greatly to the growth and development of
the company. Based on the job evaluation of employees, we can assess what kind of employees are essential in the organization and predict which employees should be promoted. Therefore,
when task transfer is needed, systematic learning opportunities will be available for sufficient time to acquire job-related skills, knowledge, and information. Continuous HR development
will make it possible to improve employees’ ability level and organizational performance by receiving on-the-job training.
The problem we seek to solve is the main demand of the company is to detect in advance those employees who can be promoted. It requires a classification technique to solve existing
problems. The prediction algorithm used in this classification technique is the Logistic Regression Model, Decision Tree, and Random Forest.

## Data Info
!([Screenshot 2024-08-21 at 19.22.14.png](https://raw.githubusercontent.com/RidhatullahAkmalurrizalFirdausi/Data-Analytics-and-Machine-Learning-Group-Project/main/Screenshot%202024-08-21%20at%2019.22.14.png)) 

## Percentage of Employees Promoted and not Promoted in Each Department
!(by each dept.png)

## Percentage of Employees Promoted and not Promoted by Recruitment Channel
!(by rec chan.png)

## Percentage of Employees Promoted and not Promoted by Educational Background 
!(by ed back.png)

## Model Evaluation
!(Screenshot 2024-08-21 at 19.28.32.png)

## Conclusion
To sum up the result of the model first, we have found that the best model shown by the validation set via accuracy, and precision, was the random forest model. Despite the decision
tree having shown great recall value, the random forest still had a strong recall value as well, and we decided to take the random forest as the model that fit our dataset the most. With such a result,
we used the test dataset to once more test the model. As a result, the random forest model predicted that 787 people would be promoted. The actual number of promoted employees in
the dataset was 1043 people, and the best model we made has shown about 75 percent  accuracy. Compared to the accuracy we got from the validation set evaluation (around 93
percent), the test set accuracy was significantly lower. Thus, We believed that the models we made were overfitted in general (accurate on validation but less accurate when applying the test
set), and we concluded that making a better model out of the dataset requires a lower portion of the training set compared to the validation set and the test set. Moreover, since we had
trouble adjusting the epoch that was closest to its optimum, we felt there would be more progress required in terms of such steps.
