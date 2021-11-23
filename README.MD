[![Cron CI](https://github.com/travisboss/Jefe-Lists/actions/workflows/cron.yml/badge.svg?branch=main)](https://github.com/travisboss/Jefe-Lists/actions/workflows/cron.yml)

<a href="https://www.buymeacoffee.com/jefeList" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

_This list is updated nightly._

Big thanks to [Adguard](https://github.com/AdguardTeam/HostlistCompiler), [OISD](https://oisd.nl/), [Wally3K](https://firebog.net/), [NextDNS](https://github.com/nextdns), [Anudeep](https://github.com/anudeepND/whitelist) and [oneoffdallas](https://github.com/oneoffdallas/dohservers) for creating these lists, without them I would not be writing these words.

<hr />

### Moved from energized unblock to anudeep whitelist, if find issues please raise a bug.

### Removed Pegasus list see [here](https://github.com/AmnestyTech/investigations/issues/4#issuecomment-888181343)

**Can use with adguard, adguard home, ublock, adblock, adblockplus, opera, adnuseaum and any service that accepts adblock styntax**

All I am trying to do is compile some adblock syntax only lists with Adguards Hostlist Compiler and what you see here is:

1. allowlist.txt - This is a compiled down list from Anudeep's whitelist, simply removing a lot of comments and any parts that are not allowed per Adguard.
2. wally3k_blocklist.txt - This is a compiled list from Wally3k of all his ticked lists at https://v.firebog.net/hosts/lists.php?type=tick checked against Anudeep's whitelist, and removing all comments.
3. oisd_blocklist.txt - I have compiled [osid adp full list](https://abp.oisd.nl/) to remove comments, checked against Anudeep's whitelist and I have added [oneoffdallas DoH](https://github.com/oneoffdallas/dohservers) to this list, I do not want users to use DoH on my network and bypass my DNS.
4. nextdns_blocklist.txt - I have added what NextDNS uses for there default recommended list and checked against Anudeep's whitelist and remove comments, you can find the lists here https://github.com/nextdns/metadata/blob/master/privacy/blocklists/nextdns-recommended.json

If you are unsure what list to use I generally recommend `nextdns_blocklist.txt`, but feel free to try the others and see how they work for you. If you find an issue please submit a bug and PR's are welcome! I am looking for help to maybe streamline my github action.

I have changed the name of the ticked list to wally3k_blocklist.txt and for now I have removed the non-ticked list, there are too many issues with the lists themselves and the build time is just too long and unreliable.
