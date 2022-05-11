# rl-action-recognition
Deep Reinforcement Learning for skeleton-based action recognition


To run this code, please download the data from the following link:<br> https://drive.google.com/open?id=1CZrSrpnWLbCTseQ2VrOiax1qE6nfGkG0 . <br>
This link contains 20 .csv files and in each of them, there exist 10 actions done by a person. The first column of each file is the corresponding action's label.<br> 
* To read and process the data, please run the **Data reading** section.<br>
* To visualize frames, please run **visualizing two frames from data samples** sub-section. You can change,
frame_1=200, frame_2=50, x=1 tp see frames of different actions done by different people respectively. 
* To train CNN (to be used in FDNET), please run the section **CNN network which is used as the pre-trained classifier in the policy gradient**. The following subsection gives the test accuracy before frame selection.
* To train the policy gradient and test it, please run the section **policy gradient (Reinforce) for frame selection**
