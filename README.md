# AmmoBin.ca [ ![Codeship Status for ammobinDOTca/ammobin-client](https://app.codeship.com/projects/992b88f0-d18a-0135-270c-42cf0d64356b/status?branch=master)](https://app.codeship.com/projects/262429) [![Greenkeeper badge](https://badges.greenkeeper.io/ammobinDOTca/ammobin-client.svg)](https://greenkeeper.io/)

meta search site for ammo prices across canada. built with [nuxt.js](https://nuxtjs.org) (and thus vue.js).

![Screenshot-2017-9-27 The place to view the best online ammo prices across Canada.png](https://raw.githubusercontent.com/ammobinDOTca/ammobin-client/master/Screenshot-2017-9-27%20The%20place%20to%20view%20the%20best%20online%20ammo%20prices%20across%20Canada%20.png)

## how to run
1. ```docker run ammobindotca/ammo-bin-client -p 3000:3000```

## how to run locally
- ```npm i```
- ```PROD=true npm run dev``` (will target prod api)

## todo
- https://github.com/WICG/BackgroundSync/blob/master/explainer.md

## contributing
- do some work
- submit pr

## vendors to add
- https://shophighfalls.com/collections/rifle-ammo?view=ALL (css rules hinder pulling data. will need to update scraper)
- http://shop.sylvestresportinggoods.com/Rifle-Ammunition/?p=catalog&mode=catalog&parent=506&pg=1&CatalogSetSortBy=price
- https://www.tesro.ca/ammunition-and-pellets/smallbore-ammunition.html?limit=36
- http://www.grouseriver.com/Hunting-Shooting/Ammunition
- https://blue-wolf-firearms-canada.myshopify.com/collections/rimfire
- https://www.londerosports.com/firearms/ammunitions/rifle?limit=all
- https://gunworx.ca/collections/ammunition
- https://www.latulippe.com/en/our-stores/
- http://doctordeals.ca/product-category/smoking-gun/ammunition/rifle-ammo/
- https://waspmunitions.ca/WASP-REMANUFACTURED-AMMUNITION-c14772333
- https://rampartcorp.com/collections/ammunition
- http://store.easthilloutdoors.com/ammo/bulk-ammo

## blocked
- http://www.danchasse.com/shop_free/index.php?categoryID=109 (je ne parle en francis)
- http://www.westcoasthunting.ca/ (prices + counts hidden on item page. would need to scrape everypage)
- http://westrifle.com/wrstore/index.php?main_page=index&cPath=2 (everything was sold out nov 2017)
- https://www.siwashsports.ca/product-category/ammunition/centerfire-ammunition/ (cant buy things online as of dec 17 2017, will add once this feature is enabled on the site)
- https://eccfirearms.blogspot.ca/2011/02/ammunition-ecc-firearms-has-widest.html  (cant buy oneline as of feb 17 2018)
- gotenda (implemented bot detection on their site)

## skipped
- wholesalesports.com
- marstar.ca
- http://www.prairieshotammo.com/find-a-dealer-3.html (but should review these retailers to see if they have online shops)
## incomplete vendors
- none

## docker hub
https://hub.docker.com/r/ammobindotca/ammobin-client/
