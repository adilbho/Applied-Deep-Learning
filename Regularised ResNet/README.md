Implement an Image Classification model using ResNet50.

• Implement a data augmentation class mixup, using the mixup algorithm, such that:

o The mixup algorithm can be applied to images and labels in each training iteration.

o Have an input flag “sampling_method” and appropriate hyperparameters for two options:

  ▪ sampling_method = 1: λ is sampled from a beta distribution as described in the research paper.

  ▪ sampling_method = 2: λ is sampled uniformly from a predefined range.

o Visualise your implementation, by saving to a PNG file “mixup.png”, a montage of 16 images
with randomly augmented images that are about to be fed into network training.

• Implement a task script completing the following:

o Train a new ResNet classification network with mixup data augmentation, for each of the two
sampling methods, with 10 epochs.

o Save the two trained model and submit your trained model within the task folder.

o Report the test set performance in terms of classification accuracy versus the epochs.

o Visualise your results, by saving to a PNG file “result.png”, a montage of 36 test images with
printed messages clearly indicating the ground-truth and the predicted classes for each.
