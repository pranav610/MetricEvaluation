# Metric Reporting
This is the repository for the course term project of Database Management Laboratory CS39202 for the Spring semester 2022-23, at IIT Kharagpur.
## Contributors

- [Pranav Kulkarni](https://github.com/pranav610/)
- [Utsav Mehta](https://github.com/UtsavMehta1902/)
- [Swapnil Yasasvi](https://github.com/linpawsivsasay123)
- [Sidharth Vishwakarma](https://github.com/sidvisw)
- [Khush Bajaj](https://www.linkedin.com/in/khush-bajaj-a8601224a)

## 1. Installation  
1st create python virtual environment and activate it.  
```bash
python3 -m venv env
source env/bin/activate
```
Then install the required packages using the following command
```bash
python3 -m pip -r requirements.txt
```
## 2. How to run the code:
```bash
python3 hospitalmanagement-master/manage.py makemigrations hospital
python3 hospitalmanagement-master/manage.py migrate
python3 hospitalmanagement-master/manage.py runserver
```

- **Task**

1. Execution time: The total time taken to execute the query, including time spent waiting on locks or I/O. (done)
2. CPU time: The amount of CPU time used to execute the query.
3. Memory usage: The amount of memory used by the query, including shared buffers and work memory. (done)
4. Rows returned: The number of rows returned by the query. (done)
5. Block I/O time: The amount of time spent performing block I/O operations (reading from or writing to disk) during the execution of the query. (done)
6. Disk usage: The amount of disk space used by the query, including temporary files created during execution. (done)
7. Lock time: The amount of time the query spent waiting on locks.
8. Parse and plan time: The amount of time spent parsing and planning the query, including optimization and generating the execution plan. (done)
9. Number of executions: The number of times the query has been executed.(done)
10. Calls and rows per call: The average number of calls and rows returned per call for the query. (done)
11. Statement text: The text of the SQL statement being executed. (done)
