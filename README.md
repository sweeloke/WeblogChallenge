# WeblogChallenge

This exercise is inspired by the weblog challenge (https://github.com/PaytmLabs/WeblogChallenge)

The program is written in Scala and executed on Spark at Databricks community edition.

## Processing & Analytical goals:

1. Sessionize the web log by IP. Sessionize = aggregrate all page hits by visitor/IP during a session.
    https://en.wikipedia.org/wiki/Session_(web_analytics)

2. Determine the average session time

3. Determine unique URL visits per session. To clarify, count a hit to a unique URL only once per session.

4. Find the most engaged users, ie the IPs with the longest session times

## Scala Program on Databricks:

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4065787460472196/110870947396635/158314600501441/latest.html
