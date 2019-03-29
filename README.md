# UCI Human Activity Recognition Using Smartphones Data Set

This [dataset](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) contains 561 features derived from movement measured by the accelerometer and gyroscope of a smartphone, which was attached to the waist of volunteers, while performing six activities: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING. Each instance of the dataset is labeled with the corresponding activity. A total of 10299 instances is available: 70% as the training set, 30% as the test set.

I used this dataset as an exercise to explore the [Scikit-Learn documentation on Supervised Learning](https://scikit-learn.org/0.16/supervised_learning.html). I fitted all classification models available on a sample of the original dataset, then refitted the best-perfoming models on the whole dataset, then explored the documentation of the best-performing model to fine-tune the parameters.

By the end, I got 96.61% accuracy on the test set, considering my approach to be very successful.
