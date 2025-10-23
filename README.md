# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
```
```python
marks = [13, 45, 63, 78]
student = ['A', 'B', 'C', 'D']
plt.plot(marks, student)
plt.xlabel('Marks')
plt.ylabel('Student')
plt.title('Student Marks')
plt.show()

student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
## Output
<img width="468" height="744" alt="image" src="https://github.com/user-attachments/assets/3ab76862-8534-4a5f-a038-c19dcaf37eef" />

```python
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')

plt.show()
```
## Output
<img width="475" height="729" alt="image" src="https://github.com/user-attachments/assets/8c5fed06-aae3-449e-aa8f-f97efda3d822" />

```python
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```
## Output
<img width="389" height="690" alt="image" src="https://github.com/user-attachments/assets/92ad5632-3d5a-444d-b1f9-0701800d6111" />

```python
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```
## Output
<img width="471" height="352" alt="image" src="https://github.com/user-attachments/assets/9ae3add2-5a67-4228-a1ef-46245bff20ed" />

```python
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```
## Output
<img width="473" height="386" alt="image" src="https://github.com/user-attachments/assets/e7d10659-5fbf-48fa-ad53-5f71f1f1398c" />

```python
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
## Output
<img width="450" height="353" alt="image" src="https://github.com/user-attachments/assets/4242d737-f64b-4235-8c09-0fd2a0078569" />

```python
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
## Output
<img width="460" height="290" alt="image" src="https://github.com/user-attachments/assets/ca729242-b833-44e9-9b03-19b6b5f41132" />

```python
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
## Output'
<img width="475" height="400" alt="image" src="https://github.com/user-attachments/assets/caf5e79c-9d79-43cd-930b-d4d3991a42b9" />

# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
