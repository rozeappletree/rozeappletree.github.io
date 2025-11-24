---
layout: post
title:  "How To Connect GitHub Pages & Custom Domain"
date:   2025-11-25 10:00:00 +0800
categories:
- How To
tags: [dev]
---

## How To Connect GitHub Pages & Custom Domain

Add `A record` with `@` host in DNS records. And `CNAME record` with `www` host with 60mins.

```
A  @  185.199.108.153  AUTO TTL
A  @  185.199.109.153  AUTO TTL
A  @  185.199.110.153  AUTO TTL
A  @  185.199.111.153  AUTO TTL
CNAME Record  www  rozeappletree.github.io  60mins TTL
```
And then just paste the domain without `www` in "settings" > "pages" > "custom domains". eg. `aixp.com`

references: 

- [x] https://www.youtube.com/watch?v=2K7asqt8wMw
- [x] https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain
- [x] use different repo (https://github.com/rozeappletree/seemyaixp) for subdomain. https://thomasgauvin.com/writing/setting-up-a-subdomain-github-pages-namecheap/
- [ ] https://www.namecheap.com/support/knowledgebase/article.aspx/9678/2237/how-to-redirect-subdomain-to-a-certain-ip-address-along-with-a-port/
