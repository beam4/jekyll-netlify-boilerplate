Views
======

## How to set up Domain Name

### On domain name resolve

#### Explain on domain name

I got the website, in https://newvisionchurchnp.netlify.app, by following tutorial on https://buildchurchsite.netlify.app, with static webpage aproach for free. Then I need a domain name for easy to remember,also easy to spread, I want a domain name https://newvisionnp.org instead. My coworker bought a domain name newvisionnp.org for NRs.1199 first year and NRs. 1650 next year to follow from Nest Nepal,you can search google to find it. The domain name suppose to be as short as possible,permanent use, not changed after set if possible.

Before set up, let me say my impression on Nest Nepal's technical support, they call it a 'ticket' to send a technical question. The answer is not clear, even it is DNS configration, which suppose to be simple, it is impossible to solve your problem, their intention seems to make you buying more of other produtions, so caution, my advice is not buying from this company.

DNS configuration is to set up in Cloudflare.com, need to set CNAME,A and Nameserver; in netlify.com,need to set primary domain, primary domain means if you visit https://newvisionnp.org it will automatically visit http://www.newvisionnp.org instead; tls automatically set up, means https automatic add to any web address with http.

#### 1. Log in on cloudflare.com

According cloudflare docs, https://developers.cloudflare.com/fundamentals/get-started/setup/add-site/

Then sign up and log in cloudflare.com, on dashboard page of cloudflare.com, click 'add site', add your newly bought domain name, next to 'Search' button, click 'Add record', then add record form appeared, first set CNAME to www point to newvisionchurchnp.netlify.app; second set A to @ point to 75.2.60.5 complete.

There is a remind of 'nameserver' settings, you need to replace in Nest My Domain name server setting form follow the guide. 

#### 2. Config on netlify

Its purpose is to add custome domain name, set primary domain, 'netlify DNS' double greened on both DNS records, https automatically set.

Follow the netlify docs https://docs.netlify.com/domains-https/custom-domains/configure-external-dns/

Detail: Site settings >> Domain management, click 'Add custome domain' then set primary domain, set www.newvisionnp.org as primary domain, then check https automatically set. 

#### 3. Summary

The DNS configuration suppose to be very simple, it let the user config by themselves, so it must be very simple.
