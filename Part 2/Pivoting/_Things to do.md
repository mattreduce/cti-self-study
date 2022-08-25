# Pivoting: Things to do

- [ ] Try a TLS certificate pivot by…
    - [ ] Identifying the default SHA256 hash value shipped on Cobalt Strike servers (see [here](https://www.recordedfuture.com/identifying-cobalt-strike-servers)),
    - [ ] Searching for that hash value in Censys ([https://search.censys.io/](https://search.censys.io/)), and
    - [ ] Identifying IP addresses that result
    - [ ] What do those IP addresses potentially represent?
    - [ ] What could you do to try to validate if that pivot you performed was meaningful?
- [ ] Find a recent blog post on a threat group or malware family that contains some pivotable artifact (look at the RSS feed you hopefully set up based on [Part 1 of this plan](https://medium.com/katies-five-cents/a-cyber-threat-intelligence-self-study-plan-part-1-968b5a8daf9a)). Try searching for those artifacts in free search sources and see if you can reproduce the research from the blog post about any pivots and/or find any new artifacts from pivoting.

Resources from Katie:

>Here are some free search sources you might find useful for this: Censys (https://search.censys.io/), Shodan (https://www.shodan.io/), DomainTools WhoIs (https://whois.domaintools.com/), VirusTotal (https://www.virustotal.com/), URLhaus (https://urlhaus.abuse.ch/), and Malware Domain List (https://www.malwaredomainlist.com/). There are many others listed on Awesome Threat Intelligence that you can try as well.
>
>If you need an example to get you started, try looking up hash values and IPs from this ESET blog post in VirusTotal.