# jira-version-report-changes-table
Show changes in a Version in a table

Create readable table with scope changes of a JIRA Version/Release/Fix Version  
The existing graph is nice, but hard to read the details

Known bug: you have to refresh the page after first load and after selecting another version in the dropdown

## INSTALL
1. Install 'User JavaScript and CSS' extension for Chrome https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=en
2. Open a random JIRA Version report in your browser. The url probably contains "chart=versionReport" now.
3. Click 'User JavaScript and CSS' icon in Chrome (Blue/red dotted lines-icon)
4. Click 'Add new'
5. fill in:
 - Name: Version report
 - URL: replace url by 'https://jira.*/*chart=versionReport*'
 - Options: enable JavaScript and JQuery 3
 - Copypaste this whole script in the JS-pane. Keep CSS pane empty
6. Save
7. Go to JIRA Version report and refresh. The table should appear above the graph
