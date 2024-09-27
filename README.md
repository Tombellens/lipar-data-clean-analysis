# README: A Career Dataset of Flemish Ministerial Advisors (1999-2020)

## Overview
This project introduces a comprehensive dataset on the career paths of 754 Flemish ministerial advisors (MAs) spanning from 1999 to 2020. The dataset covers key variables such as gender, age, educational backgrounds, and career trajectories. By leveraging both traditional government rosters and online sources like LinkedIn, the dataset provides valuable insights into the backgrounds of these influential actors in Flemish policy.

This research was carried out as part of my PhD at **KU Leuven** and serves as a significant contribution to elite career studies, offering a rich foundation for future research into the roles and paths of ministerial advisors in Belgium.

A **temporary draft** of the research note detailing the dataset is also included in the repository.

## Key Objectives
1. **Dataset Creation**:  
   To create a comprehensive and detailed dataset on Flemish MAs, with a focus on their gender, age distribution, education, and career paths before, during, and after their service in ministerial offices.

2. **Data Collection**:  
   The dataset was created using a combination of government rosters and LinkedIn profiles, parsed and processed using machine learning techniques. It involved steps like name identification, career data collection, and data coding.

3. **Descriptive Analysis**:  
   The research provides an initial exploratory description of the data, addressing key aspects such as gender balance, educational backgrounds, pre-cabinet experience, and post-cabinet career paths of Flemish MAs.

## Methodology
- **Data Sources**:  
   - **Government Rosters**: Annual lists from the Flemish government, covering ministers and their advisors.
   - **LinkedIn Profiles**: Scraped and parsed using machine learning to extract career positions, educational background, and other relevant details.
   
- **Data Processing**:  
   - The data was processed using a PostgreSQL database with a Flask-based backend and an Angular front-end interface.
   - Zero-shot learning and GPT-based models were employed to extract and structure data from LinkedIn profiles into JSON format.

- **Data Coding**:  
   - Positions were coded according to sector and role, using categories such as private sector, public sector, civil society, academia, and various political categories (ministerial offices, legislatures, etc.).

## Key Findings
- **Gender Distribution**:  
   Approximately 39.05% of Flemish MAs in the dataset are female, with significant variations across different ranks within ministerial cabinets.
   
- **Educational Background**:  
   76.56% of MAs hold a Master’s degree, and many possess multiple advanced degrees, particularly in public management and business.

- **Pre-Cabinet Experience**:  
   On average, MAs held 2.6 career positions before entering ministerial offices, with significant representation from the private sector, civil society, and academia.

- **Post-Cabinet Career Paths**:  
   After serving in ministerial offices, many MAs transitioned to roles in the civil service (24.91%) or the private sector (12.29%), indicating the stepping-stone nature of these positions.

## Citation
If you use this work, please cite:
- **Bellens, T. & Bellens, J. & Brans, M.** (2024). *A Career Dataset of Flemish Ministerial Advisors (1999-2020): Leveraging Online Data Sources*. Research Note, KU Leuven.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For more information, please contact the authors via the repository link or email provided in the paper.
