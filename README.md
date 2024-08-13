### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 
### AIM: 
To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
### Buying Table:
![Screenshot 2024-08-13 091751](https://github.com/user-attachments/assets/c30a6346-9264-47c8-83f4-5cfc60e496ac)
### Banking Table:
![Screenshot 2024-08-13 092014](https://github.com/user-attachments/assets/04d68c4d-1912-4e00-9b30-51c912edab6d)
### Employee Table:
![Screenshot 2024-08-13 092158](https://github.com/user-attachments/assets/40702c7f-ed6f-48ff-91bd-47387aee2614)

### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
### Buying Table:
![Screenshot 2024-08-13 092535](https://github.com/user-attachments/assets/e06f0d13-12e2-4f8c-bf65-5a0f4b860909)
### Banking Table:
![Screenshot 2024-08-13 092857](https://github.com/user-attachments/assets/247d9f04-eada-4f4d-94e0-bd4f9520896f)
### Employee Table:
![Screenshot 2024-08-13 093016](https://github.com/user-attachments/assets/9ae1d660-ee4f-4b6b-89c7-66bee1824f46)

### RESULT: 
Thus, generation of association rules using apriori algorithm is executed succesfully.
