# RealTimeEEGVowelPrediction

We did a real time prdiction based on EEG data of silent Vowel.

EED data of silent vowel means that EEG signal data when the subject is thinking the vowel without speaking it out.

So we predicted the which vowel the subject thought based on the eeg data.

And as we showed the result of the prediction in real time to subject, the sucject could be trained to think vowel in more efficient way.

Although we constructed all experiment codes and preparation, there was small misunderstanding of EEG.

We put the amplitude* time data of EEG into the CNN model. But this data was too instable.

But when we changed the amplitude* time data to frequency* time data, it becomes much stable.

As we used ampitude* time data, we could not predict preoperly. 

Next time, we will try again with freq* time data.
