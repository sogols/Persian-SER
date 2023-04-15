# Persian-SER

SVM model: 

Data: ShEMO (except Fear)
Feature extractor: OpenSmile (functionals)
Feature Set: eGeMAPSv02

    # male:
    # Accuracy: 76.35305021907651
    # UAR: 55.13157619478546
    # Time: 3.6 + 16.7 
   
    # female:
    # Accuracy: 69.86364814095091
    # UAR: 60.62245031009332
    # Time: 2.5 + 12.8
    
    # modified shemo data:
    # Accuracy: 74.40915409507315
    # UAR: 59.16878570719483
    # Time: 9.7 + 47.5
    
    # shemo data:
    # Accuracy: 74.40915409507315
    # UAR: 59.16878570719483
    # Time: 8.4 + 44.0
    

CNN model:

Feature Set: Raw signals
Extractor: Librosa


    #categorical_accuracy: 0.7038
