---
title: Template
draft: false
tags:
---
Up lên domain mới .. kkk
### Custom Domain[](https://quartz.jzhao.xyz/hosting#custom-domain)

Here’s how to add a custom domain to your GitHub pages deployment.

1. Head to the “Settings” tab of your forked repository.
2. In the “Code and automation” section of the sidebar, click “Pages”.
3. Under “Custom Domain”, type your custom domain and click “Save”.
4. This next step depends on whether you are using an apex domain (`example.com`) or a subdomain (`subdomain.example.com`).
    - If you are using an apex domain, navigate to your DNS provider and create an `A` record that points your apex domain to GitHub’s name servers which have the following IP addresses:
        - `185.199.108.153`
        - `185.199.109.153`
        - `185.199.110.153`
        - `185.199.111.153`
    - If you are using a subdomain, navigate to your DNS provider and create a `CNAME` record that points your subdomain to the default domain for your site. For example, if you want to use the subdomain `quartz.example.com` for your user site, create a `CNAME` record that points `quartz.example.com` to `<github-username>.github.io`.