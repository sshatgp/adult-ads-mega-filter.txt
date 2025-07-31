# adult-ads-mega-filter.txt
مرحبًا! هذه قائمة مخصصة لحظر الإعلانات والمحتوى المزعج في متصفح Soul Browser باستخدام تنسيق EasyList.
! ==========================
! Mega Adult Adblock Filter – Comprehensive
! Includes: AdSpyglass, Adult Ads, Popups, Video Ads, Tracking
! ==========================

! ---- AdSpyglass Blocking ----
||adspyglass.com^$all
||*.adspyglass.com^$all
||adspyglass[0-9]*.com^$all
||*.adspyg.com^$all
||*.adspygif.com^$all
||*.adspystatic.com^$all
||*.adspycdn.com^$all
##div:has-text(/^ADS? BY ADSPYGLASS$/i)
##div:has-text(/^Advertisement$/i)
##div:has-text(/^Advertising$/i)
##span:has-text(/^Advertisement$/i)
##span:has-text(/^Advertising$/i)
##p:has-text(/^Advertisement$/i)
##p:has-text(/^Advertising$/i)
||*.adspygif.com^$image
||*.videoads.com^$media
||*.vast*.com^$media
||*.ads*.mp4$media
||*.preroll*.mp4$media
||adspyglass.com^$popup
||*.adspyglass.com^$popup
##iframe[src*="adspyglass"]
##iframe[src*="videoads"]
##div[class*="sponsor"]
##section[class*="sponsor"]
##aside[class*="sponsor"]

! ---- Major Adult Ad Networks ----
||juicyads.com^$all
||*.juicyads.com^$all
||exoclick.com^$all
||*.exoclick.com^$all
||trafficstars.com^$all
||*.trafficstars.com^$all
||trafficfactory.biz^$all
||*.trafficfactory.biz^$all
||doublepimp.com^$all
||*.doublepimp.com^$all
||plugrush.com^$all
||*.plugrush.com^$all
||camsoda.com^$all
||*.camsoda.com^$all
||xlovecam.com^$all
||*.xlovecam.com^$all
||bongacams.com^$all
||*.bongacams.com^$all
||stripchat.com^$all
||*.stripchat.com^$all
||livejasmin.com^$all
||*.livejasmin.com^$all
||adultadworld.com^$all
||*.adultadworld.com^$all
||adxpansion.com^$all
||*.adxpansion.com^$all
||popads.net^$all
||*.popads.net^$all
||popcash.net^$all
||*.popcash.net^$all
||clickadu.com^$all
||*.clickadu.com^$all
||ero-advertising.com^$all
||*.ero-advertising.com^$all
||adnium.com^$all
||*.adnium.com^$all
||adskeeper.com^$all
||*.adskeeper.com^$all
||adshost2.com^$all
||*.adshost2.com^$all
||trafficjunky.net^$all
||*.trafficjunky.net^$all
||ads.brazzers.com^$all
||ads.metart.com^$all
||ads.youporn.com^$all
||ads.redtube.com^$all
||ads.pornhub.com^$all
||ads.playboy.com^$all
||ads.xhamster.com^$all
||ads.xtube.com^$all
||ads.manyvids.com^$all
||ads.onlyfans.com^$all
||ads.myfreecams.com^$all
||ads.cam4.com^$all
||ads.chaturbate.com^$all
||ads.camster.com^$all
||ads.fap.com^$all
||ads.erome.com^$all
||ads.amateur.tv^$all
||ads.slutload.com^$all
||ads.tube8.com^$all
||ads.xvideos.com^$all
||ads.hclips.com^$all
||ads.spankbang.com^$all
||ads.fux.com^$all
||ads.voyeurhit.com^$all
||ads.femjoy.com^$all
||ads.metcams.com^$all
||ads.modelhub.com^$all
||ads.erotube.com^$all
||ads.tnaflix.com^$all
||ads.yourlust.com^$all
||ads.nudevista.com^$all
||ads.fuq.com^$all
||ads.povd.com^$all
||ads.smutty.com^$all
||ads.fuqer.com^$all
||ads.redxxx.com^$all
||ads.xtapes.to^$all
||ads.sunporno.com^$all
||ads.pornburst.xxx^$all
||ads.filmyporn.xxx^$all
||ads.pornyeah.com^$all
||ads.pornid.xxx^$all
||ads.fapster.xxx^$all
||ads.playvids.com^$all
||ads.eroticbeauties.net^$all
||ads.eroticbeauties.xyz^$all
||ads.eroticmedia.xxx^$all
||ads.pornhits.com^$all
||ads.sexvid.xxx^$all
||ads.slut.io^$all
||ads.18plus.xxx^$all
||ads.adultvideos.com^$all
||ads.nastyvideotube.com^$all
||ads.luscious.net^$all
||ads.fucktube.com^$all
||ads.bigtits.com^$all
||ads.amateurcool.com^$all
||ads.freesexy.com^$all
||ads.xnxx.com^$all

! ---- Popup Blocking ----
||*.popupad.*^$popup
||*.popunder.*^$popup
||*.popads.*^$popup
||*.clickadu.*^$popup
||*.trafficjunky.*^$popup
||*.popcash.*^$popup
||*.adstune.*^$popup
||*.fastclick.*^$popup
||*.interstitial.*^$popup
||*.redirectvoluum.*^$popup
||*.lpcloudsvr.*^$popup
||*.go2cloud.org^$popup

! ---- Video Ads (Pre/Mid/Post-roll) ----
||*.preroll.*$media
||*.videoads.*$media
||*.vast.*$media
||*.adsrvmedia.*$media
||*.adsvideo.*$media
||*.advideo.*$media
||*.ads*.mp4$media
||*.midroll.*$media
||*.postroll.*$media
||*.ads-*.mp4$media
||*.commercials*.mp4$media

! ---- Hide Ad Containers ----
##div[class*="ad-container"]
##div[class*="ads-container"]
##div[id*="ad-container"]
##div[id*="ads-container"]
##div[class*="sponsor"]
##div[id*="sponsor"]
##section[class*="sponsor"]
##aside[class*="sponsor"]
##div[class*="ad-banner"]
##div[class*="banner-ad"]
##div[class*="top-ad"]
##div[class*="bottom-ad"]
##iframe[src*="ads"]
##iframe[src*="adserver"]
##iframe[src*="juicyads"]
##iframe[src*="exoclick"]
##iframe[src*="trafficstars"]
##iframe[src*="plugrush"]
##iframe[src*="livejasmin"]
##iframe[src*="stripchat"]
##iframe[src*="bongacams"]
##iframe[src*="camsoda"]
##iframe[src*="xlovecam"]

! ---- Remove Text Ads ----
##div:has-text(/^Advertisement$/i)
##div:has-text(/^Advertising$/i)
##div:has-text(/^Sponsored$/i)
##span:has-text(/^Advertisement$/i)
##span:has-text(/^Advertising$/i)
##span:has-text(/^Sponsored$/i)
##p:has-text(/^Advertisement$/i)
##p:has-text(/^Advertising$/i)
##p:has-text(/^Sponsored$/i)

! ---- Block Tracking & Ad Scripts ----
||*.ads.js^$script
||*.admanager.js^$script
||*.bannerads.js^$script
||*.prerollads.js^$script
||*.videoads.js^$script
||*.sponsorads.js^$script
||*.trackads.js^$script
||*.clicktrack.js^$script
||*.impression-track.js^$script
