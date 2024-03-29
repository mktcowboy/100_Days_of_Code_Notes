# 100 Days of Code notes
*URLs are left in long form for click-through transparency!*

#### CATEGORIES
- [Hotkeys](#hotkeys)
- [Learn](#learn)
- [Python](#python)
	- [RegEx](#regex)
	- [Gits](#gits)
- [Pandas](#pandas)
    - [Pandas Articles](#pandas-articles)
	- [Methods](#methods)
- [Data Science](#data-sci)
	- [Jupyter](#jupyter)
	- [Numpy](#numpy)
	- [Scipy](#scipy)
	- [Datetime](#datetime)
	- [DS Blogs](#ds-blogs)
		- [DS Articles](#ds-articles)
- [Data Viz](#data-viz)
	- [Matplotlib](#matplotlib)
	- [Seaborn](#seaborn)
	- [Plotly](#plotly)
	- [Dashboards](#dashboards)
		- [Dash](#dash)
		- [Streamlit](#streamlit)
		- [Grafana](#grafana)
	- [Data Viz Articles](#data-viz-articles)
- [SQL](#sql)
- [APIs](#apis)
- [Scraping](#scraping)
	- [Beautiful Soup](#beautiful-soup)
- [Markdown](#markdown)
- [Google](#google)
- [AI / ML](#ai--ml)
	- [ChatGPT](#chatgpt)
	- [OpenCV](#opencv)
	- [Image Processing](#image-processing)
	- [XGBoost](#xgboost)
- [Mapping](#mapping)
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
	- [Flask](#flask)
	- [Java](#java)
	- [RubyonRails](#ruby-on-rails)
	- [Jekyll](#jekyll)
	- [Domains](#domains)
- [News](#news)
- [Other Articles](#other-articles)

  
___
## Hotkeys

- Home (key)  - jump to top of page
- End (key) - jump to bottom
- `Shift + F5` - reload webpage
- `Alt + Tab`  - switch b/w open programs
- `Alt + ←`  - web page back
- `Ctrl + L`  - lock computer
- `Ctrl + X`  - cut
- `Ctrl + Y`  - redo
- `Ctrl + Z`  - undo

Visual Studio
- `ctrl d` - selects next same item, replace
- `ctrl + k (release) + o` - opens active file in new window

Articles on shortcuts & hotkeys
- https://www.computerhope.com/shortcut.htm

## Learn
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

`ctrl+c` Kills python scripts mid run

`dir(module)` - shows what commands are available
Good to see what options are available

`Os.makedirs()` - https://www.geeksforgeeks.org/python-os-makedirs-method/

.map() - https://realpython.com/python-map-function/

Awesome Python (git resources) - https://github.com/vinta/awesome-python#readme

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

Zip (python operator)
- https://www.geeksforgeeks.org/zip-in-python/
- https://www.freecodecamp.org/news/the-zip-function-in-python-explained-with-examples/
- `df['sig2'] = [1 if c < sma else 0 for c, sma in zip(df['Close'],df['sma'])]`

Return statements
- https://realpython.com/python-return-statement/

pyEnchant - http://pyenchant.github.io/pyenchant/
- spellchecking library for Python, based on the excellent Enchant library
- tutorial - http://pyenchant.github.io/pyenchant/tutorial.html

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
	- https://medium.com/pythoneers/text-detection-and-extraction-from-image-with-python-5c0c75a8ff14

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
- pypdf and tabula 
	- https://stackoverflow.com/questions/56017702/how-to-extract-table-from-pdf-in-python
- pdfkit
    - Installing - https://anaconda.org/conda-forge/python-pdfkit
	- https://pypi.org/project/pdfkit/
	-  https://github.com/conda-forge/python-pdfkit-feedstock
	- Github - https://github.com/JazzCore/python-pdfkit
- Wkhtmltopdf - https://wkhtmltopdf.org/
	- `pip install wkhtmltopdf`

https://www.programcreek.com/python/
- Search for code, shows examples

Fuzz string matching
- Fuzz git - https://github.com/seatgeek/fuzzywuzzy
- https://towardsdatascience.com/string-matching-with-fuzzywuzzy-e982c61f8a84
	- Good code snippets
- https://www.geeksforgeeks.org/how-to-do-fuzzy-matching-on-pandas-dataframe-column-using-python/
    - Analyzing strings in df's using fuzz
    - Application of fuzz to df lists
- Analyzing strings with 2 methods - https://srinivas-kulkarni.medium.com/jaro-winkler-vs-levenshtein-distance-2eab21832fd6
- String matching - https://typesense.org/learn/fuzzy-string-matching-python/


Plyer - library for accessing features of your hardware / platforms
- Docs - https://plyer.readthedocs.io/en/latest/#
- Articles 
	- https://www.geeksforgeeks.org/python-desktop-notifier-using-plyer-module/
		- Desktop notifications
	- https://medium.com/analytics-vidhya/create-desktop-notifier-using-python-6dab0a1c348c

---

### RegEx

converters - english to regex
- https://regex101.com
- https://www.autoregex.xyz

Separating columns by characters
	- https://stackoverflow.com/questions/67223873/separate-column-data-based-on-comma-characters-using-pandas-regex

Removing $ signs from strings
- `.replace( '[\$,)]','', regex=True)`

---

### *Gits*

https://github.com/mmabrouk/chatgpt-wrapper
- chatgpt wrapper

https://github.com/AlgoSkyNet/freqtrade
https://github.com/cgdeboer/rigger
- Random identity generator

https://github.com/cgdeboer/iteround
- sum-safe rounding library for Python iterables

https://github.com/AykutSarac/jsoncrack.com
- JSON crack - easily viz JSONs as graphs

https://github.com/resemble-ai
- Speech AI

https://github.com/tensortrade-org/tensortrade
https://github.com/topics/git-scraping
- Git scraping

https://github.com/ayushi7rawat/Ultimate-Python-Resource-Hub
- Ultimate python resource hub
- Look into for practice material

https://github.com/soimort/you-get
- youtube downloader

# Pandas

### Pandas Articles


Filtering dataframes
- https://medium.com/@jobethmuncy/different-ways-to-view-a-pandas-dataframe-528d193b7320
    - `df.loc[df['column'].isnull()]`
		- Null values in certain column
	- `df.loc[df['column'] >= 100, :]`
		- filtering for >=
	- `df[df['Lot Frontage'].between(50, 60)]`
		- filtering for between
	- `df[~df['Lot Frontage'].between(50, 60)`
		- `~` character returns instances NOT between those values
	- `df.loc[(df['column'] >= 1000) & (df['column'] > 100)]`
		- two different filters
	- `df['column'].unique()`
		- shows unique values

--- 
### Methods 

.append 
- Examples of using this method https://datascienceparichay.com/article/append-rows-to-a-pandas-dataframe/

.astype*
- Cast a pandas object to a specified dtype
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.astype.html

.at 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.at.html
	- Access a single value for a row/column label pair
	- `df.at[4, 'B']`
	- `df.loc[5].at['B']`

.clip 
- https://tinyurl.com/2p8c8zvh
- Replace < 0 with 0 - https://tinyurl.com/3b32stjj
	- `.clip(lower=0)`
	- `df['IBR'] = df['IBR'].clip(lower=0)`

.columns 
- prints column names 

.concat 
- https://www.geeksforgeeks.org/how-to-concatenate-two-or-more-pandas-dataframes/
	- Vertical - axis=0
	- Horizontal - axis=1
- https://towardsdatascience.com/pandas-concat-tricks-you-should-know-to-speed-up-your-data-analysis-cd3d4fdfe6dd
- Join vs merge vs concat 
	- https://stackoverflow.com/questions/38256104/differences-between-merge-and-concat-in-pandas
	- Merge with on='column' 

.contains
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.contains.html
- Drop rows that contain string - https://www.statology.org/pandas-drop-rows-that-contain-string/

.convert
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.convert_dtypes.html

.cumprod() 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.cumprod.html
- cumulative product over a DataFrame

.cumsum()
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.cumsum.html


.date_range 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.date_range.html
- `date_range(start=  , end=  )`

.diff 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.diff.html
	- Difference with previous row

.drop 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.drop.html

.drop_duplicates 
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html

.duplicated()
- https://www.geeksforgeeks.org/python-pandas-dataframe-duplicated/

.from_dicts(dicts)
- Construct DataFrame from dict of array-like or dicts
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.from_dict.html
- https://tinyurl.com/bdz9893a

.groupby
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html
- Groupby sum - https://www.datasciencemadesimple.com/group-by-sum-in-pandas-dataframe-python-2/

.grouper 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Grouper.html
- Similar to groupby and also used in conjunction with groupby

.iat 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.iat.html
- Access a single value for a row/column pair by integer position.
- Similar to iloc


.idxmin - returns min 

.idxmax - returns max
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.idxmax.html

.iloc 
- `data.iloc[:, 0:2]`
  - first two columns of data frame with all rows
- `.iloc[:, 1:]` 
  - last row, all columns
- `df.iloc[-51:-1]` 
  - selects 'last' 50 rows

.insert
- `.insert(loc=1, column='City', value=city)`
- docs - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.insert.html

.isna 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.isna.html
- https://datatofish.com/rows-with-nan-pandas-dataframe/
- `df[df['column name'].isna()]`

.isnull()
- `isnull().sum()` - returns total null values in column

.json.normalize
- Used on API calls
	- Makes output moar pretty

.le() 
- less than or equal to <=
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.le.html
-  (eq, ne, le, lt, ge, gt) other similar comparison operators

.loc 
- `Df.loc['row name'] = df.sum()`
	- Add a new row that is the sum of the columns
- If statements with .loc - https://datatofish.com/if-condition-in-pandas-dataframe/
- `df.loc[df['column name'] condition, 'new column name'] = 'value if condition is met'`

.mask 
- replace value where condition is true
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.mask.html

.melt() 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.melt.html
- Unpivot df from wide to long

.merge
- Joins dfs
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.merge.html
- https://www.shanelynn.ie/merge-join-dataframes-python-pandas-index-1/
- Merge multiple dfs
	- `final_df = reduce(lambda  left,right: pd.merge(left,right,on=['column_name'],
		                    how='outer'), dfs)`

.pivot_table 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html


.query 
- https://thecleverprogrammer.com/2021/12/28/query-data-using-python/
- Essentially a filter

.rank()
- % rank - `.rank(pct=True)`
	- `df['%rank']=df.column_name.rank(pct=True)`
- rolling % rank - `df.rolling(10).apply(lambda x: x.rank(pct=True).iloc[-1])`
	- Specifies rolling window
	- https://stackoverflow.com/questions/53584774/rolling-percent-rank-in-pandas

- 

.read 
- `.read_csv` - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html
- `.read_excel` - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_excel.html
	
.rename
- `Df.rename(columns = {'old':'new'}, inplace=True)`
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.rename.html
- https://www.geeksforgeeks.org/python-pandas-dataframe-rename/

.replace 
- Replace values given in to_replace with value
	- `.replace(to_replace=None, value= )`
- https://www.geeksforgeeks.org/python-pandas-dataframe-replace/
- https://datagy.io/pandas-replace-values/
	- Multiple values
- Single values in df 
	- https://stackoverflow.com/questions/50938519/trying-to-change-a-single-value-in-pandas-dataframe

.resample()
- `df4 = df3.resample('W').last()`
	- weekly resample, using last value

.reset_index
- Docs - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.reset_index.html
- https://www.geeksforgeeks.org/reset-index-in-pandas-dataframe/

.set_option('precision', 2)
- Sets round display to 2 without rounding

.sort_values
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.sort_values.html

str.contains 
- Docs - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.contains.html
- https://www.statology.org/pandas-drop-rows-that-contain-string/
	- Dropping samples that contain - examples

.str.extract
- Extract capture groups in the regex pat as columns in a DataFrame
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.extract.html

.strftime() 
- https://www.geeksforgeeks.org/python-pandas-datetimeindex-strftime/

.str.split
- https://www.geeksforgeeks.org/python-pandas-split-strings-into-two-list-columns-using-str-split/
-  https://stackoverflow.com/questions/38231591/split-explode-a-column-of-dictionaries-into-separate-columns-with-pandas
- https://datascienceparichay.com/article/split-pandas-column-of-lists-into-multiple-columns/
	- see for code snippets


.str.strip 
- Remove leading and trailing characters
- Docs - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.strip.html

.to_csv
-  https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.to_csv.html
- https://datagy.io/pandas-dataframe-to-csv/ 
	- More details on parameters


.to_numeric 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_numeric.html
	- Converts to numeric type

.where 
- replace values where the condition is False
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.where.html



*Other Info*

What Is `[::-1]` in Python?
- [::-1] means reversing a string, list, or any iterable with an ordering
- reverse slicing - https://www.codingem.com/reverse-slicing-in-python/

Effective pandas (book/git) - https://github.com/mattharrison/effective_pandas_book

Working with index
	- Set and reset 
	- https://datagy.io/pandas-drop-index-column/

Appending new rows to DFs
 - `Df.loc['row name'] = df.sum()`
    - add new row that is the sum of the columns
- https://datascienceparichay.com/article/append-rows-to-a-pandas-dataframe/

loc / iloc
- filtering https://www.shanelynn.ie/pandas-iloc-loc-select-rows-and-columns-dataframe/
    - iloc uses position
	- loc uses labels

Working with strings 
- Removing characters from strings - https://datagy.io/python-remove-character-from-string/
- find similar strings https://pythoninoffice.com/how-to-find-similar-strings-using-python/
- Adding string columns - https://towardsdatascience.com/combine-two-string-columns-pandas-fde0287485d9

Changing datatypes 
- .convert - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.convert_dtypes.html
- .to_numeric 
	- Multiple options - https://www.datasciencemadesimple.com/convert-character-to-numeric-pandas-python-string-to-integer-2/
- .astype*
	- Cast a pandas object to a specified dtype
	-  https://devenum.com/pandas-convert-multiple-columns-to-float/
	-  https://www.askpython.com/python/built-in-methods/python-astype

NaN values
- Replacing NaN values
	- https://moonbooks.org/Articles/How-to-replace-NaN-values-in-a-pandas-dataframe-/
- Display rows with NaN values - https://stackoverflow.com/questions/43424199/display-rows-with-one-or-more-nan-values-in-pandas-dataframe
	- `df[df['column name'].isna()]`
	- `df1 = df[df.isna().any(axis=1)]`
		- sets new df to NaN values

If statements 
	- https://datatofish.com/if-condition-in-pandas-dataframe/


Reordering columns
- https://datagy.io/reorder-pandas-columns/
- `.insert(loc=1, column='City', value=city)`


		


# Data Sci
*python for data science*

R - based python libraries
- https://rpy2.github.io/doc/latest/html/index.html
	- run both R and Python together

Numerize - https://github.com/davidsa03/numerize
- used to show large numbers into its readable format
    - 1000000 -> 1M
- https://www.geeksforgeeks.org/python-numerize-library/

Ice Cream - https://github.com/gruns/icecream
- helps visualize data workflow
- Never use print() to debug again

PCA 
- https://towardsdatascience.com/principal-component-analysis-algorithm-in-real-life-discovering-patterns-in-a-real-estate-dataset-18134c57ffe7


QQ Plots (quantile-quantile)
- Understanding them - https://data.library.virginia.edu/understanding-q-q-plots/
	- graphical tool to help us assess if a set of data plausibly came from some theoretical distribution such as a Normal or exponential

Texthero - https://texthero.org
- work with text data efficiently
- Designed to work with pandas
- https://towardsdatascience.com/texthero-text-preprocessing-representation-and-visualization-for-a-pandas-dataframe-525405af16b6
- Guide - https://analyticsindiamag.com/texthero-guide-a-python-toolkit-for-text-processing/

Dataquest - https://community.dataquest.io
- Look into getting in the slack channel

---
### *Jupyter*

tips and tricks - https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/
 - Esc + F Find and replace on your code but not the outputs.
 - `%config InlineBackend.figure_format ='retina'`
	- Makes matplotlib HD output

Nbviewer - https://nbviewer.org
- 'simple way to share jupyter notebooks'
- good examples w/ code on their homepage

Docker

- Dockerizing jupyter projects - https://towardsdatascience.com/dockerizing-jupyter-projects-39aad547484a

- How to run jupyter on docker - https://towardsdatascience.com/how-to-run-jupyter-notebook-on-docker-7c9748ed209f
	- 'Docker simplifies and accelerates your workflow, while giving developers the freedom to innovate with their choice of tools, application stacks, and deployment environments for each project.'

Dark mode
-  https://medium.datadriveninvestor.com/how-can-i-customize-jupyter-notebook-into-dark-mode-7985ce780f38


---

### *Numpy*

.where()
- Multiple conditions - https://www.statology.org/numpy-where-multiple-conditions/

.select() 
- https://numpy.org/doc/stable/reference/generated/numpy.select.html
- Return an array drawn from elements in choicelist, depending on conditions.
- Difference between where and select - https://towardsdatascience.com/the-difference-between-where-and-select-functions-of-python-numpy-9c81273ed5fb

---
### *Scipy*
- z-scores 
	- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.zscore.html
	- calc z-score from scratch - https://datagy.io/python-z-score/


--- 
### *Datetime*

selecting a date range
- `df2 = df.loc['2022-1-1' : '2022-7-4']`

Changing datetime formats with strftime 
- https://pynative.com/python-datetime-format-strftime/
	- `.strftime("%Y-%m-%d")`
	- DROPS HOURS/MIN/SEC FROM DATETIME COLUMN
	- `data.reset_index(inplace = True)
		data['Date'] = data['Date'].dt.strftime("%Y-%m-%d")
data.set_index('Date', inplace=True) `

plotting dates
- 	`ax = data.plot(x='Date', y='Close', figsize=(12,6))
	xcoords = ['2015-01-01', '2016-01-01','2017-01-01', '2018-01-01', '2019-01-01', '2020-01-01',
	          '2021-01-01']
	for xc in xcoords:
    plt.axvline(x=xc, color='black', linestyle='--')`

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

--- 
### *DS Blogs*
- https://datascienceparichay.com
- https://www.sarem-seitz.com/
	- Forecasting with Decision Trees and Random Forests https://www.sarem-seitz.com/forecasting-with-decision-trees-and-random-forests/
- https://cmdlinetips.com
	- advanced topics like stats for ML
- https://www.tomasbeuzen.com/python-programming-for-data-science/README.html
    - Stopped here - https://www.tomasbeuzen.com/python-programming-for-data-science/chapters/chapter2-loops-functions.html
- https://www.analyticsvidhya.com/blog/
	- Stats 
- https://www.kdnuggets.com

---

### *DS Articles*

Common excel formulas in python
- https://medium.com/analytics-vidhya/common-excel-formulas-in-python-c5a7ce0ae07a
	- Df.merge
	- Np.where > If functions
		- https://www.educba.com/numpy-where/

17 stats tests - https://machinelearningmastery.com/statistical-hypothesis-tests-in-python-cheat-sheet/

Hypothesis testing - https://towardsdatascience.com/significance-or-hypothesis-tests-with-python-7ed35e9ac9b6

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



# Data Viz

### *Matplotlib*

quickstart guide 
- https://matplotlib.org/stable/tutorials/introductory/quick_start.html#sphx-glr-tutorials-introductory-quick-start-py

Annotations - https://matplotlib.org/stable/tutorials/text/annotations.html

Dates
-  formats - https://matplotlib.org/stable/api/dates_api.html
- Date ranges - https://www.geeksforgeeks.org/matplotlib-dates-drange-in-python/
- other date info - https://matplotlib.org/stable/api/dates_api.html#module-matplotlib.dates

`%matplotlib inline` - for jupyter notebooks plotting

- retina display settings
    - high resolution plotting
	- `%config InlineBackend.figure_format = "retina"`
    - https://www.delftstack.com/howto/matplotlib/matplotlib-retina/
    

---

### *Seaborn*
- Setting titles 
	- `.set(title='Chart Name')`
- color palettes - https://seaborn.pydata.org/tutorial/color_palettes.html
	- color blind palatte looking v attractive
- annotating charts
	- https://balaji4u.medium.com/adding-annotations-to-seaborn-plots-5e5b134140c8
	- https://www.python-graph-gallery.com/46-add-text-annotation-on-scatterplot
		- Good examples
- lineplot 
	- 	https://seaborn.pydata.org/generated/seaborn.lineplot.html
	- `.lineplot()`
- stacked barplot
	- `.plot(kind='bar', stacked=True)`
	- https://www.statology.org/seaborn-stacked-bar-plot/
	- https://stackoverflow.com/questions/67320415/stacked-barplot-in-seaborn-using-numeric-data-as-hue
- Multiple time series 
	- https://seaborn.pydata.org/examples/timeseries_facets.html

---
### *Plotly*
- candlestick charting - https://plotly.com/python/candlestick-charts/

Figure Factory (Plotly)
- https://plotly.com/python/figure-factory-table/
	- Advanced viz for data sci 
	- Hist > https://plotly.com/python/distplot/



---
### *Dashboards*

### Dash
- https://towardsdatascience.com/plotly-dashboards-in-python-28a3bb83702c
- Plotly Dash gallery https://dash.gallery/Portal/
- React for python devs - https://dash.plotly.com/react-for-python-developers



### Streamlit 
- Installing - https://docs.streamlit.io/library/get-started/installation
- Syntax error hello world - https://stackoverflow.com/questions/72548682/streamlit-run-file-name-py-syntaxerror-invalid-syntax
	- Need to open through anaconda navigator > new > cmd
- Getting started = https://docs.streamlit.io/library/get-started
- Create an app - https://docs.streamlit.io/library/get-started/create-an-app
- Main concepts - https://docs.streamlit.io/library/get-started/main-concepts
- Run from jupyter notebook - https://dev.to/surendraredd/streamlit-code-running-from-jupyter-notebook-4olc
- Run in vscode - https://medium.com/geekculture/how-to-run-your-streamlit-apps-in-vscode-3417da669fc
- Excel sheet interactive - 
https://medium.com/@vishaltyagi.dev098/excel-sheet-interactive-dashboard-python-streamlit-114f7c240fc8
- API reference docs - https://docs.streamlit.io/library/api-reference
	- St.write() - https://docs.streamlit.io/library/api-reference/write-magic/st.write
	- Magic - https://docs.streamlit.io/library/api-reference/write-magic/magic
- *Articles*
	- Awesome streamlit - https://awesome-streamlit.readthedocs.io/en/latest/_copy_of_project_root/README.html
	  - Peruse for info, help etc..
	- Getting started w/ stock charts - https://medium.com/geekculture/getting-started-with-streamlit-ed81eafcb298
		- References yfinance 
	- Cannot be instantiated - https://github.com/streamlit/streamlit/issues/5140
	- In depth intro - https://medium.com/towards-data-science/streamlit-101-an-in-depth-introduction-fc8aad9492f2
	- Multi page streamlit app - https://towardsdatascience.com/a-multi-page-interactive-dashboard-with-streamlit-and-plotly-c3182443871a


### *Grafana*

https://grafana.com/docs/grafana/latest/
- popular with traders for managing systems

what is grafana
- https://medium.com/globant/grafana-up-and-running-what-is-grafana-f519e9ae8749
	- provides monitoring capabilities using diverse statistical visualizations at the time that allows you to integrate multiple data sources over the same platform.

--- 
### *Data Viz Articles*

https://altair-viz.github.io
- another data viz package
	- declarative statistical visualization library for Python, based on Vega and Vega-Lite

scatter plots 
- https://pythongeeks.org/python-scatter-plot/
- regression on scatters
	- https://www.statology.org/scatterplot-with-regression-line-python/


Highlighting datapoints in scatterplots
- https://cmdlinetips.com/2019/11/how-to-highlight-data-points-with-colors-and-text-in-python/
	- Filter for 'outlier' values then plot with other values in dif color

How to create two y-axis matplotlib
- https://www.statology.org/matplotlib-two-y-axes/
	- questionable if you should even make these 

Font Awesome - https://fontawesome.com/docs/web/setup/get-started
- For icons in folium

https://holoviews.org
- ' open-source Python library designed to make data analysis and visualization seamless and simple'
- Gallery - https://holoviews.org/gallery/index.html

https://pyecharts.org/#/en-us/
- `pip install pyecharts`
- Python based, highly interactive and highly performant javascript visualization library
	- Check out the scatterplot
	- has sliding scale that removes values like a filter


# SQL

Using indexing - https://use-the-index-luke.com


DBMS - https://medium.com/codex/database-management-system-2e1198ca2136

Data lemur - https://datalemur.com/
- Shows questions from interviews @ top companies (FANG)

W3 School SQL - https://www.w3schools.com/SQl/default.asp

Learn relational DBs
	- https://www.freecodecamp.org/news/how-to-run-freecodecamps-relational-databases-curriculum-using-docker-vscode-and-coderoad/

Other resources
-   https://twitter.com/SumanDe36754787/status/1559885703969837056?s=20&t=162meZF2BKo0E77q2SdZAQ

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

Scrapy Docs - https://doc.scrapy.org/en/latest/index.html

Articles
- 24 best free & paid scrapers - https://www.scrapehero.com/top-free-and-paid-web-scraping-tools-and-software/

- https://www.scrapehero.com/scrape-alibaba-using-scrapy/
 
- https://www.geeksforgeeks.org/python-web-scraping-tutorial/
 
- https://www.scrapehero.com/how-to-build-and-run-scrapers-on-a-large-scale/

Listly - https://saraametwalli.medium.com/speed-up-your-data-collection-with-listly-f09827a8dddb
- add-on to web browsers
- helps w/ scraping


Scraping with Pandas - https://medium.com/gustavorsantos/web-scraping-with-pandas-8a0f86035971
- Needs to be tables for it to draw any data from the page

---
### Beautiful Soup

Docs - https://beautiful-soup-4.readthedocs.io/en/latest/




# Markdown
Guide - https://www.markdownguide.org/

'Hacks' - https://www.markdownguide.org/hacks/
- niche commands like centered text, color, hidden comments etc..

Links
-   *Interdocument links* - https://github.com/aogilvie/markdownLinkTest#small-title
	- see raw code for examples
    - takes # in front of link to reference
	-		[Seaborn](100DOC_Notes.md#seaborn) 		
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


# AI / ML

### ChatGPT
- prompts
	- prompts guide based on categories - https://share-docs.clickup.com/36128479/d/h/12ehpz-1187/bc2728462e9a971
		- biz/accounting/marketing/sales/HR
	- 10 use cases for chatgpt as an SWE https://twitter.com/sergiorocks/status/1613553920210604037?s=46&t=6B1gYE6eBOWxF1OeKEZjEw
		- Using chat gpt for help coding
	- Good examples of how to better use it
https://medium.com/geekculture/using-chatgpt-in-python-eeaed9847e72
	- python ChatGPT wrapper https://github.com/mmabrouk/chatgpt-wrapper
		- Guide for linux - https://www.linuxuprising.com/2023/01/use-chatgpt-from-command-line-with-this.html
Using wolfram to optimize chatgpt - https://twitter.com/DrJimFan/status/1615725708281581568?s=20&t=ndivpLpenPHTROWIX1AWXA
ChatGPT to generate malware code - https://mashable.com/article/chatgpt-malware-ai-code

---

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

---

## Image Processing
- Improving the quality of images for text retrieval https://tesseract-ocr.github.io/tessdoc/ImproveQuality.html
	
- CNN / DCNs for image recognition - https://towardsdatascience.com/convolutional-neural-networks-explained-how-to-successfully-classify-images-in-python-df829d4ba761

https://www.instructables.com/Traffic-Speed-Camera-That-Recognizes-License-Plate/

Image Recognition Repos 
- https://github.com/gautamkumarjaiswal?after=Y3Vyc29yOnYyOpK5MjAxOS0wNC0yNlQwMzoyNTo1NC0wNTowMM4K8Rmr&tab=repositories

Edge Impulse 
- https://edgeimpulse.com

Vizy AI camera
	- https://docs.vizycam.com/doku.php

Motion Scope
	- https://docs.vizycam.com/doku.php?id=wiki:motionscope_app
		○ Auto detections motion and speed


DALLE-2 vs Midjourney vs StableDiffusion - https://tinyurl.com/3fyfrrj4

Deepfake AI video - https://twitter.com/TedsLittleDream/status/1562836627885416449?s=20&t=xo_Zi6PrLsbp5O73YjKmDg
- Check out how she made this, apps etc

---
### XGBoost

- https://www.datacamp.com/tutorial/xgboost-in-python
- https://machinelearningmastery.com/feature-importance-and-feature-selection-with-xgboost-in-python/


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

Poetry (dependency mgmt)
- Similar to virtual env 
- https://python-poetry.org/docs/
- Poetry vs venv - https://serpapi.com/blog/python-virtual-environments-using-virtualenv-and-poetry/

Virtual box - https://www.virtualbox.org/manual/UserManual.html

## Editors 

Visual Studio

shortcuts 
- `ctrl + d`
	- select item > `ctrl + d` to select next item, next, next etc.. then replace

How to change the interpreter - https://stackoverflow.com/questions/47602151/how-to-change-interpreter-in-visual-studio-code
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

Metasploitable 
- https://docs.rapid7.com/metasploit/quick-start-guide



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

Linking to other tabs and webpages - https://tinyurl.com/yc6af9ph
- `Ctrl-k`




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

Emmet 
- plugin, improves HTML, CSS workflow
- Cheat sheet shortcuts -https://docs.emmet.io/cheat-sheet/
- Emmet in VSCode - https://code.visualstudio.com/docs/editor/emmet

### *Flask*

https://flask.palletsprojects.com/en/2.2.x/
- QuickStart
	- Runs to local host type setup
- Command line 
	- `flask run`
	- `flask --debug run`
- Disabling cache for dev tools
	- https://stackoverflow.com/questions/5690269/disabling-chrome-cache-for-website-development

### *Java*

Tutorials 
- https://www.digitalocean.com/community/tutorials/java-web-application-tutorial-for-beginners

Installing Java on path for pdf reading
- https://stackoverflow.com/questions/54817211/java-command-is-not-found-from-this-python-process-please-ensure-java-is-inst


### *Ruby on Rails*
- Intro / what is it > https://railsware.com/blog/ruby-on-rails-guide/
	- Web dev framework

### *Jekyll*
- https://jekyllrb.com
- https://github.com/topics/jekyll-theme
	- blog-aware, site generator written in Ruby. It takes raw text files, runs it through a renderer and produces a publishable static website
	- Beautiful jekyll - https://github.com/daattali/beautiful-jekyll
		- ready-to-use templates, nice websites quickly


### *Domains*
- How to register - https://websitesetup.org/how-to-register-domain-name/
- How to get free domains - https://sitechecker.pro/how-to-get-free-domain-name/
- ICANN - https://www.icann.org
- Costs related to domains - https://websitesetup.org/how-much-costs-domain-name/

# News

https://thehackernews.com/

https://thegradient.pub
- good articles on compsi


# Other Articles



https://www.codegrepper.com/index.php
-  code examples

LaTex for python math formulas - https://github.com/google/latexify_py

https://github.com/jivoi/awesome-osint
- open source intelligence tools and resources

Sorting algos  - https://www.toptal.com/developers/sorting-algorithms

Tracking cars using license plates - https://twitter.com/intidc/status/1574263808607997953

https://fly.io/blog/

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