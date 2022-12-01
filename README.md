# Comparative analysis of Different GANs’ implement on Face Aging
Generative adversarial network (GAN) methods create highly realistic new data from input images. One of its applications in the image-to-image transformation area is the face aging. In the face aging task, aged face images are synthesized by plugging in images from a person’s younger years. Face aging can be useful in multiple areas such as in biometric systems, in forensics for ﬁnding missing children, in entertainment, and many more. Currently, several GANs are available for face aging applications and this paper focuses on comparing the four GANs which are Cycle-Consistent Adversarial Network (CycleGAN), Attention-Guided Generative Adversarial Network (AttentionGAN), style-based Generative Adversarial Network (StyleGAN), Lifespan Age Transformation Synthesis (LATS). For comparison, these models are trained on the FFHQ (Flickr Faces HQ) dataset. The results of each model are evaluated quantitatively with two image quality assessment metrics (FID and PSNR), and qualitatively with a perceptual study on synthesized images from the same input image. It has been concluded that overall LATS has the best performance over the other models.

# Code Instruction
For CycleGAN and AttentionGAN: The code we provided here are python files excluding the dataset path. You need to download the dataset then modify the code including the dataset path to implement.  
For StyleGAN and LATS: Since they are pretained models, you can just run the code directly in colab. 
