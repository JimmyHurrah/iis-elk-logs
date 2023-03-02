### A "good enough" setup for analysing local iis log files

- Put logs in ./logs as *.log
- Adjust grok pattern in iis.conf

```cli
> docker compose up
```
Open http://localhost:5601 in a browser
