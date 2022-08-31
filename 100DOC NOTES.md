# 100 Days of Code notes
*URLs are left in long form for click-through transparency!*

#### CATEGORIES
- [Hotkeys](#hotkeys)
- [Learn](#learn)
- [Python](#python)
- [Data Science](#data-sci)
	- [Datetime](#datetime)
- [Data Viz](#data-viz)
	- [Dashboards](#dashboards)
- [Pandas](#pandas)
- [SQL](#sql)
- [APIs](#apis)
- [Scraping](#scraping)
- [Markdown](#markdown)
- [Google](#google)
- [Mapping](#mapping)
- [Image Processing](#image-processing)
- [OpenCV](#opencv)
- [Comp Sci](#comp-sci)
	- [CMD / Powershell](#cmd--powershell)
	- [Virtual Envs](#virtual-environments)
	- [Editors](#editors)
	- [Cache](#cache)
	- [Git](#git)
- [Linux](#linux)
- [Hacking](#hacking)
- [Excel](#excel)
- [Web Dev](#web-dev)
- [Articles](#articles)

  
___
## Hotkeys

- Home (key)  - jump to top of page
- End (key) - jump to bottom
- Alt + Tab  - switch b/w open programs
- Alt + ←  - web page back
- Ctrl + L  - lock computer
- Ctrl + X  - cut
- Ctrl + Y  - redo
- Ctrl + Z  - undo

Articles 
- https://www.computerhope.com/shortcut.htm

## Learn
*info below helps when day-to-day projects get slow* 
- CodeAcademy
	-   Linear regression - https://tinyurl.com/mrx746ew
- HackerRank - https://www.hackerrank.com/dashboard
	- Learn/study/test python and other dev skills
- Freecodecamp.org
	- https://www.freecodecamp.org/learn/data-analysis-with-python/
		- Doesn’t actually have coding involved, only videos with questions
- 'Hacking'
		- https://liveoverflow.com/faq/get-started-with-hacking/
- Datacamp - https://www.datacamp.com
- Leetcode.com - https://leetcode.com/problemset/all/
- 100 days challenge 
	- Resources - https://www.100daysofcode.com/resources/
	- Go through these
	- Start using markdown

- Coding Interview Uni - https://github.com/jwasham/coding-interview-university
	- FAANG interview prep
    - Other resources in this git
	    - https://exercism.org/tracks
		- https://www.codewars.com/
		- https://www.hackerearth.com/

- SQL 
    - Postgres
	    - https://www.crunchydata.com/blog/learn-postgres-at-the-playground

___

# Python 
*general python notes*

Os.makedirs() - https://www.geeksforgeeks.org/python-os-makedirs-method/

`ctrl+c` Kills python scripts mid run

Awesome Python (git resources)- https://github.com/vinta/awesome-python#readme

Python apps to use for dev - https://twitter.com/pyquantnews/status/1559514346396520451?s=20&t=5XOg4-ws-T4Gf-Xcf-CJhA
- Voila 

Working with paths in python
- https://lerner.co.il/2018/07/24/avoiding-windows-backslash-problems-with-pythons-raw-strings/
- Os.path
    - https://docs.python.org/3/library/os.path.html
- https://realpython.com/python-pathlib/
- path.join - https://www.geeksforgeeks.org/python-os-path-join-method/

Pathlib - https://towardsdatascience.com/why-you-should-start-using-pathlib-as-an-alternative-to-the-os-module-d9eccd994745

%s use in python - https://www.geeksforgeeks.org/what-does-s-mean-in-a-python-format-string/


f-strings
- https://www.freecodecamp.org/news/python-print-variable-how-to-print-a-string-and-variable/
- https://www.freecodecamp.org/news/python-f-strings-tutorial-how-to-use-f-strings-for-string-formatting/
- https://realpython.com/python-f-strings/

r-strings ending with a backslash - https://docs.python.org/3/faq/design.html#why-can-t-raw-strings-r-strings-end-with-a-backslash

Kite Blog (python) - https://www.kite.com/blog/category/python/

Slack Python groups
- https://medium.com/@slackinday/an-ultimate-list-of-190-slack-communities-ee92a12a8df2
- https://techbeacon.com/app-dev-testing/46-slack-groups-developers
- Full stack python - https://www.fullstackpython.com

Python dev roadmap - https://roadmap.sh/python

Loops tutorial advanced - https://www.dataquest.io/blog/tutorial-advanced-for-loops-python-pandas/

Iterating over lists - https://www.geeksforgeeks.org/iterate-over-a-list-in-python/


Tesseract (character recognition)
- Git - https://github.com/UB-Mannheim/tesseract
    - wrote scripts that use this
	- screenshot to text output 
- Articles 
    - https://towardsdatascience.com/extract-text-from-image-using-python-8e8cfbbce743

URL shortener in python
	- https://www.thepythoncode.com/article/make-url-shortener-in-python

Python ORM
- Tortoise - https://betterprogramming.pub/this-is-why-you-should-use-tortoise-orm-in-your-python-projects-a3897dc5309e

Python for sports betting
- Articles
    - Soccer model - https://python.plainenglish.io/python-betting-model-for-six-football-leagues-11b6ccd8cd54
    - Modern soccer stats - https://liamjhartley.medium.com/football-statistically-mysterious-812f22b3f4a6
    - Scraping lineups - https://python.plainenglish.io/how-to-scrape-predicted-lineups-from-fantasy-football-scout-with-python-b11e92ea57f2

Python modules to keep an eye on - https://medium.com/geekculture/5-python-libraries-that-make-everyday-coding-simpler-a04064c305c
- Rstr
- Sh
-  humanize

QR code generators
- PyQRcode - https://pythonhosted.org/PyQRCode/
- Segno - QR code generator - https://segno.readthedocs.io/en/latest/
    - moar in depth QR coding options

Instaloader - https://instaloader.github.io
- Examples - https://github.com/instaloader/instaloader/issues/513

VSCode / python - https://code.visualstudio.com/docs/python/python-tutorial


Finding libraries to use with your code 
- https://python.libhunt.com/
- https://snyk.io/advisor/python
	- shows open source examples

Removing parentheses from strings w/ re - https://www.delftstack.com/howto/python/python-remove-parentheses-from-string/


CS50 - Intro to comp sci (python) at Harvard - https://cs50.harvard.edu/python/2022/

Telegram Bots
- https://core.telegram.org/bots#6-botfather
- Weather bot with python - https://nordicapis.com/create-a-weather-bot-in-telegram-using-python/

Papermill - https://papermill.readthedocs.io/en/latest/usage-parameterize.html
- Article that explains usage - https://towardsdatascience.com/jupyter-notebook-as-a-function-create-reusable-notebooks-with-papermill-8f9bea5b9727

code snippets - https://towardsdatascience.com/13-useful-python-snippets-that-you-need-to-know-91580af9b1f6

Converting CSV to pdf - https://www.geeksforgeeks.org/how-to-convert-csv-file-to-pdf-file-using-python/
- pdfkit
    - Installing - https://anaconda.org/conda-forge/python-pdfkit
	- https://pypi.org/project/pdfkit/
	-  https://github.com/conda-forge/python-pdfkit-feedstock
	- Github - https://github.com/JazzCore/python-pdfkit
- Wkhtmltopdf - https://wkhtmltopdf.org/
	- `pip install wkhtmltopdf`

https://www.programcreek.com/python/
- Search for code, shows examples

You-get (youtube dl) - https://github.com/soimort/you-get

Fuzz string matching
- Fuzz git - https://github.com/seatgeek/fuzzywuzzy
- https://towardsdatascience.com/string-matching-with-fuzzywuzzy-e982c61f8a84
	- Good code snippets
- https://www.geeksforgeeks.org/how-to-do-fuzzy-matching-on-pandas-dataframe-column-using-python/
    - Analyzing strings in df's using fuzz
    - Application of fuzz to df lists
- Analyzing strings with 2 methods - https://srinivas-kulkarni.medium.com/jaro-winkler-vs-levenshtein-distance-2eab21832fd6
- String matching - https://typesense.org/learn/fuzzy-string-matching-python/


Ultimate python resource hub (git) - https://github.com/ayushi7rawat/Ultimate-Python-Resource-Hub
- LOTS OF GREAT RESOURCES
- Look into for practice material


Plyer - library for accessing features of your hardware / platforms
- Docs - https://plyer.readthedocs.io/en/latest/#
- Articles 
	- https://www.geeksforgeeks.org/python-desktop-notifier-using-plyer-module/
		- Desktop notifications
	- https://medium.com/analytics-vidhya/create-desktop-notifier-using-python-6dab0a1c348c


# Data Sci
*python for data science*

Texthero - https://texthero.org
- work with text data efficiently
- Designed to work with pandas
- https://towardsdatascience.com/texthero-text-preprocessing-representation-and-visualization-for-a-pandas-dataframe-525405af16b6
- Guide - https://analyticsindiamag.com/texthero-guide-a-python-toolkit-for-text-processing/

Nbviewer - https://nbviewer.org
- 'simple way to share jupyter notebooks'
- good examples w/ code on their homepage


Python for data sci (blog)
- https://www.tomasbeuzen.com/python-programming-for-data-science/README.html
    - Stopped here - https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter2-loops-functions.html

Stats - https://www.analyticsvidhya.com/blog/

Hypothesis testing - https://towardsdatascience.com/significance-or-hypothesis-tests-with-python-7ed35e9ac9b6

Dataquest - https://community.dataquest.io
- Look into getting in the slack channel

Numpy data types - https://numpy.org/doc/stable/reference/arrays.dtypes.html

Ints vs floats - https://www.delftstack.com/howto/python/float-vs-int-in-python/

Removing $ sign from data columns 
- https://towardsdatascience.com/5-methods-to-remove-the-from-your-data-in-python-and-the-fastest-one-281489382455
    - "My personal choice would be to use the fourth method, the list comprehension with the .strip method"
    - `.replace( '[\$,)]','', regex=True)`
        - works best
        - `df['Sales'] = df['Sales'].replace( '[\$,)]','', regex=True)`
    - `[x.strip('$') for x in df]`
    - `str.replace('$','')`
- Strip method .strip()
    - https://www.tutorialsteacher.com/python/string-strip
	- https://www.w3schools.com/python/ref_string_strip.asp
	- https://www.programiz.com/python-programming/methods/string/strip
	- https://www.geeksforgeeks.org/python-string-strip/


https://www.kdnuggets.com - Data sci website 
- Good info, articles, links etc.. 

### Datetime

Dateutil 
- Timezones 
	- `from dateutil import tz
	- from datetime import datetime
	-  now = datetime.now(tz=tz.tzlocal())
- Pandas date_range - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.date_range.html
	- Date_range(start=  , end=  )

Extracting other date info - https://datagy.io/pandas-extract-date-from-datetime/
General - https://realpython.com/python-datetime/
- YYYY-MM-DD HH:MM:SS - ISO standard

Dateparser - human readable dates
- https://dateparser.readthedocs.io/en/latest/
- Works with relative dates
- `parse('1 hour ago')`


# Data Viz

Seaborn color palettes - https://seaborn.pydata.org/tutorial/color_palettes.html
- color blind palatte 

Font Awesome - https://fontawesome.com/docs/web/setup/get-started
- For icons in folium

https://holoviews.org - Plotting w/ python
- ' open-source Python library designed to make data analysis and visualization seamless and simple'
- Gallery - https://holoviews.org/gallery/index.html

Figure Factory (Plotly)
- https://plotly.com/python/figure-factory-table/
	- Advanced viz for data sci 
	- Hist > https://plotly.com/python/distplot/


### Dashboards
Dash
- https://towardsdatascience.com/plotly-dashboards-in-python-28a3bb83702c
- Plotly Dash gallery https://dash.gallery/Portal/
- React for python devs - https://dash.plotly.com/react-for-python-developers



Streamlit 
- Installing - https://docs.streamlit.io/library/get-started/installation
- Syntax error hello world - https://stackoverflow.com/questions/72548682/streamlit-run-file-name-py-syntaxerror-invalid-syntax
	- Need to open through anaconda navigator > new > cmd
- Getting started = https://docs.streamlit.io/library/get-started
- Create an app - https://docs.streamlit.io/library/get-started/create-an-app
- Main concepts - https://docs.streamlit.io/library/get-started/main-concepts
- API reference docs - https://docs.streamlit.io/library/api-reference
	- St.write() - https://docs.streamlit.io/library/api-reference/write-magic/st.write
	- Magic - https://docs.streamlit.io/library/api-reference/write-magic/magic
- Articles 
	- Awesome streamlit - https://awesome-streamlit.readthedocs.io/en/latest/_copy_of_project_root/README.html
	- Peruse for info, help etc..
	- Getting started w/ stock charts - https://medium.com/geekculture/getting-started-with-streamlit-ed81eafcb298
		- References yfinance 
	- Cannot be instantiated - https://github.com/streamlit/streamlit/issues/5140
	- In depth intro - https://medium.com/towards-data-science/streamlit-101-an-in-depth-introduction-fc8aad9492f2


# Pandas
.astype()
	- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.astype.html

Pivot Tables
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html

Df.rename
	- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.rename.html
		
Df.to_csv
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.to_csv.html
- https://datagy.io/pandas-dataframe-to-csv/
    - More details on parameters

Appending new rows to DFs
 - `Df.loc['row name'] = df.sum()`
    - add new row that is the sum of the columns
- https://datascienceparichay.com/article/append-rows-to-a-pandas-dataframe/


Index reset - https://datagy.io/pandas-drop-index-column/

loc / iloc
- filtering https://www.shanelynn.ie/pandas-iloc-loc-select-rows-and-columns-dataframe/
    - iloc uses position
	- loc uses labels

Split
- https://stackoverflow.com/questions/38231591/split-explode-a-column-of-dictionaries-into-separate-columns-with-pandas
- https://datascienceparichay.com/article/split-pandas-column-of-lists-into-multiple-columns/
    - see for code snippets

Changing datatypes
- Pd.dataframe.convert - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.convert_dtypes.html
- Pd.to_numeric - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_numeric.html#pandas.to_numeric

Effective pandas (book/git) - https://github.com/mattharrison/effective_pandas_book

Groupby - https://www.datasciencemadesimple.com/group-by-sum-in-pandas-dataframe-python-2/

Working with strings 
- Removing characters from strings - https://datagy.io/python-remove-character-from-string/
- find similar strings https://pythoninoffice.com/how-to-find-similar-strings-using-python/
- Adding string columns - https://towardsdatascience.com/combine-two-string-columns-pandas-fde0287485d9

Nan Values
- .isna - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.isna.html
	- https://datatofish.com/rows-with-nan-pandas-dataframe/
- `df[df['column name'].isna()]`
- `df1 = df[df.isna().any(axis=1)]`
	- sets new df to NaN values
- Checking NaN values
	- https://stackoverflow.com/questions/43424199/display-rows-with-one-or-more-nan-values-in-pandas-dataframe




# SQL

Using indexing - https://use-the-index-luke.com

Other resources
-   https://twitter.com/SumanDe36754787/status/1559885703969837056?s=20&t=162meZF2BKo0E77q2SdZAQ

W3 School SQL - https://www.w3schools.com/SQl/default.asp

Learn relational DBs
	- https://www.freecodecamp.org/news/how-to-run-freecodecamps-relational-databases-curriculum-using-docker-vscode-and-coderoad/

DBMS - https://medium.com/codex/database-management-system-2e1198ca2136

Microsoft Access - https://www.microsoft.com/en-us/microsoft-365/access



# APIs

RapidAPI - https://rapidapi.com/hub
- 50 most popular - https://rapidapi.com/blog/most-popular-api/

Zillow Listings API - https://www.zillowgroup.com/developers/api/rentals/listing-api/

Rick and Morty API -  https://rickandmortyapi.com/documentation/

Call API for each element in a list - https://stackoverflow.com/questions/58323668/call-api-for-each-element-in-list

Using json_normalize - https://tinyurl.com/4ajufwh9 

other JSON examples - https://medium.com/@arun_prakash/mastering-apis-and-json-with-python-2685dfb0a115
Requests, JSONs etc.. Basics

JSON editor/viewer - https://jsoneditoronline.org/

API looping
- https://www.reddit.com/r/learnpython/comments/92hcf7/how_to_loop_api_call_requests_yelp_fusion/
- https://0x2142.com/from-postman-to-python-your-first-get-request/

FastAPI - https://fastapi.tiangolo.com/

Hiding API keys with conda - https://medium.com/@brendan.m.connelly/how-to-hide-your-api-keys-in-python-fb2e1a61b0a0

Curl - https://curl.se/
- Book explaining uses and how to use - https://everything.curl.dev/
- What does it do? - https://everything.curl.dev/project/does
- Git > everything curl - https://github.com/bagder/everything-curl
- Articles
    - Examples - https://geekflare.com/curl-command-usage-with-example/




# Scraping
*scraping / crawling web data* 

Requests - https://pypi.org/project/requests-html/

Make scraping easier - https://medium.com/analytics-vidhya/the-modern-way-of-web-scraping-requests-html-2567ba2554f4

residential proxy networks
-  https://medium.com/spur-intelligence/residential-proxies-the-legal-botnet-that-nobody-talks-about-4470cae7e3c
- Bright Data - https://brightdata.com/

Scraping zillow 
- https://www.scrapehero.com/how-to-scrape-real-estate-listings-on-zillow-com-using-python-and-lxml/
- https://gist.github.com/scrapehero/5f51f344d68cf2c022eb2d23a2f1cf95
- https://github.com/ChrisMuir/Zillow

Findall li in ul
	- https://www.geeksforgeeks.org/beautifulsoup-find-all-li-in-ul/

Scraping twitter - https://proxyscrape.com/blog/how-to-scrape-twitter-using-python/


Beautiful Soup Docs - https://beautiful-soup-4.readthedocs.io/en/latest/
Scrapy Docs - https://doc.scrapy.org/en/latest/index.html

Articles
- 24 best free & paid scrapers - https://www.scrapehero.com/top-free-and-paid-web-scraping-tools-and-software/

https://www.scrapehero.com/scrape-alibaba-using-scrapy/
		○ Scraping tutorial - https://www.geeksforgeeks.org/python-web-scraping-tutorial/
		○ Scrape hero - https://www.scrapehero.com/how-to-build-and-run-scrapers-on-a-large-scale/

Listly - https://saraametwalli.medium.com/speed-up-your-data-collection-with-listly-f09827a8dddb
- add-on to web browsers
- helps w/ scraping




# Markdown
Guide - https://www.markdownguide.org/

'Hacks' - https://www.markdownguide.org/hacks/
- niche commands like centered text, color, hidden comments etc..

Links
-   *Interdocument links* - https://github.com/aogilvie/markdownLinkTest#small-title
    - Start using these
	- Look at the raw code for examples
    - takes # in front of link to reference
    - https://raw.githubusercontent.com/aogilvie/markdownLinkTest/master/README.md
	- W3 links info - https://www.w3schools.io/file/markdown-links/

Other markdown docs
- https://tomcam.github.io/least-github-pages/markdown-links.html
- https://stackoverflow.com/questions/51187658/markdown-reference-to-section-from-another-file
- https://stackoverflow.com/questions/7653483/github-relative-link-in-markdown-file
- Examples below

Markdown to PDF
- https://www.w3schools.io/file/markdown-convertpdf/
				
Markdown-it - https://markdown-it.github.io/
- https://www.npmjs.com/search?q=keywords:markdown-it-plugin

Markdown to website builder?
- Git - https://harrywang.medium.com/how-to-host-static-markdown-web-pages-using-github-pages-61f80a3a5136

Why markdown for notes - https://jamesbvaughan.com/markdown-pandoc-notes/
- 'I have a Makefile that converts all of my Markdown notes to HTML using pandoc and deploys them to my server where they’re served behind HTTP auth'

Convert onenote to markdown - https://medium.com/security-privacy-risk-management-blockchain/easy-way-to-convert-onenote-notes-to-markdown-e9558a989397
- Uses pandoc - https://pandoc.org

Articles 
- https://medium.com/@michael.isprihanto/how-to-guide-markdown-in-visual-studio-code-e8a68cc01f64
- https://marketplace.visualstudio.com/items?itemName=MadsKristensen.MarkdownEditor
- getting started - https://www.markdownguide.org/getting-started
- What is markdown? - https://www.slashgear.com/776429/what-is-markdown-and-why-should-you-use-it-instead-of-microsoft-word/


# Google 

Colab
- Why colab? Vs jupyter - https://towardsdatascience.com/4-reasons-why-you-should-use-google-colab-for-your-next-project-b0c4aaad39ed
- Getting files setup, path, data etc.. - https://medium.com/data-arena/how-to-load-files-insert-images-in-google-colabatory-c5d1365d60d4

Google sheets w/ python
- https://towardsdatascience.com/how-to-import-google-sheets-data-into-a-pandas-dataframe-using-googles-api-v4-2020-f50e84ea4530
	- Work through this..
- https://pyshark.com/google-sheets-api-using-python/

How to import gsheets data - 
 - https://predictivehacks.com/the-easiest-way-to-connect-python-with-google-sheets/
 - Gsheets module - https://pypi.org/project/gsheets/


Google sheets API
- https://developers.google.com/sheets/api/quickstart/python
	-  quickstart
	- Github code - https://github.com/googleworkspace/python-samples/blob/main/sheets/quickstart/quickstart.py
https://www.programiz.com/python-programming/function
	- Using def functions
	- More functions info - https://www.programiz.com/python-programming/function-argument
https://booksoncode.com/articles/clean-code

Google alerts 
	- https://www.google.com/alerts#
-   Alerts for search items

Adsense best practices - https://www.google.com/adsense/start/resources/best-practices-for-google-adsense/




# Mapping

Manual lat/long generator - https://www.latlong.net



Geocoding
- Geopy - https://pypi.org/project/geopy/
    - Usage with Pandas - https://geopy.readthedocs.io/en/latest/#usage-with-pandas
- Geopandas
    - `conda install geopandas`
    - docs - https://geopandas.org/en/stable/getting_started.html
    - Data Structures - https://geopandas.org/en/stable/docs/user_guide/data_structures.html
    - install info - https://stackoverflow.com/questions/59284004/fiona-installation-error-on-windows-using-pip

- geoJSON 
	- All zipcodes from all states - geojson files - https://github.com/OpenDataDE/State-zip-code-GeoJSON
	- for mapping with mapbox - https://github.com/jazzband/geojson 
	- https://snyk.io/advisor/python/folium/functions/folium.GeoJson
	- open source code examples https://snyk.io/advisor/python/folium/functions/folium.GeoJson
- Google
    - https://developers.google.com/maps/documentation/geocoding/
    - RapidAPI (google) https://rapidapi.com/blog/google-maps-api-react/
	    - free for the first 500 requests a month
	
Mapbox / Plotly
- https://towardsdatascience.com/meet-plotly-mapbox-best-choice-for-geographic-data-visualization-599b514bcd9a
- https://www.askpython.com/python/examples/plot-geographical-data-python-plotly
- https://towardsdatascience.com/how-to-create-interactive-map-plots-with-plotly-7b57e889239a
- gallery for inspo - https://tinyurl.com/4s7dr8he


Folium
- https://towardsdatascience.com/mapping-messy-addresses-part-2-insights-from-folium-bafd55858faf
    - Good info, pull code

Mapping Articles 
- https://rajatamil.medium.com/google-maps-api-geocode-explained-2022-828a059ba6cc
- https://stackoverflow.com/questions/69854674/python-generate-lat-long-points-from-address
- http://ocefpaf.github.io/python4oceanographers/
	- Good articles on mapping / oceanography
- Mapping zipcodes w/ folium - https://towardsdatascience.com/visualizing-data-at-the-zip-code-level-with-folium-d07ac983db20

Calculating distance between 2 points using Haversine
- https://towardsdatascience.com/calculating-distance-between-two-geolocations-in-python-26ad3afe287b




# Image Processing
- Improving the quality of images for text retrieval https://tesseract-ocr.github.io/tessdoc/ImproveQuality.html
	
- CNN / DCNs for image recognition - https://towardsdatascience.com/convolutional-neural-networks-explained-how-to-successfully-classify-images-in-python-df829d4ba761

https://www.instructables.com/Traffic-Speed-Camera-That-Recognizes-License-Plate/

Image Recognition Repos 
- https://github.com/gautamkumarjaiswal?after=Y3Vyc29yOnYyOpK5MjAxOS0wNC0yNlQwMzoyNTo1NC0wNTowMM4K8Rmr&tab=repositories

Vizy AI camera
	- https://docs.vizycam.com/doku.php

Motion Scope
	- https://docs.vizycam.com/doku.php?id=wiki:motionscope_app
		○ Auto detections motion and speed


DALLE-2 vs Midjourney vs StableDiffusion - https://tinyurl.com/3fyfrrj4

Deepfake AI video - https://twitter.com/TedsLittleDream/status/1562836627885416449?s=20&t=xo_Zi6PrLsbp5O73YjKmDg
- Check out how she made this, apps etc


## OpenCV
- https://www.askpython.com/python/examples/count-objects-in-an-image
    - Count objects in pics 
    - Good examples and implementation
	- Wrote script on work comp, runs but quality is sus
- https://medium.com/analytics-vidhya/detecting-and-counting-objects-with-opencv-b0f59bc1e111
	- Has links to other good articles at the end
- https://stackoverflow.com/questions/38619382/how-to-count-objects-in-image-using-python
	- Counting objects in an image
- https://www.geeksforgeeks.org/python-using-pil-imagegrab-and-pytesseract/
    - Does a good job of processing image to get into 'readable' format
    - Using imagegrab and pytesseract

# Comp Sci

## CMD / Powershell

CMD 
- `Where.exe python` - Shows path to python installs
- Dir 
	- list files based on other criteria 
	- To reverse sorting orders add - in call prefix ex: `dir /o-n`
	- https://codesteps.com/2011/04/27/windows-dir-command-how-to-list-the-files-by-sort-order/
		-  `dir /os` or `dir /o-s ` >> files based on size
		-  `dir /od` or `dir/o-d` >> based on date/time
		- LS is linux equivalent - https://phoenixnap.com/kb/linux-ls-commands
- Mkdir - make directory
	- https://www.tutorialspoint.com/unix_commands/mkdir.htm
- Pushd & popd 
	- Pushd is similar to cd 
https://www.howtogeek.com/659146/how-to-use-pushd-and-popd-on-linux/

## Virtual Environments
venv - https://docs.python.org/3/library/venv.html

Primer / basics - https://realpython.com/python-virtual-environments-a-primer/
- Activating - `venv\Scripts\activate`
- Deactivate - `deactivate`
- Installing packages to venv - `python -m pip install ___`
	- Because you first created and activated the virtual env, pip installs the packages in an isolated location

Pip env
-  automatically creates and manages a virtualenv for your projects
- Install - https://pypi.org/project/pipenv/
- Docs / home - https://pipenv.pypa.io/en/latest/#install-pipenv-today
	- See for more info
- Not recognized - https://stackoverflow.com/questions/69795302/pipenv-is-not-recognized-as-an-internal-or-external-command-operable-program
- Installing packages with pipenv - slow - https://github.com/pypa/pipenv/issues/2873


Virtual box - https://www.virtualbox.org/manual/UserManual.html

## Editors 

Visual Studio

- How to change the interpreter - https://stackoverflow.com/questions/47602151/how-to-change-interpreter-in-visual-studio-code
- `ctrl + shit + p`

### Anaconda

Anaconda Navigator - https://anaconda.org/anaconda/anaconda-navigator

Jupyter checkpoint files - https://stackoverflow.com/questions/46421663/what-are-jupyter-notebook-checkpoint-files-for

## Cache

How to - https://medium.com/fintechexplained/advanced-python-how-to-implement-caching-in-python-application-9d0a4136b845


# Linux 

50 best linux commands 
- https://medium.com/beyondx/basic-linux-commands-8b356ddf736b
	
https://medium.com/beyondx/
virtual-machine-tutorial-9043f0fce02b
	- Virtualbox tutorial

# Hacking
Beginner hacking info 
- https://medium.com/@toxglot/3-things-to-do-if-you-want-to-be-a-penetration-tester-168e6d52be31
	- HackTheBox


# Git

Creating a good git repo - https://www.profileme.dev

Cheat sheet - https://about.gitlab.com/images/press/git-cheat-sheet.pdf

Gitlab docs - https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html
 - Git is gitlab which is different from github..

Git log - https://www.w3docs.com/learn-git/git-log.html





# Excel
Hotkeys - http://allhotkeys.com/microsoft_excel_hotkeys.html
 - CTRL 1 - format cells

Excel filter text by string length 
- `???` = len string is 3 




# Web Dev
Built with - https://builtwith.com/
- Shows what websites are built with..

Pandoc - https://pandoc.org
- Universal doc converter
- Convert markdown files to websites, pdfs etc..

https://webflow.com
		- Web dev simplified
		- Go through tutorial, start page

[Wix](Wix.com) - website builder

HTML - https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics

Jekyll - https://jekyllrb.com
- https://github.com/topics/jekyll-theme
	- blog-aware, site generator written in Ruby. It takes raw text files, runs it through a renderer and produces a publishable static website
	- Beautiful jekyll - https://github.com/daattali/beautiful-jekyll
		- ready-to-use templates, nice websites quickly


Domains 
- How to register - https://websitesetup.org/how-to-register-domain-name/
- How to get free domains - https://sitechecker.pro/how-to-get-free-domain-name/
- ICANN - https://www.icann.org
- Costs related to domains - https://websitesetup.org/how-much-costs-domain-name/


# Articles

Faceswap - https://forum.faceswap.dev/viewtopic.php?f=4&t=20
- leading free and Open Source multi-platform Deepfakes software
- Forum - https://forum.faceswap.dev
- Guides - https://forum.faceswap.dev/app.php/tag/Guide

Awesome PHP - https://github.com/ziadoz/awesome-php
- Git with useful PHP libraries

Explaining black box models w/ Shap - https://towardsdatascience.com/how-to-explain-black-box-models-with-shap-the-ultimate-guide-539c152d3275

NOAA data - https://www.ncei.noaa.gov

Metasearch engine, aggregates results - https://docs.searxng.org

Code practice resources - https://www.interviewbit.com

dev community - https://dev.to

ScreenRec - https://screenrec.com/screen-recorder/

https://medium.com/@insightsbees
- Go through articles for code work
- Lots of good examples

Fanwave - https://okc.fanwave.io/
- okc local concerts website

Rust OS projects - https://www.dunebook.com/amazing-rust-opensource-projects/

What is Heroku - https://trifinlabs.com/what-is-heroku/

Got package - https://www.npmjs.com/package/got

Wiki of unknowns - https://wikenigma.org.uk/start

Checks differences in docs - https://www.diffchecker.com

10 Usability Heuristics for User Interface Design - https://www.nngroup.com/articles/ten-usability-heuristics/

copilot - AI pair programming https://copilot.github.com/

2Captcha - https://2captcha.com/
	- Solves captchas for you 

Creates random email addresses - https://10minutemail.com
- works well

Cheat sheets - https://www.codecademy.com/resources/cheatsheets/all

Shortening URLs - https://free-url-shortener.rb.gy/

Upload pics, creates URL link - https://imgur.com/upload

Removing files from OneNote without deleting them - https://siit.co/blog/how-to-remove-local-onedrive-files-without-deleting-them/2158

Code reviews - https://mtlynch.io/human-code-reviews-1/#let-computers-do-the-boring-parts
	- Tips on how to do them, what to get out/have them do etc..

Clean code book summary - https://python.plainenglish.io/10-tools-to-help-claw-your-way-back-to-sanity-while-coding-python-df0af160c33e

Intro to optimization w/ Genetic Algos
	- https://towardsdatascience.com/introduction-to-optimization-with-genetic-algorithm-2f5001d9964b

Understanding Path Analysis
https://www.thoughtco.com/path-analysis-3026444

Packages to look into
- Pypdf2
- ReportLab

Why we sleep - book notes - 
https://www.grahammann.net/book-notes/why-we-sleep-matthew-walker

Text Message Sending Services
- SMSPVA - https://smspva.com/
- Getsmscode - https://www.getsmscode.com/

useful PC and Gaming software
	- https://www.reddit.com/r/pcgaming/comments/6wdclg/my_list_of_useful_pc_and_gaming_software/

Smart home power monitoring system - https://sense.com/technology

Backend Dev
	- https://roadmap.sh/backend
		○ Shows roadmap for becoming backend dev

Powershell vs CMD - https://www.educba.com/powershell-vs-command-prompt/
- Most commands executed on cmd can be run on PowerShell


Go (language)
- Overview - https://www.tutorialspoint.com/go/go_overview.htm
- Examples - https://gobyexample.com

Have I been pwn'd - https://haveibeenpwned.com/Passwords

10 no-code tools for entrepreneurs - https://twitter.com/heyeaslo/status/1519859023436079105?s=21&t=SsKbqx4LO2wDOPhjoLvwwQ

PJ trackers
- Git - https://github.com/ihacker42/plane-notify
- ADSB exchange API - https://www.adsbexchange.com/data/rest-api-samples/
    - Cost $10/mo for API

Inside AirBNB data - http://insideairbnb.com/explore

Klimat app - https://klimat.app
- For Strava
- How-to > https://everydaymtb.com/klimat-app-add-weather-data-to-strava-rides/