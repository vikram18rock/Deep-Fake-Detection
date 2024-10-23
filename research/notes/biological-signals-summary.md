Summary of [[dfd_using_biological_features_survey.pdf|this]] research article
## Introduction
Explained:
1. What is deep fake?
2. How are they generated?
3. Evolution of deep fakes.
4. Rise of need for detecting deep fakes.
5. Malicious usage of deep fake technology and it's after effects
6. Detection of collapsing of pixels and other abnormalities to detect deep fakes
7. Evolution of GANs discriminators to dodge the abnormality validations and failure of detection of collapsing of pixels.
### GAN
we see two different neural networks: 
- the generator 
- the discriminator

The generators job is to fool the discriminator. The more accurate discriminator is the better generator will be.

### Background: overview of Deepfake
Explained the causes of deepfakes creation in the first place.

## Statement of Problem
Aim is to study the Deepfake detection methods that employ biological features in detection. 

Broadly, study is on five biological features:
- Eyebrow
- Eye blinking
- Eye movement
- Ear and mouth movement
- Heartbeat detection

### DEEP FAKE
This section Discusses
- DeepFake Creation
- DeepFake Detection
- Fake Image Detection
- Current Deep Fake detection methods
- Deep fake detection current challenges and Next steps

#### DeepFake Creation

> [!info] Deep Auto Encoder
> A type of Convolution model, used to compress an image

FakeApp was created using a `Auto encoder - Decoder` coupled architecture

Large number of 
Creation Steps
1. Shared auto encoder for both the subjects, but different decoders for decoding the subjects are trained.
2.  Here we do the following on each frame from both the subjects
	1. Face recognition isolates visages from source image
	2. Now this visage say `visage A` is encoded
	3. then decoded using `decoder B`
	4. repeat for next frame
3. Preprocessing for increasing resolution of images helps polishing the outcome
4. 

> [!info] visage
> especially in contexts like computer vision, deepfakes, or image manipulation, **visage** refers to the **facial aspect of the image**—essentially, the appearance or structure of a person's face depicted in that image.





