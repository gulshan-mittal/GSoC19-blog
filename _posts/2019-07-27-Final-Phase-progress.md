---
layout: post
title: "Final Phase Progress"
---

It is a great feeling to work on the Red Hen Rapid Annotator-2.0 Project and adding production level code in the project. This post includes all my work which will be done during the Final Phase evaluation. This phase is directly headed towards the coding and submission part of the project. This also includes removing all the code smells and documenting all the things done so far.

# [](#header-1)Decisions made post Phase 2

After the phase 2 evaluation some features has been redefined. The following things is decided on several deliberation with the mentors:
1. Changes in the Update Information form. Confirm password and old password field is to be added.
2. Changes have been incorporated in the feature of Asking admin right. When the admin revoke the request of the experimenter for the admin role then the request is deleted and the user (experimenter) would again sent a request if they need admin rights.  

# [](#header-2) Work Done for Evaluation 2

| S. No | Features Implemented | Status  |
|---|-----|-----|
| 1. |Delete feature for a single annotation|   ✅ |
| 2.|Send notification features is added.|   ✅ |
| 3.| Partitioning the data feature is completed. | ✅ |
| 4. | Now on the view result page images, videos and audio are also added (small size) for the manual upload method so that if a user has any doubt he/she can just take a quick look from that because in manual method user  don't have any source link to the data(image, video, audio) . Also by adding this, UI becomes more attractive and clean.| ✅ |
| 5. | Pagination for the display of annotation files. | ✅ |
| 6. | Pagination for the Annotation Results. | ✅ |
| 7. | Merged the Concordance Code with the current code to provide users  to directly upload the concordance.txt for uploading data.| ✅ |
| 8. | Changes in the Ask Admin Rights. | ✅ |
| 9. | Changes incorporated in update information form. | ✅ |
| 10. | Remove code Smells. | ✅ |
| 11. | Updated the requirements.txt and Installation guide.| ✅ |

# [](#header-3) Progress made so far

The following features has been implemented in Final Phase till so far:

* **Delete feature for a single annotation**. Now user can delete the annotations individually if he/she has any doubt in it. Earlier, only deleting of whole annotations feature is present. Now both are present.
  

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-delete.png?raw=true)


* **Send notification features is added**. If an annotator completes the annotations assigned by a user then he/she can send a notification to the experimenter by clicking on send notification button which appears after completing the task. Also, the experimenter got notified with the no of notifications he/she has received like in the facebook a red circle with the no of notification in it.

    * In the following image user can send notification by clicking on send notification button.

        ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-notif2.png?raw=true)

    * Notification got sent when the user click on notification button along with a feedback.

        ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-notif1.png?raw=true)

    * Experimenter get notification in red colour on the bell icon on the navbar as on shown below.

        ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-notif3.png?raw=true)

    * Experimenters can click on bell icon to see the notifications they have recieved.

        ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-notif4.png?raw=true)

* **Partitioning the data feature is completed**.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-dp1.png?raw=true)

* Now on the view result page images, videos and audio are also added (small size) for the manual upload method so that if a user has any doubt he/she can just take a quick look from that because in manual method user  don't have any source link to the data(image, video, audio) . Also by adding this, UI becomes more attractive and clean.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-pagination2.png?raw=true)

* **Implemented Pagination for the display of annotation files**.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final_pagination.png?raw=true)

* **Implemented Pagination for the display of annotation results**.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-pagination2.png?raw=true)

* Merged the Concordance Code with the current code to provide users  to directly upload the concordance.txt for uploading data.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-con1.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-con2.png?raw=true)



* Changes incorporated in update information form. Following is the updated form:

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/final-updateform.png?raw=true)

* Implemented Changes in the Ask Admin Rights.

* Remove all the code smells.

* Updated the requirements.txt and Installation guide.

* All the above things have implemented with the necessary feedback, warnings and error logs. 