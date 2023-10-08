# job\_scrape

Scrape recommended remote jobs from [LinkedIn](https://www.linkedin.com) and [Builtin](https://builtin.com/)
and write out results to CSV files.\
Assumes you've recently used a local web-browser to log in; uses those cookies.

```
$ ./linkedin-jobs-scrape.py -h
usage: linkedin-jobs-scrape.py [-h] [--jobs JOBS]

options:
  -h, --help            show this help message and exit
  --jobs JOBS, -j JOBS  int, number of jobs to scrape

```

```
$ ./builtin-jobs-scrape.py -h
usage: linkedin-jobs-scrape.py [-h] [--jobs JOBS]

options:
  -h, --help            show this help message and exit
  --jobs JOBS, -j JOBS  int, number of jobs to scrape
```
