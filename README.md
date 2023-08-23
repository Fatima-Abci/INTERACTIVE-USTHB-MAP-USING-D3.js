# INTERACTIVE-USTHB-MAP-USING-D3.js
## ABOUT THE PORJECT
Visualizing the activities of the Computer Science faculty at USTHB (University of Science and Technology Houari Boumediene) using the **D3.js library**.
## FUNCTIONALITIES
Before presenting the functionalities of the project, let's take a look at a visual overview of the USTHB map.
<p align="center"> 
<img src="https://github.com/Fatima-Abci/INTERACTIVE-USTHB-MAP-USING-D3.js/blob/master/images/map.png" alt="USTHB map" width="850" height="400">
</p>

### STUDENTS
---
Visualizing how computer science students utilize classrooms based on their field of study, chosen time slot, and the specified day. The classroom associated with the selected field will be highlighted in green, while classrooms related to other fields will be colored in red.
<p align="center"> 
<img src="https://github.com/Fatima-Abci/INTERACTIVE-USTHB-MAP-USING-D3.js/blob/master/images/students_functionality.png" alt="students fuctionality" width="850" height="400">
</p>

**When a user hovers over a highlighted classroom, a tooltip will be displayed, showing all the information about it.**

### TEACHERS
---
visualizing the classrooms used by a specific teacher, those classrooms will be colored in orange. 
<p align="center"> 
<img src="https://github.com/Fatima-Abci/INTERACTIVE-USTHB-MAP-USING-D3.js/blob/master/images/teachers_functionality.png" alt="teachers fuctionality" width="850" height="400">
</p>

## USAGE
- `usthb.geojson` represents the map of USTHB and it was created using https://geojson.io/#map=2/0/20.
- `dataF.json` contains all the schedules of the computer science faculty.
- `index.html` holds all the logic of the project.
- `styles.css` was used for the visual design and layout of the project.
