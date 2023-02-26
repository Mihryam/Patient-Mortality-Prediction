# Patient-Mortality-Prediction
A deep neural network model designed to provide an analytic framework that medical professionals can use to predict patient mortality at any time of interest. 
This solution provides essential feedback to clinicians when trying to assess the impact of treatment decisions, or raise early warning signs to flag at-risk patients in a busy hospital care setting.

The data used was provided by PICU at Children's Hospital Los Angeles (CHLA).


Electronic Health Records (EHRs) contain a wealth of patient medical information that can:

<li>
Save valuable time when an emergency arises
<li>
Eliminate unnecesary treatment and tests
<li>
Prevent potentially life-threatening mistakes
<li>
Improve the overall quality of care a patient receives when seeking medical assistance

  
Datasets were stored in HDF5 formats. HDF5 stands for "hierarchical data format version number 5". The HDF format is designed specifically to store and organize large amounts of scientific data and was originally designed by the National Center for Supercomputing Applications.

## EXPLORE THE DATA
<li>
Data is an irregular time series of measurements taken over the course of a patient's stay at PICU.
<li>
5000 unique patients were encountered in th training set
<li>
Each encounter includes multiple observations during the hospital stay
<li>
Each observation includes values in some of the 265 measurement variable categories

### Measurements Include:
<li>
Statistics: Gender, Age, Weight
<li>
Vitals: Heart Rate, respiratory Rate
<li>
Labs: Glucose, Creatinine
<li>
Interventions: Intubation, O2
<li>
Drugs: Dopamine, epinephrine

Not all measurements were taken for all patients

Dependent variable:
Alive – 1
Not alive – 0

1,113,529 observations (rows) containing 265 variables (columns) over the 5000 patients in the training data set

Mean observations per patient encounter = 223

Median observations per patient encounter = 94


