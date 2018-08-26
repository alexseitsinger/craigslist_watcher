# Craigslist Watcher

## Description

Returns a list of urls for each new post found on craigslist.

## Installation

```
pip install craigslist-watcher
```

or

```
pipenv install craigslist-watcher
```

## Methods

1. watch(interval, url) - Returns a list of urls for each unique new post found at url. Repeats after every interval of seconds.

## Usage

```python
from craigslist_watcher import watch

new_posts = watch(60, "https://southcoast.craigslist.org/search/web?query=&excats=&userid=&postedToday=1&search_distance=&postal=")
```