# Daily Google Lighthouse reports for redaxo.org

This repo schedules a job which regularily records [Google Lighthouse](https://github.com/GoogleChrome/lighthouse-ci) reports of several redaxo.org core pages.
The results can be found in the [Actions tab](https://github.com/FriendsOfREDAXO/lighthouse-redaxo.org/actions?query=workflow%3ALighthouse), attached to each Action run as Artifacts.

Additionally you can find online versions of the reports of the last 7 days, by drilling into the "Audit URLs using Lighthouse" Github Action step.

All configuration can be found in a single file: [schedule.yml](https://github.com/FriendsOfREDAXO/lighthouse-redaxo.org/blob/master/.github/workflows/schedule.yml)
