<div align="center">
    <h2>Intelligence Data</h2>
    <p align="center">
        <strong>Filterlists and intel managed by @Safing</strong>
    </p>
</div>

<div align="center">

[![maintained](https://img.shields.io/maintenance/yes/2020?label=maintained&style=flat-square)](https://github.com/safing/intel-data/commits/master)
[![maintained](https://img.shields.io/reddit/subreddit-subscribers/safing?style=flat-square&color=blue)](https://www.reddit.com/r/safing)

</div>
<hr>

This repository contains filterlists and other intelligence data used by the [Portmaster](https://github.com/safing/portmaster) and managed by Safing. It contains multiple files for various categories, see below for a list of available lists.

Note that this repository is meant as an addition to various other filterlists available. Checkout the awesome <b><i>[filterlists.com](https://filterlists.com)</i></b> site too!

## Categories

This repository contains the following categories split into multiple files:

- [ads.txt](./lists/ads.txt): Services that serve ads and track their audiences.
- [analytics.txt](./lists/analytics.txt): Services that provide visitor analysis/profiling.
- [fakenews.txt](./lists/fakenews.txt): Services that deliberately provide wrong information.
- [fraud.txt](./lists/fraud.txt): Services that scam people.
- [malware.txt](./lists/malware.txt): Services that are (ab)used for attacking devices through technical means.
- [phishing.txt](./lists/phishing.txt): Services that engage in credential fishing.
- [telemetry.txt](./lists/telemetry.txt): Services that collect application telemetry.
- [tracking-other.txt](./lists/tracking-other.txt): Services that are believed to serve ads or track users, but their exact use is unknown or not categorized.

## Contributing

Contributions of any kind are welcome! Thanks for taking the time to contribute! :tada:

### Community

Join our community around forging powerful privacy tools at reddit:

[![maintained](https://img.shields.io/reddit/subreddit-subscribers/safing?style=flat-square&color=blue)](https://www.reddit.com/r/safing)


### Filterlists

When contributing new domains for the filter list categories, please make sure to follow the few principels outlined here:


**Open an Issue / PR**

All contributions to this repository should be preceeded by an issue. The issue or PR
number should *always* be added as a comment to the added filterlist entry. This allows for better reasoning of why an entry has been added and also provides guidance to verify if a list entry is still relevant (see below).

For example:
```
some-tracking-domain.com  #100
```

**Ordering of list entries**

If you plan to add new domains to one ore more of the filterlist categories contained in this repository please make sure to add them to the end of the file. This will allow users to reason about how old list entries are and if the may be obsolete.

If you took time and verified some of the top (and oldest) list entries, please move them to the bottom of the file if they are still relevant.

**Commit message**

You are free to describe the reason for the commit in the commit message but please always start the commit with `Fixes #12` so the issue get's closed when merged and
github will link the commit to the issue to find all the details and discussions.

## License

This repository is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Refer to the link or to the [LICENSE file](.LICENSE) for more information.
