# WeblogChallenge

## Processing & Analytical goals:

1. Sessionize the web log by IP. Sessionize = aggregrate all page hits by visitor/IP during a session.
    https://en.wikipedia.org/wiki/Session_(web_analytics)

2. Determine the average session time

3. Determine unique URL visits per session. To clarify, count a hit to a unique URL only once per session.

4. Find the most engaged users, ie the IPs with the longest session times

# Solution

## Tools used
- Spark v1.6.0
- Scala v2.10.5
- CDH QuickStart VM 5.13.0

## Steps to run the script

The project has be run in spark-shell
1) On  CDH QuickStart VM open the terminal and strat the Spark Shell using spark-shell command
2) Update the input file location on line #29 of the script src/main/scala/weblogchallenge.sc
3) Then Copy the code snippet
3) Enter paste mode in spark shell using :paste and paste the code
4) Hit Ctrl + D after pasting the code
5) Wait for spark to finish the execution
6) The results/processed logs are saved as text files in HDFS at the following path: paytm/output/
