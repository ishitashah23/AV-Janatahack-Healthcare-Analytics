# JanataHack Healthcare Analytics

This competition was hosted on 18th and 19th July 2020.   

## Team Members
https://github.com/ishitashah23 and 
https://github.com/shrey-B

# Problem Statement 

Congratulations – you have been hired as Chief Data Scientist of MedCamp – a not for profit organization dedicated in making health conditions for working professionals better. MedCamp was started because the founders saw their family suffer due to bad work life balance and neglected health. 

MedCamp organizes health camps in several cities with low work life balance. They reach out to working people and ask them to register for these health camps. For those who attend, MedCamp provides them facility to undergo health checks or increase awareness by visiting various stalls (depending on the format of camp). MedCamp has conducted 65 such events over a period of 4 years and they see a high drop off between “Registration” and Number of people taking tests at the Camps. In last 4 years, they have stored data of ~110,000 registrations they have done.

One of the huge costs in arranging these camps is the amount of inventory you need to carry. If you carry more than required inventory, you incur unnecessarily high costs. On the other hand, if you carry less than required inventory for conducting these medical checks, people end up having bad experience.

## The Process:
MedCamp employees / volunteers reach out to people and drive registrations.
During the camp, People who “ShowUp” either undergo the medical tests or visit stalls depending on the format of health camp.

## Other things to note:
Since this is a completely voluntary activity for the working professionals, MedCamp usually has little profile information about these people.
For a few camps, there was hardware failure, so some information about date and time of registration is lost.
MedCamp runs 3 formats of these camps. The first and second format provides people with an instantaneous health score. The third format provides information about several health issues through various awareness stalls.
Favorable outcome:
For the first 2 formats, a favourable outcome is defined as getting a health_score, while in the third format it is defined as visiting at least a stall.
You need to predict the chances (probability) of having a favourable outcome.

## Train / Test split:
Camps started on or before 31st March 2006 are considered in Train
Test data is for all camps conducted on or after 1st April 2006.

## Outcome
Predicted probability of a favourable outcome

## Evaluation Metric
The evaluation metric for this hackathon is ROC-AUC Score.

## Public and Private split
The public leaderboard is based on 50% of test data, while final rank would be decided on remaining 50% of test data (which is private leaderboard)

## Final Results
Public leaderboard score - 0.808603 </br>
Private leaderboard score - 0.72649

## Winning results 
Public leaderboard score - 0.84816 </br>
Private leaderboard score - 0.78533

