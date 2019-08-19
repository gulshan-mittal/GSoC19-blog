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
| 5. | Pagination for the display of annotation files | ✅ |
| 6. | Pagination for the Annotation Results. | ✅ |
| 7. | Merged the Concordance Code with the current code to provide users  to directly upload the concordance.txt for uploading data.| ✅ |
| 8. | Changes in the Ask Admin Rights | ✅ |
| 9. | Changes incorporated in update information form | ✅ |
| 10. | Remove code Smells | ✅ |
| 11. | Updated the requirements.txt and Installation guide.| ✅ |

# [](#header-3) Progress made so far

The following features has been implemented in Final Phase till so far:

* **Delete feature for a single annotation**. Now user can delete the annotations individually if he/she has any doubt in it. Earlier, only deleting of whole annotations feature is present. Now both are present.
  

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag11.png?raw=true)


    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag6.png?raw=true)
    
    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag7.png?raw=true)
    
    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag8.png?raw=true)


    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag9.png?raw=true)
    
    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag10.png?raw=true)


​    

​    

​    

* Displaying a warning, If labels are changed when the annotators have started the annotation process.

    * In the following image one more label "spring" is added to the existing labels.

        ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/changed_lables.png?raw=true)

    * Now, the warning is shown to the annotators when they try to annotate the data.

        ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/warning_labels.png?raw=true)

    * Now, the Label Warnings are also added on the Label Page.

        * When the User wants to edit the label

            ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/labels2.png?raw=true)

        * When the User wants to delete the label

            ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/label1.png?raw=true)

        * When the User wants to add more labels

            ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/labels3.png?raw=true)

        * When the User wants to delete annotation Levels.

            ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/labels4.png?raw=true)

* Progress bar and Progress Status is implemented on the Annotation Page. Now the user can track his/her performance. Progress Bar is looking Awesome! 

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/progress_bar.png?raw=true)

* Implemented Account Menu in nav-bar which contain Settings for Updating Information, check Progress and logout sections.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/account_info.png?raw=true)

* Implemented functionality to Update the Profile Information.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/update_info1.png?raw=true)

* Implemented functionality to check the progress of other annotators assigned be a user and also provide a way to check the progress of a user which is included in the experiment. Now a user can select the experiment from a drop-down list and can see the progress of that experiment by all the annotators in a bar chart type graph.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/check_progress.png?raw=true)

* Corrected the Bug of Displaying Names when a user is added as a Owner or as an annotator.  Earlier Full name is displayed which is a major fault as Full name can be same for two users.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/add_annotator.png?raw=true)

* Now the Display time can take Float values with the precision of .01 seconds means now the before and after time gap can be up to 0.01 seconds. 

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/display_time.png?raw=true)

* Space Bar Cannot be used as a Key for the Annotations as it is used for pausing/playing the videos.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/space_key.png?raw=true)

* Registration Process is Authenticated by validating the user's email. Now an email will be sent to the user for validating the email. The user has to click on the verification link to verify his account and then only the user can login to his/her account.

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/otp_1.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/otp_2.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/otp_3.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/otp_4.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/otp_5.png?raw=true) 

* Forgot Password functionality is added. Now a user has to verify his email by entering an OTP sent to his email. First the user has to enter his/her username and email address and then after an OTP is sent to the registered email. User has to enter that OTP for updating his/her password. 

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/forgot_1.png?raw=true)


    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/forgot_2.png?raw=true)


    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/forgot_3.png?raw=true)


    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/forgot_5.png?raw=true)


​    
​    

* All the above things have implemented with the necessary feedback, warnings and error logs. 