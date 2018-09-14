# Psoriasis

## Domain Knowledge
Psoriasis is a long-lasting auto-immune disease with abnormal patchy skin which is currently incurable.

### Wait here only!!!!!
From here only we can understand a lot in terms of images of the patients or just by seeing them in person while performing the interview.

_**For the answers to the 3 questions go to the end**_

## Domain Knowledge
> The differential diagnosis of erythemato-squamous diseases is a real problem in dermatology. They all share the clinical features of erythema and scaling, with very little differences. The diseases in this group are psoriasis, seboreic dermatitis, lichen planus, pityriasis rosea, chronic dermatitis, and pityriasis rubra pilaris.
> Usually a biopsy is necessary for the diagnosis but unfortunately these diseases share many histopathological features as well. Another difficulty for the differential diagnosis is that a disease may show the features of another disease at the beginning stage and may have the characteristic features at the following stages. 
 
> Patients were first evaluated clinically with 12 features. Afterwards, skin samples were taken for the evaluation of 22 histopathological features. The values of the histopathological features are determined by an analysis of the samples under a microscope. 

## Believing as a News Reader
#### What will I see as soon as the patient enters.

Its APPEARANCE!!
But all the patients that I am going to interview are the people suffering from diseases relating to Dermatology.
Every Person may look the same in terms of patchy skin and I don’t even know what sort of a patchy skin does a patient having Psoriasis has.

## Dataset
I have 1,00,000 patients suffering from diseases mainly relating to dermatology.
From which I know that 10,250 are suffering from Psoriasis.

0.1025 probability of finding 1 person having Psoriasis. 1 in 10 people are suffering from this disease.
Probability of Combinations possible for selecting 10 suffering from Psoriasis among 100000 is 0.013.
13 in 1000 combinations would be right.

## Probability
* Probability of a group - 0.013 (13 in 1000) having Psoriasis
* Probability of a person – 0.10 ( 1 in 10) having Psoriasis

But selecting each individual one by one accounts to 10^(-11) of people having Psoriasis

## The demarcated scaly and erythematous plaque

![Typical Psoriasis](https://images.medicinenet.com/images/psoriasis-neck.jpg)

## 10 Questions that I will ask.
* Tell me for how long how you have been facing these problems ? Does it(Skin disease) runs in the family?
* Do you sweat a lot? What type of a skin do you have (dry/ oily neutral)?
* Do you face the problem of severe itching?
* Where do you live? Is that area very much polluted? Are there bacterial infections possible in that area?
* What sort of clothes do you wear? What kind of job do you have? Is it sedentary or agile?
* Do you like to wear tight clothing? Are there any abrasions or surfaces which may create friction on the surface?
* Can I see your nails?
* Did you face any problem in your childhood regarding itching and having a red and scaly skin?
* Were you able to scratch the surfaces where you faced these problems?
* Are your joints swelled up?
* What according is the disease you are having? Does that disease disturb you?

_The questions are asked to create a basic understanding of features that have to be taken into consideration by the NewsReporter's Brains's Machine Learning Models_

## An Unsupervised Learning Approach

Indeed an interesting problem because this could have been a plane and simple Supervised Learning Approach.

This problem statement is a k-means clustering problem.
But this approach can not be taken by the News Reporter because he/she is not aware about Machine Learning Algorithms (assumption).

Explanation of which has been described in the word file and also on Wikipedia..
### For Machine Learning Engineers

[UCI Dermatology Dataset](https://archive.ics.uci.edu/ml/datasets/dermatology)

Fetch the data and read everything which

## Other than questions
* Clicking images of diseased part of the body. (Very Crucial) because human memory is very fragile and can be tampered with very easily.
* Observing the behavior of the patient by analyzing the subconscious movements. (for eg. Itching, sweating, fidgeting etc)

## News Reporter's Result
News Reporter eventually would be able to shortlist people having Psoriasis. It is based on continuous evaluation of the patients that the News Reporter will become skilled in selecting those with having Psoriasis.
The process will end way before actually interviewing people actually having Psoriasis. Probability can be increased from 0.1 to 0.35 and then eventually 0.72 and 0.99.
Then at this accuracy the News Reporter will be able to shortlist patients.

## Answers to the questions asked

* **Question1**: What is the process to calculate the sample size?
According to the formulas already provided by statistics we should apply **Cochran's Sample Size Formulas** which clearly states that 
![Cochran](http://www.statisticshowto.com/wp-content/uploads/2018/01/cochran-1.jpeg)
where these variables represent confidence interval, confidence levels and Margin Error to estimate the Sample Size required without even using the Standard Deviation of the dataset provided.
![99% Conf)idence Interval](https://www.kean.edu/~fosborne/bstat/px/t-99-ci.gif)


* **Question2**: What is the process for testing the sample size value?

The process for testing the Sample Size value is the Unsupervised Learning Approach using **k-means clustering** for the proper classification. 
This verification will occur after the model is trained in the dataset and features provided by the **News Reporter**.

![GIF for k-means clustering](https://upload.wikimedia.org/wikipedia/commons/e/ea/K-means_convergence.gif)

* **Question3**: What will be the sample size based on given dataset details?

To calculate the sample size we have to again apply statistcal formulas but they can optimised by the help of other **Machine Learning Algorithms**.





