# Youtube_data_hunt
Hello!
'Youtube_data_hunt' is a project that aims to get the desired data from Youtube API using Channel_Id. Here, we try to get the desired data from Youtube API and store in MongoDB Atlas. Then the stored data is migrated to MySQL and display it through Streamlit.

# Required modules--<br>
1 Streamlit<br>
2 googleapiclient.discovery<br>
3 pymongo<br>
4 pandas<br>
5 mysql.connector<br>
6 sqlalchemy<br>

# Understanding the workflow--<br>
I have used Python programming language, MySQL, MongoDB Atlas. There are few connections to be made with MySQL, MongoDB Atlas and Youtbe API. I have built a function named 'get_channel_videos' to request and get data from Youtube. Then coded few blocks of code to organize the retrieved data. Next, I have used streamlit.<br>

streamlit--<br>
Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps. <br>

Here, I have created a input box for channel_Id and five different buttons to do different tasks.<br>
Buttons Included-- <br>
1 button to retrieve Channel data<br>
2 button to store data in MongoDB Atlas<br>
3 button to retrieve data from MongoDB Atlas<br>
4 button to create a channel table in mysql<br>
5 button to display basic channel info in tabular form<br>
