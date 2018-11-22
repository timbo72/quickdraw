Quick, Draw! Kaggle Competition Starter Pack
The code in this repo is all you need to make a first submission to the Quick, Draw! Kaggle Competition. It uses the FastAi library.

I provide instructions on how to run the code below.

My code is a pretty blatent rip off of radekosmulski who deserves all credit for this work.
This code is based on code from a fast.ai MOOC that will be publicly available in Jan 2019
 
The files data_prep.ipynb and submission.ipynb are to be considered V1.0.
QuickDraw.ipynb is V2 with the main difference being that where V1 generated .png files before processing V2 creates a .txt file with the vector data. The images are then created by the dataloader.

Over the course of 9 submissions I managed an accuracy of %89.9 which landed me in the top %50 on the public leaderboard (at the time of writing the competition has not closed so that may change).

I believe I was let down by a number of early techincal issues and poor documentation of my working process. The poor recording of my work in particular means I have been unable to reproduce my highest score and two changes that were expected to have a noticable impact on accuraccy have not helped (increasing model depth and training image volume).