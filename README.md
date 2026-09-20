# Information about the Repo

This repository serves as a collection for various services I may use or have used.  
A service is eligible to be added if it can block something and improves the privacy/usability/security.

## Services that are supported

> [!IMPORTANT]
> Deprecation notice regarding the pihole list `hosts.txt`  
> This list will no longer be updated. Any additional work will be carried over to the new `blocklist.txt` file which pihole only partially supports.  
> Thus I created a new list to not break the support \:\)  
> *Any advice regarding this change is welcome*

  
|Filename|Maintained|Purpose/service|What's on it|
|:-|:-|:-|:-|
|`blocklist.txt`|✅|Technitium/ABP|AdBlockPlus-compliant list that is compatible with technitium|
|`eternalIPBlocklist.txt`|✅|OPNsense IP blocklist|IPs/endpoints that performed portscanning or other malicious looking activities on my WAN interface|  
|`hosts.txt`|❌|pihole blocklist|Usually annoying ads or things I (personally) don't trust like novel TLDs (e.g. `.zip`) that could be used maliciously|
|`uBlock-Blocker.txt`|✅|uBlock Origin list|Annoying cookie banners or ads that prevent me from using the site|

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
