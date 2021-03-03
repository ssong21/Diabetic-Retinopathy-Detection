# Diabetic Retinopathy Detection in CFPs using a CNN
Training a convolutional neural network that can determine the presence of diabetic retinopathy in color fundus photographs of the retina, a binary classification task.
Please read ml_final_ssong21.pdf for the formal writeup of this project, which describes the dataset, CNN architecture, results, future work, and related work.
# Motivation
The US Center for Disease Control and Prevention estimates that 34.2 million people in
the US have diabetes and the World Health Organization estimates that 422 million people have
diabetes worldwide. Diabetic retinopathy is an eye disease associated with long-standing
diabetes and is the leading cause of blindness in the working-age population of the developed
world. Around 40% of Americans with diabetes have some stage of the disease, and it is
estimated to affect over 93 million people worldwide. Progression of vision impairment can be
significantly hindered if diabetic retinopathy is detected early on; however, detection is
inherently difficult as the disease often shows few symptoms until it is too late to provide
effective treatment.
Currently, detecting diabetic retinopathy is a time-consuming and manual process that
involves a retina specialist evaluating color fundus photographs of the retina based on the
presence of lesions associated with the vascular abnormalities caused by the disease. The delay
necessitated by a manual diagnosis can lead to lost follow up, miscommunication, and delayed
treatment. Furthermore, the expertise and equipment required for diagnosis is lacking in areas
where the rate of diabetes in local populations is high, where DR detection is most needed. As
the number of individuals with diabetes continues to grow to epidemic proportions, the current
infrastructure in place for DR diagnosis will become even more insufficient. Given the pandemic
size of the diabetic population, a comprehensive, automated method of diabetic retinopathy
screening/detection will be necessary to mitigate the rising threat of the disease.



# Instructions
Running the code:
1. The file must be run on Google Colab.
2. Add the final_photos_all.zip file to your google drive (My Drive). Make sure that it is NOT located in any folders, otherwise the program will not run properly. NOTE: final_photos_all is not publicly available, please contact me by email if you wish to run the code.
3. To make training faster, make sure to enable GPU usage (Edit -> Notebook Settings -> GPU -> save).
4. Upon first run, you will have to authenticate Google Drive in the first cell.
5. If it doesn’t run properly (might’ve missed something to add here), please contact me by email, ssong21@amherst.edu.
