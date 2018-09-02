# CSV to Dashlane
Convert a .csv file (exported from another password manager) to make it compatible with Dashlane

Because this script is using XMLHttpRequest to get the csv file content, it needs to be executed on a webserver (prefer local webserver for more safety).

You can edit the columns names and placeholders to make them fit with Dashlane expectations.
To do so, edit lines 47 and 49. In the given version, columns names and placeholder are translated in french.

How to :
- Place the csv file and csv_to_dashlane.html in the same directory on your webserver.
- Open csv_to_dashlane.html in your browser, throught your webserver.
- The page will prompt the file url or absolute / relative path. If the csv file is in the exact same directory, just type the csv file's name. Otherwise, type the url or absolute / relative path of the file.
- If everythings goes right, after a few seconds or less, the page will display the converted content.
- Copy the whole content of the page, then paste it in an empty .txt file.
- Rename this .txt file with the .csv extension.
- Import the new .csv file in Dashlane.
- It should success import all your passwords ;)
