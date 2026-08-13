# Awesome Offensive-OSINT-Tools with stars

This repository contains tools and links that can be used during OSINT in Pentest or Red Team. Currently, there are numerous awesome lists with tons of tools, but Offensive Security specialists often don't need such an extensive selection. This motivated the creation of this list. These tools cover almost all the needs of Offensive Security specialists and will help you get the job done efficiently.

If the tool performs multiple functions, for example collecting subdomains **and** URLs, it will be listed in two places.

## 📖 Table of Contents

* [Search Engines](#-search-engines)
* [Email addresses](#-email-addresses)
* [Source code](#-source-code)
* [SubDomain's](#-subdomains)
* [URLs](#-urls)
* [Dark Web](#-dark-web)
* [Intelligence](#-intelligence)
* [Network Info](#-network-info)
* [DnsHistory](#-dnshistory)
* [Certifications](#-certifications)
* [FTP servers](#-ftp-servers)
* [Passive Infrastructure scanner](#-passive-infrastructure-scanner)
* [Microsoft Exchange](#-microsoft-exchange)
* [Telegram](#-telegram)
* [Google Dorks](#-google-dorks)
* [Nickname search](#-nickname-search)
* [Phone number](#-phone-number)
* [Wifi](#-wifi)
* [Cloud](#-cloud)
* [Information gathering tools](#-information-gathering-tools)
* [Useful links](#-useful-links)

## [↑](#-table-of-contents) Contributing

**Welcome!** If you find that any of your favourite offensive tools is not on the list, you can suggest adding it.

***

## [↑](#-table-of-contents) Search Engines

Search Engines for Investigation Domains/IP Addresses.

* [Censys](https://censys.io/)
* [Shodan](https://www.shodan.io/)
* [Greynoise.io](https://viz.greynoise.io/)
* [ZoomEye](https://www.zoomeye.org/)
* [Onyphe](https://www.onyphe.io/)
* [Fofa](https://fofa.info/)
* [Binaryedge](https://app.binaryedge.io/)
* [FullHunt](https://fullhunt.io/)
* [Netlas](https://app.netlas.io/)
* [Quake360](https://quake.360.net/quake/#/index)
* [Criminalip](https://www.criminalip.io/)
* [Synapsint](https://synapsint.com/)
* [Natlas](https://natlas.io/)
* [Leakix](https://leakix.net/)
* [Dorki.io](https://dorki.io/)

## [↑](#-table-of-contents) Email addresses

Tools that help you collect email addresses. Usually the search requires the domain of the company.

* [theHarvester](https://github.com/laramies/theHarvester) ⭐ 17,029 | 🐛 9 | 🌐 Python | 📅 2026-08-12
* [h8mail](https://github.com/khast3x/h8mail) ⭐ 5,249 | 🐛 39 | 🌐 Python | 📅 2023-08-15 - Email OSINT & Password breach hunting tool
* [Poastal](https://github.com/jakecreps/poastal) ⭐ 603 | 🐛 11 | 🌐 Python | 📅 2024-04-08 - Tool that provides valuable information on any email address
* [Eyes](https://github.com/N0rz3/Eyes) ⚠️ Archived - Email osint tool
* [EmailFinder](https://github.com/Josue87/EmailFinder) ⚠️ Archived - Search emails from a domain through search engines
* [ronin-recon](https://github.com/ronin-rb/ronin-recon) ⭐ 42 | 🐛 39 | 🌐 Ruby | 📅 2026-01-15 - Recursive recon engine and framework that can enumerate subdomains, DNS records, port scan, grab TLS certs, spider websites, and collect email addresses.
* [Prospeo.io](https://app.prospeo.io/domain-search)
* [Hunter.io](https://hunter.io/)
* [Snov.io](https://snov.io/)
* [Phonebook](https://phonebook.cz/)
* [findemail.io](https://findemail.io/)
* [Omail](https://omail.io/leads/download.html)
* [Skymem](https://www.skymem.info/)
* [Signalhire](https://www.signalhire.com/)
* [Rocketreach](https://rocketreach.co/)
* [Infoga](https://github.com/m4ll0k/Infoga)
* [Email-format](https://www.email-format.com/) - Analyses the company's mail format.
* [Anymailfinder](https://anymailfinder.com/) - Find Verified Emails
* [tomba.io](https://tomba.io/) - email finder
* [contactout.com](https://contactout.com/) - person finder

## [↑](#-table-of-contents) SubDomain's

Tools for automatic search of subdomains. Most of them require API keys to work correctly.

### Tools

* [Spiderfoot](https://github.com/smicallef/spiderfoot) ⭐ 20,399 | 🐛 273 | 🌐 Python | 📅 2026-04-13
* [theHarvester](https://github.com/laramies/theHarvester) ⭐ 17,029 | 🐛 9 | 🌐 Python | 📅 2026-08-12
* [Amass](https://github.com/OWASP/Amass) ⭐ 14,974 | 🐛 235 | 🌐 Go | 📅 2026-07-19
* [Photon](https://github.com/s0md3v/Photon) ⭐ 13,108 | 🐛 58 | 🌐 Python | 📅 2026-08-07 - Incredibly fast crawler designed for OSINT.
* [Bbot](https://github.com/blacklanternsecurity/bbot) ⭐ 10,348 | 🐛 31 | 🌐 Python | 📅 2026-08-13
* [Sudomy](https://github.com/screetsec/Sudomy) ⭐ 2,422 | 🐛 41 | 🌐 Shell | 📅 2024-06-27
* [GooFuzz](https://github.com/m3n0sd0n4ld/GooFuzz) ⭐ 1,582 | 🐛 0 | 🌐 Shell | 📅 2025-12-21 - Enumerate directories, files, subdomains or parameters without leaving evidence on the target's serve
* [alterx](https://github.com/projectdiscovery/alterx) ⭐ 989 | 🐛 7 | 🌐 Go | 📅 2026-07-10 - Fast and customizable subdomain wordlist generator using DSL.
* [Subdominator](https://github.com/RevoltSecurities/Subdominator) ⭐ 799 | 🐛 5 | 🌐 Python | 📅 2026-06-21
* [SubGPT](https://github.com/s0md3v/SubGPT) ⚠️ Archived - SubGPT looks at subdomains you have already discovered for a domain and uses BingGPT to find more.
* [sub.Monitor](https://github.com/e1abrador/sub.Monitor) ⭐ 172 | 🐛 2 | 🌐 Python | 📅 2024-01-30 - Passive subdomain continous monitoring tool
* [ronin-recon](https://github.com/ronin-rb/ronin-recon#readme) ⭐ 42 | 🐛 39 | 🌐 Ruby | 📅 2026-01-15 - Recursive recon engine and framework that can enumerate subdomains, DNS records, port scan, grab TLS certs, spider websites, and collect email addresses.
* [subdomain-enum](https://github.com/chaitanyakrishna/subdomain-enum) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2023-03-18 - securitytrails api
* [subchase](https://github.com/tokiakasu/subchase) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2023-09-29 - Chase subdomains by parsing the results of Google and Yandex search results

*Only sites/tools whose search is not automated by the tools above are listed here.*

* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [dash.pugrecon.celes.in](https://dash.pugrecon.celes.in/)
* [Securitytrails](https://securitytrails.com/)
* [Shrewdeye](https://shrewdeye.app/)
* [Phonebook](https://phonebook.cz/)
* [Nmmapper](https://nmmapper.com/)
* [subdomainfinder.c99.](https://subdomainfinder.c99.nl/) - A subdomain finder is a tool used to find the subdomains of a given domain.
* [SubDomainRadar.io](https://subdomainradar.io) - Discover hidden subdomains with unparalleled accuracy and speed

## [↑](#-table-of-contents) URLs

Tools for passive collection and analysis URLs

* [Spiderfoot](https://github.com/smicallef/spiderfoot) ⭐ 20,399 | 🐛 273 | 🌐 Python | 📅 2026-04-13
* [theHarvester](https://github.com/laramies/theHarvester) ⭐ 17,029 | 🐛 9 | 🌐 Python | 📅 2026-08-12
* [Gau](https://github.com/lc/gau) ⭐ 5,060 | 🐛 35 | 🌐 Go | 📅 2026-03-20
* [Waymore](https://github.com/xnl-h4ck3r/waymore) ⭐ 2,718 | 🐛 2 | 🌐 Python | 📅 2026-06-11
* [urlhunter](https://github.com/utkusen/urlhunter) ⭐ 1,698 | 🐛 0 | 🌐 Go | 📅 2025-01-23 - a recon tool that allows searching on URLs that are exposed via shortener services
* [GooFuzz](https://github.com/m3n0sd0n4ld/GooFuzz) ⭐ 1,582 | 🐛 0 | 🌐 Shell | 📅 2025-12-21 - Enumerate directories, files, subdomains or parameters without leaving evidence on the target's serve
* [Urlfinder](https://github.com/projectdiscovery/urlfinder) ⭐ 897 | 🐛 4 | 🌐 Go | 📅 2026-08-10
* [Uscrapper](https://github.com/z0m31en7/Uscrapper) ⭐ 787 | 🐛 4 | 🌐 Python | 📅 2024-11-24 - Tool that allows users to extract various personal information from a website.
* [Xurlfind3r](https://github.com/hueristiq/xurlfind3r) ⭐ 719 | 🐛 3 | 🌐 Go | 📅 2026-02-23
* [Ominis-Osint](https://github.com/AnonCatalyst/Ominis-Osint) ⭐ 604 | 🐛 0 | 🌐 Python | 📅 2026-08-07 - The tool extracts relevant information such as titles, URLs, and potential mentions of the query in the results.
* [ronin-recon](https://github.com/ronin-rb/ronin-recon#readme) ⭐ 42 | 🐛 39 | 🌐 Ruby | 📅 2026-01-15 - Recursive recon engine and framework that can enumerate subdomains, DNS records, port scan, grab TLS certs, spider websites, and collect email addresses.
* [Unja](https://github.com/ninjhacks/unja) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2022-08-03
* [Rextracter.streamlit](https://rextracter.streamlit.app/) - Gathers links and analyses content

## [↑](#-table-of-contents) Source code

Tools for finding mentions in code. Useful to search for company/company mentions to find passwords/secrets/confidential information.

* [Publicwww](https://publicwww.com/)
* [Nerdydata](https://www.nerdydata.com/)
* [Searchcode](https://searchcode.com/)
* [Grep.app](https://grep.app/)

## [↑](#-table-of-contents) Dark web

An undiscovered area, the author is too dumb for that. Will gradually expand.

* [Ahmia](https://ahmia.fi/)

## [↑](#-table-of-contents) Intelligence

Threat Intelligence tools containing extensive company information, subdomains, DNS information, URLs and much more.

* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)
* [Pulsedive](https://pulsedive.com/)
* [ThreatBook](https://threatbook.io/)
* [Alienvault](https://otx.alienvault.com/)
* [DomScan](https://domscan.net/tools/security) - Domain intelligence for DNS, WHOIS/RDAP, TLS, subdomains, reputation, redirects, and typosquatting.
* [Hudson Rock - Cybercrime Intelligence Tools](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools)
* [LeakRadar](https://leakradar.io)

## [↑](#-table-of-contents) Network Info

IP/Domain network analysis tools.

* [Bgp.he](https://bgp.he.net/)
* [whoistory](http://whoistory.com/)
* [Asnlookup](https://asnlookup.com/)
* [centralops](http://centralops.net/)
* [Bgp.tools](https://bgp.tools/)
* [Myip](https://myip.ms/)
* [IpInfo](https://ipinfo.io/) | [Cmd version](https://github.com/ipinfo/cli) ⭐ 2,049 | 🐛 3 | 🌐 Go | 📅 2026-04-28
* [Whoisxmlapi](https://main.whoisxmlapi.com/)

## [↑](#-table-of-contents) DnsHistory

Tools for viewing the DNS history of a domain.

* [Bigdomaindata](https://bigdomaindata.com)
* [Dnshistory](https://dnshistory.org/)
* [Viewdns](https://viewdns.info/)
* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)

## [](#-table-of-contents) Certifications

* [Crt.sh](https://crt.sh/)
* [Web-check](https://github.com/Lissy93/web-check) ⭐ 34,485 | 🐛 31 | 🌐 TypeScript | 📅 2026-08-11 + [Web version](https://web-check.as93.net/)

## [↑](#-table-of-contents) FTP servers

Tools allowing you to search for and download files located on public FTP servers.

* [Searchftps](https://www.searchftps.net/)

## [↑](#-table-of-contents) Passive Infrastructure scanner

Tools for automated passive IP address/subnet scanning.

* [Smap](https://github.com/s0md3v/Smap) ⭐ 3,279 | 🐛 1 | 🌐 Go | 📅 2026-04-13
* [Nmap-censys](https://github.com/censys/nmap-censys) ⭐ 59 | 🐛 0 | 🌐 Lua | 📅 2021-12-03

## [↑](#-table-of-contents) Microsoft Exchange

Tools that help in passive/semi-passive analysis of Microsoft Exchange.

* [ExchangeFinder](https://github.com/mhaskar/ExchangeFinder) ⭐ 190 | 🐛 9 | 🌐 Python | 📅 2023-01-30 | #SemiOSINT

## [↑](#-table-of-contents) Telegram

Tools for investigating Telegram chats.

* [Telepathy](https://github.com/jordanwildon/Telepathy) ⭐ 1,234 | 🐛 43 | 🌐 Python | 📅 2026-08-10

## [↑](#-table-of-contents) Google Dorks

Tools for Google Dorks.

* [Pagodo](https://github.com/opsdisk/pagodo) ⭐ 3,387 | 🐛 5 | 🌐 Python | 📅 2025-12-01
* [Search](https://github.com/pbkompasz/search) ⚠️ Archived - Custom queries in Google
* [Google hacking database](https://www.exploit-db.com/google-hacking-database)
* [Recruitin](https://recruitin.net/) - Compiles Google dorks to search on LinkedIn, Dribbble, GitHub, Xing, StackOverflow, Twitter

## [↑](#-table-of-contents) Nickname search

Nickname search tools.

* [Sherlock](https://github.com/sherlock-project/sherlock) ⭐ 89,368 | 🐛 324 | 🌐 Python | 📅 2026-08-12
* [maigret](https://github.com/soxoj/maigret) ⭐ 36,711 | 🐛 22 | 🌐 Python | 📅 2026-08-12
* [Social analyzer](https://github.com/qeeqbox/social-analyzer) ⭐ 23,738 | 🐛 26 | 🌐 JavaScript | 📅 2026-01-12
* [recon-ng](https://github.com/lanmaster53/recon-ng/) ⭐ 5,847 | 🐛 38 | 🌐 Python | 📅 2024-11-01
* [snoop](https://github.com/snooppr/snoop) ⭐ 4,000 | 🐛 1 | 🌐 Python | 📅 2026-07-30
* [whatsmyname](https://github.com/webbreacher/whatsmyname) ⭐ 2,757 | 🐛 6 | 🌐 Python | 📅 2026-08-12
* [nexfil](https://github.com/thewhiteh4t/nexfil) ⭐ 2,602 | 🐛 8 | 🌐 Python | 📅 2023-09-30
* [socialscan](https://github.com/iojw/socialscan) ⭐ 1,813 | 🐛 14 | 🌐 Python | 📅 2026-08-03
* [userrecon](https://github.com/wishihab/userrecon) ⚠️ Archived
* [Search4](https://github.com/0xknown/Search4) ⭐ 203 | 🐛 1 | 🌐 Python | 📅 2022-07-17
* [SocialPath](https://github.com/woj-ciech/SocialPath) ⭐ 169 | 🐛 3 | 🌐 CSS | 📅 2021-01-26
* [gideon](https://github.com/YouVBeenHacked/gideon) ⭐ 143 | 🐛 3 | 🌐 Python | 📅 2023-12-11
* [Sherlock](https://github.com/mesuutt/sherlock) ⭐ 78 | 🐛 1 | 🌐 Go | 📅 2022-05-14
* [netizenship](https://github.com/rahulrajpl/netizenship) ⭐ 49 | 🐛 2 | 🌐 Python | 📅 2022-12-08
* [NicknameFinder](https://github.com/restanse/NicknameFinder) ⭐ 38 | 🐛 4 | 🌐 Python | 📅 2021-04-27
* [Arina-OSINT](https://github.com/AlexC-ux/Arina-OSINT) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-11
* [Castrick](https://castrickclues.com/)

## [↑](#-table-of-contents) Phone number

Sometimes situations happen that require analysing an employee's phone number to get more information.

* [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga) ⭐ 17,464 | 🐛 117 | 🌐 Go | 📅 2026-01-06 + [Web Demo](https://demo.phoneinfoga.crvx.fr/)
* [GhostTrack](https://github.com/HunxByts/GhostTrack) ⭐ 14,783 | 🐛 111 | 🌐 Python | 📅 2024-01-11
* [BuscaPaginasBlancas](https://github.com/GeiserX/BuscaPaginasBlancas) ⚠️ Archived - Python tool for automated lookups on Spanish white pages (PaginasBlancas.es) to find phone numbers and addresses
* [Osint.industries](https://osint.industries/)
* [Emobiletracker](https://www.emobiletracker.com/)
* [Castrick](https://castrickclues.com/)
* [Predicta Search](https://www.predictasearch.com/)

## [↑](#-table-of-contents) Wifi

* [3Wifi](https://3wifi.stascorp.com/) - free base of access points

## [↑](#-table-of-contents) Cloud

Tools for searching, gathering information from cloud.

* [Cloud\_sherlock](https://github.com/Group-IB/cloud_sherlock) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2023-05-18

## [↑](#-table-of-contents) Information gathering tools

* [Th3inspector](https://github.com/Moham3dRiahi/Th3inspector) ⭐ 2,651 | 🐛 13 | 🌐 Perl | 📅 2025-04-21
* [Gasmask](https://github.com/twelvesec/gasmask) ⭐ 1,455 | 🐛 6 | 🌐 Python | 📅 2021-06-11
* [Cylect.io](https://cylect.io/)

## [↑](-table-of-contents) Useful links

Links to guide, methodologies and any information that would be useful.

* [Cloud OSINT](https://github.com/7WaySecurity/cloud_osint) ⭐ 135 | 🐛 0 | 📅 2026-04-08 - Repository with information related to Cloud Osint
* [WhereToGo](https://github.com/valeriyshevchenko90/WhereToGo) ⭐ 127 | 🐛 0 | 📅 2022-07-07 - list of popular services that might be used in organizations. By having an account of the user - you can try to find entry points to the organization data. #semiosint
* [Information Disclosure Write-Ups And PoCs](https://github.com/soxoj/information-disclosure-writeups-and-pocs) ⭐ 31 | 🐛 0 | 🌐 PHP | 📅 2025-03-13

## Todo

* Add mobile number analysis tools (put into a category)
* Make a mindmap

## Warning

Some of the sites included might require registration or offer more data for $$$, but you should be able to get at least a portion of the available information for no cost.

***

*Inspired by <https://github.com/jivoi/awesome-osint> ⭐ 28,045 | 🐛 8 | 📅 2026-08-03*

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
