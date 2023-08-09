# CMPG-323-Overview-34212728



# Repository Address

1. Project 1 - Repository: CMPG-323-Overview-34212728 
2. Project 2 - Repository: API-Development - 34212728 
3. Project 3 - Repository: Pattern & Standards - 34212728 
4. Project 4 - Repository: Robotics Process Automation - 34212728 
5. Project 5 - Repository: Data Visualization - 34212728
6. Exam (POE) Submission - Repository: Portfolio of Evidence - 34212728


For each project in the CMPG 323 course, a separate repository will be created, serving as a dedicated space for version control, collaboration, and submission of project-related materials, such as code and documents. These repositories will be structured and grouped under the CMPG 323 Overview project within the GitHub account. Each repository will be equipped with the specified milestones, labels, and README.md file, as outlined in the tasks. This organization ensures a streamlined and organized workflow for managing all the course projects.



# Project and Repository Integration

## Overview

This repository serves as the central hub for organizing and managing all the projects for the CMPG 323 course. Each project has its dedicated repository, and the integration between projects and repositories is crucial for efficient collaboration and version control.

## Diagram

The following diagram depicts the relationship between the projects and their corresponding repositories:

![](https://github.com/KagisoS11/CMPG-323-Overview-34212728/blob/main/Screenshot%202023-08-01%20164850.png)


## How the Integration Works

1. Each of the CMPG 323 course projects (Project 1 to Project 5) has its dedicated repository. Similarly, the Exam (POE) has its separate repository.

2. The CMPG 323 Overview Repository acts as a central hub, linking and connecting to all the individual project repositories.

3. Within each project repository, you can store the respective project's source code, documentation, and other relevant materials.

4. The CMPG 323 Overview Repository utilizes milestones to effectively track project deadlines and important milestones for each project.

5. Labels are used in the CMPG 323 Overview Repository to categorize and manage issues and pull requests that are associated with the various projects.

6. In the README.md file of each project repository, specific project-related details are provided. This includes information about the branching strategy, usage of .gitignore files, and how to handle sensitive information and credentials.

7. By utilizing the Project and Repository views in the GitHub Kanban project, you gain a comprehensive overview of all the projects, their current statuses, and the progress made on each.

With this seamless integration, you can easily navigate between the CMPG 323 Overview Repository and the individual project repositories, ensuring a well-organized and efficient workflow throughout the entire semester. 

Sure, here's a concise and point-form explanation for the README.md:

# Use of .gitignore File:

- Prevents unnecessary files from being tracked and committed.
- Protects sensitive information such as API keys, passwords from exposure.
- Reduces merge conflicts caused by platform-specific files.
- Helps maintain a manageable repository size by excluding large binaries.
- Focuses on essential code and project files, improving navigation.
- Specifies files and directories to ignore based on project needs.

## What to Include in .gitignore:

- Build artifacts and temporary files (e.g., build/, temp/, *.tmp).
- Sensitive information files (e.g., secrets.txt, config.ini, credentials.json).
- Editor-specific files (e.g., .vscode/, .idea/).
- Compiled code and binaries (e.g., *.exe, *.o, *.dll).
- System and hidden files (e.g., .DS_Store, Thumbs.db).

## Maintenance and Updates:

- Periodically review and update .gitignore for new files or dependencies.
- Keep the version control system clean and efficient for collaboration.

Sure, here's a concise and point-form explanation for storing credentials and sensitive information in the README.md:

# Storage of Credentials and Sensitive Information:

- **Never** store sensitive information (e.g., passwords, API keys) directly in the codebase.
- Use environment variables to store sensitive data securely.
- Utilize a configuration file (e.g., config.ini) to keep sensitive details separate from the code.
- Add the configuration file to .gitignore to prevent accidental exposure in version control.
- Share sensitive information only with authorized team members through secure channels.
- Regularly review and update access permissions to maintain data security.

