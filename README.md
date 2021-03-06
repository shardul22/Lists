# The Block List Project
[![GitHub issues](https://img.shields.io/github/issues/blocklistproject/lists)](https://github.com/blocklistproject/Lists/issues)
[![GitHub closed issues](https://badgen.net/github/closed-issues/blocklistproject/Lists?color=green)](https://github.com/blocklistproject/Lists/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub contributors](https://img.shields.io/github/contributors/blocklistproject/lists)](https://github.com/blocklistproject/Lists/graphs/contributors)
![GitHub repo size](https://img.shields.io/github/repo-size/blocklistproject/lists)
![GitHub](https://img.shields.io/github/license/blocklistproject/lists?color=blue)
![GitHub Maintained](https://img.shields.io/badge/Open%20Source-Yes-green)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/blocklistproject/lists)
![GitHub last commit](https://img.shields.io/github/last-commit/blocklistproject/lists)
![GitHub Maintained](https://img.shields.io/badge/maintained-yes-green)
[![Website](https://img.shields.io/website?down_color=red&down_message=Down&up_color=green&up_message=Online&url=https%3A%2F%2Fblocklist.site)](https://blocklist.site)
[![ko-fi](https://badgen.net/badge/Support%20Us/Ko-Fi?color=orange)](https://ko-fi.com/P5P521OPP)
[![patreon](https://badgen.net/badge/Support%20Us/Patreon?color=red)](https://www.patreon.com/bePatron?u=8892646)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fblocklistproject%2FLists&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Traffic+%28Daily%2FTotal%29&edge_flat=false)

&nbsp;



Please see below our crypto addresses:

| Algorand | Basic Attention Token | ZCash |
| :-------------: | :-------------: | :-------------: |
| <img src="https://blocklistproject.github.io/Lists/img/algo-qr-code.png" width="125"> | <img src="https://blocklistproject.github.io/Lists/img/btc-qr-code.png" width="125"> | <img src="https://blocklistproject.github.io/Lists/img/zcash-qr-code.png" width="125"> |



[Become a Patron](https://www.patreon.com/bePatron?u=8892646)

&nbsp;

# Update:
Special and HUGE thank you to [@fishcharlie](https://github.com/fishcharlie) for his automation contribution to the project. With his contribution it is no longer required to edit the alt-version or dnsmasq versions of the lists when doing pull requests. This is now done automatically on commit. Thank you to all those that help this project to continue moving forward.

&nbsp;

- [Details](#details)
- [Updates](#updates)
- [Versions](#versions)
- [Usage](#usage)
- [Lists](#lists)
- [Using with Pi-hole](#using-with-pi-hole)
- [Using with other tools](#using-with-other-tools)
- [Sponsors](#sponsors)
- [License](#license)

&nbsp;

# Details:

These lists were created because the founder of the project wanted something with a little more control over what is being blocked. Many lists are all or nothing. We set out to create lists with more control over what is being blocked.



&nbsp;

## Versions:

We have recently created an alternative versions of our lists.

### Original Version:

<Original>&nbsp;All urls in the version of the list are listed in the host file as follows</Original>

<p>  &nbsp;&nbsp;0.0.0.0 example.com</p>

&nbsp;

### No Leading 0s Version:

<p>&nbsp;All urls in this version of the list are listed in the host file as follows</p>

<p>  &nbsp;&nbsp;example.com</p>

Our users brought it to our attention that some devices error out if the url is preceded by an IP address.

&nbsp;

### Beta dnsmasq Version:

<p>&nbsp;All urls in this version of the list are listed in the host file as follows</p>

<p>  &nbsp;&nbsp;server=/example.com/</p>

It was requested to add support for dnsmasq. We are currently testing 1 of our lists before creating a full set of lists. Please provide feedback.

&nbsp;


# Usage:

These converted files can be used with various DNS and domain-blocking tools:

## Using with [Pi-hole](https://pi-hole.net/):

1. Copy the link to the Pi-hole format for the desired list (from the appropriate table below).
2. Add the URL to your Pi-hole's block lists (**Login** > **Group Management** > **Adlists** > **Paste list URL in "Address" field, add comment** > **Click "Add"**)
3. Update Gravity (**Tools** > **Update Gravity** > **Click "Update"** )

&nbsp;
<sup>Instructions current as of Pi-hole 5.2.4</sup>
&nbsp;

# Lists:

## Main Lists

| List | Original | No IP | dnsmasq | Description | Sponsor<sup>&#8224;</sup> |
| -- | -- | -- | -- | -- | -- |
| Abuse | [Link](https://blocklistproject.github.io/Lists/abuse.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/abuse-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/abuse-dnsmasq.txt) | Lists of sites created to deceive |[magicminiman.com](https://magicminiman.com)|
| Ads | [Link](https://blocklistproject.github.io/Lists/ads.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/ads-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/ads-dnsmasq.txt) | Ad servers / sites |  |
| Crypto | [Link](https://blocklistproject.github.io/Lists/crypto.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/crypto-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/crypto-dnsmasq.txt) | Crypto / cryptojacking based sites <br> <sup>Can break normal "good" crypto sites</sup> |  |
| Drugs | [Link](https://blocklistproject.github.io/Lists/drugs.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/drugs-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/drugs-dnsmasq.txt) | RE sites that deal with illegal drugs <br><sub>Including RX drugs illegal to posses in the US</sub> |  |
| Everything | [Link](https://blocklistproject.github.io/Lists/everything.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/everything-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/everything-dnsmasq.txt) | List including all non beta list domains |  |
| Facebook | [Link](https://blocklistproject.github.io/Lists/facebook.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/facebook-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/facebook-dnsmasq.txt) | Block FB and FB related / owned services |  |
| Fraud | [Link](https://blocklistproject.github.io/Lists/fraud.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/fraud-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/fraud-dnsmasq.txt) | Sites create to fraud |  |
| Gambling | [Link](https://blocklistproject.github.io/Lists/gambling.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/gambling-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/gambling-dnsmasq.txt) | All gambling based site legit and illegal |  |
| Malware | [Link](https://blocklistproject.github.io/Lists/malware.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/malware-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/malware-dnsmasq.txt) | Known sites that host malware |  |
| Phishing | [Link](https://blocklistproject.github.io/Lists/phishing.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/phishing-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/phishing-dnsmasq.txt) | Sites created to phish info |  |
| Piracy | [Link](https://blocklistproject.github.io/Lists/piracy.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/piracy-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/piracy-dnsmasq.txt) | Knows sites that allow for illegal downloads |  |
| Porn | [Link](https://blocklistproject.github.io/Lists/porn.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/porn-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/porn-dnsmasq.txt) | Porn or sites that promote porn | [W1T3H4T](https://www.patreon.com/user/creators?u=26512074) |
| Ransomware | [Link](https://blocklistproject.github.io/Lists/ransomware.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/ransomware-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/ransomware-dnsmasq.txt) | Known sites that host or contain ransomware |  |
| Redirect | [Link](https://blocklistproject.github.io/Lists/redirect.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/redirect-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/redirect-dnsmasq.txt) | Sites that redirect your from your intended site |  |
| Scam | [Link](https://blocklistproject.github.io/Lists/scam.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/scam-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/scam-dnsmasq.txt) | Sites that intend to scam |  |
| TikTok | [Link](https://blocklistproject.github.io/Lists/tiktok.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/tiktok-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/tiktok-dnsmasq.txt) | Copy and pasted into your device |  |
| Torrent | [Link](https://blocklistproject.github.io/Lists/torrent.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/torrent-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/torrent-dnsmasq.txt) | Torrent directory <br> <sub>Will likely block legit torrent sites used for legal software download</sub> |  |
| Tracking | [Link](https://blocklistproject.github.io/Lists/tracking.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/tracking-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/tracking-dnsmasq.txt) | Sites dedicated to tracking and gathering visitor info |  |

&nbsp;

## Beta Lists

| List | Original | No IP | dnsmasq | Description | Sponsor<sup>&#8224;</sup> |
|--|--|--| -- | -- | -- |
| Smart TV | [Link](https://blocklistproject.github.io/Lists/smart-tv.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/smart-tv-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/smart-tv-dnsmasq.txt) | Smart TV call home and ads |  |
| Basic Start List | [Link](https://blocklistproject.github.io/Lists/basic.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/basic-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/basic-dnsmasq.txt) | Just a quick basic starter list |  |
| WhatsApp List | [Link](https://blocklistproject.github.io/Lists/whatsapp.txt) | [Link](https://blocklistproject.github.io/Lists/alt-version/whatsapp-nl.txt) | [Link](https://blocklistproject.github.io/Lists/dnsmasq-version/whatsapp-dnsmasq.txt) | User requested list that blocks only WhatsApp |  |

&nbsp;

## Deprecated Lists

| List | Description | Deletion date (dd.mm.yyyy) |
|--|--| -- |
| YouTube | This lists was removed due to the way YouTube serves its ads | 01.10.2021 |


<sup>*Not supported by or affiliated with Pi-hole.</sup>

&nbsp;

<sup>&#8224; A sponsor is someone that supports us on Patreon. All list are free and will always be free. This is just a way to say thank you to those that help keep this project going! </sup>

## Using with other tools:

We are currently working on verifying compatibility with other tools. Please stand by. If you have a suggestion on a tool we should support please comment on our [Reddit](https://www.reddit.com/r/blocklistproject/) page.

## Sponsors:

Special thank you to [Cloud 4 SURE](https://www.cloud4sure.net) for their generous donation every month to help cover our Linode bill.

# License:

For more details, see the [LICENSE](https://github.com/blocklistproject/Lists/blob/master/LICENSE) file.

&nbsp;

<sup>These files are provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, arising from, out of or in connection with the files or the use of the files.</sup>

<sub>Any and all trademarks are the property of their respective owners.</sub>
