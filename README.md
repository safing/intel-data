<div align="center">
    <h2>Filterlists and Intelligence Data</h2>
    <p align="center">
        <strong>by the community, for the community</strong><br />
        managed by Safing
    </p>
</div>

<hr>

This repository contains filterlists and other intelligence data used by the [Portmaster](https://github.com/safing/portmaster).  
It is maintained by the community and managed by Safing.

## External Sources

All Portmaster's external sources are listed in the [sources.yml](./lists/sources.yml).

Currently, the Portmaster cannot yet ingest custom sources directly. If you know about a great source, please open an issue so we can discuss adding it.  
If you came here for the sources, also check out [filterlists.com](https://filterlists.com).

## Filter Lists

These lists are managed in this repo:

- [ads.txt](./lists/ads.txt): Services that serve ads and track their audiences.
- [analytics.txt](./lists/analytics.txt): Services that provide visitor analysis/profiling.
- [fraud.txt](./lists/fraud.txt): Services that scam people.
- [malware.txt](./lists/malware.txt): Services that are (ab)used for attacking devices through technical means.
- [phishing.txt](./lists/phishing.txt): Services that engage in credential fishing.
- [telemetry.txt](./lists/telemetry.txt): Services that collect application telemetry.
- [tracking-other.txt](./lists/tracking-other.txt): Services that are believed to serve ads or track users, but their exact use is unknown or not categorized.
- [securedns.txt](./lists/securedns.txt): Services that provide secure DNS resolving. Used for bypass prevention.
- [securedns-ip4.txt](./lists/securedns-ip4.txt): Same, but IPv4 addresses.
- [securedns-ip6.txt](./lists/securedns-ip6.txt): Same, but IPv6 addresses.
- [p2p.txt](./lists/p2p.txt): Services that provide STUN, TURN, ICE or similar services that expose the user's IP address and enable peer to peer networking behind NAT. Used for advanced privacy protection.
- [p2p-ip4.txt](./lists/p2p-ip4.txt): Same, but IPv4 addresses.
- [p2p-ip6.txt](./lists/p2p-ip6.txt): Same, but IPv6 addresses.

## Contributing

Contributions of any kind are welcome! Thanks for taking the time to contribute! :tada:

### Community

Join our community around forging powerful privacy tools at reddit:

[![maintained](https://img.shields.io/reddit/subreddit-subscribers/safing?style=flat-square&color=blue)](https://www.reddit.com/r/safing)


### Filterlists

When contributing new domains for the filter list categories, please make sure to follow the few principels outlined here:

**Open an Issue / PR**

All contributions to this repository should be preceeded by an issue. Please always add a description, so one can quickly understand why the domain is in the list.

For example:
```
some-tracking-domain.com  # short description
```

**Ordering of list entries**

If you plan to add new domains to one or more of the filterlists, please make sure to add them to the end of the file. This will allow users to reason about how old list entries are and if the may be obsolete.

If you took time and verified some of the top (and oldest) list entries, please move them to the bottom of the file if they are still relevant.

**Commit message**

You are free to describe the reason for the commit in the commit message but please always start the commit with `Fixes #12` so the issue get's closed when merged and Github will link the commit to the issue to find all the details and discussions.

## License

This repository is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Refer to the link or to the [LICENSE file](.LICENSE) for more information.
