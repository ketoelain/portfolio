# Data Scientist

### Education

### Work experience
Data scientist @ University Hospital Frankfurt am Main

### Projects
#### 1 Web-based Dashboard on ECMO utilization in Germany: An interactive visualization, analyses, and prediction based on real-life data
The purpose of this project was to create a dashboard to visualise publicly available treatment data on extracorporeal membrane oxygenation (ECMO) in Germany. The data was sourced from the Federal Statistical Office of Germany and from the quality reports of the “Gemeinsame Bundesauschuss” (GBA) and was fully anonymised upon delivery.
ECMO Dashboard provides visualised information on conducted ECMO runs on annual basis from 2006 to 2020 as well as number of patients and their origins from 2005 to 2021. The dashboard also includes patient forecasts for the years 2022 and 2023. Due to delay in data availability the forecasts lie in the past.
ECMO Dashboard was created using Python and Plotly Dash. The data was parsed, merged, and processed using Python and Numpy & Pandas libraries. The quality reports consisted of several xml files from each individual hospital in Germany and the data contained therein was parsed using custom Python scripts. The design of the dashboard was created according to the requirements of our medical colleagues at Frankfurt University Hospital. 

You can visit ECMO Dashboard at:

https://ecmo-dash.de/

https://ecmo-project.de/

You can also see our publication at:
https://doi.org/10.1007/s10916-024-02068-w.

#### 2 ECMO Reader: an open-source data acquisition and analysis system for extracorporeal membrane oxygenation devices
This project introduces an open-source Python program with a graphical user interface for managing and visualising extracorporeal membrane oxygenation data in real-time. It was developed for Getinge ECMO devices (CardioHelp, Rotaflow I, Rotaflow II; ECMO devices used at Frankfurt University Hospital) and it allows the cyclical measurement data (blood temperature, pressures, pump parameters etc.) to be recorded and visualized (in real-time) in a structured way. It also enables documentation of custom treatment events (e.g. visitations, oxygenator changes, patient transports, and complications). 
The purpose of this projects is to create a tool that subsequently allows the creation of medical datasets that can be used to analyse and to potentially improve patient outcomes. By documenting treatment events via manual input create end points that can be used in analysing the recorded measurement data. This opens the doors for the creation of machine learning models that can be used in real-time to predict changes in patient condition before their onset.
The software also visualises the measurement data in real time during the treatment. This in turn potentially allows the medical staff to recognise trends in the data that may hint at approaching complications. This additional help can allow the medical experts to intervene before potential complications have time to clincally manifest. 
The software runs on a Raspberry Pi 4B with an integrated touchscreen. It includes a lithium ion battery for seamless operation when an external power source is not available. 

#### 3 Project ENVISION
Project ENVISION was a project involving by a multidisciplinary public-private consortium with the purpose of developing an existing digital tool used at multiple hospitals in Germany (Sandman.MD, a digital anaesthesia documentation tool for surgeries), to an intelligent decision-support system for monitoring, prediction and treatment of COVID-19 patients in ICUs – the Sandman.IC. The Sandman.IC is built to be integrated into an AI-driven data analytics suite with predictive modelling tools and smart alert functionality. The digital tool validation was initiated in intensive care units of 13 hospitals across Europe.
Our collective efforts were managed and coordinated by our team at Frankfurt University Hospital. My role in our work was to coordinate the development of Sandman.IC according to the requirements and specifications of the medical partners of our project. This involved close cooperation with our private sector partner responsible for the developtment of the app, as well as our AI experts at Tampere University in Finland for the creation and integration of the AI components of the system. 
The data we used in our project was sourced from multiple hospitals. Another big part of my work involved coordinating and managing the data collection at our clinical partners. This meant processing and combining heterogenous datasets in multiple languages, anonymising the datasets to comply with GDPR and our project's requirements, as well as harmonising the collected data to be used in training our machine learning models.


You can check out our project and its results at:
https://www.envision-icu.eu/.


#### 4 Evolution of a theranostic applicator for microwave ablation treatment
This project was set up to further develop an MRI-compatible, novel dual-mode microwave applicator for diagnosis and thermal ablation treatment. My part of the work involved measuring and evaluating the image artefacts caused by the microwave applicator. This is relevant for the accurate placement of the applicatior during treatment. 
The MR images were acquired with Siemens Magnetom Aera 1.5 Tesla using several imaging sequences (T1-TSE, T2-TSE, T1-FLASH, T1-VIBE). The artefact measurement was conducted using an automated, custom-made script created in MATLAB. The definition of an image artefact was adopted from the American Society for Testing Materials, defining an artefact as a ±30 % deviation from the median background intensity. The artefact diameters were measured at the widest position along the applicator shaft, near the applicator tip, and along the applicator shaft. The statistical analysis of the measurements was conducted using Microsoft Excel. 

You can find the publication for our work at:
https://doi.org/10.1515/freq-2022-0088.
