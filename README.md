Classes of Whatsapp Web change with time, so the code has to be updated with the proper new classes. Example: Line 114 points to the user name ('id'). (More info on /classes/ and in the last lines of portbcn-early-release.py)

Run by typing "python3 portbcn-early-release.py" on terminal and scan the QR with a phone.

Requirements:
 - Python 3
 - Selenium (+geckodriver)
 - Firefox


The triggers for the SQL database and Folium mapping haven't been implemented yet. There will probably be a threading feature as well in order to report multiple incidents at the same time.
