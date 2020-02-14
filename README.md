# sfmc_domain_count

This is a summary of your top 200 domains in a Data Extension, sorted by the number of people in the audience.  

How I Use
---------
I capture these numbers monthly into a Google Sheet so I can show changes over time.  I have an automation that runs this query once a month.

Pre-Requisite
-------------
The query calls for "audience_rollup_sixmonths" (not yet documented here on Github), but you can use any Data Extension of records, provided it has a column called "strDomain" containing the domain portion of an email address.  

For my purposes, a data extension of email addresses that I consider active in my email program, refreshed regularly.
