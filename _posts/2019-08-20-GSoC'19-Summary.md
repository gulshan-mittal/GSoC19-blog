---
layout: post
title: "GSoc'19 Summary"
---

GSoC’19 completed well. Thanks to my mentors who guided me along and suggested ways out of ambiguous scenarios. [View entire source code](https://github.com/gulshan-mittal/RapidAnnotator-2.0).

# [](#header-3) About the Project

Red Hen’s Rapid Annotator provides a platform to users to annotate large chunks of data in a short span of time and with least possible efforts. It provides the features of annotating images/videos/audios/text during collaborative situation also. With Red Hen Lab’s we will try to enable users to visualize the progress of each annotator separately and annotators can notify experimenter when the annotation is finished to make the annotation work more efficient.

# [](#header-1) Tools & Language
* Flask (Python Framework)
* Javascript (+ Html5 / css3 / bootstrap)

# [](#header-1) Installation and User Guide

Please refer the following links to install the Rapid Annotator-2.0

* For installation guide refer [here](https://github.com/RedHenLab/RapidAnnotator-2.0/blob/master/docs/installation_guide.md).
* For user guide refer [here](https://github.com/RedHenLab/RapidAnnotator-2.0/blob/master/docs/user_guide.md).

By the end of Phase 1, Phase 2 and Final Phase, I had accomplished all the intended tasks.

# [](#header-1) Phase 1 at a glance

# [](#header-4) Work Done for Evaluation 1

| S. No | Features Implemented | Status  |
|---|-----|-----|
| 1. |Enhancements According to User Feedback Report includes (Community Bondind Period Work)|   ✅ |
| 2.|Addition of Admin in the experiment. Now, Admins should be able to see and access all others experiments.|   ✅ |
| 3.| Resolve issue of the green warning over the login and sign up buttons |   ✅ |
| 4.|Added “Undo” functionality for the last element in the set of annotations.|   ✅ |
| 5.|Include Video link and captions in the result export.|   ✅ |
| 6.|Added support for tagging Scheme|   ✅ |
| 7.|Added functionality of pausing the video with the space and again play it using the space key|   ✅ |
| 8.|Displaying a warning, If labels are changed when the annotators have started the annotation process.|   ✅ |


# [](#header-1) Phase 2 at a glance

# [](#header-4) Work Done for Evaluation 2

| S. No | Features Implemented | Status  |
|---|-----|-----|
| 1. |Implemented changes suggested in Tagging Scheme|   ✅ |
| 2.|Displaying a warning, If labels are changed when the annotators have started the annotation process. On the Label Page also.|   ✅ |
| 3.| Implemented Progress Bar and Progress Status on the Annotation page. | ✅ |
| 4. | Implemented Account Menu in nav-bar which contain Settings for Updating Information, check Progress and logout sections. | ✅ |
| 5. | Implemented functionality to Update the Profile Information | ✅ |
| 6. | Implemented functionality to check the progress of other annotators assigned be a user and also provide a way to check the progress of a user which is included in the experiment. | ✅ |
| 7. | Corrected the Bug of Displaying Names when a user is added as a Owner or as an annotator. | ✅ |
| 8. | Now the Display time can take Float values with the precision of .01 seconds. | ✅ |
| 9. | Space Bar Cannot be used as a Key for the Annotations as it is used for pausing/playing the videos. | ✅ |
| 10. | Registration Process is Authenticated by validating the user's email. | ✅ |
| 11. | Forgot Password functionality is added. Now a user has to verify his email by entering an OTP sent to his email. | ✅ |

# [](#header-1) Final Phase at a glance

# [](#header-4) Work Done for Final Evaluation

| S. No | Features Implemented | Status  |
|---|-----|-----|
| 1.|Send notification features is added.|   ✅ |
| 2.| Partitioning the data feature is completed. | ✅ |
| 3. | Now on the view result page images, videos and audio are also added (small size) for the manual upload method so that if a user has any doubt he/she can just take a quick look from that because in manual method user  don't have any source link to the data(image, video, audio) . Also by adding this, UI becomes more attractive and clean.| ✅ |
| 4. | Pagination for the display of annotation files. | ✅ |
| 5. | Pagination for the Annotation Results. | ✅ |
| 6. | Merged the Concordance Code with the current code to provide users  to directly upload the concordance.txt for uploading data.| ✅ |
| 7. | Changes in the Ask Admin Rights. | ✅ |
| 8. | Changes incorporated in update information form. | ✅ |
| 9. | Remove code Smells. | ✅ |
| 10. | Updated the requirements.txt and Installation guide.| ✅ |

I have made 4 blogposts to help understand my project better at every pahse and to know what problems I faced during project & how to resolve them. They are posted on my github.io [here](https://gulshan-mittal.github.io/GSoC19-Blog/)

# [](#header-1) Pull Request : Merge the codebase

I have made one pull request as per mentors guideline where I have merged all the code which I had wrote during GSoC period. The link to merge request can be found [here](https://github.com/RedHenLab/RapidAnnotator-2.0/pull/21).


Most of the features have been added in the Project. But still, there's always a way for improvement. Like, delete feature I have added earlier for single annotation which I have to remove due to codebase structure is not compatible with that. I will be contributing to organization even after GSoC period. So, if possible, I'll try to add that feature for sure.
