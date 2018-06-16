<h1><u>INT-Vision</u></h1>
<br>
<h1>ALL DATA AND CODE IN THIS REPOSITORY IS FOR PERSONAL USE ONLY, NO PART OF THIS PROJECT WAS USED FOR COMMERCIAL PURPOSES</h1>
<br><br><br>
<h2>This is a computer vision project, it was presented at Angelhack Bangalore,in 2018.
<br>
It detects bored and disinterested faces, particular use cases are offices, schools, conferences and meetings of any sort.
A bored face is detected from the combination of micro-expressions like happy, sad, disgust, angry etc, which are recieved from azure emotion api and used for training a local SVC model.
<br>
You will need azure subcription key and api url check algo/api.py for details.
<br>
It works fully on Python3, and the required dependencies are listed below-:
</h2>

<h3>
os<br>
requests<br>
numpy<br>
OpenCV<br>
matplotlib<br>
requests<br>
ScikitLearn<br>
Time Module<br>
Threading Module<br>
sys<br>
urllib<br>
multiprocessing<br>
tkinter
</h3>
<br><br>

<h1><u>How to use</u></h1>
<h3>Model training data is available in xval and yval text files, you just need to put your api key and url in api.py then run the following command inside algo folder-:</h3>
<br>
<h4>python3 qw.py</h4>
