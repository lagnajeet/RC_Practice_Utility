RC_Practice_Utility
===================

The utility takes an index array with the reading comprehensions and the respective questions and answers. The following is the format of the array.

data[passage_index][0]=passage data 
data[passage_index][1]=Questions (Array) 
data[passage_index][1][Question_index][0]=Question 
data[passage_index][1][Question_index][1]=Answer 
data[passage_index][1][Question_index][2]=Option1 
data[passage_index][1][Question_index][3]=Option2 
data[passage_index][1][Question_index][..]=Option.. 
data[passage_index][1][Question_index][..]=Option.. 
data[passage_index][1][Question_index][N]=OptionN

See the data.js file for example data format. Make sure to replace the data.js file with your data file in RC.html file.

<script src="data.js" type="text/javascript" charset="utf-8"></script>
