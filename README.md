COVID-19 Visualization and Insights Hub - An Interactive Power BI Dashboard for COVID-19 Trends

a. Project Overview
    The COVID-19 Visualization and Insights Hub is an interactive Power BI dashboard that provides insights into COVID-19 trends, including case progression, test positivity rates, and mortality statistics. The project aims to help researchers, healthcare professionals, and policymakers analyze COVID-19 data effectively through dynamic visualizations.

Key Features:
  Interactive Filters – Analyze data based on different timeframes and locations.
  Trend Analysis – Line graphs, histograms, and bar charts to track case progression.
  ETL Process – Data cleaning and preprocessing using SQL Server & Excel.
  The project repository is managed using GitHub for version control, ensuring structured collaboration,     
  efficient change tracking, and version management.

b. Repository Structure
      The project repository is structured as follows:
        Covid-Insights/ (Main repository folder)
        COVID_INSIGHTS.pbix (Power BI report file containing dashboards and insights)
        COVID_DATA.csv (Dataset used for Power BI visualizations)
        README.md (Project documentation and setup guide)

c. Setup Instructions
    Prerequisites
      Before running the project, ensure you have the following:
      	•	Power BI Desktop installed on your system
      	•	A GitHub account to manage version control
      	•	Visual Studio Code (VS Code) for Git integration
    Steps to Set Up the Project Locally
        Clone the Repository:
          git clone https://github.com/DurgaPrasanna86/Covid-Insights.git
          cd Covid-Insights
        Open the Power BI File and Explore Visualizations and DAX measures

d. Version Control & Branching Strategy
        We used GitHub and Git to track changes, manage feature development, and collaborate effectively.            Our workflow includes:
          Branching Strategy
                Main Branch (main) – Stores the stable version of the project
                Feature Branches – Used for developing and testing new updates
          Git Commands Used
              Cloning Repository:
                    git clone https://github.com/DurgaPrasanna86/Covid-Insights.git
              Creating a Feature Branch:
                    git checkout -b feature-branch-name
              Committing Changes:
                    git add COVID_INSIGHTS.pbix
                    git commit -m "Updated Power BI report with new measures"
              Pushing Changes to GitHub:
                    git push origin feature-branch-name
              Merging Feature Branch into Main:
                    git checkout main
                    git merge feature-branch-name
                    git push origin main
              Tagging a Release:
                    git tag -a v1.0 -m "Initial stable release"
                    git push origin v1.0

e. How to Contribute?
    Fork the repository
	  Create a new branch for your feature
	  Make changes and test in Power BI
	  Commit your changes with meaningful messages
	  Push the branch and create a Pull Request (PR)
	  Wait for the PR to be reviewed and merged

f. Change Control Process
        Identifying Changes:
            Data updates, new measures, or visual improvements in Power BI
        Creating a Feature Branch:
	          Developers create separate branches for each update
        Testing and Validation:
	          Each change is tested locally before committing
        Review and Merge:
	          A Pull Request (PR) is reviewed by team members before merging into the main branch
        Tagging Releases:
	          Major updates are tagged for version tracking

    Thank you for exploring the COVID-19 Visualization and Insights Hub!
    











       
