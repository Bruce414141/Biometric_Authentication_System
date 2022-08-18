# Biometric_Authentication_System
This is a project required for the completion of Honours degree with the University of the Witwatersrand
The project is concerned primarily with privacy preservation in Multimodal Biometric Authentication Systems.
I use 2 biometric modalities 1)Fingerprint 2)Face for authentication in the process.
I used 2 datasets both obtained from kaggle(A public free library of datasets).
I use source code jupyter notebooks that was trained on the respective datasets also found on kaggle.

System design
The primary focus of this project is to preserve the privacy of the User of the biometric system.
This is going to be done by using some sort of machine learning tokenisation of the biometric data.  
These tokens are going to be the signals that will be sent for authentification purposes instead of the biometric data itself thus preserving the privacy of the user.

Feature Extraction 
After this process the data will be sent thru a machine learning network that will generate a token using certain principles.
Non-reversibility
Non-revocability
User-Uniqueness

Ultimate key generation
This is the process where by the token and score from the one model are combined to form the ultimate key.

Visit the research proposal for more details.
