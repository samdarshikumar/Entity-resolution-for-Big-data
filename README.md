# Entity-resolution-for-Big-data
Devloped an entity Resolution framework for Big data using Binning,Blocking and pairwise matching techniques for data analytics. This framework shows similarly percentage Matrix between each entity.
Utilities
Functions and Its Uses:
1. read_file:
This Module enables user to Read a File or a Database into DataFrame.
The File can be a Flatfile or a Url of type csv, txt, xml or json.
The Database can be of type MySQL, SQLite, PostgreSQL, Oracle, Teradata, Netezza or Hive.

2. var_type:
This Function checks whether the Database columns is:

Constant
Boolen
Numeric Continuous
Numeric Categorical
Date
Unique
Others
3. missing_value_treatment:
This Function handle Missing Values in a Database.
It can peform 2 types of Imputations:-

KNN (K-Nearest Neighbors) Based Treatment.
Columnwise Treatment.
4. check_inputdata_attributes_column_type:
This Function checks the type of input dataframe columns.
The types are:

Constant
Boolean
Numeric With Length=1
Numeric Continuous
Uniformly Spaced
Non-Uniformly Spaced
Uniformly Distributed
Date
Only Text
Text with Number & Special Character
Not Known
Note:
If a Numeric column is Uniformaly Spaced and also Uniformly Distributed then the function will return "Uniformly Distributed".
