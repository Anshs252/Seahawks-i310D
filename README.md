# Wikipedia-dsa
Goal:
The objective of this project is to examine the frequency of revisions made on Wikipedia since December, 2021. The data will be collected, transformed, and visualized to reveal any intriguing patterns or insights regarding the page edits.

# API Links
Wikiemedia rest API: https://www.mediawiki.org/wiki/API:Main_page
Pandas: https://pandas.pydata.org/docs/
Mathplotlib: https://matplotlib.org/stable/users/index.html
Requests: https://docs.python-requests.org/en/latest/

# MIT License:

Copyright (c) 2023 [Saiansh Saxena]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Data Types and Descriptions: 
date: (Integer) The month in 2022 formatted as YYYY-MM.
editors: (Integer) The total number of revisions made in Wikipedia within the corresponding month.

The end date for each month is assumed to be the 28th day for simplicity, which may not accurately represent the total revisions in months with more than 28 days.

# Issues: 
The end date for every month is assumed to be the 28th day for simplicity purposes, but that does not accurately represent the total revisions for every month as for most, 2-3 days are left unaccounted for. 
