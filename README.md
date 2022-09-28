# workshop-Multivariate-analysis
AIM:

To perform multivarient analysis on the given data set.

ALGORITHM:

1.clean the data
2. Remove outliers
3.Apply the skew function and kurtosis
4.Apply bivarient analysis on numerical and categorical
5.Apply multivarient analysis

CODE: 
DETECTING NULL AS PD:

![image](https://user-images.githubusercontent.com/114581999/192780519-6331eb58-5953-4b44-b5ce-805e46e9d42c.png)

INFO:

![image](https://user-images.githubusercontent.com/114581999/192780576-7cdfe12b-9516-4615-aaa0-895f53db94f1.png)

REMOVING NULL DATA:

![image](https://user-images.githubusercontent.com/114581999/192780695-75d57f96-b6b8-43bc-8578-981afa93c770.png)

KURTOSIS:

![image](https://user-images.githubusercontent.com/114581999/192780796-9278dd01-1f7a-4746-9cd3-1e9b66f1c2a2.png)

SKEW:

![image](https://user-images.githubusercontent.com/114581999/192780873-3c4d75f6-6b38-479c-9506-aadae0696f7c.png)

NUMERICAL & NUMERICAL:

![image](https://user-images.githubusercontent.com/114581999/192780952-ad0deeb5-d372-439b-83ac-7081620afc72.png)

NUMERICAL & CATEGORIAL:

BOX PLOT:

![image](https://user-images.githubusercontent.com/114581999/192781084-e6ff0bad-2acf-4448-9104-39a96133c571.png)

BAR PLOT:

![image](https://user-images.githubusercontent.com/114581999/192781157-3880ab8e-f14e-4f6a-be5d-a3e4844e692a.png)

DIST PLOT:

![image](https://user-images.githubusercontent.com/114581999/192781276-8b6f80fd-8ca3-4a63-a472-281379cf5b4d.png)

MULTIVARIENT ANALYSIS:

CORRELATION:
![image](https://user-images.githubusercontent.com/114581999/192781387-da04b4a5-e2cc-4754-be82-a9c04d797a9d.png)

HEAT MAP:

import numpy as np

import seaborn as sn

import matpIotIib.pypIot as pit

data= pd.read_csv("/content/Data_set.csv")

data = np.random.randint(low = 1, high = 100, size = (10, 10)) print("The data to be plotted:\n")
print(data)

hm = sn.heatmap(data = data)

pit.show()

![exp 0444](https://user-images.githubusercontent.com/114581999/192781778-49357100-2792-4b7e-8f43-0d34e82bb22b.png)

