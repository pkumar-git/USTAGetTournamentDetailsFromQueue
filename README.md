# USTAGetTournamentDetailsFromQueue
This UiPath application retrieves USTA tournament details for each USTA tournament URL added by a separate
dispatcher application to the Orchestrator queue. It retrieves details like tournament level, name, venue, 
deadline information etc and stores the details in an Excel sheet.  The Excel file is saved in the 
C:\Users\pdksa\Documents\Tournaments\USTA folder.

Currently it retrieves only junior tournaments for the "18 and under" age division, though it is a straightforward 
change to retrieve any other/all age divisions.  It also retrieves all levels of tournaments, and again, it is a 
straightfoward change to retrieve only certain levels of tournaments.  Only tournaments whose registration status
is open are retrieved.

It requires the latest USTALibrary package to be available. 
