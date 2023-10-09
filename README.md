# job\_scrape

Scrape recommended remote jobs from [LinkedIn](https://www.linkedin.com) and [Built In](https://builtin.com/)
and write out results to CSV files.\
Assumes you've recently used a local web-browser to log in; uses those cookies.

```
$ ./linkedin-jobs-scrape -h
usage: linkedin-jobs-scrape [-h] [--jobs JOBS] [--sleeptime SLEEPTIME] [--outset OUTSET]

options:
  -h, --help            show this help message and exit
  --jobs JOBS, -j JOBS  int, number of jobs to scrape
  --sleeptime SLEEPTIME, -s SLEEPTIME
                        int, number of seconds to sleep between each job-scrape
  --outset OUTSET, -o OUTSET
                        int, job index to start scraping at
```

```
$ ./builtin-jobs-scrape -j 5 -s 60
[0]: "EquiTrust Life Insurance Company", "Commission Specialist", "https://recruiting.ultipro.com/EQU1003TRSTL/JobBoard/92b5f1e0-a63e-95b3-de89-a29e3b4c78d2/OpportunityDetail?opportunityId=ba926baf-fb37-4090-9a39-78a405744357&source=Built In", "https://builtin.com/job/finance/commission-specialist/2060567"
[1]: "Motorola Solutions", "Sr. Account Manager/Executive (Wisconsin)", "https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Wisconsin-Remote-Work/Sr-Account-Manager-Executive--Wisconsin-_R41489?source=BuiltInNationwide", "https://builtin.com/job/sales/sr-account-managerexecutive-wisconsin/2069829"
[2]: "Pennymac", "Architect, Data Science", "https://careers-pennymac.icims.com/jobs/28762/architect%2c-data-science/job?ss=1&mode=job&iis=BuiltIn&iisn=BuiltIn", "https://builtin.com/job/data/architect-data-science/2069840"
[3]: "Cox Enterprises", "Bilingual Service Center Specialist II, Employee Service Center", "https://click.appcast.io/track/hnpikmk-org?cs=mo1&jg=65v4&bid=q948nGl57dNhZO5Va2AQmA==/", "https://builtin.com/job/customer-success/bilingual-service-center-specialist-ii-employee-service-center/2069632"
[4]: "Block", "COM Compliance Specialist, Cash App", "https://www.smartrecruiters.com/Square/67890bfa-cc06-4fd3-b864-a64896f9c293?trid=3d4e5ece-fa6a-4ee3-821c-26c11ac9645b", "https://builtin.com/job/finance/com-compliance-specialist-cash-app/2069431"
[5]: "Optum", "Associate Director Network Contracting - Remote in New York", "https://ad.doubleclick.net/ddm/clk/564543718;373569178;b?https://careers.unitedhealthgroup.com/job/19236829/associate-director-network-contracting-remote-in-new-york-remote/?src=JB-22390&utm_source=builtin.com&utm_medium=job_posting&utm_campaign=Optum_NA_Non_Clinical&utm_content=niche_site&utm_term=373569178&ss=paid/", "https://builtin.com/job/operations/associate-director-network-contracting-remote-new-york/2069451"
```
---
# Friendly Application Platforms
```
https://grnh.se
https://app.greenhouse.io
https://jobs.lever.co/
```
