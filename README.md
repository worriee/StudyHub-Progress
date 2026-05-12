```
FLOW & PROGRESS SUGGESTIONS
-Dashboard UI | Macaya, Astrologo
-Login & Logout | Mahilum, Macaya
-StudyHub Logo | Mahilum, Macaya, Astrologo
-Dark Mode | Mahilum



MONTH-DATE | CONTRIBUTORS (official order of the progress)

03-30 | Mahilum
-added login features
-added personal info window (after a user logs in they can proceed here and edit their personal details in this window)

04-12 | Macaya
-new Dashboard panel, Account panel, Transaction History panel, and Inbox panel
-added more features

04-15 | Mahilum
-added dark theme
-organized resources

04-16 | Mahilum
-new window Add Project
-added a table in transaction history panel
-added drag and drop feature in Add Project window
-optimization on dark theme

04-17 | Mahilum, Macaya
-minimal ui improvements of Add Project window

04-17 8pm | Mahilum
-renamed table names

04-22 | Mahilum, Macaya
-implemented the ui and logic of Add Project window (a UserControl Card that displays in Dashboard panel that shows the details of the project)
-rework of ui in Dashboard panel

04-24 | Mahilum
-added validation in most input fields
-rework of logic in Dashboard panel (UserControl card)
-implemented user session logic (UserSession.cs)
-some dark theme optimizations

04-27 | Mahilum
-added logout button and logic
-fixed bugs in dark mode
-fixed password security while typing, e.g., *****

05-03 | Salaber, Astrologo
- added logic code in userhistory
- added SQL Server Database 

05-07 | Villegas
-added SQL Server database connection (StudyHubDB)
-created Users table for account storage
-fixed disappearing profile picture after login/logout
-added PersonalInfo SQL update saving logic
-improved dashboard account synchronization with SQL database

05-10 to 05-12 FINAL | Mahilum, Villegas, Macaya
-added and fixed a database tables for login details, chat room, dashboard card, message card and transaction history
-fixed darkmode issues
-added a new feature (chatroom) and fixed chatroom ui (where users chat each other to discuss their transaction)
-optimizations in scenarios where the winforms app is crashing after logout and some cases
-added a timer logic that frequently refreshes the chatroom (for realtime chat history), dashboard and message cards being displayed and transaction history table (for retrieving status)
-added a year level option in addproject window (now the project being swapped includes a year level to it)
-added a logic in search bar to search the cards on dashboard (u can search only the project title or name of a user)
-added a logic in year level filter that it filters based on their year

```
