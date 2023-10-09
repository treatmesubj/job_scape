# job\_scrape

Scrape recommended remote jobs from [LinkedIn](https://www.linkedin.com) and [Built In](https://builtin.com/)
and write out results to CSV files.\
Assumes you've recently used a local web-browser to log in; uses those cookies.

```
$ ./linkedin-jobs-scrape -h
usage: linkedin-jobs-scrape [-h] [--jobs JOBS]

options:
  -h, --help            show this help message and exit
  --jobs JOBS, -j JOBS  int, number of jobs to scrape
```

```
$ ./builtin-jobs-scrape -j 5
```
