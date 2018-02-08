# v0.3.0

* Novelty detection.  Tracks significantly different from those seen during training can be identified.
* New class 'cat'
* Improved model.  
* Improvements to clip classification (state decay, and smoothing refinements). 

# v0.2.1

## Major Features and Improvements

* Can now classify non-static videos
* Improvements to classification speed
* Updated and improved model 
* 6 classes (birds, false-positive, hedgehog, possum, rat, stoat) 

**Known issues**
* Obscured animals tend to be classified as stoats or rats.
* False-positive class was trained on false-positives generated by the static video tracking algorithm, tracking on non-static vidoes tends to generate different kinds of false-positives which may not be identified correctly.  

# v0.1.0

## Major Features and Improvements

* Initial model 
* 5 classes (birds, false-positive, hedgehog, possum, rat) 