## What is Pandas?

* Officially stands for **Python Data Analysis Library**.
* It is an open-source Python library.
* It is a tool used by data scientists to:
  * read,
  * write,
  * manipulate, and
  * analyze the data.




## Why Pandas?

* It helps you explore and manipulate data efficiently.
* It helps you analyze large volumes of data with ease. When we say large volumes, it can be in **millions of rows/records**.




## Why is Pandas so Popular?

* Easy to read and learn
* Extremely fast and powerful
* Integrates well with other visualization libraries



## Importing Pandas

Anytime you want to use a library in Python, the first step is to make it accessible.

You can import/load Pandas in your notebook or any other Python IDE in two different ways:

* **`import pandas`**
* **`import pandas as pd`**

Just as we use the 'np' shorthand for NumPy, we will use the 'pd' shorthand for Pandas. It simply serves as an alias, and it is easier to use 'pd' instead of writing the full form ‘pandas’ while coding.

In this course, we will use **`import pandas as pd`**.


## What is a CSV file?








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d9f0b76fe56547028e47aadd24a72420.png)









* CSV files are usually created by programs that handle large amounts of data. They are a convenient way to export data from spreadsheets and databases and import or use them in other programs.
* CSV is a simple file format that stores tabular data, such as a spreadsheet or database.
* A CSV file stores tabular data (numbers and text) in plain text.
* Each line of the file is a data record/row.
* Each record consists of one or more fields, separated by commas.
* The use of the comma as a field separator is the source of the name for this file format.



## What does a CSV file look like?









![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3d8387f243f04387b7e26c2dfb87fef2.png)










## Working with CSV files in Python

* For working with CSV files in Python, there is an inbuilt module named csv.
* However, a common method for working with CSV files is using Pandas. It makes importing and analyzing data much easier.
* One crucial feature of Pandas is its ability to write and read Excel, CSV, and many other types of files.




## Pandas read_csv

* Functions like the Pandas read_csv() method enable you to work with files effectively.
* The read_csv() function reads the CSV file into a DataFrame object.
* A CSV file is similar to a two-dimensional table, and the DataFrame object represents a two-dimensional tabular view.
* The most basic way to read a CSV file in Pandas:




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_05cbcb6e9bd7452ca0a20d6632799f3c.png)



* Now, let's understand how to provide the filename:





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3ab585b60bf7438388328132eb62eed7.png)




* One can do many other things through read_csv to change the returned object completely.
* For instance, one can read not just a local CSV file but even one from a URL, or choose what columns need to be imported so that we don't have to edit the array later.
* These modifications can be done by the various arguments it takes.

### Pandas to_csv with example

* The easiest way to write DataFrames to CSV files is using the Pandas to_csv function.
* **Syntax:**




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f5966255a3954954b00b240424e929c9.png)



* **If you want to export without the index, add index=False**:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c2d4878eb34d465f98240d3894801922.png)

* **Example:**

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_75be7123fc7e427d824eecf456830695.png)




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c540acd080ce418f9a6d7b98a2aa6f1e.png)







### Playing with Data Using Pandas










<iframe width="560" height="315" src="https://www.youtube.com/embed/h8b2pvBT11I?start=120" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>











### Handling Missing Values










<iframe width="560" height="315" src="https://www.youtube.com/embed/EaGbS7eWSs0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>









### Notebooks

* [Playing with Data Using Pandas](https://nbviewer.org/url/alphabench.com/data/intro_pandas.ipynb)
* [Handling Missing Values](https://github.com/codebasics/py/blob/master/pandas/5_handling_missing_data_fillna_dropna_interpolate/handling_missing_data_fillna_dropna_interpolate.ipynb)