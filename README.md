# Pymaceuticals Inc. Analysis

The Jupyter Source file `pymaceuticals.ipynb` reads in 2 datasets (`Mouse_metadata.csv` and `Study_results.csv`) from the `data` folder. Pandas library was imported to create and merge DataFrames, Scipy library was imported to help with statistical analysis and Matplotlib library was imported to help creating various type of data visualization.

Findings:
- There are in total 10 types of drug regimens tested on mice in this study, with 9 treatments and 1 placebo. "Capomulin" was tested 230 times, being the drug regimen tested the highest number of times on mice comparing to all other drug regimens. Following by "Ramicane" tested 228 times, and "Ketapril" tested 188 times.

  ![image](https://user-images.githubusercontent.com/120543690/221255084-2fe0338d-2348-453d-b1bd-ac684e0337e4.png)

- Out of all mice tested (after removing all data for the duplicate mouse), 49% were female and 51% were male.

  ![image](https://user-images.githubusercontent.com/120543690/221255293-41a4196d-3954-4a7b-8832-96ac2d94db32.png)

- Looking at the distribution of the final tumor volume of each mouse across four of the treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin), mice tested with "Ramicane" seem to have the lowest median final tumor volume. Mice tested with "Infubinol" have the highest median final tumor volume, slightly above the second highest median final tumor volume for mice tested with "Ceftamin".

  ![image](https://user-images.githubusercontent.com/120543690/221255440-941a7a47-e7a0-4ddf-a175-cc536fd23650.png)

- Looking at the tumor volume change over time for the mouse (ID l509) treated with "Capomulin", the tumor volume increased steadily from days 0 to 20, then has a general downward trend for tumor volume from days 20 to 35 and a slight upward trend after day 35.

  ![image](https://user-images.githubusercontent.com/120543690/221255529-fe2e31ec-cc9e-4421-a2e6-a51d09e77c95.png)

- There is a fairly strong positive relationship existing between the average tumor volume and mouse weight for mice treated with "Capomulin" regimen (correlation coefficient between the two variables is 0.84). The marjority of points on the scatterplot lies fairly close to the line of best fit.

  ![image](https://user-images.githubusercontent.com/120543690/221255629-93e3445c-831f-4479-a2e8-03066a2d93aa.png)

