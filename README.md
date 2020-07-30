# Indian Liver Patients

<img src="https://github.com/favicon.ico" width="48">
<div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="vertical" data-theme="dark" data-vanity="mohit-kundu"><a class="LI-simple-link" href='https://in.linkedin.com/in/mohit-kundu?trk=profile-badge'>Mohit Kundu</a></div>

## Problem Context
Patients with Liver disease have been continuously increasing because of excessive consumption of alcohol, inhale of harmful gases, intake of contaminated food, pickles and drugs. This dataset was used to evaluate prediction algorithms in an effort to reduce burden on doctors.

## Content
This data set contains 416 liver patient records and 167 non liver patient records collected from North East of Andhra Pradesh, India. The "Dataset" column is a class label used to divide groups into liver patient (liver disease) or not (no disease). This data set contains 441 male patient records and 142 female patient records.

Any patient whose age exceeded 89 is listed as being of age "90".

<img src="https://static.india.com/wp-content/uploads/2017/07/hepatitis.jpg?impolicy=Medium_Resize&w=1200&h=800">

## Features of the data set :

### Column Name

1. **Age** - Tells the person's age.
        
>         Google - This we all know....duh

2. **Gender** - (Male or Female) Tells the person's gender. This is a very controversial column as we now know that there can be a spectrum of genders. But here we will only consider two genders.
            
>          ME - My sincere apologies to the people who do not orient themselves as "Male" or "Female". I hope in near future we will have a dataset where the spectrum of genders are included.            
     Google - Oh my! you knew that gender is not binary but a spectrum. Impressive..
     ME - Thank you google.

3. **Total_Bilirubin** - Well, I'm a mechancial engineer and not a doctor. So obviously I have no clue what this means. Let's ask google baba.

>         Google - A bilirubin test measures the amount of bilirubin in your blood. It’s used to help find the cause of health conditions like jaundice, anemia, and liver disease.
>         Bilirubin is an orange-yellow pigment that occurs normally when part of your red blood cells break down. Your liver takes the bilirubin from your blood and changes its chemical make-up so that most of it is passed through your poop as bile.
>         If your bilirubin levels are higher than normal, it’s a sign that either your red blood cells are breaking down at an unusual rate or that your liver isn’t breaking down waste properly and clearing the bilirubin from your blood.Another option is that there’s a problem somewhere along the pathway that gets the bilirubin out of your liver and into your stool. 
        
>         ME - Thank you Google. So fellows, I think now you have some knowledge on this as I do. And if you knew it already, you are awesome.
        
4. **Direct_Bilirubin** - It's technically the same as "Total_Bilirubin". The difference will be given us by our own google.
        
>         Google - Bilirubin attached by the liver to glucuronic acid, a glucose-derived acid, is called direct, or conjugated, bilirubin. Bilirubin not attached to glucuronic acid is called indirect, or unconjugated, bilirubin. All the bilirubin in your blood together is called total bilirubin. 
>         
>         ME - Damn you google, how much information do you have.....
        
5. **Alkaline_Phosphotase** - .......

>         Google - Alkaline phosphatase (ALP) is an enzyme in a person's blood that helps break down proteins. The body uses ALP for a wide range of processes, and it plays a particularly important role in liver function and bone development.Using an ALP test, it is possible to measure how much of this enzyme is circulating in a person’s blood.
>         
>         ME - I knew this....
>         Google - No, you don't
>         Me - Yeah.....you know everything....

6. **Alamine_Aminotransferase** - First of all it is "Alanine" and not "Alamine" . Rest our friend google will tell.

>         Google - Alanine aminotransferase (ALT) is an enzyme found primarily in the liver and kidney. It was originally referred to as serum glutamic pyruvic transaminase (SGPT). Normally, a low level of ALT exists in the serum. ALT is increased with liver damage and is used to screen for and/or monitor liver disease. Alanine aminotransferase (ALT) is usually measured concurrently with AST as part of a liver function panel to determine the source of organ damage. 
>         
>         ME - So, we need to change the column name to aviod confusion.
        
7. **Aspartate_Aminotransferase** - Help Google.....

>         Google - AST (aspartate aminotransferase) is an enzyme that is found mostly in the liver, but also in muscles. When your liver is damaged, it releases AST into your bloodstream. An AST blood test measures the amount of AST in your blood. The test can help your health care provider diagnose liver damage or disease.
>         
>         ME - WOOAAAHHH.......
        
8. **Total_protein** - Albumin and globulin are two types of protein in your body. The total protein test measures the total amount albumin and globulin in your body. It's used as part of your routine health checkup. It may also be used if you have unexpected weight loss, fatigue, or the symptoms of a kidney or liver disease.
        
>         ME - Atlast, something I knew.        
>         Google - You googled it. Don't play smart with me.
>         ME - uughhhh........There's no pleasing you.
        
9. **Albumin** - I think it's related to the protein in our bodies....
            
>         Google - Albumin is a protein made by your liver. Albumin helps keep fluid in your bloodstream so it doesn't leak into other tissues. It is also carries various substances throughout your body, including hormones, vitamins, and enzymes. Low albumin levels can indicate a problem with your liver or kidneys.
>         
>         ME - Close enough!!...
>         Google - *Face palms*

10. **Albumin_and_Globulin_Ratio** - This one's pretty eas......

>         Google - The Albumin to Globulin ratio (A:G) is the ratio of albumin present in serum in relation to the amount of globulin. The ratio can be interpreted only in light of the total protein concentration. Very generally speaking, the normal ratio in most species approximates 1:1.
>         
>         ME - I give up....
>         Google - Who made you a data scientist
>         ME - heyyy!! That's mean..
>         Google - The Arithmetic Mean is the average of the numbe....
>         ME - I know THAT...

11. **Dataset** - This is labelled incorrectly. From my perspective it should be "Liver_Disease" indicating that the patient has liver disease or not 

## Type of Machine Learning Problem
It is a binary classification problem, where given the above set of features, we need to predict if a given patient has liver disease or not.
* Supervised Machine learning Techniques Used:
  +   K Nearest Neighbour
  +   Gaussian Naive Bayes
  +   Support Vector Machine (SVM)
  +   Decision Tree Classifier
  +   Logistic Regression
  +   Stochastic Gradient Descent
  +   Random Forest Classifier

## Evaluation Metrics Used - 
Since this is binary classification problem, we use the following metrics:

* Confusion matrix - For getting a better clarity of the no of correct/incorrect predictions by the model
* ROC-AUC - It considers the rank of the output probabilities and intuitively measures the likelihood that model can distinguish between a positive point and a negative point.

## Implementations
> To see the implementation check this link - https://www.kaggle.com/mohitkundu1/liver-patient-prediction or https://github.com/m0-k1/Indian-Liver-Patients/blob/master/Liver-Patient-Prediction.ipynb
