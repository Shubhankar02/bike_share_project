<h1>Python Script to Explore US Bikeshare Data</h1>

<h2>Aim:</h2>

This Python script is written for Project assigned by Udacity in Machine Learning foundation Nanodegree Program. It is used to explore data related to bike share systems acoss the Chicago, New York City, and Washington. It imports data from csv files and compute descriptive statistics from the data.
It also take users' raw input which makes this program user interactive.

<h2>How to run the script - Requirements:</h2>
<p>
You can run the script using a Python integrated development environment (IDE) such as Spyder. To install Spyder, you will need to download the Anaconda installer. This script is written in Python 3, so you will need the Python 3.x version of the installer. After downloading and installing Anaconda, you will find the Spyder IDE by opening Anaconda Navigator.</p>

Alternatively you can install any code editor like Atom or Sublime Text editor or Visual studio Code. After installing Anaconda you can run this script in the anaconda prompt by typing> python (filename)

<h2>Theory of Bike Share Data:</h2>
<p>Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.</p>

<p>Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.</p>


<h2>Datasets:</h2>


<p>
The datasets used for this script contain bike share data for the first six months of 2017. Some data wrangling has been performed by Udacity's staff before being provided to the students of DAND. Under the permission of Udacity, I have uploaded a copy of the datasets <a href="https://drive.google.com/drive/folders/13jJCbT1Fs5hlOBvhlznuCdzvdaLNA2cl?usp=sharing">here</a> on Google Drive, since The file sizes are too big to be uploaded on GitHub. After downloading the datasets, place all the files in the same folder with this Python script.
</p>
<p>
<strong>***Note:</strong> After opening the script file check the file path in the CITY_DATA dictonary. If your file path doesn't match then it will throw an error.<strong> ***</strong>
</P>
<p>
data provided by <a href="https://www.motivateco.com/">Motivate</a> a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.
</p>
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:
<ul>
  <li>Gender</li>
  <li>Birth Year</li>
</ul>
  
<h2>Questions explored</h2>
  
The script answers the following questions about the bike share data:
<ul>
  <li>What is the most popular month for start time?</li>
  <li>What is the most popular day of week (Monday, Tuesday, etc.) for start time?</li>
  <li>What is the most popular hour of day for start time?</li>
  <li>What is the total trip duration and average trip duration?</li>
  <li>What is the most popular start station and most popular end station?</li>
  <li>What is the most popular trip?</li>
  <li>What are the counts of each user type?</li>
  <li>What are the counts of gender?</li>
  <li>What are the earliest (i.e. oldest person), most recent (i.e. youngest person), and most popular birth years?</li></ul>

