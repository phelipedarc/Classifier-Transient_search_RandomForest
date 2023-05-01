

<img src="https://farm66.staticflickr.com/65535/49055715328_092031af74_o.png"  width="150" />

# Random Forest Classifier for Astrophysical Transients and Artifacts Separation

This project provides a tutorial on how to use a Random Forest Classifier to separate astrophysical transients from artifacts. Transients are astronomical objects with variable luminosity, such as supernovas, kilonovas, and others. Historically, identifying these transients in the sky has been done by trained astronomers using visual inspection, aided by the use of image differentiation algorithms. These algorithms subtract from an image containing a candidate transient (search) a previously captured image (template), looking for areas of concentrated flux that could indicate the presence of a transient. One of the most common problems with this method is the Bad-Subtraction, which occurs when the search and template are misaligned, generating artifacts that can be mistaken for transients (false positives). To address this problem, a machine learning algorithm (Random Forest) is used.

## Usage:
The tutorial provides step-by-step instructions on how to use a Random Forest Classifier to separate astrophysical transients from artifacts. It also explains how to correct the Bad-Subtraction problem by training the classifier to distinguish between real transients and artifacts.

## Credits
This code was developed by Phelipe Darc.
(21/11/2022)
