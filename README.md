# Wordpress-to-DayOne

This `main.py` script parses wordpress journal entries and creates [Day One](http://dayoneapp.com) entries in your DayOne app. This script imports Title, Date & Time, Text, and Tags from wordpress entries.

You need to have python2 installed to run the script and it works flawlessly on Mac OSX with latest version of DayOne app and its [command line tools](https://help.dayoneapp.com/en/articles/435871-command-line-interface-cli) installed.

### Download WordPress posts as an XML file

1. Log into WordPress wp-admin page.
2. Click on Export under Tools and select the posts option.
3. Download the XML file and rename it to `personal_data.xml`.

### Run main.py

1. Place the files `main.py` and `personal_data.xml` in the same folder.
2. Create a folder named `files` in the same folder as `main.py`.
3. Run the file as `$ python main.py`

<b>BOOM!</b> All of your wordpress entries are imported to DayOne.

Now, in DayOne `Preferences > Advanced` click `Convert all hashtags to Native tags` and <b>BAM!</b> all your imported entries will be tagged with the same tags as in wordPress journal.
