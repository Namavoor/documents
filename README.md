## Documentation Guideline 

Note: This guideline only applies to this repository "documents" 

### 1. Overview
   
Welcome to the "documents" repository! This is where you can find all the documentation for our project. To ensure consistency and ease of collaboration, all documentation is maintained in markdown.

We believe that clear and helpful documentation is essential to the success of any project, and we encourage everyone to contribute to its improvement. Whether you find an error, have a suggestion for improvement, or simply want to clarify something, your input is always valuable to us.

Thank you for being a part of this project and helping us make our documentation as clear and helpful as possible. Let's work together to make this project a success!


### 2. How to contribute


1. Browse through the listed issues and choose one that interests you. If you don't find something you like, create a new issue and give it a descriptive title and a clear explanation of the problem.
2. Assign yourself to the issue you wish to work on. This informs other team members that you are actively working on that task.
3. Create a pull request with the issue number and the word "closes" in the description. This helps to link your pull request to the issue, making it easier for others to track your progress. Don't forget to follow the repository's branching strategy which is mentioned below in chapter 3.0
4. Get started on the task assigned to you and work diligently until it is completed.
5. Once you're done, create a review by submitting a merge pull request. This notifies other team members that your work is ready to be reviewed and merged into the codebase.

Following these steps will help you stay organized and work efficiently on the project. Good luck!


### 3. Branching Strategy 

The "documents" repository implements a well-defined branching strategy consisting of two branches - main and draft. 

The main branch serves as the authoritative source of the project documentation, representing the final and approved versions of all documents. 

On the other hand, the draft branch is used for ongoing document development, including creating new documentation, enhancing existing content, and fixing errors. Whenever changes are made to documents in the draft branch, they should be merged back into the main branch to ensure consistency and accuracy across all project documents. 

By adopting this branching strategy, the project team can effectively manage the document development process, avoid versioning conflicts, and ensure that stakeholders have access to the most up-to-date and reliable documentation.

<p align="center">
<img src="https://github.com/Namavoor/documents/blob/main/doc_images/documents_branching-strategy.drawio.png"/>
</p>

#### 3.1. Branch naming

When you do pull request, you create a new branch on draft branch by naming the branch starting with "draft/[the document name you are working on]

For example, "draft/system_development_plan"

#### 3.2. Pull Request description

When submitting a pull request, it is essential to provide clear and concise information for ease of collaboration with others. To do so, it is recommended to include the issue link and issue number in the description. Additionally, a brief explanation of the changes made, updates, fixes, or additions added should be provided, along with the reason behind the changes. This will help the reviewers understand the purpose of the pull request easily and quickly, improving the efficiency of collaboration.


### 4. Adding images 

For adding images to any documents, firstly, it is essential to add the image in "doc_images" folder in the "documents" repository. Then use the link to embed the image in the document. 

