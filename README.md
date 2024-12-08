# Extract-information-from-log-files
Key Enhancements:

1. Formatted Terminal Output:

Added headings and aligned data in columns for better readability.

Used formatted string literals to ensure consistent alignment.


2. CSV Output Structure:

The output file now strictly follows the specified format with section headers.

Empty rows separate each section to ensure clarity when viewing the CSV file.


Sample Terminal Output

Requests per IP:
IP Address           Request Count
------------------------------
192.168.1.1          8
203.0.113.5          11
10.0.0.2             7
198.51.100.23        8
192.168.1.100        7

Most Frequently Accessed Endpoint:
/home (Accessed 6 times)

Suspicious Activity Detected:
IP Address           Failed Login Count
------------------------------
203.0.113.5          11
192.168.1.100        7

Results saved to log_analysis_results.csv

Sample CSV Output

Requests per IP
IP Address,Request Count
192.168.1.1,8
203.0.113.5,11
10.0.0.2,7
198.51.100.23,8
192.168.1.100,7

Most Accessed Endpoint
Endpoint,Access Count
/home,6

Suspicious Activity
IP Address,Failed Login Count
203.0.113.5,11
192.168.1.100,7
