# Listed-AIML-Assignment-1
This assignment was done on Google Colab.
In order to run this assignment, first we have to run the first cell which installs all the dependencies and clones the wav2lip repository which is required in order to run the assignment.
Then, we have to store the video and audio in a folder called input which is in turn stored in a folder called wav2lip.
Then, in the next cell, the upload method should be set to custom path and the path where the video file is stored has to be uploaded in the PATH_TO_YOUR_VIDEO variable. Ensure that the video uploaded is lesser than 100 seconds, else you'll have to change the condition where the time limit of the video is set.
Similarly, the audio file is uploaded in the next cell.
Then, we need to run the last cell where we can set some values to the pad_left, pad_right, pad_top, pad_bottom, rescale_factor, nosmooth and use_hd_model if necessary.
This produces a preview of the output and we can download the output from the Wav2Lib/results folder.

I would like to specify that this process only gives an intermediate level of lipsyncing and more alterations have to be done to the code and more preprocessing techniques need to be undertaken in order to improve the accuracy and smoothness of the lipsync. Since there was a time crunch and the mail urged us to complete and submit the assignment as soon as possible, I am submitting this. However, do know that improvements could have been made given more time.
