# Log Ingestor and Query Interface (SDE-1 and SDE Intern Assignment)

Developed a log ingestor system that can efficiently handle vast volumes of log data, and offer a simple interface for querying this data using full-text search or specific field filters.

Both the systems (the log ingestor and the query interface) has been built using flask , HTML , CSS & Javascript.

I am using firebase realtime database for storing the logs and provided the credendials for your use. If you want to use your own credendials then get the cred from firebase. [Visit firebase console](https://console.firebase.google.com/). Make sure you are creating project for web.
## Project Overview
![image](https://github.com/Vivek-Soni-5/chat360-task/assets/120296187/c6762bd9-368b-4577-9757-14fdec4c3c5b)
![image](https://github.com/Vivek-Soni-5/chat360-task/assets/120296187/efe4413e-335b-4c01-bd84-b4f9bedfbb28)
![image](https://github.com/Vivek-Soni-5/chat360-task/assets/120296187/fdc4c010-98db-49a3-bab5-caf7f8daafc9)



## Quick Start (Steps to Run this project)

Here are some steps to run this project:

1. Clone the project ( open new terminal on your VSCode) 

```
git clone https://github.com/Vivek-Soni-5/chat360-task.git
```

2. Make Virtual Environment for this project (optional)

```
python -m venv venv
```

3. Start Virtual Environment (if setup virtual enviroment)

```
venv/Scripts/activate
```

4. Install dependencies

```
pip install -r requirements.txt
```

5. Run the project

```
python main.py
```

6. Open localhost in browser

```
http://localhost:3000/
```

7. To Populate the logs

```
http://localhost:3000/
```

8. To filter logs

```
http://localhost:3000/get_logs
```

8. To filter  Multiple logs

```
http://localhost:3000/multiple_log_query
```



