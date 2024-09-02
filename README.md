# Extended research project
**Title**: An Investigation of Trust in Automated Performance Reviews from Various Professional Perspectives

**Description**: This project aims to develop a questionnaire to measure trust in workplace automation and identify distinct participant groups based on their trust levels, providing insights into whether strategies for adopting automated performance reviews should be more tailored to specific contexts. It aims to answer the following questions:

**RQ1**: Is the developed questionnaire a reliable measure of trust in automated systems?

**RQ2**: Do Professional Types reveal differing attitudes towards automated systems?

**RQ3**: Can alternative groupings provide clearer insights than Professional Types into attitudes towards automated systems?
The objective of this repository is to allow for the reproduction of the methods used in said report

## 1. Table of Contents
- [Installation](#2-installation)
- [Data](#3-data)
- [Usage](#4-usage)
## 2. Installation
### Python
This project was developed using Python (v. 3.11.7) and Anaconda. It is recommended that the project is run using JupyterLab (v. 3.6.7). Ensure that you have installed all necessary libraries before running the code.
## 3. Data
This project is based around data recovered from participants in a questionnaire. The questionnaire in question went through 3 pilots, and then went live. While the questionnaires and their data cannot be shared due to privacy laws, the links to the previews to all pilots and the main questionnaire are available.

Pilot 1: https://www.qualtrics.manchester.ac.uk/jfe/preview/previewId/ee08e234-157a-4974-bc92-7956ffc0518f/SV_1SwXjS9P4YUpW7k?Q_CHL=preview&Q_SurveyVersionID=current

Pilot 2: https://www.qualtrics.manchester.ac.uk/jfe/preview/previewId/e845f5d3-bfcb-4c80-adbd-266c0b979472/SV_2hk3eK6xwMdAMyW?Q_CHL=preview&Q_SurveyVersionID=current

Pilot 3: https://www.qualtrics.manchester.ac.uk/jfe/preview/previewId/012695b3-99ed-4566-8829-592fe1d570c6/SV_ahfDx0sGGi1BITY?Q_CHL=preview&Q_SurveyVersionID=current

Questionnaire: https://www.qualtrics.manchester.ac.uk/jfe/preview/previewId/b01ee86f-eb89-4655-8fd0-6d0742245127/SV_bBGWiAb74TZLSLQ?Q_CHL=preview&Q_SurveyVersionID=current

You may use these previews to remake the questionnaire if you so wish, so as to obtain data with which to use the .ipynb files available in this repository.
## 4. Usage
Once you have the data, ensure that the columns are the same as those found in the empty_data.xsl file, including the separate Data and Metadata sheets. This will ensure that the code runs with no issues.
First, run the GeneratingCSVs.ipynb file, in order to generate and save the required dataframes for ExploringDataframes to run without issues. Read each function's description and what it does carefully, and then you can run the code to generate images similar to those in the CSDI-11418910-report.pdf file, or you can add your own code to it to explore the datasets on your own using the functions therein. In order to properly redo what was done in the original experiment, simply run the file without changing the code.
