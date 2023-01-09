# I will take these lists down on 01/16/2023, thank you all. My suggest is to look at [Hagezi Lists](https://github.com/hagezi/dns-blocklists)

[![Cron CI](https://github.com/travisboss/Jefe-Lists/actions/workflows/cron.yml/badge.svg?branch=main)](https://github.com/travisboss/Jefe-Lists/actions/workflows/cron.yml)

[NextDNS Referral Code](https://nextdns.io/?from=nwmzs7gc)

_This list is updated nightly._

Big thanks to [Adguard](https://github.com/AdguardTeam/HostlistCompiler), [OISD](https://oisd.nl/), [Wally3K](https://firebog.net/), [NextDNS](https://nextdns.io/?from=nwmzs7gc), [AdguardTeam HttpsExclusions](https://github.com/AdguardTeam/HttpsExclusions) and [oneoffdallas](https://github.com/oneoffdallas/dohservers) for creating these lists, without them I would not be writing these words.

<hr />

**Can use with adguard, adguard home, ublock, adblock, adblockplus, opera, adnuseaum and any service that accepts adblock styntax**

All I am trying to do is compile some adblock syntax only lists with Adguards Hostlist Compiler and what you see here is:

1. [allowlist.txt](https://raw.githubusercontent.com/travisboss/Jefe-Lists/main/allowlist.txt) - This is a compiled down list from AdguardTeam HttpsExclusions.

2. [wally3k_blocklist.txt](https://raw.githubusercontent.com/travisboss/Jefe-Lists/main/wally3k_blocklist.txt) - This is a compiled list from Wally3k of all his ticked lists at https://v.firebog.net/hosts/lists.php?type=tick checked against AdguardTeam HttpsExclusions, and removing all comments.

3. [oisd_blocklist.txt](https://raw.githubusercontent.com/travisboss/Jefe-Lists/main/oisd_blocklist.txt) - I have compiled [osid adp full list](https://raw.githubusercontent.com/sjhgvr/oisd/main/abp_full.txt) to remove comments, checked against AdguardTeam HttpsExclusions and I have added [oneoffdallas DoH](https://github.com/oneoffdallas/dohservers) to this list, I do not want users to use DoH on my network and bypass my DNS.

4. [nextdns_blocklist.txt](https://raw.githubusercontent.com/travisboss/Jefe-Lists/main/nextdns_blocklist.txt) - I have added what [NextDNS](https://nextdns.io/?from=nwmzs7gc) uses for there default recommended list and checked against AdguardTeam HttpsExclusions and remove comments, you can find the lists here https://github.com/nextdns/metadata/blob/master/privacy/blocklists/nextdns-recommended.json

5. [deviceTracking_blocklist.txt](https://raw.githubusercontent.com/travisboss/Jefe-Lists/main/deviceTracking_blocklist.txt) - this is a combined list of device trackers including Alexa, Apple, Huawei, Roku, Samsung, Sonos, Windows, Xiaomi from [NextDNS](https://nextdns.io/?from=nwmzs7gc).

6. [oisd_1hostlite_blocklist.txt](https://raw.githubusercontent.com/travisboss/Jefe-Lists/main/oisd_1hostlite_blocklist.txt) - This is a compiled list of oisd full and 1host lite.

If you are unsure what list to use I generally recommend `oisd_1hostlite_blocklist.txt`, but feel free to try the others and see how they work for you. If you find an issue please submit a bug and PR's are welcome! I am looking for help to maybe streamline my github action.
