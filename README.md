# KismetLog
Kismet Log Viewer v2 Tool: https://blog.secureideas.com/2013/07/kismet-log-viewer-v2-tool-released.html


What is Kismet Log Viewer v2
KLV v2 is a tool that combines multiple Kismet log files in the .netxml format, summarizes the data, and outputs an easy-to-read html or csv file.

KLV v2 is a complete rewrite in Python, currently with limited functionality. The original KLV was written in 2003 by Brian Foy of Mindflip.org, but doesn't support the .netxml format in newer versions of Kismet.

Secure Ideas actively supports open source and giving back
to the community. In that light, we’re announcing the release of an updated tool
for parsing and viewing Kismet log files.

Kismet is a fantastic tool for wireless network assessments.
It passively detects networks, SSIDs, and with enough time can even decloak
hidden networks by capturing the name from clients that connect. And with an
extensible plugin architecture, it can even sniff other, non-802.11, types of
wireless traffic.
One common use during a wireless assessment is to walk or
drive the facilities of a client to determine what wireless traffic is actually
being used. Then that information can be compared to documentation of what the
client believes should be in use. Often times we find misconfigurations,
unapproved use, and even unauthorized devices that have been added to the
network.
One area that Kismet stumbles though is the ability to
easily review log files after the assessment. During the assessment, viewing
data and activity is very easy and accessible, but later when you’re trying to
analyze the results it’s more difficult. Kismet creates a LOT of log data, and
most of it is in XML or CSV format that makes it easy to parse, but there is no
native functionality to view those logs.
Several years ago a number of tools had been released that
parsed and presented this log data in an easy-to-read HTML format. Unfortunately
with changes to the Kismet structure and log format, none of those tools still
work correctly. 
To remedy that, today I’m releasing Kismet Log Viewer v2, an
update to the original Kismet Log Viewer released by Brian Foy in 2003. KLV v2
reads in multiple Kismet .netxml files, summarizes the data, and outputs an
HTML or CSV file.
This initial release has some limitations. Like most
development, functional priority was based on necessity; I wrote what I needed
first. But I plan to continue extending the tool to add more functionality.
So without further ado, here’s the links you care about:
Kismet Log Viewer v2:
http://klv.professionallyevil.com/
And here’s an example report:
http://klv.professionallyevil.com/kismet-log-summary.html
Hopefully you’ll find this tool useful. If you find
problems, or have suggestions, please feel free to contact me.
Nathan Sweaney is a Senior Security Consultant for Secure Ideas. If you are in need of a penetration test or other security consulting services you can contact him at nathan@secureideas.com or visit the Secure Ideas – Professionally Evil site for services provided.



Team Members
The KLV v2 team is made up of the following volunteers:

Nathan Sweaney - Project Lead


