# Serverless-Computing-Behind-the-Scenes-of-Major-Platforms-Data-Set

This data set (found at https://nuigalwayie-my.sharepoint.com/:f:/g/personal/0102835s_nuigalway_ie/Es0MJAURRoZJueNgPIB3VmQBYMMRCWPA2JsaaiPCVFTdXw?e=c5pDX9 ) is the result of calling python based benchmarking functions on AWS Lambda and Google Cloud Functions every hour over the course of one month. These functions measure: 
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
