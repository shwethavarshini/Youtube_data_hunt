# Youtube_data_hunt
Hello!
'Youtube_data_hunt' is a project that aims to get the desired data from Youtube API using Channel_Id. Here, we try to get the desired data from Youtube API and store in MongoDB Atlas. Then the stored data is migrated to MySQL and display it through Streamlit.

Required modules--
1 Streamlit
2 googleapiclient.discovery
3 pymongo
4 pandas
5 mysql.connector
6 sqlalchemy

Understanding the workflow--
I have used Python programming language, MySQL, MongoDB Atlas. There are few connections to be made with MySQL, MongoDB Atlas and Youtbe API. I have built a function named 'get_channel_videos' to request and get data from Youtube. Then coded few blocks of code to organize the retrieved data. 

Next, I have used streamlit.
streamlit--
Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps. 

Here, I have created a input box for channel_Id and five different buttons to do different tasks.
Buttons Included-- 
1 button to retrieve Channel data
2 button to store data in MongoDB Atlas
3 button to retrieve data from MongoDB Atlas
4 button to create a channel table in mysql
5 button to display basic channel info in tabular form
