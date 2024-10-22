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
```
import matplotlib.pyplot as plt

x=[1,2,3]
y=[2,4,1]

plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')

plt.title('Two lines on the same graph')

plt.legend()

plt.show()
```
![image](https://github.com/user-attachments/assets/ade639af-0d60-4443-b64e-16235a690975)

```
x1=[1,2,3]
y1=[2,4,1]

plt.plot(x1,y1,label='line 1')

x2=[1,2,3,]
y2=[4,1,3]

plt.plot(x2,y2,label='line 2')

plt.xlabel('x-axis')
plt.ylabel('y axis')

plt.title('Two lines on the same graph!')

plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/0acd62c1-27f3-4bbb-b2ca-df24fd2451c5)

```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]

plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)

plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')

plt.title('Some cool customization')

plt.show()
```
![image](https://github.com/user-attachments/assets/28a4b676-98c9-440e-8403-a9949f44563d)
```
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yeild_apples)

```
![image](https://github.com/user-attachments/assets/3b565473-4730-459e-8888-80752c48140c)

```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)

```
![image](https://github.com/user-attachments/assets/cf616547-fa4f-4cac-b50e-a30dad37205f)
```
years=range(2000,2012)

apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.93,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]

plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('year')
plt.ylabel('Yield (tons per hectare)')

plt.title('Crop Yeilds in kanto')
plt.legend(['apples','oranges'])
```
![image](https://github.com/user-attachments/assets/e9886cc6-8ec4-4ee2-b6a7-6cee6b485e1b)

```
import matplotlib.pyplot as plt

x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color='blue')
plt.show()
```
![image](https://github.com/user-attachments/assets/55b1f65a-6c64-4be7-ad19-25b840bce574)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]

plt.scatter(x,y,label='stars',color='green',marker='*',s=30)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title(' My Scatter Plot')
plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/3fca1103-a7a6-42c9-9799-82d3016fe30e)

```
```


# Result:
 Include your result here
