#!/usr/bin/env python
# coding: utf-8

# In[4]:


# 1.Write a Pandas program to create and display a one-dimensional array-like object containing an array of data using Pandas module.
import pandas as pd
l=pd.Series([3,2,4,5,6])
print(l)


# In[5]:


# 2.Write a pandas program to convert a pandas module series to python list
l=pd.Series([3,2,4,5,6])
print(l.tolist())


# In[13]:


# 3.Write a pandas program to add, subtract, multiple and divide two pandas series
l1=pd.Series([3,2,4,5,6])
l2=pd.Series([2,3,4,1,2])
print("Addition of two series:")
print(l1+l2)
print("Subtraction of two series:")
print(l1-l2)
print("Multiplication of two series:")
print(l1*l2)
print("Divide two series:")
print(l1/l2)


# In[16]:


# 4.Write a Pandas program to convert all the string values to upper, lower cases in a given pandas series. Also find the length of the string values.
s="apple"
print(s.upper())
print(len(s))


# In[27]:


# 5.Write a Pandas program to remove whitespaces, left sided whitespaces and right sided whitespaces of the string values of a given pandas series
s1=pd.Index([' a',' p' ,'p','l', 'e '])
print(s1)
print(s1.str.strip())
print(s1.str.lstrip())
print(s1.str.rstrip())


# In[29]:


# 6.Write a Pandas program to create and display a DataFrame consist of student name, father name , mobile number as columns and register number as index.
import numpy as np
l= {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
        'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
        'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
        'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}
labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']

df = pd.DataFrame(l, index=labels)
print(df)


# In[31]:


# 7.Write a Pandas program to get list from DataFrame column headers.
import pandas as pd
import numpy as np
l= {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
        'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
        'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
        'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}
labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']
df = pd.DataFrame(l, index=labels)
print(list(df.columns.values))


# In[32]:


# 8.Write a Pandas program to change the name of the student.
exam_data  = {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
        'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
        'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
        'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}
labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']
df = pd.DataFrame(exam_data , index=labels)
print("Original rows:")
print(df)
print("\nChange the name 'James' to ‘Suresh’:")
df['name'] = df['name'].replace('James', 'Suresh')
print(df)


# In[33]:


# 9.Write a Pandas program to insert a new column “grade” in existing DataFrame.
df = pd.DataFrame({'srNo': [1, 2, 3],'Name': ['Geeks', 'for','Geeks'],'id': [111, 222,333]})
print(df)
print(df.dtypes)


# In[34]:


# 10.Write a pandas program to create and display a dataframe from a specified dictionary data which has the index labels
l= {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin', 'Jonas'],
        'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19],
        'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
        'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}
labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']

df = pd.DataFrame(l , index=labels)
print(df)

