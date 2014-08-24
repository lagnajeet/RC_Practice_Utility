RC_Practice_Utility
===================

The utility takes an index array with the reading comprehensions and the respective questions and answers. The following is the format of the array.

data[passage_index][0]=passage data <br>
data[passage_index][1]=Questions (Array) <br>
data[passage_index][1][Question_index][0]=Question <br>
data[passage_index][1][Question_index][1]=Answer <br>
data[passage_index][1][Question_index][2]=Option1 <br>
data[passage_index][1][Question_index][3]=Option2 <br>
data[passage_index][1][Question_index][..]=Option.. <br>
data[passage_index][1][Question_index][..]=Option.. <br>
data[passage_index][1][Question_index][N]=OptionN<br>

See the data.js file for example data format. Make sure to replace the data.js file with your data file in RC.html file.
<br>
<script src="data.js" type="text/javascript" charset="utf-8"></script>
