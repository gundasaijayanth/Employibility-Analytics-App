
# Employability Analytics Application  
**A Power BI Dashboard for Career Insight, Skill Gap Detection, and Salary Benchmarking**



## Project Description

The Employability Analytics Application helps job seekers and career advisors analyze job market trends, identify skill gaps, and make informed career decisions. Built using Power BI and driven by a curated dataset of global job postings, this dashboard visualizes salary ranges, work types, roles, required skills, and geographical distribution of opportunities.



## 📂 Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Live Dashboard](#live-dashboard)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)



## Installation

No code installation required for the Power BI Dashboard. However, to explore or modify the dataset:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/employability-analytics.git
cd employability-analytics
```


## Usage
To explore the Power BI dashboard:
```bash
Open Power BI Desktop → Import the dataset (.csv) → Load visuals and explore filters.
```
To run skill or salary analysis manually:

-   Use Python scripts or Excel formulas (included in `/scripts` or `/analysis-tools` folder).


## Features
-   **Skill Gap Analysis**: Compare user skills with job requirements.
    
-   **Salary Benchmarking**: View salary trends across roles and countries.
    
-  **Career Mapping**: Identify roles that match qualifications and experience.
    
-  **Location-Based Insights**: Discover job density using geographic mapping.
    
- **Work Type Trends**: Analyze full-time, contract, intern roles globally.


## 📁 Project Structure

```bash
employability-analytics/
├── data/                         # Contains the sampled_job_descriptions dataset (CSV/Excel)
├── visuals/                      # Power BI report files (.pbix) and image previews
├── docs/                         # Reports, roadmap, design documents, and deliverables
├── analysis/                     # Python scripts or Jupyter notebooks for extra analysis
├── src/                          # Source code (if any backend logic is added)
│   ├── __init__.py
│   ├── preprocessing.py          # Data cleaning and preprocessing logic
│   ├── skill_analysis.py         # Skill gap and qualification matching logic
├── dashboard.html                # (Optional) Embedded Power BI Dashboard for GitHub Pages
├── requirements.txt              # Python dependencies (if applicable)
├── README.md                     # Project overview and usage guide
└── LICENSE                       # Project license (MIT)
```


## Live Dashboard
Check out the published Power BI dashboard here: [View Dashboard]



## Dashboard Preview
![image](https://github.com/user-attachments/assets/6b7225db-fd6c-4488-8911-ec0138bf586b)


## Contributing
Pull requests are welcome!  
For major changes, please open an issue first to discuss your proposed updates.

## License
MIT License. See [LICENSE](LICENSE) for more details.

## Acknowledgements
-   **Power BI** for the visualization tools
    
-   All team members of IS-5960-03 Team 8 at Saint Louis University
    
-   Prof. Maria Weber for her guidance and feedback
