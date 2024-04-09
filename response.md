I will go ahead with Scenario 2, since I have a bit more experience in image processing. I am breaking down the scenario. So, the requirements are:
1.A process to streamline the images of artisan products automatically with detailed product description/specification. Which is to annotate the images with their description and specifications.

2. The system should have high precision in annotation. That means the model has to be trained well and run with least human intervention.

Process to follow:
1.Data preparation - The jewellery data needs to be collected from the makers, cleaned, validate the available annotations; label/annotate the images which has no description/specification. So the annotation can be manual or using other tools, or with the help of libraries in Roboflow, where there are different libraries with annotations available such as:https://universe.roboflow.com/iba-0zzb3/bagsearch-jewellery. Roboflow will be efficient to annotate what the jewellery is in the image, however will be ineffective to provide a description/specification for the jewellery, hence manual intervention is required at this point.

2.Model selection and training the model - This is when Deep Learning models such TensorFlow and PyTorch are getting used. Train the models with the pre-trained image classification, I am assuming, the image features as the independant variables and the description as the dependant variable, where NLP will have to be applied to generate accurate description.

3. Feature engineering, hyper parameter tuning, feature extraction, identify which methodology improves the precision of the model. Validate and deploy the project. 