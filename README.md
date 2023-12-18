# Serverless-Computing-Behind-the-Scenes-of-Major-Platforms-Data-Set

This data set (found at https://nuigalwayie-my.sharepoint.com/personal/0102835s_universityofgalway_ie/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F0102835s%5Funiversityofgalway%5Fie%2FDocuments%2FDK%20PhD%20Repo%2FServerlessBenchmarkData2020&ga=1 ) is the result of calling python based benchmarking functions on AWS Lambda and Google Cloud Functions every hour over the course of one month. These functions measure: 
cpu information from the /proc/cpuinfo file
cpu timing statistics from the /proc/stats file
request and response time of a function
run time of a function (request to response)
function computation start and stop
function computation time (start to stop)
start lag i.e. cold start (request to start)
uptime of VM
CPU Utilization (number of primes tested for primality)
memory allocation of a function
memory allocation of a VM
disk I/O throughput
unique VM ID
unique function ID
array of function IDs that executed on a particular VM

The tools used for benchmarking can be found at https://github.com/psykodan/serverless_test_functions
