# Sentinel 2 imagery alerts
**NICAR 25**

This is an example workflow one might use for checking in on an area of interest over the last 7 days. It uses the open url query and a bounding box to check imagery from the last week. You can change the configurations of the date range, bounding box (AOI), cloud coverage.

It is setup using GitHub actions so that the CSV saved at the root of this GitHub repo displays the latest imagery available. It will run every day at 9:00AM UTC. You can adjust this to what you want in the `main.yml`

### For more information
Please reach out for information about this example.
GitHub Actions basics is well covered from [this tutorial here]("https://palewi.re/docs/first-github-scraper/index.html").
