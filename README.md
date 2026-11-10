# byronfor25.com redirect

byronfor25.com is the secondary address for Byron Sigcho-Lopez's 25th Ward
campaign site. The site itself lives at https://sigchofor25.com and is built
from the `BSL-for-Congress` repo.

This repo only does two things:

- `index.html` and `404.html` send every visit to the same path on
  sigchofor25.com.
- `events/all.ics` and `events/all-es.ics` are copies of the calendar feeds,
  refreshed every six hours by `.github/workflows/mirror-feeds.yml`, so
  calendar subscriptions made at the old address keep updating.
