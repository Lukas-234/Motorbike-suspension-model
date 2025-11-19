# Motorbike-suspension-model
This is our group project on modelling the suspension system on a motorbike. With the aim of finding a spring coeffcient and damping coefficient that minimises vertical rider acceleration.

## What does each file do:
- The main file to use will be the "Final Run" folder.
- The following files: "Data analysis", "ODE Files", "Root finding" all are the draft codes that were used to contribute to the final code. These should not be used.
- The Final report will be located next to the README

## How to run the code:
All files to run the final code will be in the "Final Run" folder. It includes the final code itself as well as all the data to run the code.

## Changing conditions
To add or remove roads, scroll to the relevant section of code (line 762) and remove or add as desired
To change parameters scroll to the relevant secrtion of the code(line 747) and change as desired. 


## How to obtain new road data:
1. Open google earth pro
2. Using the path tool on google earth create a path over a chosen road (to increase accuracy have as many points as possible on the road)
3. Save that path file as a kmz file
4. Go to this website:  https://www.gpsvisualizer.com/elevation
5. With the website above, save the lattitude, longitude, and altitude data as a text file
6. Open that text file in excel and save it as a .xlsx file


## Where to find all numerical methods in the code
Root Finding:
4-376

Interpolation/ Data analysis:
450-493

ODEs:
495-573
