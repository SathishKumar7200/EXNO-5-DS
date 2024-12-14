# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:
        Include the necessary Library.

STEP 2:
        Read the given Data.

STEP 3:
        Apply data visualization techniques to identify the patterns of the data.

STEP 4:
        Apply the various data visualization tools wherever necessary.

STEP 5:
        Include Necessary parameters in each functions.

# Coding and Output:
 from google.colab import drive
drive.mount('/content/drive')


![Screenshot 2024-12-14 222341](https://github.com/user-attachments/assets/8d5499e0-d25d-485b-b222-cff39b3c43b9)

import matplotlib.pyplot as plt
x_values=[0, 1, 2, 3, 4, 5]
y_values=[0, 1, 4, 9, 16, 25]
plt.plot(x_values, y_values)
plt.show()


![Screenshot 2024-12-14 222353](https://github.com/user-attachments/assets/43e39fdc-218d-4e3c-becb-429e098091bf)

import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()


![Screenshot 2024-12-14 222424](https://github.com/user-attachments/assets/c24ad533-ba96-4196-b7bc-599682db6ca0)

x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()


![Screenshot 2024-12-14 222437](https://github.com/user-attachments/assets/1a10d622-a808-471d-8a84-62c0bbc7ec5f)

x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()


![Screenshot 2024-12-14 222447](https://github.com/user-attachments/assets/d16a5e2e-3a61-4225-b553-cd24e487f88f)

yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)


![Screenshot 2024-12-14 222459](https://github.com/user-attachments/assets/91a62e7f-29a2-4284-a113-0cd08c4911e8)


years=[2010,2011,2012,2013,2014,2015]
yields=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years, yields)


![Screenshot 2024-12-14 222511](https://github.com/user-attachments/assets/ecfc7415-dee7-4ec1-a1f0-af9c4626e8f2)

years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.932,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('years')
plt.ylabel('Yield (tons per hectare)');


![Screenshot 2024-12-14 222524](https://github.com/user-attachments/assets/081577eb-3913-499c-bdcc-9f0c5215abd9)


plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('years')
plt.ylabel('yield (tons per hectare)')
plt.title("crop yields in kanto")
plt.legend(['apples', 'oranges']);


![Screenshot 2024-12-14 222537](https://github.com/user-attachments/assets/ef586772-af45-4665-a7c9-97604f624408)

years=[2010,2011,2012,2013,2014,2015]
yields=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yields)
plt.xlabel('years')
plt.ylabel('yield (tons per hectare)');


![Screenshot 2024-12-14 222548](https://github.com/user-attachments/assets/5c5ae2ca-018b-4c7e-83d5-df01c2c56abc)

years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.xlabel('years')
plt.ylabel('yield (tons per hectare)')
plt.title("Yields of Oranges (tons per hectare)");


![Screenshot 2024-12-14 222600](https://github.com/user-attachments/assets/0b0c445f-3caf-40cf-92d4-0e30c440b512)

years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.932,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('years')
plt.ylabel('yield (tons per hectare)')
plt.title("crops yields in kanto");
plt.legend(['apples','oranges'])


![Screenshot 2024-12-14 222612](https://github.com/user-attachments/assets/70623f6c-d2a4-42ef-a385-be365190a94b)

x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()


![Screenshot 2024-12-14 222621](https://github.com/user-attachments/assets/4e61d61a-0e28-410b-9283-567642ad9314)

x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My Scatter plot!')
plt.legend()
plt.show()


![Screenshot 2024-12-14 222632](https://github.com/user-attachments/assets/774bfb7f-f4f5-425c-9fc6-f70eae7aeed0)

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

x=np.arange(0,10)
y=np.arange(11,21)



x


![Screenshot 2024-12-14 222643](https://github.com/user-attachments/assets/7e831b23-7550-44b6-93cf-ba0df9956ce1)

y


![Screenshot 2024-12-14 222653](https://github.com/user-attachments/assets/c742274d-27b7-48bd-a744-dcd53901ece6)

plt.scatter(x,y,c='r')
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')


![Screenshot 2024-12-14 222708](https://github.com/user-attachments/assets/ddb5f321-ab55-4313-a9bc-5de6ab712cab)

y=x*x
y


![Screenshot 2024-12-14 222720](https://github.com/user-attachments/assets/b7236f33-a5a8-4acc-a9d8-d89e2f6ae8d0)

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.title('2D diagram')
plt.ylabel('Y axis')
plt.xlabel('X axis')


![Screenshot 2024-12-14 222733](https://github.com/user-attachments/assets/d7fa2dff-99cc-4e7c-98ae-a7a1707cc2c0)

plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*-')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')


![Screenshot 2024-12-14 222749](https://github.com/user-attachments/assets/487f8d82-e80e-4924-9d9b-64a9884920d9)

np.pi


![Screenshot 2024-12-14 222757](https://github.com/user-attachments/assets/5af13cbe-293a-45b8-a87b-0aa26064dc00)

x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()


![Screenshot 2024-12-14 222807](https://github.com/user-attachments/assets/2ad95354-0e32-4955-91cd-41a56b6ce4bc)

import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()


![Screenshot 2024-12-14 222818](https://github.com/user-attachments/assets/b74ef0f1-857a-46eb-a444-787a83b9f9de)

plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()


![Screenshot 2024-12-14 222829](https://github.com/user-attachments/assets/ead303a6-8ed9-4bcb-a38c-005e538727ec)

import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth = np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()


![Screenshot 2024-12-14 222841](https://github.com/user-attachments/assets/d5fd7de7-d1df-446b-974b-8f652fb9b359)

import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color='green')
plt.show()


![Screenshot 2024-12-14 222850](https://github.com/user-attachments/assets/63293d64-3abf-42d7-8b0f-951f9d18c4c8)

plt.barh(names,values,color='yellowgreen')
plt.show()


![Screenshot 2024-12-14 222859](https://github.com/user-attachments/assets/d3bb17f9-fff8-41f7-b141-934773db3487)

height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-label')
plt.title('My barchart!')
plt.show()


![Screenshot 2024-12-14 222910](https://github.com/user-attachments/assets/ff4ceb5a-183a-4bb9-bad6-da3d42b2cec9)

x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('y axis')
plt.xlabel('x axis')
plt.show()


![Screenshot 2024-12-14 222941](https://github.com/user-attachments/assets/38806149-7035-4347-99b7-24875f954a16)

ages=[2,5,70,40,30,45,50,45,43,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no. of people')
plt.title('My histogram')
plt.show()


![Screenshot 2024-12-14 222951](https://github.com/user-attachments/assets/56956a81-5346-495a-abc1-ff9edcb97648)


x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()


![Screenshot 2024-12-14 223001](https://github.com/user-attachments/assets/04931945-459c-4320-837a-5d648d2dfccc)


import matplotlib.pyplot as plt
import numpy as np

np.random.normal(loc=0,scale=1,size=100)
data=np.random.normal(loc=0,scale=1,size=100)
data


![Screenshot 2024-12-14 223012](https://github.com/user-attachments/assets/a30c4e46-cef2-499d-a679-65d5a171b7e9)


fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Value')
ax.set_title('Box Plot')
plt.show()


![Screenshot 2024-12-14 223022](https://github.com/user-attachments/assets/70734de8-7c29-4073-bf42-da9799e5e211)

activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()


![Screenshot 2024-12-14 223032](https://github.com/user-attachments/assets/e76f63d7-efef-4258-b5a0-c00456afce9b)

labels='python','c++','c','java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()


![Screenshot 2024-12-14 223045](https://github.com/user-attachments/assets/edcb8b19-19c8-47f7-9f06-36c5e4410651)

activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()


![Screenshot 2024-12-14 223058](https://github.com/user-attachments/assets/70195241-c7c0-41f1-8599-8a05293dbe56)

# Result:
       The above code is excuted successfully.
