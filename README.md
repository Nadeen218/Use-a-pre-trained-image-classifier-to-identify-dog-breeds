# Use a pre-trained image classifier to identify dog breeds

## Description
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registering pets that aren’t actual dogs.

You need to use an already developed Python classifier to make sure the participants are dogs.

## Principal Objectives
1. Correctly identify images of dogs, even if the breed is misclassified.  
2. Correctly classify the breed of the dogs in the images.  
3. Determine which CNN architecture (ResNet, AlexNet, VGG) performs best considering accuracy and runtime.

## Project Outline
- Use the `time` module to measure program runtime.  
- Accept user inputs via command-line arguments.  
- Create pet image labels from filenames and store them in a dictionary.  
- Use the classifier function to classify images and generate labels.  
- Compare classifier labels to pet image labels and store results.  
- Classify labels as "Dog" or "Not Dog" using a provided `dognames.txt` file.  
- Calculate and print results showing algorithm performance.

## Tasks

- Classify images as *dogs* or *not dogs*.
- Compare the performance of three CNN models: AlexNet, VGG, and ResNet.
- Evaluate the accuracy and runtime of each model.

## Submission Results & Feedback

- Successfully implemented the image classification system using pre-trained CNN models (AlexNet, VGG, ResNet).
- Achieved accurate identification of dogs vs. non-dogs with an accuracy of 100%.
- Runtime performance was measured, showing a trade-off between speed and accuracy.

<img width="837" height="577" alt="result" src="https://github.com/user-attachments/assets/25ad36d2-a358-4005-bedc-02c425a05c13" />



<img width="839" height="687" alt="feedback" src="https://github.com/user-attachments/assets/fe88f16f-281c-49b7-a268-505b6d8fe80b" />



