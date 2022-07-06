# Data_Analysis_No_Show_Appointment

<p dir="auto">
<a href="https://www.python.org" rel="nofollow"><img src="https://camo.githubusercontent.com/c676b5f90a1650624a0a9832d7954edda1db39ad3347d90c8c51e88ff2f92252/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d4646443433423f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d6461726b677265656e" alt="" data-canonical-src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&amp;logo=python&amp;logoColor=darkgreen" style="max-width: 100%;">
 </a> <a href="https://numpy.org" rel="nofollow"><img src="https://camo.githubusercontent.com/e4f918596bfc1a8746d3bf5426a212500a5b36b1e5c63869cbe65b071dcdb48a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e756d70792d3737374242343f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465" alt="" data-canonical-src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&amp;logo=numpy&amp;logoColor=white" style="max-width: 100%;"></a> <a href="https://pandas.pydata.org" rel="nofollow"><img src="https://camo.githubusercontent.com/5e18e9b742657f6921829e31b6ee09d5d345633d8680cf1881f637d8e7bc44f1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50616e6461732d3243324437323f7374796c653d666f722d7468652d6261646765266c6f676f3d70616e646173266c6f676f436f6c6f723d7768697465" alt="" data-canonical-src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&amp;logo=pandas&amp;logoColor=white" style="max-width: 100%;"></a><a href="https://matplotlib.org" rel="nofollow"><img src="https://camo.githubusercontent.com/b8f888055ab43caf0282c9c13b362891a9c8999c718c0ff304f293a31e6e5989/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d6174706c6f746c69622d3131353537633f267374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d7768697465" alt="" data-canonical-src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&amp;logo=matplotlib&amp;logoColor=white" style="max-width: 100%;"></a>  
<a href="https://colab.research.google.com" rel="nofollow"><img src="https://camo.githubusercontent.com/ce254316621ae7180772f1e8355fd15d6258eda95d51897e76068d11e6fa7987/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f6c61622d4639414230303f7374796c653d666f722d7468652d6261646765266c6f676f3d676f6f676c65636f6c616226636f6c6f723d353235323532" alt="" data-canonical-src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&amp;logo=googlecolab&amp;color=525252" style="max-width: 100%;"></a></p>

## Introduction
#### A person makes a doctor appointment, receives all the instructions and not show up. Who to blame?

The dataset contains 110,527 medical appointments and its 14 associated variables ( PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hypertension, Diabetes, Alcoholism, Handcap', SMS_received, No-show )

<a href="https://www.kaggle.com/datasets/joniarroba/noshowappointments" rel="nofollow">https://www.kaggle.com/datasets/joniarroba/noshowappointments</a>

## Exploratory Data Analysis
Therefore, with the help of data  analysis and visualization, we can:
* Percentage of patient who showed up and vice versal
* How other variables such as gender, sms received by the patient or not among other variables in the data affects patients showing up or not for their appointment

## Conclusion
80% of patient showed up while 20% did not show up in the data given.

For other categorical features, Finding the proportion of categories is important for how to best make ones judgement. Counts would not give a good picture hence representing in percetages is important.

There is no difference between male and female who show up. 80% of male showed up, same as female.

60 years and above (seniors) showed up more (85%) followed by childern, 0-12 (80%).

People who did not receive sms showed up more (83%) than patient who received( 72%). Sms seems not to be effective.

## Limitations
The first limitation is of the data provided, more data would give more insights.

The N0-show column before i cleaned it was confusing, I thought Yes -means they showed up and vice versal, but i had to read the description of data again to get the right label meaning.
