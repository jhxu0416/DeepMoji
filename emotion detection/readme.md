# Introduction
During the 1970s, psychologist Paul Eckman identified six basic emotions which are happiness, sadness, fear, disgust, anger and surprise.

In this project, model is designed to detect only two emontions inculding happiness, sadness.

Tweet is labeled as postive (happy) if it has emoji (:joy: FACE WITH TEARS OF JOY) in the it.

Tweet is labeled as slightly postive (slightly happy) if it has emoji (:blush: SMILING FACE WITH SMILING EYES) in the it.

Tweet is labeled as slightly negative (slightly sad) if it has emoji (:unamused: UNAMUSED FACE) in the it.

Tweet is labeled as negative (sad) if it has emoji (:sob: LOUDLY CRYING FACE) in the it.

# Model
This project uses transfer learning based on DeepMoji's bi-LSTM structre and replace the final softmax layer.