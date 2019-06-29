---
layout: post
title: "Phase 2 Progress"
---

It is a great feeling to work on the Red Hen Rapid Annotator-2.0 Project and adding production level code in the project. This post includes all my work which will be done during the Phase 2 evaluation. This phase is directly headed towards the coding part of the project.

# [](#header-1)Decisions made post Phase 1

After the phase 1 evaluation some features has been redefined. The following things is decided on several deliberation with the mentors:
1. There will be a warning on edit, delete and add label data modal on the Label Page. This will enable user to understand if any changes made by him/her can effect the annotations in progress.
2. Add support for tagging Scheme is redefined.  Now there will be a Global Name for all the Annotation levels belonging to an experiment. User can import all annotation levels belonging to that Global Name. 

# [](#header-2) Work Done for Evaluation 2

| S. No | Features Implemented | Status  |
|---|-----|-----|
| 1. |Implemented changes suggested in Tagging Scheme|   ✅ |
| 2.|Displaying a warning, If labels are changed when the annotators have started the annotation process. On the Label Page also.|   ✅ |
| 3.| Implemented Progress Bar and Progress Status on the Annotation page. |   ✅ |



# [](#header-3) Progress made so far

The following features has been implemented in Phase 2 till so far:

* **Added support for tagging Scheme**. Now in the tagging scheme the annotation labels can be reused by the user for other experiments as well. This will save user's time a lot and provide a more comprehensible way for the annotations. Now when user click on Make global button (Description; A button for making the experiment global so that other users can import it) then a dialog box will open in which a user can put the name (global name) for all the annotation levels that a user will while importing that annotations. I have implemented the scheme in which a user can import all the annotation levels of a particular experiment. I have done this because as a User it feels so easy to just import all the annotation levels and delete one or two according to his/her comfort. If we have done this in another way like importing single annotation level then it becomes so cumbersome to import 10 annotation levels of a single experiment and later if he needs only say 8 so the user has to do same efforts as he/she would do in other method. Below Images are showing the tagging scheme
    

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag11.png?raw=true)


    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag6.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag7.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag8.png?raw=true)
    

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag9.png?raw=true)

    ![image](https://github.com/gulshan-mittal/GSoC19-Blog/blob/master/assets/images/tag10.png?raw=true)

    

    

    

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