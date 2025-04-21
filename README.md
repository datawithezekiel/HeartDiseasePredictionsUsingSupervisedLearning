Heart Disease Prediction Model for Peterside Hospital

The Project I have Been Working On

Hi there! 

I'm the data scientist recently hired by Peterside Hospital to build this heart disease prediction tool. When Dr. Ikpro first approached me about creating a model that could help identify at-risk patients earlier, I knew this would be a project that could make a real difference in people's lives here in Lagos.

Why Peterside Hospital Is Special to Me
Working at Peterside Hospital has been an incredible experience. Founded in 2000 by the brilliant Dr. Efemena Ikpro, this place has become a healthcare landmark in Lagos. I'm constantly amazed by the dedication of the 300+ healthcare professionals I collaborate with daily. From the cardiology department that's guided my work to the nurses who'll eventually use this tool, everyone shares a commitment to combining compassionate care with cutting-edge technology.
The Dataset I Worked With
I started with health records from 303 patients, focusing on 14 key indicators that my research showed were most predictive of heart disease:
For each patient, I analyzed everything from basic demographics (age, sex) to detailed cardiac measurements. Some of the most revealing features turned out to be chest pain characteristics, ST depression measurements during exercise, and the number of major vessels affected.
As I explored this data, patterns began emerging that helped shape my approach to building the model.
How I Built This Model
After several late nights and many cups of coffee, I tested multiple machine learning approaches to find the algorithm that worked best with our unique patient population. I was particularly focused on minimizing false negatives - we really don't want to miss anyone who might be developing heart disease.
The breakthrough came when I realized that combining feature engineering specific to cardiovascular indicators with the right algorithm could significantly boost our prediction accuracy.
Setting Up My Project

# See what the model predicts
risk_probability = predict(model, patient_data)
print(f"Heart Disease Risk: {risk_probability:.2%}")
Results I'm Proud Of
After countless iterations and refinements, my model achieved performance metrics that I'm genuinely proud of:

Accuracy: 85.2%
Precision: 87.1%
Recall: 84.4%
F1-Score: 85.7%
AUC-ROC: 85.3%

Each percentage point represents potential early interventions that could save lives.

About Me
This project represents my commitment to using data science for healthcare advancement in Nigeria. 

With a background in Engineering, IT and Data Science, 
I'm passionate about creating tools that bridge the gap between cutting-edge AI and practical medical applications.

Let's Connect!

I'm always looking to collaborate with other professionals interested in healthcare AI. 
If you have questions, suggestions, or just want to chat about the project, reach me at:
ezekiel.ebuetse@gmail.com
