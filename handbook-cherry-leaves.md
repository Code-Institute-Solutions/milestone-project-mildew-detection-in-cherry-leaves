In case you have chosen the **Project Idea: Mildew Detection in Cherry Leaves**, please consider the following instructions

---

## Repository Template
In case you do not want to build one repo from scratch, we suggest you fork this [repo](https://github.com/Code-Institute-Solutions/milestone-project-mildew-detection-in-cherry-leaves). Once you forked you may also personalize and rename the repo if you want to.

---

## Business Case Assessment
You have already conducted a business case assessment, so you can also use that information to build your project README file.

* 1: What are the business requirements?	
    * 1 - The client is interested in having a technique to visually differentiate a cherry leaf that is healthy and that contains powdery mildew.
    * 2 - The client is interested to predict if a cherry leaf is healthy or contains powdery mildew.

* 2: Is there any business requirement that can be answered with conventional data analysis?		
    * Yes, we can use conventional data analysis to conduct a study to visually differentiate a cherry leaf that is healthy and that contains powdery mildew.

* 3: Does the client need a dashboard or an API endpoint?		
    * The client needs a dashboard.

* 4: What does the client consider as a successful project outcome?		
    * A study showing how to visually differentiate a cherry leaf that is healthy and that contains powdery mildew.
    * Also, the capability to predict if a cherry leaf is healthy or contains powdery mildew.

* 5: Can you break down the project into Epics and User Stories?		
    * Information gathering and data collection.
    * Data visualization, cleaning, and preparation
    * Model training, optimization and validation,
    * Dashboard planning, designing, and development.
    * Dashboard deployment and release. 

* 6: Ethical or Privacy concerns?	
    * The client provided the data under an NDA (non-disclosure agreement), therefore the data should be shared only with professionals that are officially involved in the project.

* 7: Does the data suggest a particular model?		
    * The data suggests a binary classifier, indicating if the cherry leaf is healthy or contains powdery mildew.

* 8: What are the model's inputs and intended outputs?
    * The input is the cherry leaf image and the output is a prediction informing if a cherry leaf is healthy or contains powdery mildew.

* 9: What are the criteria for the performance goal of the predictions?	
    * We agreed with the client 97% of accuracy.

* 10: How will the client benefit?		
    * The client will not supply the market with a product of compromised quality.


---

## Project considerations
* Business Requirement 1
    * Your study should include at least analysis on: (1) average image and variability image for each class (healthy or powdery mildew), and (2) an image montage for each class.

* Business Requirement 2
    * You may deliver an ML system that is capable to predict if a cherry leaf is healthy or contains powdery mildew.
    * You may use either conventional ML or Neural networks to map the relationships between the features and the target.


---

## Dashboard expectations
* Your dashboard should contain at least:
    * A project summary page, showing the project dataset summary and client's requirements.
    * A page listing your findings related to a study to visually differentiate a cherry leaf that is healthy and that contains powdery mildew
    * A page containing: 
        * Link to download a set of cherry leaves images for live prediction (you may use the Kaggle repository that was provided to you).
        * User Interface with a file uploader widget. The user should have the capacity to upload multiple images. 
        * For each image, it will display the image and a prediction statement, indicating if a cherry leaf is healthy or contains powdery mildew and the probability associated with this statement.
        * A table with the image name and prediction results, and a download button to download the table.
    * A page indicating your project hypothesis and how you validated it across the project.
    * A technical page displaying your model performance.
