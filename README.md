# face-recognition-deep-learning

How Facial Recognition Algorithm Works

1. what is face recognition
Facial recognition is a biometric identification process to identify, verify, and authenticate the person using facial features from any photo or video. Facial recognition system works on comparing facial biometric patterns of the face of interest with the database of known faces to find the match.

how does it work:

1.Face Detection
The facial recognition process starts with the human face and the necessary facial features pattern of the person to be identified. When we think of a human face, we probably also think of the very basic set of features, which are eyes, nose, and mouth. Similarly, facial recognition technology also needs to learn what a face is and how it looks. This is done by using deep neural network & machine learning algorithms on a large database of images with human faces looking at different angles or positions.
The process starts with human eyes, which is one of the most accessible features to detect, and then it proceeds to detect eyebrows, nose, mouth, etc. by calculating the width of the nose, distance between the eyes, and the shape & size of mouth.

2.Feature Extraction
Once the face is detected, the software is trained with the help of computer vision algorithms to detect the facial landmarks (eyebrow corners, eyes gap, tip of the nose, mouth corners, etc.) Each landmark is considered as nodal points, and each face has approximately 80 nodal points. These landmarks are the key to distinguish each face present in the database.
After this, the registered face in the database is adjusted in position, size and scale to match with user’s face. It would help whenever the user’s face moves or expression changes; the software will accurately recognize it.

3. Face Representation
When the facial feature is extracted, and landmarks, face position, orientation & all key elements are fed into the software, the software generates a unique feature vector for each face in the numeric form. These numeric codes are also called Faceprint, similar to Fingerprint in contact biometric system. Each code uniquely identifies the person among all the others in the training dataset. The feature vector is then used to search through the entire database of enrolled users during the face detection process.

4.Face Matching
After generating the unique vector code, it is compared against the faces in the database. The database has all the information of registered users. If the software identifies the match for exact feature in the database, it provides all the person’s details. If the compared featured vector value is below a certain threshold value, the feature-based classifier returns the id of the match found in the database.

Deep learning in face detection

Deep Learning can be used to solve different problems in image analysis and pattern recognition. Face recognition is it's one of the applications. The use of face recognition to solve different social problems like personal authentication and security is increasing rapidly. In past different face recognition techniques have been introduced like Fisherfaces, Eigenfaces, and LBPH. These methods have low accuracy, so neural networks are used. The deep learning based neural networks are the most accurate. The parameters of the network can be tuned to achieve high accuracy. Face recognition requires a data base of individuals to train a neural network using deep learning. The trained network is then capable of recognition.


Phase 1:
face detection
face landmarks
face encoding
face recognition
face digittal makeup
face similarity
Demographics Face Recognition


 Phase 2:
Deep Learning Models for Face Recognition
review each models.


Phase 3:
face detection systems

