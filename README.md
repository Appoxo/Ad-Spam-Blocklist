# Information about the Repo

This repository serves as a collection for various services I use, will use or have used.  
A service is eligible to be added if it can block something and improves the privacy/usability/security.

## Services that are supported

The services are located in each sub-directory. If neccessary a README.md will be provided with guidance on formatting.  

> [!IMPORTANT]
> Deprecation notice regarding the pihole list `hosts.txt`  
> This list will no longer be updated. Any additional work will be carried over to the new `blocklist.txt` file which pihole only partially supports.  
> Thus I created a new list to not break the support \:\)  
> *Any advice regarding this change is welcome*

|Service|Maintained|Style-Compatibility/<br>Compliance|
|:-|:-|:-|
|Technitium|✅|ABP|
|OPNsense|✅|IP hosts/subnets|
|pihole|❌|hosts-file|
|uBlock-Origin|✅|uBlock Origin compliant|

### Additional service information

#### Technitium

Services that want my (our) data.  
I don't want to share my data unknowlingly <sup>(exceptions apply™)</sup>

#### OPNsense

IPs/endpoints that have performed portscanning or other malicious looking activities on my WAN interface.  
If I find out a service has additional endpoints, I will perform ASN blocking as well.

#### PiHole

Same as Technitium.

#### uBlock Origin

The list contains entries for ad-elements or annoying stuff I have disliked.  
Examples:

- In-feed promotions that mimic posts on reddit
- badges on youtube that indicate if the video was/is featured content or auto-dubbed

## How to contribute

Create a PR with the changes to any list currently present \:\)

### Entries to be added/removed

Open a PR, depending on the entry I will merge it.  
Should I deny the PR, I suggest creating a fork instead and (optionally) follow any upstream changes (should you like to).

### Services to be added

Open a PR with the service you want to add (e.g. Blocklist for technitium).  
Depending on the case, I'll add it.

## FAQ ⁉️

❓: I was added to a block-list, how can I be removed?  
❗: Open a PR and provide a reason why you think the URL/IP/whatever was blocked unfairly/unjustified. Depending on your reasoning I'll consider it.  

❓: Can you add another service?  
❗: Most likely not. Unless I also use it.  
❗: In case I don't use it but see the benefit to it, I may still add it if you do the maintenance.  

❓: A?  
❗: B!  
