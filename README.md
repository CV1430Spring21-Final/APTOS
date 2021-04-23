# diabetic_retinopathy
CNN model that detects Diabetic Retinopathy

## Fengyi Jiang, Venkata Shubhang Kandiraju, Haotian Fu, Joey Bai.

### How to Run: 
#### Download Dataset using command line argument: 
pip3 install kaggle
kaggle datasets download -d tanlikesmath/diabetic-retinopathy-resized
#### Set path: 
Set path to be the directory to the downloaded folder. 
#### (Optional) Load full model:
Use Google Drive Link with Brown Account: https://drive.google.com/file/d/1VjOy2ekSLotuQm9GqI1hMahndPKyqQMO/view?usp=sharing
Our Github Large File System credit depleted. So have to use Google Drive.

### Problem Statement

Diabetic retinopathy (DR) is an eye disease that arises due to diabetes and is a leading cause of blindness around the world. It's a hard disease to catch early on, when it's most treatable, due to lack of significant symptoms. 

DR contributes to significant global burden to due to the widespread prevalence of diabetes - 422 million patients around the world. Out of these patients with diabetes, 146 million people have some form of DR.

This makes DR a major problem around the world that needs to be tackled soon. One of the ways to reduce blindness caused by DR is to catch the disease early and that can be done by leveraging technology at the right places in the healthcare system.

Here in this paper we aim to showcase a deep learning based solution to automatically detect presence of DR in the retina. We feel that a solution like this can be very beneficial to catching DR early on in places where the patients to ophthalmologists ratio is very low. 

Eventually, as rates of early diagnosis of DR go up so will the cases of blindness as early stage disease can be treated effectively.

### Code Format: 
Code is formatted in Jupyter Notebook format. 

And inceptionv3_0421_2021.ipynb is the access point for the running the project.

### Project File Structure

InceptionV3_weights Folder :Model weights for the InceptionV3 Model.

VGG16_weights Folder: Model weights for the VGG16 Model.

### Notebook Public Access: 

The notebook can be accessed through PaperSpace VM instances as well: https://console.paperspace.com/te7cu6qao/notebook/rsjnvjdl33ub6wv 

