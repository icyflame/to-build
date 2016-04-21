# to-build

> A list of things to build as soon as I get some free time!

***

### 1. [write-good](https://github.com/btford/write-good) Chrome Extension

> For grammatical error free emails, and other conversation on the web.

#### Idea:

1. A chrome extension
2. Add option to the right click menu (Check for errors)
3. And show errors using easiest way to start with, then, slowly move on to in place highlighting, and other fancy stuff!

***

### 2. AIR news Scraper

> Scrape the page newsonair.nic.in every morning, and send an email to all subscribers

#### Idea:

1. Something that is deployed on heroku
2. Every morning around 8:45 scrape the page
3. Ensure that it is the news bulletin of that day
4. Also, include the link to the voice MP3 of that days morning news.

***

### 3. ~~Directory walker~~ <- Use `du -h --max-depth=1`

> Something like a disk usage analyser that works from inside the terminal itself

#### Idea:

1. CLI Gem
2. Command should be something like `disk_usage --depth 2` <- which should walk down two levels
3. Have sort orders -> `[descending (default), ascending (?)]`
4. Use the `du -hs` call internally, unless something faster is available (? **RESEARCH**)

***

### 4. ~~Github Canned Responses [Already exists]~~ <- GitHub has enabled native support for this!

> A clone of [this](https://github.com/notwaldorf/github-canned-responses)

#### Idea:

1. Add LGTM
2. Have an option for custom responses (probably there in the original as well.)

***

### 5. Transmission Digital Ocean Droplet setup Userdata

> Copying and pasting user data YML should automatically spawn a client, and mail the password to me!

#### Idea:

1. Update the present yml on `icyflame/do_user_scripts`.
2. Put KGP IP in the whitelist, and create a template json file (on gist maybe)
3. Fetch this file, replace the original file with this one
4. `sed` for the dummy password like `REPLACE_THIS` and put a random password there.
5. Restart the transmission daemon
6. Two options:
	- Mail this password using something like postfix (harder setup most probably!)
	- Store this password in the home directory (still have to ssh, but with just one step. Still a pain!)

***

### 6. Ruby utility script to edit MP3 Tags

> ruby edit-tags.rb file-name.mp3

#### Idea:

1. Find a MP3 Tag Editor Library
2. Ask user for all the values of each of the tags
3. Rename the file as per the format `Artist - Title - Album.mp3` at the end of the tag edit.
