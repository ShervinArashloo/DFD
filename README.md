# DFD

Digitally manipulated face images/videos, and especially those obtained via the recent artificial intelligence and deep learning algorithms which are commonly referred to as “DeepFake” (DF) techniques, present highly realistic looking images/videos of people saying and doing fake things. Such fake content now possesses the capacity to pose a significant impact on how one may decide the validity of information spread online. Such content modification and generation techniques may affect the human rights and the quality of public discourse-especially considering that DeepFakes may be deployed maliciously as a mechanism for manipulation, misinformation, persuasion and harassment. Due to the rapid advancement of DeepFake techniques, identification and detection of digitally manipulated media has become a technically demanding and rapidly evolving major challenge.
The majority of the existing DeepFake detection methods in the literature assume the problem as a closed-set two-class recognition task and collect both real and fake data to train a binary classifier to detect fake content. This modelling formalism, however, suffers from certain drawbacks. First, creation of fake training data is both computationally demanding and time consuming. Second, and more important, in the test phase, the trained binary classifiers are biased towards detecting samples which are generated by the models “seen” during the training stage. Any test sample which may be potentially developed using an “unseen model” then has a high chance of passing the detection system. Since, the creation of new DeepFake models has a fast pace as one may witness from the relevant literature, the DF detection problem in real-world settings is quite a challenging one.
Considering that DeepFakes pose a great threat to both the individuals as well as the society as a whole, the current project aims to propose and implement new and high-performance automated techniques for the DeepFake detection problem, and to improve upon the state-of-the-art methods in the real-world and challenging conditions of DeepFake image/videos. In this context, a particular focus shall be placed on the “unseen” scenario where a test sample is generated using a DeepFake model that was not seen during the training stage of the system. 

Manipulation of faces in images/videos may be classified into four major groups based on the type and degree of manipulation involved as

•	Entire Face Image Synthesis: this type of face manipulation generates full non-existent facial images, typically via deep learning approaches such as Generative Adversarial Networks (GAN), e.g., by using the StyleGAN method [Karras et al., 2019]. Such techniques have managed to produce impressive outcomes, creating high definition face images with a great extent of authenticity.

•	Identity Replacement: this type of manipulation corresponds to changing the face of a subject in a video stream with that of a different individual. Typically, two methods are deployed for this purpose: 1) the conventional computer graphics methods such as FaceSwap ; and 2) new deep learning approaches referred to as DeepFakes , e.g., the FaceApp mobile application.

•	Attribute Manipulation: this type of face image manipulation, also referred to as face retouching or face editing, corresponds to making partial or minor changes to some features of a face such as the gender, adding glasses, age, the colour of the skin or the hair [Gonzalez-Sosa, 2018]. This type of manipulation is typically conducted using GANs such as the StarGAN method [Choi et al., 2018]. Applications such as FaceApp enable users to perform such attribute manipulations very conveniently.

•	Expression Swap: also referred to as face reenactment, involves modification of the facial expression of a subject according to the expressions of another person in a different video. Despite the existence of different manipulation techniques for this purpose [Liu et al., 2019], the most popular ones are those of Face2Face [Thies et al., 2016] and Neural Textures [Thies et al., 2019]. Some popular face reenactments include mouth reenactment (a.k.a. dubbing), gaze and pose reenactment.

![Bilkent logo](Types.png)
