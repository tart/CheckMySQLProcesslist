## Usage:

./checkMySQLProcesslist.sh [-H hostname] [-P port] [-u username] [-p password]

## Description

Executes just one "Show processlist" query on the server.

|| Counted Process' || Warning Limit || Critical Limit ||
| All | 144 | 377 |
| Queries | 21 | 55 |
| Queries running more than 10 seconds | 8 | 21 |
| Queries runnig more than a minute | 3 | 8 |
| Queries runnig more than 10 minutes| 1 | 3 |
| Queries runnig more than a hour | | 1 |
| Sleeping | | |
| Quering | | |
| Connecting | | |
| Quiting | | |
| Preparing | | |
| Fetching | | |
| Executing | | |
| Delayed | | |
