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
[0]: "Databricks", "Solutions Architect - Financial Services", "https://databricks.com/company/careers/open-positions/job?gh_jid=5898639002&gh_src=62a881d62"
[1]: "Affirm", "Quantitative Markets Analytics Lead", "https://boards.greenhouse.io/affirm/jobs/5714618003?gh_src=689c81d53us"
[2]: "Swish Analytics", "Sports Data Scientist", "https://grnh.se/34b9c6cc5us?source=LinkedIn"
[3]: "PDW", "Director of Strategic Accounts - Army", "https://www.linkedin.com/jobs/search/?currentJobId=3733131500"
[4]: "General Dynamics Information Technology", "Cloud FinOps Analyst Expert", "https://gdit.wd5.myworkdayjobs.com/External_Career_Site/job/Any-Location--Remote/Cloud-FinOps-Analyst-Expert_RQ158987?source=Internet_LinkedIn"```
```
