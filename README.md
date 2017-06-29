# KLB Property Services

## Hosting on Github

See [Github](https://pages.github.com/).


## Getting the domain name

Add a `CNAME` to the root of the folder containing the custom domain name.

Manage the DNS via [GoDaddy](https://dcc.godaddy.com) DNS Management. See up `A` names for `192.30.252.153` and `192.30.252.154`.

Turn this:

![](dns_before.png)


Into this:

![](dns_after.png)


See [Github](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)

## Source

The site is based on [Design Studio 1-Page Template](https://github.com/website-templates/design-studio_one-page-template.git) which was forked and pushed to the `template` branch.

Basic development lifecycle is to checkout the branch into one folder and develop using `gulp` etc. Then once build (`gulp rebuild`), copy the artifacts in the `build` folder to another checkout version of `master`. 

Never attempt to merge the two branches!