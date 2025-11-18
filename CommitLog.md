# AdGuardHome_Filters Commit Log

All commits to this repository will be logged in this file.

## Commit: [9aa7bf9](https://github.com/virtualitypage/AdGuardHome_Filters/commit/9aa7bf9b2da9dc01bce84a98307fdf9c845395b9) - 2025-11-14

### Date

- 2025/11/14 22:52:21

### Change

- accept/Accept_PBAds.txt
    ```yaml
    BEFORE:
      # References: querylog
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/accept/Accept_PBAds.txt
      #
    - # Last modified: 31 August 2025
      #

      # [AppLovin]
      # https://www.applovin.com/ja/
      @@||a.applovin.com^$client=192.168.8.159
      @@||a4.applovin.com.lan^$client=192.168.8.235
      @@||a4.applovin.com^$client=192.168.8.159
      @@||akamai-res1.applovin.com^$client=192.168.8.219

      @@ -44,6 +45,7 @@

      @@||ms.applovin.com^$client=192.168.8.235
      @@||ms4.applovin.com.lan^$client=192.168.8.117
      @@||ms4.applovin.com.lan^$client=192.168.8.219
      @@||ms4.applovin.com^$client=192.168.8.117
      @@||ms4.applovin.com^$client=192.168.8.159
      @@||ms4.applovin.com^$client=192.168.8.219

      @@ -168,10 +170,8 @@

      @@||notifications-gke-sdk-bidding-b.fyber.com^$client=192.168.8.235
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.117
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.159
    - @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.159
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.219
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.235
    - @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.235
      @@||notifications-gke-sdk-bidding.fyber.com^$client=192.168.8.159
      @@||notifications-gke-sdk-bidding.fyber.com^$client=192.168.8.235
      @@||sdk-events.inner-active.mobi.lan^$client=192.168.8.117

      @@ -190,6 +190,7 @@

      @@||vast-events.inner-active.mobi.lan^$client=192.168.8.159
      @@||vast-events.inner-active.mobi.lan^$client=192.168.8.219
      @@||vast-events.inner-active.mobi.lan^$client=192.168.8.235
      @@||vast-events.inner-active.mobi^$client=192.168.8.174
      @@||vast-events.inner-active.mobi^$client=192.168.8.219
      @@||waterfall.inner-active.mobi^$client=192.168.8.117

      @@ -318,10 +319,12 @@

      @@||s.iff.inmobi.com^$client=192.168.8.235
      @@||supply.inmobicdn.net.lan^$client=192.168.8.219
      @@||supply.inmobicdn.net.lan^$client=192.168.8.235
      @@||supply.inmobicdn.net^$client=192.168.8.117
      @@||supply.inmobicdn.net^$client=192.168.8.159
      @@||supply.inmobicdn.net^$client=192.168.8.219
      @@||supply.inmobicdn.net^$client=192.168.8.235
      @@||sync.inmobi.com^$client=192.168.8.117
      @@||sync.inmobi.com^$client=192.168.8.159
      @@||sync.inmobi.com^$client=192.168.8.204
    ```

    ```yaml
    AFTER:
      # References: querylog
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/accept/Accept_PBAds.txt
      #
    + # Last modified: 14 November 2025
      #

      # [AppLovin]
      # https://www.applovin.com/ja/
      @@||a.applovin.com^$client=192.168.8.159
    + @@||a.applvn.com^$client=192.168.8.159
      @@||a4.applovin.com.lan^$client=192.168.8.235
      @@||a4.applovin.com^$client=192.168.8.159
      @@||akamai-res1.applovin.com^$client=192.168.8.219

      @@ -44,6 +45,7 @@

      @@||ms.applovin.com^$client=192.168.8.235
      @@||ms4.applovin.com.lan^$client=192.168.8.117
      @@||ms4.applovin.com.lan^$client=192.168.8.219
    + @@||ms4.applovin.com.ts.net^$client=192.168.8.219
      @@||ms4.applovin.com^$client=192.168.8.117
      @@||ms4.applovin.com^$client=192.168.8.159
      @@||ms4.applovin.com^$client=192.168.8.219

      @@ -168,10 +170,8 @@

      @@||notifications-gke-sdk-bidding-b.fyber.com^$client=192.168.8.235
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.117
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.159
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.219
      @@||notifications-gke-sdk-bidding-canary.fyber.com^$client=192.168.8.235
      @@||notifications-gke-sdk-bidding.fyber.com^$client=192.168.8.159
      @@||notifications-gke-sdk-bidding.fyber.com^$client=192.168.8.235
      @@||sdk-events.inner-active.mobi.lan^$client=192.168.8.117

      @@ -190,6 +190,7 @@

      @@||vast-events.inner-active.mobi.lan^$client=192.168.8.159
      @@||vast-events.inner-active.mobi.lan^$client=192.168.8.219
      @@||vast-events.inner-active.mobi.lan^$client=192.168.8.235
    + @@||vast-events.inner-active.mobi.ts.net^$client=192.168.8.219
      @@||vast-events.inner-active.mobi^$client=192.168.8.174
      @@||vast-events.inner-active.mobi^$client=192.168.8.219
      @@||waterfall.inner-active.mobi^$client=192.168.8.117

      @@ -318,10 +319,12 @@

      @@||s.iff.inmobi.com^$client=192.168.8.235
      @@||supply.inmobicdn.net.lan^$client=192.168.8.219
      @@||supply.inmobicdn.net.lan^$client=192.168.8.235
    + @@||supply.inmobicdn.net.ts.net^$client=192.168.8.235
      @@||supply.inmobicdn.net^$client=192.168.8.117
      @@||supply.inmobicdn.net^$client=192.168.8.159
      @@||supply.inmobicdn.net^$client=192.168.8.219
      @@||supply.inmobicdn.net^$client=192.168.8.235
    + @@||sync.inmobi.com.lan^$client=192.168.8.235
      @@||sync.inmobi.com^$client=192.168.8.117
      @@||sync.inmobi.com^$client=192.168.8.159
      @@||sync.inmobi.com^$client=192.168.8.204
    ```

- accept/Accept_domain.txt
    ```yaml
    BEFORE:
      # References: none
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/accept/Accept_domain.txt
      #
    - # Last modified: 31 August 2025
      #

      # [許可リクエスト]
    - @@/e[5-9].o.lencr.org/
    - @@/i[1-9].ytimg.com/
    - @@/media[0-9].giphy.com/
    - @@/r1[0-4].i.lencr.org/
    - @@/r1[0-4].o.lencr.org/
      @@||*.blob.core.windows.net
      @@||*.cloudfront.net
      @@||*.cloudfront.net.lan
      @@||*.user.webaccel.jp
      @@||268gr.com
      @@||a.flux.jp
      @@||a.pixiv.org
      @@||a3.shared.global.fastly.net
      @@||aa-metrics.beauty.hotpepper.jp
      @@||aapi.buzzsight.co
      @@||abema.go.link
      @@||abs-0.twimg.com
      @@||abs-zero.twimg.com
      @@||abs.twimg.com

      @@ -40,40 +50,65 @@

      @@||accounts.youtube.com
      @@||accuweather.com
      @@||acestudio.ai
      @@||aclog.itmedia.co.jp
      @@||acps-api.mixerbox.com
      @@||acps-api.mixerbox.com.cdn.cloudflare.net
      @@||ad-segments-proxy.streaks.jp
      @@||adm-srch.newsapp.nhk.or.jp
      @@||airplane.kairogame.jp
      @@||ajax.cloudflare.com
    - @@||alt6-mtalk.google.com.lan
      @@||amzn.to
      @@||analytics.ff.avast.com
      @@||analytics.yay.space
      @@||analytics.yay.space.lan
      @@||anshin.demdex.net
      @@||api-d.dropbox.com
      @@||api-stream.twitter.com.lan
      @@||api.amazon.co.jp
      @@||api.bing.com
      @@||api.cloud.huawei.com
      @@||api.cloud.huawei.com.lan
      @@||api.dollphoin.site
      @@||api.dropbox.com
      @@||api.dropboxapi.com
      @@||api.flightproxy.teams.trafficmanager.net
      @@||api.github.com
      @@||api.goodnovel.com
      @@||api.inmense.site
      @@||api.joyreadings.com
      @@||api.kickoffo.site
      @@||api.mapbox.com
      @@||api.plugin.myideal.jp
      @@||api.rudderstack.com
      @@||api.smartwaon.com
      @@||api.twicomi.com
      @@||api.twitter.com
      @@||api.unnerv.app
      @@||api.vday.io
      @@||api.webpush.jp

      @@ -81,12 +116,15 @@

      @@||api.yay.space
      @@||api.yay.space.lan
      @@||app-api.pixiv.net
      @@||app.bspace.jp
      @@||app.paypay.ne.jp
      @@||app.plugin.myideal.jp
      @@||app4.paypay.ne.jp
      @@||appassets.androidplatform.net
      @@||appassets.androidplatform.net.lan
      @@||appli.kairogame.jp
      @@||apps.nhk.or.jp
      @@||appsgrowthpromo-pa.clients6.google.com

      @@ -98,8 +136,10 @@

      @@||article-image-ix.nikkei.com
      @@||article-image.travel.navitime.jp
      @@||as-api-ws-cdn-1.tdacestudio.com
      @@||asia.tools.euroland.com
      @@||asp.shufoo.net
      @@||assets-game-prinai-com.cdn-dena.com
      @@||assets.goodnovel.com
      @@||assets.goodnovel.com.lan

      @@ -110,19 +150,32 @@

      @@||atmarkit.itmedia.co.jp
      @@||auth.cid.capcom.com
      @@||auth.ff.avast.com
      @@||azurefd-t-prod.trafficmanager.net
      @@||b.hatena.ne.jp
      @@||b.ranking.apis.sankei-digital.co.jp
      @@||bakmas.kairogame.jp
      @@||beauty-topics.com
      @@||beauty.hotpepper.jp
      @@||bees.streaks.jp
      @@||biz-media.tokyo
      @@||blog.with2.net
      @@||blogs.vmware.com
      @@||blogweb.with2.net
      @@||bolt.dropbox.com
      @@||book-pic.webnovel.com
      @@||booth.pximg.net
      @@||bot.chatbot.digital.ricoh.com
      @@||braze-images.com

      @@ -133,12 +186,18 @@

      @@||byoinnavi.jp
      @@||c-msn-com-nsatc.trafficmanager.net
      @@||c-msn-pme.trafficmanager.net
      @@||c.tenor.com
      @@||c0.wp.com
      @@||cable.yay.space
      @@||cac-ocsp.digicert.com.edgekey.net
      @@||cacerts.digicert.com
      @@||cacerts.geotrust.com
      @@||caloo.jp
      @@||capi.tigmedia.jp
      @@||capig.stape.jp

      @@ -146,8 +205,18 @@

      @@||card-ropng.img.sus-game.com.lan
      @@||card-ropng.img.sus-staging.com
      @@||cas.yay.space
      @@||cdn-content.ampproject.org
      @@||cdn.assets.paypay.ne.jp
      @@||cdn.discordapp.com
      @@||cdn.dropboxexperiment.com
      @@||cdn.esupply.co.jp

      @@ -155,27 +224,39 @@

      @@||cdn.gcore.ldoe-static.kefirgames.com.lan
      @@||cdn.globalsigncdn.com.cdn.cloudflare.net
      @@||cdn.ibispaint.com
      @@||cdn.kusurinomadoguchi.com
      @@||cdn.paypay-card.co.jp
      @@||cdn.qiita.com
      @@||cdn.smartnews.com
      @@||cdn.st-note.com
      @@||cdn.syndication.twimg.com
      @@||cdn.tigmedia.jp
      @@||cdn.twicomi.com
      @@||cdn.webpush.jp
      @@||cdn.yay.space
      @@||cfl.dropboxstatic.com
      @@||cgi.itmedia.co.jp
      @@||chatman-replay-ap-northeast-1.pscp.tv
      @@||check.gred.jp
      @@||chichi-pui.imgix.net
      @@||chirashi.otoku.aeonsquare.net
      @@||choices.trustarc.com
      @@||choices.truste.com
      @@||chromewebstore.google.com
      @@||cid.capcom.com
      @@||cl.sourcenext.com
      @@||clients.l.google.com
      @@||cloudfront.net
      @@||cloudfront.net.lan

      @@ -193,8 +274,12 @@

      @@||consentcdn.cookiebot.com
      @@||content-vita-api.snow.me
      @@||content.dropboxapi.com
      @@||contents.app.cocacola.co.jp
      @@||controlplane.tailscale.com
      @@||cookpad.com
      @@||countdown.reportitle.com
      @@||coupon.smartnews.com

      @@ -202,15 +287,27 @@

      @@||cp10.cloudflare.com
      @@||creative-hozon.com
      @@||creative.dsp.cartajp.com
      @@||csi.gstatic.com
      @@||csi.gstatic.com.lan
      @@||csm.cxpublic.com
      @@||csp.withgoogle.com
      @@||cx.api.itmedia.co.jp
      @@||d.dropbox.com
      @@||d.nordvpn.com
      @@||data.api.streaks.jp
      @@||dc.services.visualstudio.com
      @@||detectportal.firefox.com
      @@||dex50.deteql.net
      @@||dhc.demdex.net

      @@ -219,31 +316,41 @@

      @@||discord.com
      @@||dist.micres.cyberowl.jp
      @@||dl-web.dropbox.com
      @@||dmm-dig-block-simul-watch-prod.appspot.com
      @@||dms.paypay.ne.jp
      @@||dns-tunnel-check.googlezip.net
      @@||docs.gl-inet.com
      @@||docs.google.com
      @@||downloader-api-service-eqiwquegnq-uc.a.run.app
      @@||dpm.demdex.net
      @@||dpm.demdex.net.lan
      @@||drive.google.com
      @@||dsp-ad-cache-gcp-tm.trafficmanager.net
      @@||dtm00.deteql.net
      @@||duolingo.com
      @@||dyna.wikimedia.org
      @@||dynamic.webnovel.com
      @@||embed.chatbot.digital.ricoh.com
      @@||en.m.wikipedia.org
      @@||encrypted-tbn*.gstatic.com
      @@||encrypted-tbn*.gstatic.com.lan
      @@||encrypted-vtbn*.gstatic.com
      @@||epg.api.streaks.jp
      @@||event-action.app-box.jp
      @@||event-portal.dailyinnovation.biz
      @@||events.app-box.jp
      @@||events.mapbox.com
      @@||events.virtusize.jp
      @@||example.org
      @@||expedia.co.jp
      @@||explainshell.com

      @@ -251,6 +358,8 @@

      @@||ext-miniapp.paypay-card.co.jp
      @@||ext-sap.paypay-card.co.jp
      @@||fair-navi.com
      @@||fc.itmedia.co.jp
      @@||file.123chat.jp
      @@||file.imanara.jp

      @@ -262,24 +371,33 @@

      @@||fonts-api.wp.com
      @@||fonts.gstatic.com
      @@||fonts.gstatic.com.lan
      @@||fonts.wp.com
      @@||fotolia-prod-templates.global.ssl.fastly.net
      @@||fotolia-prod-templates.s3.amazonaws.com
      @@||fp.dropbox.com
      @@||free.buzzsight.co
      @@||fw.gl-inet.com
      @@||g*.gstatic.com
      @@||gacha-lineup.pokapoka-farm.com
      @@||game.capcom.com
      @@||game.snk-corp.co.jp
      @@||gamezen.org
      @@||gateway.devsisters.cloud
      @@||gateway.discord.gg
      @@||gctok*.exitgames.com
      @@||get-beauty.net
      @@||gigafile.nu
      @@||gigaplus.makeshop.jp
      @@||global-web-assets.cpcdn.com
      @@||global.stun.twilio.com
      @@||global.stun.twilio.com.lan
      @@||global.turn.twilio.com

      @@ -296,8 +414,12 @@

      @@||help.apple.com
      @@||help.twitter.com
      @@||helper-api-m-prod.prinai.com
      @@||i-l-dsp-inmobicdn-net-tm.trafficmanager.net
      @@||i-l-inmobicdn-net-tm.trafficmanager.net
      @@||i.instagram.com
      @@||i.instagram.com.lan
      @@||i.pximg.net

      @@ -306,32 +428,46 @@

      @@||i0.wp.com
      @@||ibispaint.com
      @@||ic.nordcdn.com
      @@||id-info.jihs.go.jp
      @@||id.sankei.jp
      @@||id.sonyentertainmentnetwork.com
      @@||idlink.cdp.app-box.jp
      @@||image-itmedia-co-jp.cdn.ampproject.org
      @@||image-tunag-jp.imgix.net
      @@||image.0101.co.jp
      @@||image.itmedia.co.jp
      @@||image.paypay.ne.jp
      @@||image.with2.net
      @@||images-ext-1.discordapp.net
      @@||images.ctfassets.net
      @@||imanara.jp
      @@||img-global-jp.cpcdn.com
      @@||img-global.cpcdn.com
      @@||img-sketch.pximg.net
      @@||img.buzzsight.co
      @@||img.retsta.jp
      @@||imgsct.cookiebot.com
      @@||imgweb.with2.net
      @@||imp.pixiv.net
      @@||integration.virtusize.jp
      @@||ipinfo.io
      @@||ipmcdn.avast.com.lan
      @@||ipqcache2.shufoo.net
      @@||itunes.com
      @@||ja.m.wikipedia.org
      @@||ja.wikipedia.org
      @@||jacuadpu1403.demdex.net

      @@ -341,22 +477,32 @@

      @@||jp.images-monotaro.com
      @@||js.dsp.cartajp.com
      @@||js.pay.com
      @@||jsdelivr.map.fastly.net
      @@||kairoclub.kairogame.jp
      @@||kaironotification.kairogame.jp
      @@||kakakucom.demdex.net
      @@||kanochat.jp
      @@||kao.demdex.net
      @@||kddi-h.assetsadobe3.com
      @@||key.streaks.jp
      @@||kit.fontawesome.com
      @@||kn.nice-news.net
      @@||kochi-univ-med-hosp-api.devglow.net
      @@||kochiap.dmacs.jp
      @@||kochicdn.dmacs.jp
      @@||kumaxpower.kairogame.jp
      @@||kyujin.navitime.co.jp
      @@||l.threads.net
      @@||lb.wordpress.com
      @@||lf16-geckocdn-offline.g-p-static.com
      @@||lh3.ggpht.com

      @@ -367,17 +513,22 @@

      @@||location.nhk.or.jp
      @@||log.goodnovel.com
      @@||log.nordot.jp
      @@||log.shufoo.net
      @@||log.snow.me
      @@||log.tailscale.io
      @@||logcollector.note.com
      @@||logging.devsisters.cloud
      @@||logging.prod.devsisters.cloud
      @@||login.wikimedia.org
      @@||m.goodnovel.com
      @@||m1.nintendo.net
      @@||mail.google.com
      @@||manifest.streaks.jp
      @@||map.unnerv.app
      @@||maps.google.co.jp
      @@||maps.gstatic.com

      @@ -386,6 +537,8 @@

      @@||marui.ad.zetacx.net
      @@||marui.recommend.zetacx.net
      @@||marui.search.zetacx.net
      @@||media.cld.navitime.jp
      @@||media.discordapp.net
      @@||media.tenor.com

      @@ -393,10 +546,14 @@

      @@||mediacdn.ttzgame.com
      @@||meet.google.com
      @@||megaphone.imgix.net
      @@||meshmap.unnerv.app
      @@||meta.m.wikimedia.org
      @@||meta.wikimedia.org
      @@||metric.acestudio.ai
      @@||microapps.google.com
      @@||mini-app-sdk-core.paypay.ne.jp
      @@||missions-assets.smartnews.com

      @@ -406,25 +563,36 @@

      @@||mochimoji.jp
      @@||monorail-edge.shopifysvc.com
      @@||mp.smartnews.com
      @@||mtalk.google.com
      @@||mtalk.google.com.lan
      @@||mtcs.nhk.or.jp
      @@||my-coupon-static.smartnews.com
      @@||my.komeri-card.com
      @@||n.yapp.li
      @@||navismithapis-cdn.com
      @@||navismithapis.com
      @@||news-in.feednews.com
      @@||news.google.com
      @@||newsapi.nhk.or.jp
      @@||ngp.virpro.com
      @@||nhk.or.jp.edgekey.net
      @@||nhk.or.jp.ssl.sc.omtrdc.net
      @@||nkis.nikkei.com
      @@||nkispa.nikkei.com
      @@||nlab-itmedia-co-jp.cdn.ampproject.org
      @@||nlab.itmedia.co.jp
      @@||noah-image.webnovel.com
      @@||noodle2.kairogame.jp
      @@||nordvpn.com
      @@||norton.com

      @@ -438,20 +606,29 @@

      @@||ocsp.digicert.com
      @@||ocsp.edge.digicert.com
      @@||ocsp.globalsign.com
      @@||ocsp.usertrust.com
      @@||ocsp2.globalsign.com
      @@||oms.norton.com
      @@||one.one.one.one
      @@||open-pixon.ads-pixiv.net
      @@||ota-cache1.googlezip.net
      @@||ota.googlezip.net
      @@||otlp-http-production.shopifysvc.com
      @@||otn.fujitv.co.jp
      @@||p-smith.com
      @@||p.typekit.net
      @@||paddock2.kairogame.jp
      @@||page.taponland.com
      @@||pai-gm-prod.paypay.ne.jp
      @@||partner.googleadservices.com
      @@||partsa.nikkei.com
      @@||pay.google.com

      @@ -459,28 +636,44 @@

      @@||payment.123chat.jp
      @@||payment.kanochat.jp
      @@||payments-graph.instagram.com
      @@||paypay.ne.jp
      @@||paytner.co.jp
      @@||pbs.twimg.com
      @@||pbs.twimg.com.cdn.cloudflare.net
      @@||pbs.twimg.com.lan
      @@||pfprod-beppu-input.yapp.li
      @@||pic.paypay.ne.jp
      @@||picosaba.net
      @@||pinnaclemnt.net
      @@||pixel.smartnews.com
      @@||pixel.wp.com
      @@||pixiv.net
      @@||pixiv.pximg.net
      @@||pixon.ads-pixiv.net
      @@||playback.api.streaks.jp
      @@||playdreams.online
      @@||player-api-m-prod.prinai.com
      @@||poi-static-map.cld.navitime.jp
      @@||pool.ntp.org
      @@||postserve.trafficmanager.net
      @@||pp3-sdk-api.profilepassport.jp
      @@||pp3-sdkdata-v2.profilepassport.jp
      @@||prd-real.card-type-message-wlb.verda2.akadns.net
      @@||president.jp
      @@||probe.twitter.com

      @@ -491,6 +684,9 @@

      @@||prod-fastly-ap-northeast-1.video.pscp.tv
      @@||prod-socket.pokapoka-farm.com
      @@||prod.globalsign.map.fastly.net
      @@||profile.yoshimoto.co.jp
      @@||proton.me
      @@||protonvpn.com

      @@ -505,6 +701,7 @@

      @@||push-signal.paypay.ne.jp
      @@||push-signal.paypay.ne.jp.lan
      @@||push.clients6.google.com
      @@||qiita-official-contents.imgix.net
      @@||qiita-organization-images.imgix.net
      @@||qiita-user-contents.imgix.net

      @@ -515,10 +712,14 @@

      @@||radiomap.vcdn.pos.here.com
      @@||rainradar.smartnews.com
      @@||realtimesupport.clients6.google.com
      @@||recruitrikunabinext.demdex.net
      @@||reiwa-shinsengumi.com
      @@||remotedesktop.google.com
      @@||reports.proton.me
      @@||restapi-chat-management.ppcd-support.jp
      @@||retty.me
      @@||ropng.img.sus-game.com

      @@ -530,10 +731,14 @@

      @@||s-part-0018.t-0009.t-msedge.net
      @@||s-part-0019.t-0009.fb-t-msedge.net
      @@||s-part-0019.t-0009.t-msedge.net
      @@||s.pximg.net
      @@||s.w.org
      @@||s.wordpress.com
      @@||s.ytimg.com
      @@||s0.wp.com
      @@||s1.nordcdn.com
      @@||s3.ap-northeast-1.amazonaws.com

      @@ -543,12 +748,16 @@

      @@||sb-ssl.google.com
      @@||sb.nordcdn.com
      @@||sc-static.net
      @@||screw.ttzgame.com
      @@||sdk.hellouniweb.com
      @@||sdk.rum.aliyuncs.com
      @@||seal.digicert.com
      @@||seal.globalsign.com
      @@||secure.globalsign.com
      @@||securl.nu
      @@||selfs.dai-ichi-life.co.jp
      @@||services.virtusize.jp

      @@ -559,24 +768,35 @@

      @@||shakkin-soudan-madoguchi.com
      @@||shed.dual-low.s-part-0018.t-0009.t-msedge.net
      @@||shed.dual-low.s-part-0019.t-0009.t-msedge.net
      @@||shepherd.ff.avast.com
      @@||shepherd.sb.avast.com
      @@||shepherd.sb.avast.com.lan
      @@||shiorio.com
      @@||shop.adidas.jp
      @@||shop.gofuku-ishihara.com
      @@||smartnews-assets.s3.ap-northeast-1.amazonaws.com
      @@||sn-proxy.smartnews.com
      @@||sodium.slp.pos.here.com
      @@||sodium.slp.pos.here.com.lan
      @@||source.pixiv.net
      @@||sourcenext-recommend.data-lab-pg.com
      @@||sp-*.apkrep.avcdn.net
      @@||sp-*.apkrep.avcdn.net.lan
      @@||sp-*.honzik.avcdn.net
      @@||sp-*.honzik.avcdn.net.lan
      @@||sp-trk.com
      @@||special.sankei.com
      @@||ssai-manifest.streaks.jp
      @@||ssai-variants.streaks.jp
      @@||ssai.api.streaks.jp

      @@ -595,12 +815,20 @@

      @@||static.cookpad.com
      @@||static.es.cyberowl.jp
      @@||static.line.naver.jp
      @@||static.media.cld.navitime.jp
      @@||static.newsapp.nhk.or.jp
      @@||static.paypay.ne.jp
      @@||stats.wp.com
      @@||status.itmedia.co.jp
      @@||steampowered.com
      @@||stream-log.profilepassport.jp
      @@||sundry-f-net.trafficmanager.net
      @@||supply-inmobicdn-net-tm.trafficmanager.net

      @@ -621,10 +849,19 @@

      @@||tig-contents.com
      @@||time.windows.com
      @@||timecheck.imanara.jp
      @@||toi.kuronekoyamato.co.jp
      @@||ton.twimg.com
      @@||tr.api.itmedia.co.jp
      @@||tracks.streaks.jp
      @@||translate.google.com
      @@||travel.navitime.com
      @@||tsutaeru.cloud

      @@ -638,6 +875,10 @@

      @@||twincle.schanbeauty.com
      @@||twoucan.com
      @@||tx.lbg.play.naver.jp
      @@||unpkg.com
      @@||update.code.visualstudio.com
      @@||upload.wikimedia.org

      @@ -646,12 +887,14 @@

      @@||use.fontawesome.com
      @@||use.typekit.net
      @@||user-photo.paypay.ne.jp
      @@||users.app-box.jp
      @@||v0.wordpress.com
      @@||variants.streaks.jp
      @@||vastproxy-brand-inmobi-comtm.trafficmanager.net
      @@||vday.io
      @@||vec-adm-rain.newsapp.nhk.or.jp
      @@||video-downloads.googleusercontent.com
      @@||video-ft.twimg.com
      @@||video-s.twimg.com

      @@ -661,15 +904,26 @@

      @@||video.twimg.com
      @@||video.twimg.com.lan
      @@||virtualcurrency.kairogame.jp
      @@||vod-tver-*.streaks.jp
      @@||voguecrew.net
      @@||voi.0101.co.jp
      @@||vpncdn.protonweb.com
      @@||waa-pa.clients6.google.com
      @@||wallet.google.com
      @@||wallet.yay.space
      @@||web-api.nordvpn.com
      @@||web-api.tapon.com
      @@||websocket.paypay.ne.jp
      @@||widgets.twimg.com
      @@||widgets.twimg.com.lan

      @@ -677,27 +931,33 @@

      @@||work.fife.usercontent.google.com
      @@||workspace.google.com
      @@||worldaz.relay.teams.trafficmanager.net
      @@||www-famitsu-com.cdn.ampproject.org
      @@||www.123chat.jp
      @@||www.666-666.jp
      @@||www.adidas.jp
      @@||www.agrinews.co.jp
      @@||www.amazon.co.jp
      @@||www.asahibeer-cp.jp
      @@||www.bing.com
      @@||www.broadcom.com.cdn.cloudflare.net
      @@||www.cecile.co.jp
      @@||www.city.kami.lg.jp
      @@||www.dai-ichi-life.co.jp
      @@||www.dropbox.com
      @@||www.ehimeshiryo.com
      @@||www.ekiten.jp
      @@||www.esupply.co.jp
      @@||www.expressvpn.com
      @@||www.fujitv.co.jp
      @@||www.gl-inet.com
      @@||www.goodnovel.com
      @@||www.google.co.jp
      @@||www.google.us
      @@||www.google.us.lan
      @@||www.googleadservices.com

      @@ -711,6 +971,7 @@

      @@||www.jtb.co.jp
      @@||www.juststarz.com
      @@||www.kanochat.jp
      @@||www.kensei-online.com
      @@||www.keycolle.jp
      @@||www.kfc.co.jp

      @@ -718,30 +979,37 @@

      @@||www.kochinews.co.jp
      @@||www.kojima.net
      @@||www.komeri.com
      @@||www.kurashiru.com
      @@||www.kusurinomadoguchi.com
      @@||www.lady-drug.co.jp
      @@||www.lawson.co.jp
      @@||www.lifemag.jp
      @@||www.merupero.com
      @@||www.monotaro.com
      @@||www.navitime.co.jp
      @@||www.newsapp.nhk.or.jp
      @@||www.nhk.or.jp
      @@||www.niid.jihs.go.jp
      @@||www.nijiyome.com
      @@||www.nijiyome.jp
      @@||www.nikkei.com
      @@||www.nitori-net.jp
      @@||www.onamae.com
      @@||www.paypay-card.co.jp
      @@||www.paypay.ne.jp
      @@||www.pixiv.net
      @@||www.rd.ntt
      @@||www.recaptcha.net
      @@||www.sankei.com
      @@||www.shikoku.co.jp
      @@||www.shingakunavi.ne.jp
      @@||www.smartnews.be
      @@||www.smartwaon.com
      @@||www.sourcenext.com

      @@ -749,12 +1017,18 @@

      @@||www.threads.net
      @@||www.tm.ak.prd.aadg.trafficmanager.net
      @@||www.topvalu.net
      @@||www.tsuruha-group.com
      @@||www.tsuruha-hd.com
      @@||www.virustotal.com
      @@||www.vmware.com
      @@||www.wattpad.com
      @@||www.wikipedia.org
      @@||www.yonden.co.jp
      @@||www.youtube.com
      @@||www.zakzak.co.jp

      @@ -769,9 +1043,11 @@

      @@||xvdrop.imgix.net
      @@||xvp.imgix.net
      @@||yamato-hd.co.jp
      @@||yandex.ru
      @@||yapp.li
      @@||yasurok2.wordpress.com
      @@||yorozu-kochi.go.jp
      @@||youtu.be
      @@||yt3.ggpht.com

      @@ -780,6 +1056,7 @@

      @@||yururi2019.com
      @@||za.tapon.com
      @@||zapgo.org
      @@||zozo.jp

      # [アンチ広告ブロッカー／Ad-Shield]
    ```

    ```yaml
    AFTER:
      # References: none
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/accept/Accept_domain.txt
      #
    + # Last modified: 14 November 2025
      #

      # [許可リクエスト]
    + @@/alt[0-9]-360yield.com.google.com.lan/
    + @@/alt[0-9]-mtalk.google.com.lan/
    + @@/alt[0-9]-mtalk.google.com.ts.net/
    + @@/alt[0-9]-mtalk.google.com/
    + @@/e[5-9]*.i.lencr.org/
    + @@/e[5-9]*.o.lencr.org/
    + @@/i[1-9]*.ytimg.com/
    + @@/media[0-9]*.giphy.com/
    + @@/r1[0-4]*.i.lencr.org/
    + @@/r1[0-4]*.o.lencr.org/
      @@||*.blob.core.windows.net
      @@||*.cloudfront.net
      @@||*.cloudfront.net.lan
      @@||*.user.webaccel.jp
      @@||268gr.com
    + @@||404-alt.playrix.com
    + @@||404.playrix.com
      @@||a.flux.jp
      @@||a.pixiv.org
    + @@||a3.gmo-app.jp
      @@||a3.shared.global.fastly.net
      @@||aa-metrics.beauty.hotpepper.jp
      @@||aapi.buzzsight.co
    + @@||aax-fe.amazon.co.jp
      @@||abema.go.link
    + @@||abema.tv
      @@||abs-0.twimg.com
      @@||abs-zero.twimg.com
      @@||abs.twimg.com

      @@ -40,40 +50,65 @@

      @@||accounts.youtube.com
      @@||accuweather.com
      @@||acestudio.ai
    + @@||acf.goodnovel.com
    + @@||acfs1.goodnovel.com
    + @@||acfs2.goodnovel.com
    + @@||acfs3.goodnovel.com
      @@||aclog.itmedia.co.jp
      @@||acps-api.mixerbox.com
      @@||acps-api.mixerbox.com.cdn.cloudflare.net
    + @@||acps-iaa.mixerbox.com
    + @@||acps-iaa.mixerbox.com.cdn.cloudflare.net
      @@||ad-segments-proxy.streaks.jp
    + @@||ad.ads.arutana.jp
    + @@||ad.gain-ads.com
      @@||adm-srch.newsapp.nhk.or.jp
    + @@||ads-delivery-cdn.gunosy.com
    + @@||ads-delivery.gunosy.com
    + @@||age-restrictions.playrix.com
    + @@||ahamo.com
      @@||airplane.kairogame.jp
    + @@||airport.landinghub.cloud
      @@||ajax.cloudflare.com
    + @@||alt.meet.telephony.goog
    + @@||amazon.co.jp
    + @@||amzn.asia
      @@||amzn.to
      @@||analytics.ff.avast.com
      @@||analytics.yay.space
      @@||analytics.yay.space.lan
      @@||anshin.demdex.net
    + @@||api-akm.goodnovel.com
      @@||api-d.dropbox.com
      @@||api-stream.twitter.com.lan
      @@||api.amazon.co.jp
    + @@||api.antibanads.com
      @@||api.bing.com
      @@||api.cloud.huawei.com
      @@||api.cloud.huawei.com.lan
    + @@||api.docodoco.jp
      @@||api.dollphoin.site
      @@||api.dropbox.com
      @@||api.dropboxapi.com
    + @@||api.e-kakushin.com
      @@||api.flightproxy.teams.trafficmanager.net
      @@||api.github.com
      @@||api.goodnovel.com
      @@||api.inmense.site
    + @@||api.ipify.org
      @@||api.joyreadings.com
      @@||api.kickoffo.site
    + @@||api.kochi-bank.bankapp.jp
      @@||api.mapbox.com
    + @@||api.p-c3-e.abema-tv.com
    + @@||api.photoeditorsdk.com
      @@||api.plugin.myideal.jp
      @@||api.rudderstack.com
    + @@||api.seminar.shift-ai.co.jp
      @@||api.smartwaon.com
      @@||api.twicomi.com
      @@||api.twitter.com
    + @@||api.typesquare.com
      @@||api.unnerv.app
      @@||api.vday.io
      @@||api.webpush.jp

      @@ -81,12 +116,15 @@

      @@||api.yay.space
      @@||api.yay.space.lan
      @@||app-api.pixiv.net
    + @@||app.botchan.chat
      @@||app.bspace.jp
    + @@||app.chatplus.jp
      @@||app.paypay.ne.jp
      @@||app.plugin.myideal.jp
      @@||app4.paypay.ne.jp
      @@||appassets.androidplatform.net
      @@||appassets.androidplatform.net.lan
    + @@||appimg.chatplus.jp
      @@||appli.kairogame.jp
      @@||apps.nhk.or.jp
      @@||appsgrowthpromo-pa.clients6.google.com

      @@ -98,8 +136,10 @@

      @@||article-image-ix.nikkei.com
      @@||article-image.travel.navitime.jp
      @@||as-api-ws-cdn-1.tdacestudio.com
    + @@||asapi.aweray.net
      @@||asia.tools.euroland.com
      @@||asp.shufoo.net
    + @@||asset.oceans-nadia.com
      @@||assets-game-prinai-com.cdn-dena.com
      @@||assets.goodnovel.com
      @@||assets.goodnovel.com.lan

      @@ -110,19 +150,32 @@

      @@||atmarkit.itmedia.co.jp
      @@||auth.cid.capcom.com
      @@||auth.ff.avast.com
    + @@||avatars.mds.yandex.net
      @@||azurefd-t-prod.trafficmanager.net
      @@||b.hatena.ne.jp
      @@||b.ranking.apis.sankei-digital.co.jp
    + @@||b.st-hatena.com
    + @@||backend.mr-colosseum.com
      @@||bakmas.kairogame.jp
    + @@||balancer.catsthegame.com
    + @@||bcs.amanotes.net
    + @@||beacon.riskified.com
      @@||beauty-topics.com
      @@||beauty.hotpepper.jp
    + @@||bedore.jp
      @@||bees.streaks.jp
    + @@||bff-v2.eneos-ss.app
    + @@||bff-v2.eneos-ss.app.lan
    + @@||bff-v2.eneos-ss.app.ts.net
      @@||biz-media.tokyo
    + @@||blog.hatena.ne.jp
      @@||blog.with2.net
      @@||blogs.vmware.com
      @@||blogweb.with2.net
      @@||bolt.dropbox.com
    + @@||bonkura-theater.up.seesaa.net
      @@||book-pic.webnovel.com
    + @@||bookmark.hatenaapis.com
      @@||booth.pximg.net
      @@||bot.chatbot.digital.ricoh.com
      @@||braze-images.com

      @@ -133,12 +186,18 @@

      @@||byoinnavi.jp
      @@||c-msn-com-nsatc.trafficmanager.net
      @@||c-msn-pme.trafficmanager.net
    + @@||c.marsflag.com
    + @@||c.riskified.com
      @@||c.tenor.com
      @@||c0.wp.com
      @@||cable.yay.space
      @@||cac-ocsp.digicert.com.edgekey.net
      @@||cacerts.digicert.com
      @@||cacerts.geotrust.com
    + @@||cache.dotapps.jp
    + @@||cache.dotgames.info
    + @@||cache.prd.tokyodebunker.com
    + @@||cache.sirok.jp
      @@||caloo.jp
      @@||capi.tigmedia.jp
      @@||capig.stape.jp

      @@ -146,8 +205,18 @@

      @@||card-ropng.img.sus-game.com.lan
      @@||card-ropng.img.sus-staging.com
      @@||cas.yay.space
    + @@||cats-ingame-news-origin.nazara.in
    + @@||cats-ingame-news-origin.nazara.in-dev1
    + @@||cats-ingame-news-origin.nazara.in-dev1.lan
    + @@||cats-ingame-news-origin.nazara.in-dev1.ts.net
    + @@||cdn-ak.f.st-hatena.com
    + @@||cdn-assets.mr-colosseum.com
      @@||cdn-content.ampproject.org
    + @@||cdn-masterdata.mr-colosseum.com
    + @@||cdn-os.qookkagames.com
      @@||cdn.assets.paypay.ne.jp
    + @@||cdn.blog.st-hatena.com
    + @@||cdn.dailyinnovation.biz
      @@||cdn.discordapp.com
      @@||cdn.dropboxexperiment.com
      @@||cdn.esupply.co.jp

      @@ -155,27 +224,39 @@

      @@||cdn.gcore.ldoe-static.kefirgames.com.lan
      @@||cdn.globalsigncdn.com.cdn.cloudflare.net
      @@||cdn.ibispaint.com
    + @@||cdn.image.st-hatena.com
    + @@||cdn.jsdelivr.net.cdn.cloudflare.net
      @@||cdn.kusurinomadoguchi.com
      @@||cdn.paypay-card.co.jp
    + @@||cdn.profile-image.st-hatena.com
      @@||cdn.qiita.com
    + @@||cdn.qookkagames.com
      @@||cdn.smartnews.com
      @@||cdn.st-note.com
    + @@||cdn.syncsearch.jp
      @@||cdn.syndication.twimg.com
      @@||cdn.tigmedia.jp
      @@||cdn.twicomi.com
      @@||cdn.webpush.jp
    + @@||cdn.wikiwiki.jp
      @@||cdn.yay.space
    + @@||cdnext-svg001-ipb000.stream.ne.jp
    + @@||cert.ssl.com
      @@||cfl.dropboxstatic.com
      @@||cgi.itmedia.co.jp
    + @@||chairhouse.up.seesaa.net
    + @@||challenges.cloudflare.com
      @@||chatman-replay-ap-northeast-1.pscp.tv
      @@||check.gred.jp
      @@||chichi-pui.imgix.net
      @@||chirashi.otoku.aeonsquare.net
      @@||choices.trustarc.com
      @@||choices.truste.com
    + @@||chrome.google.com
      @@||chromewebstore.google.com
      @@||cid.capcom.com
      @@||cl.sourcenext.com
    + @@||classical-sound.up.seesaa.net
      @@||clients.l.google.com
      @@||cloudfront.net
      @@||cloudfront.net.lan

      @@ -193,8 +274,12 @@

      @@||consentcdn.cookiebot.com
      @@||content-vita-api.snow.me
      @@||content.dropboxapi.com
    + @@||content.prd.tokyodebunker.com
    + @@||content.prd.tokyodebunker.com.lan
    + @@||contents.ads.arutana.jp
      @@||contents.app.cocacola.co.jp
      @@||controlplane.tailscale.com
    + @@||convertio.co
      @@||cookpad.com
      @@||countdown.reportitle.com
      @@||coupon.smartnews.com

      @@ -202,15 +287,27 @@

      @@||cp10.cloudflare.com
      @@||creative-hozon.com
      @@||creative.dsp.cartajp.com
    + @@||crt.sectigo.com
      @@||csi.gstatic.com
      @@||csi.gstatic.com.lan
      @@||csm.cxpublic.com
      @@||csp.withgoogle.com
    + @@||cu.tbs.co.jp
    + @@||cubeapi-jp.qookkagames.com
    + @@||cubeapix.qookkagames.com
    + @@||cubeapix.qookkagames.com.lan
    + @@||cubeapix.qookkagames.com.ts.net
      @@||cx.api.itmedia.co.jp
    + @@||cyberjapandata.gsi.go.jp
      @@||d.dropbox.com
      @@||d.nordvpn.com
    + @@||damedameyo.up.seesaa.net
      @@||data.api.streaks.jp
    + @@||data.wovn.io
    + @@||dc-static.wondershare.com
      @@||dc.services.visualstudio.com
    + @@||demotiles.maplibre.org
    + @@||derp7b.tailscale.com
      @@||detectportal.firefox.com
      @@||dex50.deteql.net
      @@||dhc.demdex.net

      @@ -219,31 +316,41 @@

      @@||discord.com
      @@||dist.micres.cyberowl.jp
      @@||dl-web.dropbox.com
    + @@||dlv.itmedia.jp
      @@||dmm-dig-block-simul-watch-prod.appspot.com
      @@||dms.paypay.ne.jp
      @@||dns-tunnel-check.googlezip.net
      @@||docs.gl-inet.com
      @@||docs.google.com
    + @@||doda.jp
    + @@||dotapps.jp
    + @@||doujin-hp.or.jp
      @@||downloader-api-service-eqiwquegnq-uc.a.run.app
      @@||dpm.demdex.net
      @@||dpm.demdex.net.lan
    + @@||dreamplanetstation.up.seesaa.net
      @@||drive.google.com
      @@||dsp-ad-cache-gcp-tm.trafficmanager.net
      @@||dtm00.deteql.net
    + @@||dualstack.beacon.itmedia.jp
      @@||duolingo.com
      @@||dyna.wikimedia.org
      @@||dynamic.webnovel.com
    + @@||edge.surfeasy.com.ts.net
      @@||embed.chatbot.digital.ricoh.com
      @@||en.m.wikipedia.org
      @@||encrypted-tbn*.gstatic.com
      @@||encrypted-tbn*.gstatic.com.lan
      @@||encrypted-vtbn*.gstatic.com
      @@||epg.api.streaks.jp
    + @@||err.nextersglobal.com
      @@||event-action.app-box.jp
      @@||event-portal.dailyinnovation.biz
      @@||events.app-box.jp
      @@||events.mapbox.com
      @@||events.virtusize.jp
    + @@||evocsp.managedpki.ne.jp
    + @@||ex-ann-w.webcdn.stream.ne.jp
      @@||example.org
      @@||expedia.co.jp
      @@||explainshell.com

      @@ -251,6 +358,8 @@

      @@||ext-miniapp.paypay-card.co.jp
      @@||ext-sap.paypay-card.co.jp
      @@||fair-navi.com
    + @@||faq.cecile.co.jp
    + @@||fastly.jsdelivr.net
      @@||fc.itmedia.co.jp
      @@||file.123chat.jp
      @@||file.imanara.jp

      @@ -262,24 +371,33 @@

      @@||fonts-api.wp.com
      @@||fonts.gstatic.com
      @@||fonts.gstatic.com.lan
    + @@||fonts.shopifycdn.com
    + @@||fonts.twitter.com
      @@||fonts.wp.com
      @@||fotolia-prod-templates.global.ssl.fastly.net
      @@||fotolia-prod-templates.s3.amazonaws.com
      @@||fp.dropbox.com
    + @@||fraud-buster.appspot.com
      @@||free.buzzsight.co
    + @@||frog.wix.com
      @@||fw.gl-inet.com
      @@||g*.gstatic.com
      @@||gacha-lineup.pokapoka-farm.com
    + @@||gacraft.jp
      @@||game.capcom.com
    + @@||game.prd.tokyodebunker.com
      @@||game.snk-corp.co.jp
    + @@||gameops-player-profile.playrix.com
      @@||gamezen.org
      @@||gateway.devsisters.cloud
      @@||gateway.discord.gg
      @@||gctok*.exitgames.com
    + @@||geo0.ggpht.com
      @@||get-beauty.net
      @@||gigafile.nu
      @@||gigaplus.makeshop.jp
      @@||global-web-assets.cpcdn.com
    + @@||global.sitesafety.trendmicro.com
      @@||global.stun.twilio.com
      @@||global.stun.twilio.com.lan
      @@||global.turn.twilio.com

      @@ -296,8 +414,12 @@

      @@||help.apple.com
      @@||help.twitter.com
      @@||helper-api-m-prod.prinai.com
    + @@||houmukyoku.moj.go.jp
    + @@||humanbug.shop
    + @@||hw-slg-report.eyugame.com
      @@||i-l-dsp-inmobicdn-net-tm.trafficmanager.net
      @@||i-l-inmobicdn-net-tm.trafficmanager.net
    + @@||i-ogp.pximg.net
      @@||i.instagram.com
      @@||i.instagram.com.lan
      @@||i.pximg.net

      @@ -306,32 +428,46 @@

      @@||i0.wp.com
      @@||ibispaint.com
      @@||ic.nordcdn.com
    + @@||ichef.bbci.co.uk
      @@||id-info.jihs.go.jp
    + @@||id.123apps.com
      @@||id.sankei.jp
      @@||id.sonyentertainmentnetwork.com
      @@||idlink.cdp.app-box.jp
      @@||image-itmedia-co-jp.cdn.ampproject.org
      @@||image-tunag-jp.imgix.net
      @@||image.0101.co.jp
    + @@||image.bedore.jp
      @@||image.itmedia.co.jp
    + @@||image.p-c2-x.abema-tv.com
      @@||image.paypay.ne.jp
      @@||image.with2.net
      @@||images-ext-1.discordapp.net
      @@||images.ctfassets.net
    + @@||images.dmca.com
    + @@||images.gunosy.com
    + @@||images.wondershare.com
      @@||imanara.jp
      @@||img-global-jp.cpcdn.com
      @@||img-global.cpcdn.com
      @@||img-sketch.pximg.net
      @@||img.buzzsight.co
    + @@||img.macromill.com
    + @@||img.nosh.jp
      @@||img.retsta.jp
    + @@||img.riskified.com
      @@||imgsct.cookiebot.com
      @@||imgweb.with2.net
    + @@||imp.gain-ads.com
      @@||imp.pixiv.net
    + @@||initplayback.ts.net
      @@||integration.virtusize.jp
    + @@||ipapi.co
      @@||ipinfo.io
      @@||ipmcdn.avast.com.lan
      @@||ipqcache2.shufoo.net
      @@||itunes.com
    + @@||j.wovn.io
      @@||ja.m.wikipedia.org
      @@||ja.wikipedia.org
      @@||jacuadpu1403.demdex.net

      @@ -341,22 +477,32 @@

      @@||jp.images-monotaro.com
      @@||js.dsp.cartajp.com
      @@||js.pay.com
    + @@||js.stripe.com
      @@||jsdelivr.map.fastly.net
    + @@||k2k.sagawa-exp.co.jp
      @@||kairoclub.kairogame.jp
      @@||kaironotification.kairogame.jp
      @@||kakakucom.demdex.net
      @@||kanochat.jp
      @@||kao.demdex.net
      @@||kddi-h.assetsadobe3.com
    + @@||kefirgames.com
      @@||key.streaks.jp
    + @@||kit-cdn.shazam.com
      @@||kit.fontawesome.com
      @@||kn.nice-news.net
    + @@||kochi-bank.co.jp
      @@||kochi-univ-med-hosp-api.devglow.net
      @@||kochiap.dmacs.jp
      @@||kochicdn.dmacs.jp
      @@||kumaxpower.kairogame.jp
      @@||kyujin.navitime.co.jp
    + @@||l.mixerbox.com
    + @@||l.mixerbox.com.cdn.cloudflare.net
    + @@||l.shift-ai.co.jp
      @@||l.threads.net
    + @@||lapi.oceans-nadia.com
    + @@||lawson.go.link
      @@||lb.wordpress.com
      @@||lf16-geckocdn-offline.g-p-static.com
      @@||lh3.ggpht.com

      @@ -367,17 +513,22 @@

      @@||location.nhk.or.jp
      @@||log.goodnovel.com
      @@||log.nordot.jp
    + @@||log.qookkagames.com
      @@||log.shufoo.net
      @@||log.snow.me
      @@||log.tailscale.io
      @@||logcollector.note.com
      @@||logging.devsisters.cloud
      @@||logging.prod.devsisters.cloud
    + @@||login.tailscale.com
      @@||login.wikimedia.org
      @@||m.goodnovel.com
    + @@||m.stripe.com
    + @@||m.stripe.network
      @@||m1.nintendo.net
      @@||mail.google.com
      @@||manifest.streaks.jp
    + @@||map.go.affec.tv
      @@||map.unnerv.app
      @@||maps.google.co.jp
      @@||maps.gstatic.com

      @@ -386,6 +537,8 @@

      @@||marui.ad.zetacx.net
      @@||marui.recommend.zetacx.net
      @@||marui.search.zetacx.net
    + @@||matrix.dailyinnovation.biz
    + @@||measure.lamp.avct.cloud
      @@||media.cld.navitime.jp
      @@||media.discordapp.net
      @@||media.tenor.com

      @@ -393,10 +546,14 @@

      @@||mediacdn.ttzgame.com
      @@||meet.google.com
      @@||megaphone.imgix.net
    + @@||member.tt.tanaka.jp
    + @@||memorymusic.up.seesaa.net
    + @@||mens-rinx.jp
      @@||meshmap.unnerv.app
      @@||meta.m.wikimedia.org
      @@||meta.wikimedia.org
      @@||metric.acestudio.ai
    + @@||metrics-dra.dt.hicloud.com.ts.net
      @@||microapps.google.com
      @@||mini-app-sdk-core.paypay.ne.jp
      @@||missions-assets.smartnews.com

      @@ -406,25 +563,36 @@

      @@||mochimoji.jp
      @@||monorail-edge.shopifysvc.com
      @@||mp.smartnews.com
    + @@||mpc-prod-11-s6uit34pua-uc.a.run.app
    + @@||mpc-prod-2-1053047382554.us-central1.run.app
    + @@||msg.township-ios.playrix.com
    + @@||mt.gigazine.net
    + @@||mt3-v2-apple.amanotes.io
      @@||mtalk.google.com
      @@||mtalk.google.com.lan
      @@||mtcs.nhk.or.jp
    + @@||music.amanotes.net
      @@||my-coupon-static.smartnews.com
      @@||my.komeri-card.com
    + @@||myaccount.google.com
      @@||n.yapp.li
      @@||navismithapis-cdn.com
      @@||navismithapis.com
      @@||news-in.feednews.com
      @@||news.google.com
      @@||newsapi.nhk.or.jp
    + @@||newsdig.tbs.co.jp
      @@||ngp.virpro.com
      @@||nhk.or.jp.edgekey.net
      @@||nhk.or.jp.ssl.sc.omtrdc.net
    + @@||nidan.addlv.smt.docomo.ne.jp
    + @@||nijimo.crt.sectigo.com
      @@||nkis.nikkei.com
      @@||nkispa.nikkei.com
      @@||nlab-itmedia-co-jp.cdn.ampproject.org
      @@||nlab.itmedia.co.jp
      @@||noah-image.webnovel.com
    + @@||nobunaga-shinsen-landing.qookkagames.jp
      @@||noodle2.kairogame.jp
      @@||nordvpn.com
      @@||norton.com

      @@ -438,20 +606,29 @@

      @@||ocsp.digicert.com
      @@||ocsp.edge.digicert.com
      @@||ocsp.globalsign.com
    + @@||ocsp.godaddy.com
    + @@||ocsp.godaddy.com.akadns.net
      @@||ocsp.usertrust.com
      @@||ocsp2.globalsign.com
      @@||oms.norton.com
      @@||one.one.one.one
    + @@||onetag.tws.toyota.jp
      @@||open-pixon.ads-pixiv.net
      @@||ota-cache1.googlezip.net
      @@||ota.googlezip.net
    + @@||otbp-trnelb.onetapbuy.jp
      @@||otlp-http-production.shopifysvc.com
      @@||otn.fujitv.co.jp
      @@||p-smith.com
    + @@||p.twitter.com
    + @@||p.twitter.com.lan
    + @@||p.twitter.com.ts.net
      @@||p.typekit.net
      @@||paddock2.kairogame.jp
      @@||page.taponland.com
      @@||pai-gm-prod.paypay.ne.jp
    + @@||paint-api.dailyinnovation.biz
    + @@||panorama.wixapps.net
      @@||partner.googleadservices.com
      @@||partsa.nikkei.com
      @@||pay.google.com

      @@ -459,28 +636,44 @@

      @@||payment.123chat.jp
      @@||payment.kanochat.jp
      @@||payments-graph.instagram.com
    + @@||payments.google.com
      @@||paypay.ne.jp
      @@||paytner.co.jp
    + @@||pbn-cdn.dailyinnovation.biz
      @@||pbs.twimg.com
      @@||pbs.twimg.com.cdn.cloudflare.net
      @@||pbs.twimg.com.lan
    + @@||pc.mobit.ne.jp
    + @@||pdst.fm
    + @@||pf-api.hatena.com
      @@||pfprod-beppu-input.yapp.li
    + @@||pi.music.amanotes.net
    + @@||pi.pardot.com
      @@||pic.paypay.ne.jp
      @@||picosaba.net
      @@||pinnaclemnt.net
    + @@||pinpoint.ap-northeast-1.amazonaws.com
    + @@||pinpoint.ap-northeast-1.amazonaws.com.lan
    + @@||pinpoint.ap-northeast-1.amazonaws.com.ts.net
      @@||pixel.smartnews.com
      @@||pixel.wp.com
      @@||pixiv.net
      @@||pixiv.pximg.net
      @@||pixon.ads-pixiv.net
    + @@||pki.goog
      @@||playback.api.streaks.jp
      @@||playdreams.online
      @@||player-api-m-prod.prinai.com
    + @@||plugins.mixi.jp
    + @@||pocket.shonenmagazine.com
      @@||poi-static-map.cld.navitime.jp
    + @@||policies.google.com
      @@||pool.ntp.org
      @@||postserve.trafficmanager.net
    + @@||povo.jp
      @@||pp3-sdk-api.profilepassport.jp
      @@||pp3-sdkdata-v2.profilepassport.jp
    + @@||prcdn.freetls.fastly.net
      @@||prd-real.card-type-message-wlb.verda2.akadns.net
      @@||president.jp
      @@||probe.twitter.com

      @@ -491,6 +684,9 @@

      @@||prod-fastly-ap-northeast-1.video.pscp.tv
      @@||prod-socket.pokapoka-farm.com
      @@||prod.globalsign.map.fastly.net
    + @@||productreviews.shopifycdn.com
    + @@||productreviews.shopifycdn.com.lan
    + @@||productreviews.shopifycdn.com.ts.net
      @@||profile.yoshimoto.co.jp
      @@||proton.me
      @@||protonvpn.com

      @@ -505,6 +701,7 @@

      @@||push-signal.paypay.ne.jp
      @@||push-signal.paypay.ne.jp.lan
      @@||push.clients6.google.com
    + @@||pwjp.hantogames.com
      @@||qiita-official-contents.imgix.net
      @@||qiita-organization-images.imgix.net
      @@||qiita-user-contents.imgix.net

      @@ -515,10 +712,14 @@

      @@||radiomap.vcdn.pos.here.com
      @@||rainradar.smartnews.com
      @@||realtimesupport.clients6.google.com
    + @@||recoverit.wondershare.com
    + @@||recoverit.wondershare.jp
      @@||recruitrikunabinext.demdex.net
    + @@||refinery.amanotes.io
      @@||reiwa-shinsengumi.com
      @@||remotedesktop.google.com
      @@||reports.proton.me
    + @@||res.adx.opera.com.ts.net
      @@||restapi-chat-management.ppcd-support.jp
      @@||retty.me
      @@||ropng.img.sus-game.com

      @@ -530,10 +731,14 @@

      @@||s-part-0018.t-0009.t-msedge.net
      @@||s-part-0019.t-0009.fb-t-msedge.net
      @@||s-part-0019.t-0009.t-msedge.net
    + @@||s.hatena.ne.jp
      @@||s.pximg.net
      @@||s.w.org
      @@||s.wordpress.com
    + @@||s.youtube.com
    + @@||s.youtube.com.ts.net
      @@||s.ytimg.com
    + @@||s.zeptolab.com
      @@||s0.wp.com
      @@||s1.nordcdn.com
      @@||s3.ap-northeast-1.amazonaws.com

      @@ -543,12 +748,16 @@

      @@||sb-ssl.google.com
      @@||sb.nordcdn.com
      @@||sc-static.net
    + @@||scontent.cdninstagram.com.lan
    + @@||scontent.cdninstagram.com.ts.net
      @@||screw.ttzgame.com
      @@||sdk.hellouniweb.com
    + @@||sdk.privacy-center.org
      @@||sdk.rum.aliyuncs.com
      @@||seal.digicert.com
      @@||seal.globalsign.com
      @@||secure.globalsign.com
    + @@||secure.xsolla.com
      @@||securl.nu
      @@||selfs.dai-ichi-life.co.jp
      @@||services.virtusize.jp

      @@ -559,24 +768,35 @@

      @@||shakkin-soudan-madoguchi.com
      @@||shed.dual-low.s-part-0018.t-0009.t-msedge.net
      @@||shed.dual-low.s-part-0019.t-0009.t-msedge.net
    + @@||shepherd.avcdn.net.lan
    + @@||shepherd.avcdn.net.ts.net
      @@||shepherd.ff.avast.com
      @@||shepherd.sb.avast.com
      @@||shepherd.sb.avast.com.lan
      @@||shiorio.com
      @@||shop.adidas.jp
      @@||shop.gofuku-ishihara.com
    + @@||sirok.jp
    + @@||sl.skyflag.jp
      @@||smartnews-assets.s3.ap-northeast-1.amazonaws.com
    + @@||smt.docomo.ne.jp
      @@||sn-proxy.smartnews.com
      @@||sodium.slp.pos.here.com
      @@||sodium.slp.pos.here.com.lan
    + @@||soudan-go.jp
    + @@||souko-katsuo.com
      @@||source.pixiv.net
      @@||sourcenext-recommend.data-lab-pg.com
      @@||sp-*.apkrep.avcdn.net
      @@||sp-*.apkrep.avcdn.net.lan
      @@||sp-*.honzik.avcdn.net
      @@||sp-*.honzik.avcdn.net.lan
    + @@||sp-ao.shortpixel.ai
      @@||sp-trk.com
    + @@||sp.gmossp-sp.jp
      @@||special.sankei.com
    + @@||spt.saygames.io
    + @@||src.doda.jp
      @@||ssai-manifest.streaks.jp
      @@||ssai-variants.streaks.jp
      @@||ssai.api.streaks.jp

      @@ -595,12 +815,20 @@

      @@||static.cookpad.com
      @@||static.es.cyberowl.jp
      @@||static.line.naver.jp
    + @@||static.makuake.com
      @@||static.media.cld.navitime.jp
    + @@||static.mixerbox.com
      @@||static.newsapp.nhk.or.jp
    + @@||static.parastorage.com
      @@||static.paypay.ne.jp
    + @@||static.wixstatic.com
    + @@||stats.playrix.com
      @@||stats.wp.com
      @@||status.itmedia.co.jp
    + @@||stbtoken.sps-system.com
      @@||steampowered.com
    + @@||steering-manifest.streaks.jp
    + @@||storage.radiotalk.jp
      @@||stream-log.profilepassport.jp
      @@||sundry-f-net.trafficmanager.net
      @@||supply-inmobicdn-net-tm.trafficmanager.net

      @@ -621,10 +849,19 @@

      @@||tig-contents.com
      @@||time.windows.com
      @@||timecheck.imanara.jp
    + @@||times-abema.ismcdn.jp
    + @@||tls13.taboola.map.fastly.net
      @@||toi.kuronekoyamato.co.jp
    + @@||token.sps-system.com
      @@||ton.twimg.com
    + @@||topics-smt-docomo-ne-jp.cdn.ampproject.org
    + @@||topics.smt.docomo.ne.jp
    + @@||tosidennsetu02.up.seesaa.net
    + @@||township-ios.playrix.com
    + @@||township.playrix.com
      @@||tr.api.itmedia.co.jp
      @@||tracks.streaks.jp
    + @@||traffic.omny.fm
      @@||translate.google.com
      @@||travel.navitime.com
      @@||tsutaeru.cloud

      @@ -638,6 +875,10 @@

      @@||twincle.schanbeauty.com
      @@||twoucan.com
      @@||tx.lbg.play.naver.jp
    + @@||typesquare.com
    + @@||uinfo6.playrix.com
    + @@||uinfo6.playrix.com.lan
    + @@||uinfo6.playrix.com.ts.net
      @@||unpkg.com
      @@||update.code.visualstudio.com
      @@||upload.wikimedia.org

      @@ -646,12 +887,14 @@

      @@||use.fontawesome.com
      @@||use.typekit.net
      @@||user-photo.paypay.ne.jp
    + @@||usercss.blog.st-hatena.com
      @@||users.app-box.jp
      @@||v0.wordpress.com
      @@||variants.streaks.jp
      @@||vastproxy-brand-inmobi-comtm.trafficmanager.net
      @@||vday.io
      @@||vec-adm-rain.newsapp.nhk.or.jp
    + @@||video-converter.com
      @@||video-downloads.googleusercontent.com
      @@||video-ft.twimg.com
      @@||video-s.twimg.com

      @@ -661,15 +904,26 @@

      @@||video.twimg.com
      @@||video.twimg.com.lan
      @@||virtualcurrency.kairogame.jp
    + @@||vita-mahjong-api.dailyinnovation.biz
    + @@||vitamahjong.s3.amazonaws.com
    + @@||vod-stream.nhk.jp
      @@||vod-tver-*.streaks.jp
      @@||voguecrew.net
      @@||voi.0101.co.jp
      @@||vpncdn.protonweb.com
    + @@||w010.touken-ranbu.jp
    + @@||w012.touken-ranbu.jp.lan
      @@||waa-pa.clients6.google.com
      @@||wallet.google.com
      @@||wallet.yay.space
      @@||web-api.nordvpn.com
      @@||web-api.tapon.com
    + @@||web.api.cmoa.jp
    + @@||web.bp-app.jp
    + @@||web.map-m.com
    + @@||webagent.bedore.jp
    + @@||webfont.fontplus.jp
    + @@||webfonts.xserver.jp
      @@||websocket.paypay.ne.jp
      @@||widgets.twimg.com
      @@||widgets.twimg.com.lan

      @@ -677,27 +931,33 @@

      @@||work.fife.usercontent.google.com
      @@||workspace.google.com
      @@||worldaz.relay.teams.trafficmanager.net
    + @@||worldtimeapi.org
      @@||www-famitsu-com.cdn.ampproject.org
    + @@||www-nenrei--hayami-net.cdn.ampproject.org
      @@||www.123chat.jp
      @@||www.666-666.jp
      @@||www.adidas.jp
      @@||www.agrinews.co.jp
      @@||www.amazon.co.jp
    + @@||www.ann-kate.jp
      @@||www.asahibeer-cp.jp
      @@||www.bing.com
      @@||www.broadcom.com.cdn.cloudflare.net
      @@||www.cecile.co.jp
      @@||www.city.kami.lg.jp
    + @@||www.cmoa.jp
      @@||www.dai-ichi-life.co.jp
      @@||www.dropbox.com
      @@||www.ehimeshiryo.com
      @@||www.ekiten.jp
      @@||www.esupply.co.jp
      @@||www.expressvpn.com
    + @@||www.fondesk.jp
      @@||www.fujitv.co.jp
      @@||www.gl-inet.com
      @@||www.goodnovel.com
      @@||www.google.co.jp
    + @@||www.google.com.ts.net
      @@||www.google.us
      @@||www.google.us.lan
      @@||www.googleadservices.com

      @@ -711,6 +971,7 @@

      @@||www.jtb.co.jp
      @@||www.juststarz.com
      @@||www.kanochat.jp
    + @@||www.keepersecurity.com
      @@||www.kensei-online.com
      @@||www.keycolle.jp
      @@||www.kfc.co.jp

      @@ -718,30 +979,37 @@

      @@||www.kochinews.co.jp
      @@||www.kojima.net
      @@||www.komeri.com
    + @@||www.konoka-ky.jp
      @@||www.kurashiru.com
      @@||www.kusurinomadoguchi.com
      @@||www.lady-drug.co.jp
      @@||www.lawson.co.jp
      @@||www.lifemag.jp
    + @@||www.lofter.com
      @@||www.merupero.com
      @@||www.monotaro.com
      @@||www.navitime.co.jp
      @@||www.newsapp.nhk.or.jp
    + @@||www.nexters.com
      @@||www.nhk.or.jp
      @@||www.niid.jihs.go.jp
      @@||www.nijiyome.com
      @@||www.nijiyome.jp
      @@||www.nikkei.com
      @@||www.nitori-net.jp
    + @@||www.omnycontent.com
      @@||www.onamae.com
    + @@||www.paypal.com
      @@||www.paypay-card.co.jp
      @@||www.paypay.ne.jp
      @@||www.pixiv.net
      @@||www.rd.ntt
      @@||www.recaptcha.net
    + @@||www.sagawa-exp.co.jp
      @@||www.sankei.com
      @@||www.shikoku.co.jp
      @@||www.shingakunavi.ne.jp
    + @@||www.skylark.co.jp
      @@||www.smartnews.be
      @@||www.smartwaon.com
      @@||www.sourcenext.com

      @@ -749,12 +1017,18 @@

      @@||www.threads.net
      @@||www.tm.ak.prd.aadg.trafficmanager.net
      @@||www.topvalu.net
    + @@||www.touken-ranbu.jp
    + @@||www.town.kahoku.yamagata.jp
    + @@||www.trendmicro.com
    + @@||www.trendmicro.de
      @@||www.tsuruha-group.com
      @@||www.tsuruha-hd.com
    + @@||www.twitter.com
      @@||www.virustotal.com
      @@||www.vmware.com
      @@||www.wattpad.com
      @@||www.wikipedia.org
    + @@||www.wondershare.com
      @@||www.yonden.co.jp
      @@||www.youtube.com
      @@||www.zakzak.co.jp

      @@ -769,9 +1043,11 @@

      @@||xvdrop.imgix.net
      @@||xvp.imgix.net
      @@||yamato-hd.co.jp
    + @@||yandex.com
      @@||yandex.ru
      @@||yapp.li
      @@||yasurok2.wordpress.com
    + @@||yield-manager.browsiprod.com
      @@||yorozu-kochi.go.jp
      @@||youtu.be
      @@||yt3.ggpht.com

      @@ -780,6 +1056,7 @@

      @@||yururi2019.com
      @@||za.tapon.com
      @@||zapgo.org
    + @@||zeus-api.p-c3-e.abema-tv.com
      @@||zozo.jp

      # [アンチ広告ブロッカー／Ad-Shield]
    ```

- reject/Reject_domain.txt
    ```yaml
    BEFORE:
      # References: none
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/reject/Reject_domain.txt
      #
    - # Last modified: 11 November 2025
      #

      # [拒否リクエスト]

      @@ -19,8 +19,13 @@

      ||*.c.appier.net.akadns.net
      ||*.c.appier.net.lan
      ||*.fls.doubleclick.net
      0.0.0.0 1x1.a-mo.net
      0.0.0.0 3ppa.jp.cinarra.com
      0.0.0.0 a6.smartnews-ads.com
      0.0.0.0 aax-dtb-mobile-geo.amazon-adsystem.com
      0.0.0.0 aax-eu.amazon-adsystem.com

      @@ -29,20 +34,27 @@

      0.0.0.0 aax-fe-sin.amazon-adsystem.com.lan
      0.0.0.0 aax-fe.amazon-adsystem.com
      0.0.0.0 aax-fe.amazon-adsystem.com.lan
      0.0.0.0 aax-us-east.amazon-adsystem.com
      0.0.0.0 aax-us.amazon-adsystem.com
      0.0.0.0 aax.amazon-adsystem.com
      0.0.0.0 aax.amazon-adsystem.com.lan
      0.0.0.0 ac.pe-k.site
      0.0.0.0 accounts.doubleclick.net
      0.0.0.0 acdn.adnxs.com
      0.0.0.0 acdn.adnxs.com.lan
      0.0.0.0 ad-nex.com.lan
      0.0.0.0 ad-proxy-reward-rakuten-co-jp.gslb.rdcnw.net
      0.0.0.0 ad.adsrvr.org
      0.0.0.0 ad.appier.net
      0.0.0.0 ad.doubleclick.net
      0.0.0.0 ad.doubleclick.net.lan
      0.0.0.0 ad.ust-ad.com
      0.0.0.0 adclick.g.doubleclick.net
      0.0.0.0 ade.clmbtech.com

      @@ -54,13 +66,19 @@

      0.0.0.0 adm.dsp.cartajp.com
      0.0.0.0 admanmedia.com
      0.0.0.0 adone.yicha.jp
      0.0.0.0 ads.adjust-net.jp.lan
      0.0.0.0 ads.mythad.com
      0.0.0.0 adservice.google.co.jp
      0.0.0.0 adservice.google.com
      0.0.0.0 advisionweb.yicha.jp
      0.0.0.0 advtrack.yicha.jp
      0.0.0.0 adx-tk.mtgglobals.com
      0.0.0.0 adx.g.doubleclick.net
      0.0.0.0 adx.g.doubleclick.net.lan
      0.0.0.0 adx.opera.com

      @@ -71,28 +89,48 @@

      0.0.0.0 afs.googleusercontent.com
      0.0.0.0 aggregator.service.usercentrics.eu.lan
      0.0.0.0 aid.send.microad.jp
      0.0.0.0 am.moduleapps.com
      0.0.0.0 am.moduleapps.com.lan
      0.0.0.0 am.yahoo.co.jp
      0.0.0.0 analytics-tcp.mtgglobals.com
      0.0.0.0 analytics.adjust.com
      0.0.0.0 analytics.adjust.net.in
      0.0.0.0 analytics.adjust.world
      0.0.0.0 analytics.app-adforce.jp
      0.0.0.0 analytics.gamezen.org
      0.0.0.0 analytics.google.com
      0.0.0.0 ape-androids.isappcloud.com
      0.0.0.0 ape-androids.isappcloud.com.lan
      0.0.0.0 api-events.eventstracker.io
      0.0.0.0 api-fe.supnovel.com
      0.0.0.0 api-sdk-tracking.beaconbank.jp
      0.0.0.0 api-sdk.beaconbank.jp
      0.0.0.0 api-sdk.beaconbank.jpapi-sdk.beaconbank.jp
      0.0.0.0 api.bidmachine.io
      0.0.0.0 api.btrbdf.com
      0.0.0.0 api.bytegle.site
      0.0.0.0 api.flipdesk.jp
      0.0.0.0 api.gameanalytics.com
      0.0.0.0 api.onegg.site
      0.0.0.0 api.reproio.com
      0.0.0.0 api.rpdt.net

      @@ -101,6 +139,12 @@

      0.0.0.0 api.snapx.info
      0.0.0.0 api.synapse-kddi.net
      0.0.0.0 api.synapse-kddi.net.lan
      0.0.0.0 api2.branch.io
      0.0.0.0 api3.4dvertible.com
      0.0.0.0 apis.naver.com

      @@ -114,19 +158,23 @@

      0.0.0.0 app.adjust.com.lan
      0.0.0.0 app.adjust.com.tail06b0f8.ts.net
      0.0.0.0 app.adjust.io
      0.0.0.0 app.adjust.net.in
      0.0.0.0 app.adjust.net.in.lan
      0.0.0.0 app.adjust.net.in.tail06b0f8.ts.net
      0.0.0.0 app.adjust.world
      0.0.0.0 app.adjust.world.lan
      0.0.0.0 app.dialogone.jp
      0.0.0.0 app.publer.com
      0.0.0.0 app.publer.io
      0.0.0.0 appsrv.display.io
      0.0.0.0 arg.atomex.net
      0.0.0.0 arm.appiersig.com
      0.0.0.0 arm.appiersig.com.akadns.net
      0.0.0.0 arm.appiersig.com.lan
      0.0.0.0 asia-seoul-statistics.tpmn.io
      0.0.0.0 asia.adform.net
      0.0.0.0 asia.seadform.net

      @@ -141,26 +189,36 @@

      0.0.0.0 atm.im-apps.net
      0.0.0.0 audiencedata.im-apps.net
      0.0.0.0 audiencedata.im-apps.net.lan
      0.0.0.0 automate-frontend.linksynergy.com
      0.0.0.0 automate-k8s.linksynergy.com
      0.0.0.0 automate.linksynergy.com
      0.0.0.0 aws.inshot.cc
      0.0.0.0 az416426.vo.msecnd.net
      0.0.0.0 b.adnxs.com
      0.0.0.0 b.im-apps.net
      0.0.0.0 b.logly.co.jp
      0.0.0.0 b.logly.co.jp.lan
      0.0.0.0 b.sharethrough.com
      0.0.0.0 b1.nel.goog
      0.0.0.0 b6.im-apps.net
      0.0.0.0 bam.nr-data.net
      0.0.0.0 bid.g.doubleclick.net
      0.0.0.0 bid.ssp.bance.jp
      0.0.0.0 bidcontext-us.bidmachine.io
      0.0.0.0 bm.moduleapps.com
      0.0.0.0 booster.reproio.com
      0.0.0.0 bs.karte.io
      0.0.0.0 bs.nakanohito.jp
      0.0.0.0 c.amazon-adsystem.com
      0.0.0.0 c.amazon-adsystem.com.lan
      0.0.0.0 c.amazon-adsystem.com.tail06b0f8.ts.net

      @@ -182,8 +240,11 @@

      0.0.0.0 cdn-adn-https.mtgglobals.com
      0.0.0.0 cdn-adn-https.mtgglobals.com.lan
      0.0.0.0 cdn-blocks.karte.io
      0.0.0.0 cdn-creatives.adikteev.com
      0.0.0.0 cdn-f.adsmoloco.com
      0.0.0.0 cdn-logly-co-jp.cdn.ampproject.org
      0.0.0.0 cdn.4dvertible.com
      0.0.0.0 cdn.adnxs.com

      @@ -191,58 +252,86 @@

      0.0.0.0 cdn.adsafeprotected.com
      0.0.0.0 cdn.atomex.net
      0.0.0.0 cdn.branch.io
      0.0.0.0 cdn.cquotient.com
      0.0.0.0 cdn.ihappyread.com
      0.0.0.0 cdn.jampp.com
      0.0.0.0 cdn.judge.me
      0.0.0.0 cdn.liftoff.io
      0.0.0.0 cdn.logly.co.jp
      0.0.0.0 cdn.logly.co.jp.lan
      0.0.0.0 cdn.microad.jp
      0.0.0.0 cdn.microad.jp.lan
      0.0.0.0 cdn.microad.jp.wtxcdn.com
      0.0.0.0 cdn.reproio.com
      0.0.0.0 cdn.speedcurve.com
      0.0.0.0 cdn1.judge.me
      0.0.0.0 cdn3.hsrdkt.com
      0.0.0.0 cdnwidget.judge.me
      0.0.0.0 cf-assets.synapse-kddi.net
      0.0.0.0 cf-images.ap-northeast-1.prod.boltdns.net
      0.0.0.0 cf.im-apps.net
      0.0.0.0 check-tcp.mtgglobals.com
      0.0.0.0 check-tcp.rayjump.com.lan
      0.0.0.0 checkout-api.worldshopping.jp
      0.0.0.0 cip.ust-adc.com
      0.0.0.0 cksync.yahoo.co.jp
      0.0.0.0 classify-app-sg.allawnos.com
      0.0.0.0 clb.yahoo.co.jp
      0.0.0.0 click.liftoff.io
      0.0.0.0 cloudinary-res.isappcloud.com
      0.0.0.0 cm-11451.csolution.jp
      0.0.0.0 cm-beacon.nakanohito.jp
      0.0.0.0 cm-widget.nakanohito.jp
      0.0.0.0 cm.adform.net
      0.0.0.0 cm.g.doubleclick.net
      0.0.0.0 cm.g.doubleclick.net.lan
      0.0.0.0 component-ota-sg.allawnos.com
      0.0.0.0 conduit.branch.io
      0.0.0.0 config.aps.amazon-adsystem.com
      0.0.0.0 configure-tcp-android.mtgglobals.com
      0.0.0.0 configure-tcp-android.mtgglobals.com.lan
      0.0.0.0 configure-tcp-ios.mtgglobals.com
      0.0.0.0 configure-tcp.mtgglobals.com
      0.0.0.0 configure-tcp.rayjump.com.lan
      0.0.0.0 configure.mtgglobals.com
      0.0.0.0 configure.mtgglobals.com.lan
      0.0.0.0 conn-service-us-04.allawnos.com
      0.0.0.0 conn-service-us-04.allawnos.com.lan
      0.0.0.0 conn-service-us-05.allawnos.com
      0.0.0.0 conn-service-us-05.allawnos.com.lan
      0.0.0.0 connectid.analytics.yahoo.com
      0.0.0.0 consent-api.service.consent.usercentrics.eu
      0.0.0.0 consent.adjust.com
      0.0.0.0 consent.adjust.io
      0.0.0.0 consent.adjust.net.in
      0.0.0.0 content.cdn.personaly.bid
      0.0.0.0 control.smbeat.jp
      0.0.0.0 control.smbeat.jp.lan

      @@ -250,15 +339,24 @@

      0.0.0.0 crashlyticsreports-pa.googleapis.com.lan
      0.0.0.0 crcdn01.adnxs.com
      0.0.0.0 creative-bunny.bidease.com
      0.0.0.0 creative.bidease.com
      0.0.0.0 creative.cdnyeah.com
      0.0.0.0 creative.dsp.cartajp.com
      0.0.0.0 creative.smartnews-ads.com
      0.0.0.0 cs.ademon.net
      0.0.0.0 cs.admanmedia.com
      0.0.0.0 cs.admanmedia.com.lan
      0.0.0.0 cs.advortex.cloud
      0.0.0.0 cs.nakanohito.jp
      0.0.0.0 cta.bidmachine.io
      0.0.0.0 cv.dsp.reemo-ad.jp
      0.0.0.0 d-cache.microad.jp

      @@ -266,14 +364,18 @@

      0.0.0.0 d-track.send.microad.jp
      0.0.0.0 d.adroll.com
      0.0.0.0 d.adroll.com.lan
      0.0.0.0 data.adsrvr.org
      0.0.0.0 data.flurry.com
      0.0.0.0 data.flurry.com.lan
      0.0.0.0 dcape-na.amazon.com
      0.0.0.0 dcdn.adnxs.com
      0.0.0.0 dcg.microsoft.com
      0.0.0.0 dcg.microsoft.com.lan
      0.0.0.0 deapi.funsdata.com
      0.0.0.0 dev.visualwebsiteoptimizer.com
      0.0.0.0 direct.adsrvr.org
      0.0.0.0 dmp.adform.net

      @@ -282,7 +384,10 @@

      0.0.0.0 dmp.im-apps.net.lan
      0.0.0.0 doubleclick.net
      0.0.0.0 doubleclick.net.lan
      0.0.0.0 dr-gate-city-heaven-v2.shinobi.jp
      0.0.0.0 dsb.yahoo.co.jp
      0.0.0.0 dsb.yahooapis.jp
      0.0.0.0 dsb.yahooapis.jp.lan

      @@ -291,34 +396,57 @@

      0.0.0.0 dsp-static.clickhubs.com
      0.0.0.0 dsp-trk.eskimi.com
      0.0.0.0 dsp-trvm.eskimi.com
      0.0.0.0 dt.adsafeprotected.com
      0.0.0.0 dt.adsafeprotected.com.lan
      0.0.0.0 dynamic-yda.c.yimg.jp
      0.0.0.0 dynamic2-ydn.c.yimg.jp
      0.0.0.0 e.axon.ai
      0.0.0.0 e.axon.ai.lan
      0.0.0.0 e.cquotient.com
      0.0.0.0 ec-concier.com
      0.0.0.0 edayo.ademon.net
      0.0.0.0 edayo.istact.jp
      0.0.0.0 edge.safedk.com
      0.0.0.0 edge.safedk.com.lan
      0.0.0.0 enduser.adsrvr.org
      0.0.0.0 eu.mclean.50union.com
      0.0.0.0 eu.mvconf.50union.com
      0.0.0.0 eu.mvconf.50union.com.lan
      0.0.0.0 event-action.popinfo.jp
      0.0.0.0 events-sgp.bidder.kayzen.io
      0.0.0.0 events.popinfo.jp
      0.0.0.0 fourier-videoclip-sg.allawnos.com
      0.0.0.0 fp-dev.webapp.163.com
      0.0.0.0 free2.apkzonic.com
      0.0.0.0 fw.adsafeprotected.com
      0.0.0.0 g.alicdn.com
      0.0.0.0 g.doubleclick.net.lan
      0.0.0.0 g.doubleclick.net.tail06b0f8.ts.net
      0.0.0.0 gateway.instagram.com
      0.0.0.0 gateway.instagram.com.lan
      0.0.0.0 gcmast-cdn.goldspotmedia.com
      0.0.0.0 gcmast-cdn.goldspotmedia.com.lan
      0.0.0.0 gdl.news-cdn.site

      @@ -334,33 +462,46 @@

      0.0.0.0 gntm.geeen.co.jp
      0.0.0.0 googleads.g.doubleclick.net
      0.0.0.0 googleads.g.doubleclick.net.lan
      0.0.0.0 googleads4.g.doubleclick.net
      0.0.0.0 googleads4.g.doubleclick.net.lan
      0.0.0.0 graphql.usercentrics.eu
      0.0.0.0 grp15-ias-rakuten-co-jp.rdcnw.net.akadns.net
      0.0.0.0 gsspat.jp.lan
      0.0.0.0 gui-server-sg.allawnos.com
      0.0.0.0 gw.geoedge.be
      0.0.0.0 h.accesstrade.net
      0.0.0.0 hermes-api.learnings.ai
      0.0.0.0 hk-cdn.youngle.tech
      0.0.0.0 hw.zuimeitianqi.com
      0.0.0.0 hybird.mtgglobals.com
      0.0.0.0 i.pinimgproxy.com
      0.0.0.0 i18n.mclean.50union.com
      0.0.0.0 i18n.mclean.50union.com.lan
      0.0.0.0 ib.adnxs.com
      0.0.0.0 ib.adnxs.com.lan
      0.0.0.0 ib.isappcloud.com
      0.0.0.0 ib.isappcloud.com.lan
      0.0.0.0 ib.sin1.geoadnxs.com
      0.0.0.0 icosa-service-sg-01.allawnos.com
      0.0.0.0 icosa-service-sg.allawnos.com
      0.0.0.0 id.geistm.com
      0.0.0.0 id.geistm.com.lan
      0.0.0.0 id5-sync.com
      0.0.0.0 im.c.yimg.jp
      0.0.0.0 im.c.yimg.jp.lan
      0.0.0.0 images.microcms-assets.io
      0.0.0.0 imasdk.googleapis.com
      0.0.0.0 img-cf.karte.io

      @@ -376,6 +517,7 @@

      0.0.0.0 imp-bidapi.i-mobile.co.jp
      0.0.0.0 imp-lb-us2.jampp.com
      0.0.0.0 imp-ru-ap.jampp.com
      0.0.0.0 imp.dynalyst.jp
      0.0.0.0 imp.u.send.microad.jp
      0.0.0.0 impression-ap.adikteev.com

      @@ -389,14 +531,20 @@

      0.0.0.0 insight.adsrvr.org
      0.0.0.0 instaapi.zagtechnology.com
      0.0.0.0 intake-analytics.wikimedia.org
      0.0.0.0 iota702.rtb.appier.net
      0.0.0.0 ip-api.com
      0.0.0.0 ipds.opr.adx.opera.com
      0.0.0.0 ittpx.eskimi.com
      0.0.0.0 j.microad.net
      0.0.0.0 j.microad.net.wcdnga.com
      0.0.0.0 jp-col-ext.nelo.navercorp.com
      0.0.0.0 jp-col-ext.nelo.navercorp.com.lan
      0.0.0.0 jp1-bid.adsrvr.org
      0.0.0.0 js-agent.newrelic.com
      0.0.0.0 js.ad-stir.com

      @@ -407,9 +555,13 @@

      0.0.0.0 js.dsp.cartajp.com
      0.0.0.0 js.dsp.cartajp.com.lan
      0.0.0.0 js.dsp.reemo-ad.jp
      0.0.0.0 js.istact.jp
      0.0.0.0 js.ptengine.jp
      0.0.0.0 js.ssp.bance.jp
      0.0.0.0 kapetracking.com
      0.0.0.0 kenga.tech
      0.0.0.0 kr-col-ext.nelo.navercorp.com

      @@ -418,11 +570,20 @@

      0.0.0.0 lax1-ib.adnxs.com
      0.0.0.0 lazy-tcp.mtgglobals.com
      0.0.0.0 lazy-tcp.rayjump.com.lan
      0.0.0.0 lf-cdn.coze.cn
      0.0.0.0 log.mmstat.com
      0.0.0.0 log.radiko.jp
      0.0.0.0 log2.radiko.jp
      0.0.0.0 logql.yahoo.co.jp
      0.0.0.0 lt.logly.co.jp
      0.0.0.0 m.adnxs.com
      0.0.0.0 m.adnxs.com.lan

      @@ -430,14 +591,21 @@

      0.0.0.0 ma2file.moduleapps.com
      0.0.0.0 mads.amazon-adsystem.com
      0.0.0.0 mads.amazon-adsystem.com.lan
      0.0.0.0 masspush-cdn.karte.io
      0.0.0.0 match.adsrvr.org
      0.0.0.0 match.adsrvr.org.lan
      0.0.0.0 materials.admaster.cc
      0.0.0.0 maxcdn.bootstrapcdn.com
      0.0.0.0 media.dpdvx.com
      0.0.0.0 micres.cyberowl.jp
      0.0.0.0 microad.net
      0.0.0.0 mirror2.karte.io
      0.0.0.0 mobile-collector.newrelic.com
      0.0.0.0 mobile-collector.newrelic.com.lan

      @@ -451,20 +619,26 @@

      0.0.0.0 mt-usw.appiersig.com.lan
      0.0.0.0 mtg-h5.mtgglobals.com
      0.0.0.0 mtg-h5.mtgglobals.com.lan
      0.0.0.0 mtg-native.mtgglobals.com
      0.0.0.0 mtrack.mtgglobals.com
      0.0.0.0 nam.veta.naver.com
      0.0.0.0 nam.veta.naver.com.lan
      0.0.0.0 nelo2-col.navercorp.com
      0.0.0.0 nelo2-col.navercorp.com.lan
      0.0.0.0 net-sg-gcp-cdn.mtgglobals.com
      0.0.0.0 net-sg.mtgglobals.com
      0.0.0.0 net-vg-cdn.mtgglobals.com
      0.0.0.0 net-vg.mtgglobals.com
      0.0.0.0 netdna.bootstrapcdn.com
      0.0.0.0 newplayable.mintegral.com
      0.0.0.0 nl-gcp-ad-track-sdk-europe-west4-b.mtgglobals.com
      0.0.0.0 node.aibeacon.jp
      0.0.0.0 notifications-gke-sdk-bidding-b.fyber.com
      0.0.0.0 notifications-gke-sdk-bidding-canary.fyber.com
      0.0.0.0 notifications-gke-sdk-bidding.fyber.com

      @@ -472,28 +646,43 @@

      0.0.0.0 nt-compass-fit-jp.logly.co.jp
      0.0.0.0 ntp.sjtu.edu.cn
      0.0.0.0 ntracker-collector.naver.com
      0.0.0.0 ny-event.personaly.bid
      0.0.0.0 nym1-ib.adnxs.com
      0.0.0.0 ob.cityrobotflower.com
      0.0.0.0 observe-tcp.mtgglobals.com
      0.0.0.0 opr.adx.opera.com
      0.0.0.0 ota-recruit-sg.allawnos.com
      0.0.0.0 outspot-ams-vip3.op-mobile.opera.com
      0.0.0.0 outspot2-ams.adx.opera.com
      0.0.0.0 p11.techlab-cdn.com
      0.0.0.0 pagead2.googlesyndication.com
      0.0.0.0 pidm.moduleapps.com
      0.0.0.0 ping.chartbeat.net
      0.0.0.0 pixel.adsafeprotected.com
      0.0.0.0 pixel.everesttech.net
      0.0.0.0 pl-point.mtgglobals.com
      0.0.0.0 play.mtgglobals.com
      0.0.0.0 playable-stats.mindworks-creative.com
      0.0.0.0 playable.mintegral.com.lan
      0.0.0.0 pm.yahoo.co.jp
      0.0.0.0 pm.yahoo.jp
      0.0.0.0 policy-tcp.mtgglobals.com
      0.0.0.0 policy-tcp.rayjump.com.lan
      0.0.0.0 poplink-f.probo.biz
      0.0.0.0 pp3-sdkdata-v2-ut.profilepassport.jp
      0.0.0.0 pr-bh.ybp.yahoo.com

      @@ -501,20 +690,25 @@

      0.0.0.0 prebid.a-mo.net
      0.0.0.0 prebid.a-mo.net.lan
      0.0.0.0 prebid.adnxs.com
      0.0.0.0 production-04-gcp-gateway.karte.io
      0.0.0.0 pubads.g.doubleclick.net
      0.0.0.0 pubads.g.doubleclick.net.lan
      0.0.0.0 pubsub.googleapis.com
      0.0.0.0 pubsub.googleapis.com.lan
      0.0.0.0 radar.cedexis.com
      0.0.0.0 rapids.rpdt.net
      0.0.0.0 rcm-fe.amazon-adsystem.com
      0.0.0.0 rcv.ust-ad.com
      0.0.0.0 rd.dynalyst.jp
      0.0.0.0 res.adx.opera.com
      0.0.0.0 research-image-itmedia-co-jp.cdn.ampproject.org
      0.0.0.0 resource5-cdn.ocolt.com
      0.0.0.0 resource5-cdn.ocolt.com.lan
      0.0.0.0 router.miwifi.com
      0.0.0.0 router.miwifi.com.lan
      0.0.0.0 rpt.cedexis.com

      @@ -535,31 +729,56 @@

      0.0.0.0 s.alicdn.com.w.cdngslb.com
      0.0.0.0 s.amazon-adsystem.com
      0.0.0.0 s.amazon-adsystem.com.lan
      0.0.0.0 s.logly.co.jp
      0.0.0.0 s.update.adsrvr.org
      0.0.0.0 s0.2mdn.net
      0.0.0.0 s0.sgpstatp.com
      0.0.0.0 s1.adform.net
      0.0.0.0 s2.adform.net
      0.0.0.0 s2s.adjust.com
      0.0.0.0 sau-server-sg.allawnos.com
      0.0.0.0 sb-tama-ran.musthave-magazine.tokyo
      0.0.0.0 score.im-apps.net
      0.0.0.0 scripts.im-apps.net
      0.0.0.0 sdk-api.maticooads.com
      0.0.0.0 sdk-api.maticooads.com.lan
      0.0.0.0 se-setting-tcp.mtgglobals.com
      0.0.0.0 sea1-sync.a-mo.net
      0.0.0.0 secure.adnxs.com
      0.0.0.0 secure.adnxs.com.lan
      0.0.0.0 securepubads.g.doubleclick.net
      0.0.0.0 sentry-prod.branch.io
      0.0.0.0 server.jp1media.com
      0.0.0.0 sg-ali-ad-track-sdk.mtgglobals.com
      0.0.0.0 sg-allmusic-api-adv.allsaints.tv
      0.0.0.0 sg-event.personaly.bid
      0.0.0.0 sg-new-ssplib-hb.mtgglobals.com
      0.0.0.0 sg-new-ssplib-hb.mtgglobals.com.lan
      0.0.0.0 sg-setting-tcp.mtgglobals.com
      0.0.0.0 sg-trk.bluevoox.com
      0.0.0.0 sg-trk2.bluevoox.com

      @@ -574,12 +793,16 @@

      0.0.0.0 skadnetworks.fyber.com
      0.0.0.0 so.tpocdm.com
      0.0.0.0 socdm.com
      0.0.0.0 spdmg2.i-mobile.co.jp
      0.0.0.0 spimgv1.i-mobile.co.jp
      0.0.0.0 spnativeapi-direct.i-mobile.co.jp
      0.0.0.0 spnativeapi-tls.i-mobile.co.jp
      0.0.0.0 spnativeapi-tls.i-mobile.co.jp.lan
      0.0.0.0 spnativeapi.i-mobile.co.jp
      0.0.0.0 ss-jp2.appiersig.com
      0.0.0.0 ss-jp2.appiersig.com.lan
      0.0.0.0 ss-sg.appiersig.com

      @@ -588,19 +811,24 @@

      0.0.0.0 ss-sg2.appiersig.com.akadns.net
      0.0.0.0 ss-use.appiersig.com
      0.0.0.0 ss-use.appiersig.com.akadns.net
      0.0.0.0 ssp-bidapi.i-mobile.co.jp
      0.0.0.0 ssp.img-static.tech
      0.0.0.0 ssp.send.microad.jp
      0.0.0.0 ssp.send.microad.jp.lan
      0.0.0.0 ssstwo.com
      0.0.0.0 ssyoutube.com
      0.0.0.0 st.shinobi.jp
      0.0.0.0 st.shinobi.jp.lan
      0.0.0.0 stackpath.bootstrapcdn.com
      0.0.0.0 stage-e.axon.ai
      0.0.0.0 stage-e.axon.aie.axon.ai
      0.0.0.0 static-assets.sdhahs.com
      0.0.0.0 static-assets.sdhahs.com.lan
      0.0.0.0 static-v1.va-api.net
      0.0.0.0 static.ads-twitter.com
      0.0.0.0 static.adsafeprotected.com

      @@ -608,7 +836,10 @@

      0.0.0.0 static.doubleclick.net.lan
      0.0.0.0 static.jampp.com
      0.0.0.0 static.karte.io
      0.0.0.0 stats.g.doubleclick.net
      0.0.0.0 store-visit-to-haas.east.edge.storage-yahoo.jp
      0.0.0.0 store-visit-to-haas.east.edge.storage-yahoo.jp.lan
      0.0.0.0 sub.girlslab-info.net

      @@ -621,23 +852,34 @@

      0.0.0.0 sync.adkernel.com
      0.0.0.0 sync.adkernel.com.lan
      0.0.0.0 sync.admanmedia.com
      0.0.0.0 sync.im-apps.net
      0.0.0.0 sync.intentiq.com
      0.0.0.0 sync.logly.co.jp
      0.0.0.0 sync6.im-apps.net
      0.0.0.0 sync6.im-apps.net.lan
      0.0.0.0 t-odx.op-mobile.opera.com
      0.0.0.0 t.adclr.jp
      0.0.0.0 t.adx.opera.com
      0.0.0.0 t.adx.opera.com.lan
      0.0.0.0 tags.rd.linksynergy.com
      0.0.0.0 td.doubleclick.net
      0.0.0.0 thumbnail.smartnews-ads.com
      0.0.0.0 tiger.clickhubs.com
      0.0.0.0 timecheck.moduleapps.com
      0.0.0.0 timecheck.moduleapps.com.lan
      0.0.0.0 timedomaintech.datasink.sensorsdata.cn
      0.0.0.0 tivan.naver.com
      0.0.0.0 torimochi.line-apps.com
      0.0.0.0 tp.adx.opera.com
      0.0.0.0 tr.acobt.tech

      @@ -646,15 +888,24 @@

      0.0.0.0 track-us.bidease.com
      0.0.0.0 track.adform.net
      0.0.0.0 track.adform.net.lan
      0.0.0.0 tracker.maticooads.com
      0.0.0.0 tracking.aws.judge.me
      0.0.0.0 tracking.isappcloud.com
      0.0.0.0 trk.atomex.net
      0.0.0.0 ts.amazon-adsystem.com
      0.0.0.0 ts.foisonad.com
      0.0.0.0 tsuruhahdapp-proxy.moduleapps.com
      0.0.0.0 uct.service.usercentrics.eu
      0.0.0.0 uh.nakanohito.jp
      0.0.0.0 unified.adsafeprotected.com
      0.0.0.0 universe.send.microad.jp
      0.0.0.0 ups.analytics.yahoo.com

      @@ -666,9 +917,12 @@

      0.0.0.0 user-profile.isappcloud.com
      0.0.0.0 users.popinfo.jp
      0.0.0.0 ut.rd.linksynergy.com
      0.0.0.0 v1-videocdn.gjhyss.com
      0.0.0.0 vad-bid.adsrvr.org
      0.0.0.0 vam-bid.adsrvr.org
      0.0.0.0 vc-brain.ndcpp-os.com
      0.0.0.0 vc-mirror.ndcpp-os.com
      0.0.0.0 vfw.amazon-adsystem.com

      @@ -687,6 +941,7 @@

      0.0.0.0 view.adjust.com
      0.0.0.0 view.adjust.com.lan
      0.0.0.0 vimp.u.send.microad.jp
      0.0.0.0 vogue-mode-symphony.site
      0.0.0.0 vscode-cdn.z01.azurefd.net
      0.0.0.0 vscode-unpkg-gvgaavacadd3anb4.z01.azurefd.net

      @@ -695,19 +950,37 @@

      0.0.0.0 wangmeng.online
      0.0.0.0 weather-server.allawnos.com
      0.0.0.0 weather-server.allawnos.com.lan
      0.0.0.0 win.eskimi.com
      0.0.0.0 www.awxcdn.com
      0.0.0.0 www.boredpanda.com
      0.0.0.0 www.cross-a.net
      0.0.0.0 www.google-analytics.com
      0.0.0.0 www.googletagmanager.com
      0.0.0.0 www.npttech.com
      0.0.0.0 wwwc.netcrew-analysis.jp
      0.0.0.0 x9.shinobi.jp
      0.0.0.0 xa.shinobi.jp
      0.0.0.0 yads.c.yimg.jp
      0.0.0.0 yads.c.yimg.jp.lan
      0.0.0.0 yads.yjtag.yahoo.co.jp
      0.0.0.0 yj-a.p.adnxs.com
      0.0.0.0 yj.p.adnxs.com
      0.0.0.0 youngle.techgdl.youngle.tech

      @@ -722,12 +995,16 @@

      /image[0-9].pubmatic.com/
      ||*.sdk-hb.smaato.net
      0.0.0.0 546001125.collect.igodigital.com
      0.0.0.0 a.teads.tv
      0.0.0.0 a.teads.tv.edgekey.net
      0.0.0.0 a.teads.tv.lan
      0.0.0.0 accdn.lpsnmedia.net
      0.0.0.0 ad-delivery.net
      0.0.0.0 ad.jp.ap.valuecommerce.com
      0.0.0.0 adrta.com
      0.0.0.0 ads.adingo.jp
      0.0.0.0 ads.mozilla.org

      @@ -737,14 +1014,12 @@

      0.0.0.0 ads.rubiconproject.com.lan
      0.0.0.0 ads.rubiconproject.com.ts.net
      0.0.0.0 ads.stickyadstv.com
    - 0.0.0.0 adx-f.ads.heytapmobile.com
    - 0.0.0.0 adx-f.ads.heytapmobile.com.lan
    - 0.0.0.0 adx-id.ads.heytapmobile.com
      0.0.0.0 adx.ads.vungle.com
      0.0.0.0 aml.valuecommerce.com
      0.0.0.0 aml.valuecommerce.com.lan
      0.0.0.0 amplify.outbrain.com
      0.0.0.0 analytics-tcp.mintegral.net.lan
      0.0.0.0 ap.srv.stackadapt.com
      0.0.0.0 ap.srv.stackadapt.com.lan
      0.0.0.0 apac-jp-sync.bidswitch.net

      @@ -760,10 +1035,6 @@

      0.0.0.0 api.superwall.me
      0.0.0.0 api.tradplusad.com
      0.0.0.0 apis.usonar.jp
    - 0.0.0.0 appconf-ocs-eu.heytapdl.com
    - 0.0.0.0 appconf-ocs-in.heytapdl.com
    - 0.0.0.0 appconf-ocs-sgp.heytapdl.com
    - 0.0.0.0 appconf-sgp.heytapdl.com
      0.0.0.0 apps.rokt.com
      0.0.0.0 article.squadbeyond.com
      0.0.0.0 as.jivox.com

      @@ -799,6 +1070,8 @@

      0.0.0.0 cdn-kddi-prod.adobecqms.net
      0.0.0.0 cdn-lb.vungle.com
      0.0.0.0 cdn-lb.vungle.com.lan
      0.0.0.0 cdn.cookie.sync.usonar.jp
      0.0.0.0 cdn.doubleverify.com
      0.0.0.0 cdn.doubleverify.com.lan

      @@ -816,9 +1089,6 @@

      0.0.0.0 cf.vast.doubleverify.com
      0.0.0.0 cf.vast.doubleverify.com.cdn.cloudflare.net
      0.0.0.0 chartbeat.net
    - 0.0.0.0 cl-data-f.ads.heytapmobile.com
    - 0.0.0.0 cl-data-sg.ads.heytapmobi.com
    - 0.0.0.0 cl-data-sg.ads.heytapmobi.com.lan
      0.0.0.0 cm.creativecdn.com
      0.0.0.0 cm.everesttech.net
      0.0.0.0 cm.smadex.com

      @@ -851,9 +1121,6 @@

      0.0.0.0 dalb.valuecommerce.com
      0.0.0.0 dalc.valuecommerce.com
      0.0.0.0 dalc.valuecommerce.com.lan
    - 0.0.0.0 dc-dragate-sg.heytapmobile.com
    - 0.0.0.0 dc-dragate-sg.heytapmobile.com.lan
    - 0.0.0.0 dcc-awareness-sg.heytapmobile.com
      0.0.0.0 displayf-tm.everesttech.net
      0.0.0.0 dl.listdl.com
      0.0.0.0 dossier.chartboost.com

      @@ -884,20 +1151,16 @@

      0.0.0.0 f.creativecdn.com
      0.0.0.0 fastlane.rubiconproject.com
      0.0.0.0 fastlane.rubiconproject.com.lan
    - 0.0.0.0 file-intl-push.heytapdl.com
      0.0.0.0 file.mysquadbeyond.com
      0.0.0.0 firebase-settings.crashlytics.com
      0.0.0.0 firebase-settings.crashlytics.com.lan
      0.0.0.0 firebase-settings.crashlytics.com.ts.net
      0.0.0.0 format.prod.cloud.ogury.io
    - 0.0.0.0 games-community-gl.heytapmobile.com
    - 0.0.0.0 games-community-gl.heytapmobile.com.lan
      0.0.0.0 games.tresensa.com
      0.0.0.0 geo-tracker.smadex.com
      0.0.0.0 geoclue.smaato.net
      0.0.0.0 geolocation.onetrust.com
      0.0.0.0 ghent-gce-jp.bidswitch.net
    - 0.0.0.0 global-search-gl.heytapmobile.com
      0.0.0.0 got.asia-se1gcp1.pubnative.net
      0.0.0.0 got.us-east4gcp1.pubnative.net
      0.0.0.0 graph-fallback.instagram.com

      @@ -906,6 +1169,7 @@

      0.0.0.0 graph.instagram.com.ts.net
      0.0.0.0 grid.bidswitch.net
      0.0.0.0 groundcontrol.rendering.sharethrough.com
      0.0.0.0 hblg.media.net
      0.0.0.0 hblg.media.net.lan
      0.0.0.0 hbopenbid-nrt10.pubmatic.com

      @@ -915,10 +1179,10 @@

      0.0.0.0 hbx.media.net
      0.0.0.0 htlb.casalemedia.com
      0.0.0.0 htlb.casalemedia.com.lan
    - 0.0.0.0 httpdns-push.heytapmobile.com
      0.0.0.0 i.w55c.net
      0.0.0.0 i.w55c.net.lan
      0.0.0.0 id-ap.piano.io
      0.0.0.0 id.crwdcntrl.net
      0.0.0.0 id.rlcdn.com
      0.0.0.0 idsync.rlcdn.com

      @@ -937,7 +1201,10 @@

      0.0.0.0 js.hs-scripts.com
      0.0.0.0 js.hsforms.net
      0.0.0.0 js.slvrbullet.com
      0.0.0.0 l.evidon.com
      0.0.0.0 libs.outbrain.com
      0.0.0.0 link.rubiconproject.com
      0.0.0.0 live.chartboost.com

      @@ -947,6 +1214,7 @@

      0.0.0.0 log.yshp.r-oo.valuecommerce.com
      0.0.0.0 logs.ads.vungle.com
      0.0.0.0 logs.ads.vungle.com.lan
      0.0.0.0 logsdk.kwai-pro.com
      0.0.0.0 lpcdn.lpsnmedia.net
      0.0.0.0 lyr.pubmatic.com

      @@ -958,13 +1226,6 @@

      0.0.0.0 mcdp-sngdc1.outbrain.com
      0.0.0.0 mcdp-wndc1.outbrain.com
      0.0.0.0 mcdp-wndc1.outbrain.com.lan
    - 0.0.0.0 mdp-appconf-eu.heytapdl.com
    - 0.0.0.0 mdp-appconf-eu.heytapdl.com.lan
    - 0.0.0.0 mdp-appconf-in.heytapdl.com
    - 0.0.0.0 mdp-appconf-jp.heytapdl.com
    - 0.0.0.0 mdp-appconf-jp.heytapdl.com.lan
    - 0.0.0.0 mdp-appconf-sg.heytapdl.com
    - 0.0.0.0 mdp-appconf-sg.heytapdl.com.lan
      0.0.0.0 media.grid.bidswitch.net
      0.0.0.0 medias.cloud.ogury.io
      0.0.0.0 micro.rubiconproject.com

      @@ -979,20 +1240,11 @@

      0.0.0.0 mv.outbrain.com
      0.0.0.0 navvy.media.net
      0.0.0.0 new.ads.vungle.com
    - 0.0.0.0 obus-config-sg.heytapmobile.com
    - 0.0.0.0 obus-dc121100-sg.heytapmobile.com
    - 0.0.0.0 obus-dc20123-sg.heytapmobile.com
    - 0.0.0.0 obus-dctech-sg.heytapmobile.com
    - 0.0.0.0 obus-dctech-sg.heytapmobile.com.lan
    - 0.0.0.0 obus-sg.dc.heytapmobile.com
    - 0.0.0.0 obus-sg.dc.heytapmobile.com.lan
      0.0.0.0 odb.outbrain.com
    - 0.0.0.0 omes-sec.heytapmobile.com
      0.0.0.0 ow.pubmatic.com
      0.0.0.0 ow.pubmatic.com.lan
      0.0.0.0 p.teads.tv
      0.0.0.0 paid.outbrain.com
    - 0.0.0.0 phone-manager-gl.heytapmobile.com
      0.0.0.0 pix.adrta.com
      0.0.0.0 pixel-apac.rubiconproject.com
      0.0.0.0 pixel-apac.rubiconproject.com.lan

      @@ -1053,7 +1305,6 @@

      0.0.0.0 secure-assets.rubiconproject.com
      0.0.0.0 settings.crashlytics.com
      0.0.0.0 settings.crashlytics.com.lan
    - 0.0.0.0 shortintl.push.heytapmobile.com
      0.0.0.0 showads-nrt10.pubmatic.com
      0.0.0.0 simage2.pubmatic.com
      0.0.0.0 sin.creativecdn.com

      @@ -1078,9 +1329,6 @@

      0.0.0.0 static.chartbeat.com.lan
      0.0.0.0 statics.creativecdn.com
      0.0.0.0 statsf-tm.everesttech.net
    - 0.0.0.0 stg-data-f.ads.heytapmobile.com
    - 0.0.0.0 stg-data-f.ads.heytapmobile.com.lan
    - 0.0.0.0 store-quic-gl.heytapmobile.com
      0.0.0.0 sync-tm.everesttech.net
      0.0.0.0 sync-tm.everesttech.net.lan
      0.0.0.0 sync.1rx.io

      @@ -1136,7 +1384,6 @@

      0.0.0.0 videoevents.outbrain.com
      0.0.0.0 videoexternalapi.outbrain.com
      0.0.0.0 videoexternalapi.outbrain.com.lan
    - 0.0.0.0 virusinfo-cloudscan-sn.heytapmobile.com
      0.0.0.0 vita.pstatic.net
      0.0.0.0 vpaid.doubleverify.com
      0.0.0.0 vt.outbrain.com

      @@ -1280,6 +1527,7 @@

      0.0.0.0 pancake.apple.com
      0.0.0.0 push.apple.com
      0.0.0.0 sb.music.apple.com

      # [ByteDance (tracker)]
      /p[0-9]*-ad.byteoversea.com/

      @@ -1304,7 +1552,6 @@

      0.0.0.0 api16-log-my.pangle.io
      0.0.0.0 api16-log-sg2.pangle.io.ts.net
      0.0.0.0 api16-log-va.pangle.io
    - 0.0.0.0 api16-log-va.pangle.io
      0.0.0.0 api39-sg.gts.byteoversea.net
      0.0.0.0 api39-va.gts.byteoversea.net
      0.0.0.0 api39.gtm.byteoversea.net

      @@ -1729,6 +1976,7 @@

      0.0.0.0 frontier.tiktokv.com
      0.0.0.0 frontier.tiktokv.com.lan
      0.0.0.0 gecko-sg.tiktokv.com
      0.0.0.0 i.isnssdk.com
      0.0.0.0 i.isnssdk.com.lan
      0.0.0.0 image-sg.tiktokv.com

      @@ -1774,6 +2022,8 @@

      0.0.0.0 p19-heycan-sign-va.ibyteimg.com
      0.0.0.0 p19-push-sign-va.ibyteimg.com
      0.0.0.0 p21-ad-sg.ibyteimg.com
      0.0.0.0 pitaya-sg.tiktokv.com
      0.0.0.0 pitaya-sg.tiktokv.com.lan
      0.0.0.0 pitaya.tiktokv.com

      @@ -1937,7 +2187,6 @@

      0.0.0.0 resolver.msg.global.xiaomi.net
      0.0.0.0 resolver.msg.global.xiaomi.net.lan
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com
    - 0.0.0.0 sdkconfig.ad.intl.xiaomi.com
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com.lan
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com.ts.net
      0.0.0.0 sdkconfig.intl.xiaomi.com

      @@ -2040,6 +2289,7 @@

      0.0.0.0 edgw.adingo.jp
      0.0.0.0 er.fivecdm.com
      0.0.0.0 er.fivecdm.com.lan
      0.0.0.0 eu-u.openx.net
      0.0.0.0 fledge.as.criteo.com
      0.0.0.0 fledge.criteo.com
    ```

    ```yaml
    AFTER:
      # References: none
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/reject/Reject_domain.txt
      #
    + # Last modified: 14 November 2025
      #

      # [拒否リクエスト]

      @@ -19,8 +19,13 @@

      ||*.c.appier.net.akadns.net
      ||*.c.appier.net.lan
      ||*.fls.doubleclick.net
    + 0.0.0.0 *.imptracking.com
    + 0.0.0.0 1004267de.scrollara.net
      0.0.0.0 1x1.a-mo.net
    + 0.0.0.0 22233.mc.tritondigital.com
    + 0.0.0.0 28123.mc.tritondigital.com
      0.0.0.0 3ppa.jp.cinarra.com
    + 0.0.0.0 a.vidoomy.com
      0.0.0.0 a6.smartnews-ads.com
      0.0.0.0 aax-dtb-mobile-geo.amazon-adsystem.com
      0.0.0.0 aax-eu.amazon-adsystem.com

      @@ -29,20 +34,27 @@

      0.0.0.0 aax-fe-sin.amazon-adsystem.com.lan
      0.0.0.0 aax-fe.amazon-adsystem.com
      0.0.0.0 aax-fe.amazon-adsystem.com.lan
    + 0.0.0.0 aax-fe.amazon-adsystem.com.ts.net
      0.0.0.0 aax-us-east.amazon-adsystem.com
      0.0.0.0 aax-us.amazon-adsystem.com
      0.0.0.0 aax.amazon-adsystem.com
      0.0.0.0 aax.amazon-adsystem.com.lan
    + 0.0.0.0 aax.amazon-adsystem.com.ts.net
    + 0.0.0.0 ac.jitb-asp-1.com
      0.0.0.0 ac.pe-k.site
      0.0.0.0 accounts.doubleclick.net
      0.0.0.0 acdn.adnxs.com
      0.0.0.0 acdn.adnxs.com.lan
      0.0.0.0 ad-nex.com.lan
      0.0.0.0 ad-proxy-reward-rakuten-co-jp.gslb.rdcnw.net
    + 0.0.0.0 ad.ad-stir.com
      0.0.0.0 ad.adsrvr.org
      0.0.0.0 ad.appier.net
    + 0.0.0.0 ad.ca-conv.jp
      0.0.0.0 ad.doubleclick.net
      0.0.0.0 ad.doubleclick.net.lan
    + 0.0.0.0 ad.doubleclick.net.ts.net
    + 0.0.0.0 ad.dynalyst.jp
      0.0.0.0 ad.ust-ad.com
      0.0.0.0 adclick.g.doubleclick.net
      0.0.0.0 ade.clmbtech.com

      @@ -54,13 +66,19 @@

      0.0.0.0 adm.dsp.cartajp.com
      0.0.0.0 admanmedia.com
      0.0.0.0 adone.yicha.jp
    + 0.0.0.0 ads.adex.com.ua
    + 0.0.0.0 ads.adex.com.ua.lan
    + 0.0.0.0 ads.adex.com.ua.ts.net
      0.0.0.0 ads.adjust-net.jp.lan
    + 0.0.0.0 ads.betweendigital.com
      0.0.0.0 ads.mythad.com
    + 0.0.0.0 adserver.assistads.net
      0.0.0.0 adservice.google.co.jp
      0.0.0.0 adservice.google.com
      0.0.0.0 advisionweb.yicha.jp
      0.0.0.0 advtrack.yicha.jp
      0.0.0.0 adx-tk.mtgglobals.com
    + 0.0.0.0 adx-track.domob.cn
      0.0.0.0 adx.g.doubleclick.net
      0.0.0.0 adx.g.doubleclick.net.lan
      0.0.0.0 adx.opera.com

      @@ -71,28 +89,48 @@

      0.0.0.0 afs.googleusercontent.com
      0.0.0.0 aggregator.service.usercentrics.eu.lan
      0.0.0.0 aid.send.microad.jp
    + 0.0.0.0 al-s.dc-tag.jp
    + 0.0.0.0 aladdin.genieesspv.jp
      0.0.0.0 am.moduleapps.com
      0.0.0.0 am.moduleapps.com.lan
      0.0.0.0 am.yahoo.co.jp
    + 0.0.0.0 analytex-us.userpilot.io
    + 0.0.0.0 analytics-tcp.mintegral.net.ts.net
      0.0.0.0 analytics-tcp.mtgglobals.com
      0.0.0.0 analytics.adjust.com
      0.0.0.0 analytics.adjust.net.in
      0.0.0.0 analytics.adjust.world
      0.0.0.0 analytics.app-adforce.jp
    + 0.0.0.0 analytics.brainlitix.net
    + 0.0.0.0 analytics.datafortiq.net
      0.0.0.0 analytics.gamezen.org
      0.0.0.0 analytics.google.com
    + 0.0.0.0 analytics.roomloft.net
    + 0.0.0.0 analytics.scrollara.net
    + 0.0.0.0 analytics.thinkcrate.net
    + 0.0.0.0 analytics.tidysuite.net
    + 0.0.0.0 ap-ice.360yield.com
    + 0.0.0.0 ap-win.srv.stackadapt.com
    + 0.0.0.0 apac.trk.svr-algorix.com
    + 0.0.0.0 apac03.trk.bid-algorix.com
      0.0.0.0 ape-androids.isappcloud.com
      0.0.0.0 ape-androids.isappcloud.com.lan
      0.0.0.0 api-events.eventstracker.io
      0.0.0.0 api-fe.supnovel.com
    + 0.0.0.0 api-iam.intercom.io
      0.0.0.0 api-sdk-tracking.beaconbank.jp
      0.0.0.0 api-sdk.beaconbank.jp
      0.0.0.0 api-sdk.beaconbank.jpapi-sdk.beaconbank.jp
    + 0.0.0.0 api.affiliations.site
      0.0.0.0 api.bidmachine.io
    + 0.0.0.0 api.btloader.com
      0.0.0.0 api.btrbdf.com
      0.0.0.0 api.bytegle.site
      0.0.0.0 api.flipdesk.jp
      0.0.0.0 api.gameanalytics.com
    + 0.0.0.0 api.id5-sync.com
    + 0.0.0.0 api.kaiu-marketing.com
    + 0.0.0.0 api.mixpanel.com
      0.0.0.0 api.onegg.site
      0.0.0.0 api.reproio.com
      0.0.0.0 api.rpdt.net

      @@ -101,6 +139,12 @@

      0.0.0.0 api.snapx.info
      0.0.0.0 api.synapse-kddi.net
      0.0.0.0 api.synapse-kddi.net.lan
    + 0.0.0.0 api.xintaicz.cn
    + 0.0.0.0 api.xintaicz.cn.lan
    + 0.0.0.0 api.xintaicz.cn.ts.net
    + 0.0.0.0 api2.amplitude.com
    + 0.0.0.0 api2.amplitude.com.lan
    + 0.0.0.0 api2.amplitude.com.ts.net
      0.0.0.0 api2.branch.io
      0.0.0.0 api3.4dvertible.com
      0.0.0.0 apis.naver.com

      @@ -114,19 +158,23 @@

      0.0.0.0 app.adjust.com.lan
      0.0.0.0 app.adjust.com.tail06b0f8.ts.net
      0.0.0.0 app.adjust.io
    + 0.0.0.0 app.adjust.io.ts.net
      0.0.0.0 app.adjust.net.in
      0.0.0.0 app.adjust.net.in.lan
      0.0.0.0 app.adjust.net.in.tail06b0f8.ts.net
      0.0.0.0 app.adjust.world
      0.0.0.0 app.adjust.world.lan
      0.0.0.0 app.dialogone.jp
    + 0.0.0.0 app.partnerboost.com
      0.0.0.0 app.publer.com
      0.0.0.0 app.publer.io
    + 0.0.0.0 appollo.jp
      0.0.0.0 appsrv.display.io
      0.0.0.0 arg.atomex.net
      0.0.0.0 arm.appiersig.com
      0.0.0.0 arm.appiersig.com.akadns.net
      0.0.0.0 arm.appiersig.com.lan
    + 0.0.0.0 as.uncn.jp
      0.0.0.0 asia-seoul-statistics.tpmn.io
      0.0.0.0 asia.adform.net
      0.0.0.0 asia.seadform.net

      @@ -141,26 +189,36 @@

      0.0.0.0 atm.im-apps.net
      0.0.0.0 audiencedata.im-apps.net
      0.0.0.0 audiencedata.im-apps.net.lan
    + 0.0.0.0 audio.buzzsprout.com
      0.0.0.0 automate-frontend.linksynergy.com
      0.0.0.0 automate-k8s.linksynergy.com
      0.0.0.0 automate.linksynergy.com
      0.0.0.0 aws.inshot.cc
      0.0.0.0 az416426.vo.msecnd.net
    + 0.0.0.0 az764295.vo.msecnd.net.lan
    + 0.0.0.0 az764295.vo.msecnd.net.ts.net
    + 0.0.0.0 b.6sc.co
      0.0.0.0 b.adnxs.com
      0.0.0.0 b.im-apps.net
      0.0.0.0 b.logly.co.jp
      0.0.0.0 b.logly.co.jp.lan
      0.0.0.0 b.sharethrough.com
      0.0.0.0 b1.nel.goog
    + 0.0.0.0 b1sync.zemanta.com
      0.0.0.0 b6.im-apps.net
      0.0.0.0 bam.nr-data.net
      0.0.0.0 bid.g.doubleclick.net
      0.0.0.0 bid.ssp.bance.jp
      0.0.0.0 bidcontext-us.bidmachine.io
    + 0.0.0.0 bm-ads.io
      0.0.0.0 bm.moduleapps.com
      0.0.0.0 booster.reproio.com
      0.0.0.0 bs.karte.io
      0.0.0.0 bs.nakanohito.jp
    + 0.0.0.0 bs.serving-sys.com
    + 0.0.0.0 bstatic.octopus.tokyo
    + 0.0.0.0 btloader.com
    + 0.0.0.0 c.6sc.co
      0.0.0.0 c.amazon-adsystem.com
      0.0.0.0 c.amazon-adsystem.com.lan
      0.0.0.0 c.amazon-adsystem.com.tail06b0f8.ts.net

      @@ -182,8 +240,11 @@

      0.0.0.0 cdn-adn-https.mtgglobals.com
      0.0.0.0 cdn-adn-https.mtgglobals.com.lan
      0.0.0.0 cdn-blocks.karte.io
    + 0.0.0.0 cdn-cookieyes.com
      0.0.0.0 cdn-creatives.adikteev.com
      0.0.0.0 cdn-f.adsmoloco.com
    + 0.0.0.0 cdn-f.adsmoloco.com.ts.net
    + 0.0.0.0 cdn-ima.33across.com
      0.0.0.0 cdn-logly-co-jp.cdn.ampproject.org
      0.0.0.0 cdn.4dvertible.com
      0.0.0.0 cdn.adnxs.com

      @@ -191,58 +252,86 @@

      0.0.0.0 cdn.adsafeprotected.com
      0.0.0.0 cdn.atomex.net
      0.0.0.0 cdn.branch.io
    + 0.0.0.0 cdn.caprofitx.com
    + 0.0.0.0 cdn.confiant-integrations.net
      0.0.0.0 cdn.cquotient.com
      0.0.0.0 cdn.ihappyread.com
      0.0.0.0 cdn.jampp.com
      0.0.0.0 cdn.judge.me
    + 0.0.0.0 cdn.kaizenplatform.net
      0.0.0.0 cdn.liftoff.io
      0.0.0.0 cdn.logly.co.jp
      0.0.0.0 cdn.logly.co.jp.lan
      0.0.0.0 cdn.microad.jp
      0.0.0.0 cdn.microad.jp.lan
      0.0.0.0 cdn.microad.jp.wtxcdn.com
    + 0.0.0.0 cdn.monkey-ads.com
    + 0.0.0.0 cdn.mouseflow.com
      0.0.0.0 cdn.reproio.com
    + 0.0.0.0 cdn.segment.com
      0.0.0.0 cdn.speedcurve.com
      0.0.0.0 cdn1.judge.me
      0.0.0.0 cdn3.hsrdkt.com
      0.0.0.0 cdnwidget.judge.me
    + 0.0.0.0 ce.lijit.com
    + 0.0.0.0 ced-ns.sascdn.com
    + 0.0.0.0 census-app.scorecardresearch.com
      0.0.0.0 cf-assets.synapse-kddi.net
      0.0.0.0 cf-images.ap-northeast-1.prod.boltdns.net
      0.0.0.0 cf.im-apps.net
      0.0.0.0 check-tcp.mtgglobals.com
      0.0.0.0 check-tcp.rayjump.com.lan
    + 0.0.0.0 check-tcp.rayjump.com.ts.net
    + 0.0.0.0 check.rayjump.com.lan
    + 0.0.0.0 check.rayjump.com.ts.net
      0.0.0.0 checkout-api.worldshopping.jp
    + 0.0.0.0 chet.rayjump.com.lan
    + 0.0.0.0 chet.rayjump.com.ts.net
      0.0.0.0 cip.ust-adc.com
      0.0.0.0 cksync.yahoo.co.jp
      0.0.0.0 classify-app-sg.allawnos.com
      0.0.0.0 clb.yahoo.co.jp
      0.0.0.0 click.liftoff.io
    + 0.0.0.0 cloud.xaid.jp
    + 0.0.0.0 cloudconf-app-jp.heytapmobile.com
    + 0.0.0.0 cloudconf-app-jp.heytapmobile.com.lan
    + 0.0.0.0 cloudconf-app-jp.heytapmobile.com.ts.net
    + 0.0.0.0 cloudconf-app-sg.heytapmobile.com
      0.0.0.0 cloudinary-res.isappcloud.com
    + 0.0.0.0 cm-10-140.getui.com
      0.0.0.0 cm-11451.csolution.jp
      0.0.0.0 cm-beacon.nakanohito.jp
      0.0.0.0 cm-widget.nakanohito.jp
      0.0.0.0 cm.adform.net
      0.0.0.0 cm.g.doubleclick.net
      0.0.0.0 cm.g.doubleclick.net.lan
    + 0.0.0.0 common-jp.genieesspv.jp
    + 0.0.0.0 commvod.kwcdn.com.ts.net
      0.0.0.0 component-ota-sg.allawnos.com
      0.0.0.0 conduit.branch.io
      0.0.0.0 config.aps.amazon-adsystem.com
    + 0.0.0.0 config.ssp.taxssp.com
      0.0.0.0 configure-tcp-android.mtgglobals.com
      0.0.0.0 configure-tcp-android.mtgglobals.com.lan
      0.0.0.0 configure-tcp-ios.mtgglobals.com
      0.0.0.0 configure-tcp.mtgglobals.com
      0.0.0.0 configure-tcp.rayjump.com.lan
    + 0.0.0.0 configure-tcp.rayjump.com.ts.net
      0.0.0.0 configure.mtgglobals.com
      0.0.0.0 configure.mtgglobals.com.lan
    + 0.0.0.0 configure.rayjump.com.lan
    + 0.0.0.0 configure.rayjump.com.ts.net
      0.0.0.0 conn-service-us-04.allawnos.com
      0.0.0.0 conn-service-us-04.allawnos.com.lan
      0.0.0.0 conn-service-us-05.allawnos.com
      0.0.0.0 conn-service-us-05.allawnos.com.lan
    + 0.0.0.0 connect.tapjoy.com.ts.net
      0.0.0.0 connectid.analytics.yahoo.com
      0.0.0.0 consent-api.service.consent.usercentrics.eu
      0.0.0.0 consent.adjust.com
      0.0.0.0 consent.adjust.io
      0.0.0.0 consent.adjust.net.in
    + 0.0.0.0 consent.adjust.world
      0.0.0.0 content.cdn.personaly.bid
      0.0.0.0 control.smbeat.jp
      0.0.0.0 control.smbeat.jp.lan

      @@ -250,15 +339,24 @@

      0.0.0.0 crashlyticsreports-pa.googleapis.com.lan
      0.0.0.0 crcdn01.adnxs.com
      0.0.0.0 creative-bunny.bidease.com
    + 0.0.0.0 creative-p.undertone.com
      0.0.0.0 creative.bidease.com
      0.0.0.0 creative.cdnyeah.com
      0.0.0.0 creative.dsp.cartajp.com
      0.0.0.0 creative.smartnews-ads.com
    + 0.0.0.0 crosh-tag.xlisting.jp
      0.0.0.0 cs.ademon.net
      0.0.0.0 cs.admanmedia.com
      0.0.0.0 cs.admanmedia.com.lan
      0.0.0.0 cs.advortex.cloud
    + 0.0.0.0 cs.boost-next.co.jp
    + 0.0.0.0 cs.gssprt.jp
    + 0.0.0.0 cs.krushmedia.com
      0.0.0.0 cs.nakanohito.jp
    + 0.0.0.0 csync-apac.smilewanted.com
    + 0.0.0.0 csync.loopme.me
    + 0.0.0.0 csync.smilewanted.com
    + 0.0.0.0 cta-service-cms2.hubspot.com
      0.0.0.0 cta.bidmachine.io
      0.0.0.0 cv.dsp.reemo-ad.jp
      0.0.0.0 d-cache.microad.jp

      @@ -266,14 +364,18 @@

      0.0.0.0 d-track.send.microad.jp
      0.0.0.0 d.adroll.com
      0.0.0.0 d.adroll.com.lan
    + 0.0.0.0 d9.flashtalking.com
      0.0.0.0 data.adsrvr.org
      0.0.0.0 data.flurry.com
      0.0.0.0 data.flurry.com.lan
    + 0.0.0.0 datain.37hwdata.com
      0.0.0.0 dcape-na.amazon.com
      0.0.0.0 dcdn.adnxs.com
      0.0.0.0 dcg.microsoft.com
      0.0.0.0 dcg.microsoft.com.lan
    + 0.0.0.0 de.tynt.com
      0.0.0.0 deapi.funsdata.com
    + 0.0.0.0 demand-engine.browsiprod.com
      0.0.0.0 dev.visualwebsiteoptimizer.com
      0.0.0.0 direct.adsrvr.org
      0.0.0.0 dmp.adform.net

      @@ -282,7 +384,10 @@

      0.0.0.0 dmp.im-apps.net.lan
      0.0.0.0 doubleclick.net
      0.0.0.0 doubleclick.net.lan
    + 0.0.0.0 dp.image-qoo10.jp
    + 0.0.0.0 dp1.33across.com
      0.0.0.0 dr-gate-city-heaven-v2.shinobi.jp
    + 0.0.0.0 ds.uncn.jp
      0.0.0.0 dsb.yahoo.co.jp
      0.0.0.0 dsb.yahooapis.jp
      0.0.0.0 dsb.yahooapis.jp.lan

      @@ -291,34 +396,57 @@

      0.0.0.0 dsp-static.clickhubs.com
      0.0.0.0 dsp-trk.eskimi.com
      0.0.0.0 dsp-trvm.eskimi.com
    + 0.0.0.0 dsp.logly.co.jp
      0.0.0.0 dt.adsafeprotected.com
      0.0.0.0 dt.adsafeprotected.com.lan
      0.0.0.0 dynamic-yda.c.yimg.jp
      0.0.0.0 dynamic2-ydn.c.yimg.jp
      0.0.0.0 e.axon.ai
      0.0.0.0 e.axon.ai.lan
    + 0.0.0.0 e.axon.ai.ts.net
      0.0.0.0 e.cquotient.com
    + 0.0.0.0 e.crashlytics.com.ts.net
      0.0.0.0 ec-concier.com
      0.0.0.0 edayo.ademon.net
    + 0.0.0.0 edayo.boost-next.co.jp
      0.0.0.0 edayo.istact.jp
      0.0.0.0 edge.safedk.com
      0.0.0.0 edge.safedk.com.lan
    + 0.0.0.0 edge.safedk.com.ts.net
      0.0.0.0 enduser.adsrvr.org
    + 0.0.0.0 ep1.adtrafficquality.google
    + 0.0.0.0 ep2.adtrafficquality.google
    + 0.0.0.0 epsilon.6sense.com
      0.0.0.0 eu.mclean.50union.com
      0.0.0.0 eu.mvconf.50union.com
      0.0.0.0 eu.mvconf.50union.com.lan
    + 0.0.0.0 eu.mvconf.50union.com.ts.net
    + 0.0.0.0 ev.rollnat.com
      0.0.0.0 event-action.popinfo.jp
    + 0.0.0.0 event-sg.ssp.taxssp.com
    + 0.0.0.0 events-dca.bidder.kayzen.io
      0.0.0.0 events-sgp.bidder.kayzen.io
    + 0.0.0.0 events.browsiprod.com
      0.0.0.0 events.popinfo.jp
    + 0.0.0.0 feel-live.com
    + 0.0.0.0 fldt.afafb.com
    + 0.0.0.0 flux-cdn.com
      0.0.0.0 fourier-videoclip-sg.allawnos.com
      0.0.0.0 fp-dev.webapp.163.com
      0.0.0.0 free2.apkzonic.com
    + 0.0.0.0 fundingchoicesmessages.google.com.ts.net
      0.0.0.0 fw.adsafeprotected.com
      0.0.0.0 g.alicdn.com
      0.0.0.0 g.doubleclick.net.lan
      0.0.0.0 g.doubleclick.net.tail06b0f8.ts.net
    + 0.0.0.0 gamedot-config.afafb.com
    + 0.0.0.0 gamedot-other.afafb.com
    + 0.0.0.0 gamedot.afafb.com
    + 0.0.0.0 gamedot.afafb.com.lan
      0.0.0.0 gateway.instagram.com
      0.0.0.0 gateway.instagram.com.lan
    + 0.0.0.0 gateway.instagram.com.ts.net
    + 0.0.0.0 gcdn.2mdn.net
      0.0.0.0 gcmast-cdn.goldspotmedia.com
      0.0.0.0 gcmast-cdn.goldspotmedia.com.lan
      0.0.0.0 gdl.news-cdn.site

      @@ -334,33 +462,46 @@

      0.0.0.0 gntm.geeen.co.jp
      0.0.0.0 googleads.g.doubleclick.net
      0.0.0.0 googleads.g.doubleclick.net.lan
    + 0.0.0.0 googleads.g.doubleclick.net.ts.net
      0.0.0.0 googleads4.g.doubleclick.net
      0.0.0.0 googleads4.g.doubleclick.net.lan
    + 0.0.0.0 gps.adjust.com
      0.0.0.0 graphql.usercentrics.eu
      0.0.0.0 grp15-ias-rakuten-co-jp.rdcnw.net.akadns.net
      0.0.0.0 gsspat.jp.lan
      0.0.0.0 gui-server-sg.allawnos.com
      0.0.0.0 gw.geoedge.be
      0.0.0.0 h.accesstrade.net
    + 0.0.0.0 hella-ping.afafb.com
    + 0.0.0.0 hella.afafb.com
    + 0.0.0.0 hella.afafb.com.lan
    + 0.0.0.0 hellouniweb.com.cdn.cloudflare.net
      0.0.0.0 hermes-api.learnings.ai
      0.0.0.0 hk-cdn.youngle.tech
      0.0.0.0 hw.zuimeitianqi.com
      0.0.0.0 hybird.mtgglobals.com
    + 0.0.0.0 i.alicdn.com
      0.0.0.0 i.pinimgproxy.com
      0.0.0.0 i18n.mclean.50union.com
      0.0.0.0 i18n.mclean.50union.com.lan
    + 0.0.0.0 i18n.mclean.50union.com.ts.net
      0.0.0.0 ib.adnxs.com
      0.0.0.0 ib.adnxs.com.lan
      0.0.0.0 ib.isappcloud.com
      0.0.0.0 ib.isappcloud.com.lan
      0.0.0.0 ib.sin1.geoadnxs.com
    + 0.0.0.0 ice.360yield.com
      0.0.0.0 icosa-service-sg-01.allawnos.com
      0.0.0.0 icosa-service-sg.allawnos.com
      0.0.0.0 id.geistm.com
      0.0.0.0 id.geistm.com.lan
    + 0.0.0.0 id.mysquadbeyond.com
      0.0.0.0 id5-sync.com
    + 0.0.0.0 id5-sync.com.lan
      0.0.0.0 im.c.yimg.jp
      0.0.0.0 im.c.yimg.jp.lan
    + 0.0.0.0 image.simplecastcdn.com
    + 0.0.0.0 imagedelivery.net
      0.0.0.0 images.microcms-assets.io
      0.0.0.0 imasdk.googleapis.com
      0.0.0.0 img-cf.karte.io

      @@ -376,6 +517,7 @@

      0.0.0.0 imp-bidapi.i-mobile.co.jp
      0.0.0.0 imp-lb-us2.jampp.com
      0.0.0.0 imp-ru-ap.jampp.com
    + 0.0.0.0 imp.control.kochava.com
      0.0.0.0 imp.dynalyst.jp
      0.0.0.0 imp.u.send.microad.jp
      0.0.0.0 impression-ap.adikteev.com

      @@ -389,14 +531,20 @@

      0.0.0.0 insight.adsrvr.org
      0.0.0.0 instaapi.zagtechnology.com
      0.0.0.0 intake-analytics.wikimedia.org
    + 0.0.0.0 intercom.io
      0.0.0.0 iota702.rtb.appier.net
      0.0.0.0 ip-api.com
      0.0.0.0 ipds.opr.adx.opera.com
    + 0.0.0.0 ipv6.6sc.co
      0.0.0.0 ittpx.eskimi.com
    + 0.0.0.0 j.6sc.co
      0.0.0.0 j.microad.net
      0.0.0.0 j.microad.net.wcdnga.com
    + 0.0.0.0 jbsp.adj.st
      0.0.0.0 jp-col-ext.nelo.navercorp.com
      0.0.0.0 jp-col-ext.nelo.navercorp.com.lan
    + 0.0.0.0 jp-col-ext.nelo.navercorp.com.ts.net
    + 0.0.0.0 jp.matk.temu.com.ts.net
      0.0.0.0 jp1-bid.adsrvr.org
      0.0.0.0 js-agent.newrelic.com
      0.0.0.0 js.ad-stir.com

      @@ -407,9 +555,13 @@

      0.0.0.0 js.dsp.cartajp.com
      0.0.0.0 js.dsp.cartajp.com.lan
      0.0.0.0 js.dsp.reemo-ad.jp
    + 0.0.0.0 js.gsspcln.jp
    + 0.0.0.0 js.intercomcdn.com
      0.0.0.0 js.istact.jp
      0.0.0.0 js.ptengine.jp
      0.0.0.0 js.ssp.bance.jp
    + 0.0.0.0 jscdn.appier.net
    + 0.0.0.0 jy9q.adj.st
      0.0.0.0 kapetracking.com
      0.0.0.0 kenga.tech
      0.0.0.0 kr-col-ext.nelo.navercorp.com

      @@ -418,11 +570,20 @@

      0.0.0.0 lax1-ib.adnxs.com
      0.0.0.0 lazy-tcp.mtgglobals.com
      0.0.0.0 lazy-tcp.rayjump.com.lan
    + 0.0.0.0 lazy-tcp.rayjump.com.ts.net
    + 0.0.0.0 lazy.rayjump.com.lan
    + 0.0.0.0 lazy.rayjump.com.ts.net
    + 0.0.0.0 lb.eu-1-id5-sync.com
    + 0.0.0.0 lexicon.33across.com
      0.0.0.0 lf-cdn.coze.cn
    + 0.0.0.0 log-v4-insight.kaizenplatform.net
      0.0.0.0 log.mmstat.com
    + 0.0.0.0 log.qoo10.jp
      0.0.0.0 log.radiko.jp
      0.0.0.0 log2.radiko.jp
    + 0.0.0.0 logger2.playablefactory.app
      0.0.0.0 logql.yahoo.co.jp
    + 0.0.0.0 lptag.liveperson.net
      0.0.0.0 lt.logly.co.jp
      0.0.0.0 m.adnxs.com
      0.0.0.0 m.adnxs.com.lan

      @@ -430,14 +591,21 @@

      0.0.0.0 ma2file.moduleapps.com
      0.0.0.0 mads.amazon-adsystem.com
      0.0.0.0 mads.amazon-adsystem.com.lan
    + 0.0.0.0 mads.amazon-adsystem.com.ts.net
      0.0.0.0 masspush-cdn.karte.io
      0.0.0.0 match.adsrvr.org
      0.0.0.0 match.adsrvr.org.lan
    + 0.0.0.0 match.deepintent.com
      0.0.0.0 materials.admaster.cc
      0.0.0.0 maxcdn.bootstrapcdn.com
      0.0.0.0 media.dpdvx.com
    + 0.0.0.0 media.redcircle.com
    + 0.0.0.0 mediation-receiver.afafb.com
    + 0.0.0.0 mediation-receiver.afafb.com.lan
      0.0.0.0 micres.cyberowl.jp
      0.0.0.0 microad.net
    + 0.0.0.0 middle-abtester.afafb.com
    + 0.0.0.0 middle-defend.afafb.com
      0.0.0.0 mirror2.karte.io
      0.0.0.0 mobile-collector.newrelic.com
      0.0.0.0 mobile-collector.newrelic.com.lan

      @@ -451,20 +619,26 @@

      0.0.0.0 mt-usw.appiersig.com.lan
      0.0.0.0 mtg-h5.mtgglobals.com
      0.0.0.0 mtg-h5.mtgglobals.com.lan
    + 0.0.0.0 mtg-h5.mtgglobals.com.ts.net
      0.0.0.0 mtg-native.mtgglobals.com
      0.0.0.0 mtrack.mtgglobals.com
    + 0.0.0.0 munchkin.marketo.net
      0.0.0.0 nam.veta.naver.com
      0.0.0.0 nam.veta.naver.com.lan
    + 0.0.0.0 nam.veta.naver.com.ts.net
      0.0.0.0 nelo2-col.navercorp.com
      0.0.0.0 nelo2-col.navercorp.com.lan
    + 0.0.0.0 nelo2-col.navercorp.com.ts.net
      0.0.0.0 net-sg-gcp-cdn.mtgglobals.com
      0.0.0.0 net-sg.mtgglobals.com
      0.0.0.0 net-vg-cdn.mtgglobals.com
      0.0.0.0 net-vg.mtgglobals.com
      0.0.0.0 netdna.bootstrapcdn.com
      0.0.0.0 newplayable.mintegral.com
    + 0.0.0.0 nexus-websocket-a.intercom.io
      0.0.0.0 nl-gcp-ad-track-sdk-europe-west4-b.mtgglobals.com
      0.0.0.0 node.aibeacon.jp
    + 0.0.0.0 notifications-gke-sdk-bidding-a.fyber.com
      0.0.0.0 notifications-gke-sdk-bidding-b.fyber.com
      0.0.0.0 notifications-gke-sdk-bidding-canary.fyber.com
      0.0.0.0 notifications-gke-sdk-bidding.fyber.com

      @@ -472,28 +646,43 @@

      0.0.0.0 nt-compass-fit-jp.logly.co.jp
      0.0.0.0 ntp.sjtu.edu.cn
      0.0.0.0 ntracker-collector.naver.com
    + 0.0.0.0 nurl.pubmatic.com
      0.0.0.0 ny-event.personaly.bid
    + 0.0.0.0 ny1-bid.adsrvr.org
      0.0.0.0 nym1-ib.adnxs.com
    + 0.0.0.0 o9ygyos1-ios.mobile-messenger.intercom.com
      0.0.0.0 ob.cityrobotflower.com
      0.0.0.0 observe-tcp.mtgglobals.com
      0.0.0.0 opr.adx.opera.com
      0.0.0.0 ota-recruit-sg.allawnos.com
    + 0.0.0.0 ota.lokalise.com
    + 0.0.0.0 otonal.mc.tritondigital.com
      0.0.0.0 outspot-ams-vip3.op-mobile.opera.com
      0.0.0.0 outspot2-ams.adx.opera.com
    + 0.0.0.0 p.adsymptotic.com
    + 0.0.0.0 p0.ipstatp.com
      0.0.0.0 p11.techlab-cdn.com
      0.0.0.0 pagead2.googlesyndication.com
    + 0.0.0.0 pagead2.googlesyndication.com.ts.net
      0.0.0.0 pidm.moduleapps.com
      0.0.0.0 ping.chartbeat.net
    + 0.0.0.0 pixel-sync.sitescout.com
      0.0.0.0 pixel.adsafeprotected.com
      0.0.0.0 pixel.everesttech.net
      0.0.0.0 pl-point.mtgglobals.com
      0.0.0.0 play.mtgglobals.com
      0.0.0.0 playable-stats.mindworks-creative.com
    + 0.0.0.0 playable.directservices.it
      0.0.0.0 playable.mintegral.com.lan
      0.0.0.0 pm.yahoo.co.jp
      0.0.0.0 pm.yahoo.jp
    + 0.0.0.0 pok.mintegral.net.ts.net
      0.0.0.0 policy-tcp.mtgglobals.com
      0.0.0.0 policy-tcp.rayjump.com.lan
    + 0.0.0.0 policy-tcp.rayjump.com.ts.net
    + 0.0.0.0 policy.rayjump.com.lan
    + 0.0.0.0 policy.rayjump.com.ts.net
    + 0.0.0.0 pool-apac-001-anycast.mc.tritondigital.com
      0.0.0.0 poplink-f.probo.biz
      0.0.0.0 pp3-sdkdata-v2-ut.profilepassport.jp
      0.0.0.0 pr-bh.ybp.yahoo.com

      @@ -501,20 +690,25 @@

      0.0.0.0 prebid.a-mo.net
      0.0.0.0 prebid.a-mo.net.lan
      0.0.0.0 prebid.adnxs.com
    + 0.0.0.0 prebid.smilewanted.com
      0.0.0.0 production-04-gcp-gateway.karte.io
      0.0.0.0 pubads.g.doubleclick.net
      0.0.0.0 pubads.g.doubleclick.net.lan
    + 0.0.0.0 pubads.g.doubleclick.net.ts.net
      0.0.0.0 pubsub.googleapis.com
      0.0.0.0 pubsub.googleapis.com.lan
    + 0.0.0.0 puz.afafb.com
      0.0.0.0 radar.cedexis.com
      0.0.0.0 rapids.rpdt.net
      0.0.0.0 rcm-fe.amazon-adsystem.com
      0.0.0.0 rcv.ust-ad.com
      0.0.0.0 rd.dynalyst.jp
    + 0.0.0.0 recruit.112.2o7.net
      0.0.0.0 res.adx.opera.com
      0.0.0.0 research-image-itmedia-co-jp.cdn.ampproject.org
      0.0.0.0 resource5-cdn.ocolt.com
      0.0.0.0 resource5-cdn.ocolt.com.lan
    + 0.0.0.0 retcode.alicdn.com
      0.0.0.0 router.miwifi.com
      0.0.0.0 router.miwifi.com.lan
      0.0.0.0 rpt.cedexis.com

      @@ -535,31 +729,56 @@

      0.0.0.0 s.alicdn.com.w.cdngslb.com
      0.0.0.0 s.amazon-adsystem.com
      0.0.0.0 s.amazon-adsystem.com.lan
    + 0.0.0.0 s.company-target.com
    + 0.0.0.0 s.edge.svr-algorix.com
    + 0.0.0.0 s.everestop.io
    + 0.0.0.0 s.lazybumblebee.com
      0.0.0.0 s.logly.co.jp
      0.0.0.0 s.update.adsrvr.org
    + 0.0.0.0 s.vj0.cc
      0.0.0.0 s0.2mdn.net
      0.0.0.0 s0.sgpstatp.com
      0.0.0.0 s1.adform.net
      0.0.0.0 s2.adform.net
      0.0.0.0 s2s.adjust.com
    + 0.0.0.0 s2s.adjust.com.ts.net
    + 0.0.0.0 s9.r-ad.ne.jp
      0.0.0.0 sau-server-sg.allawnos.com
    + 0.0.0.0 sb-kirabana.discover-news.tokyo
      0.0.0.0 sb-tama-ran.musthave-magazine.tokyo
      0.0.0.0 score.im-apps.net
    + 0.0.0.0 script.hotjar.com
      0.0.0.0 scripts.im-apps.net
      0.0.0.0 sdk-api.maticooads.com
      0.0.0.0 sdk-api.maticooads.com.lan
    + 0.0.0.0 sdk.open.talk.gepush.com
    + 0.0.0.0 sdk.open.talk.gepush.com.lan
    + 0.0.0.0 sdk.open.talk.gepush.com.ts.net
    + 0.0.0.0 sdk.open.talk.getui.com
    + 0.0.0.0 sdk.open.talk.getui.net
    + 0.0.0.0 sdkapi.pubadding.com
    + 0.0.0.0 sdkapi.pubadding.com.lan
    + 0.0.0.0 sdkapi.pubadding.com.ts.net
    + 0.0.0.0 sdkc.vervegroupinc.net
    + 0.0.0.0 sdksg.ssp.taxssp.com
      0.0.0.0 se-setting-tcp.mtgglobals.com
      0.0.0.0 sea1-sync.a-mo.net
    + 0.0.0.0 secure-gl.imrworldwide.com
      0.0.0.0 secure.adnxs.com
      0.0.0.0 secure.adnxs.com.lan
      0.0.0.0 securepubads.g.doubleclick.net
      0.0.0.0 sentry-prod.branch.io
      0.0.0.0 server.jp1media.com
    + 0.0.0.0 service.fyber.com
    + 0.0.0.0 settings.crashlytics.com.ts.net
      0.0.0.0 sg-ali-ad-track-sdk.mtgglobals.com
      0.0.0.0 sg-allmusic-api-adv.allsaints.tv
      0.0.0.0 sg-event.personaly.bid
      0.0.0.0 sg-new-ssplib-hb.mtgglobals.com
      0.0.0.0 sg-new-ssplib-hb.mtgglobals.com.lan
    + 0.0.0.0 sg-new-ssplib-hb.mtgglobals.com.ts.net
    + 0.0.0.0 sg-new-ssplib-hb.rayjump.com.lan
    + 0.0.0.0 sg-new-ssplib-hb.rayjump.com.ts.net
      0.0.0.0 sg-setting-tcp.mtgglobals.com
      0.0.0.0 sg-trk.bluevoox.com
      0.0.0.0 sg-trk2.bluevoox.com

      @@ -574,12 +793,16 @@

      0.0.0.0 skadnetworks.fyber.com
      0.0.0.0 so.tpocdm.com
      0.0.0.0 socdm.com
    + 0.0.0.0 sp.nova-ad.net
    + 0.0.0.0 spad.i-mobile.co.jp
    + 0.0.0.0 spcnv.i-mobile.co.jp
      0.0.0.0 spdmg2.i-mobile.co.jp
      0.0.0.0 spimgv1.i-mobile.co.jp
      0.0.0.0 spnativeapi-direct.i-mobile.co.jp
      0.0.0.0 spnativeapi-tls.i-mobile.co.jp
      0.0.0.0 spnativeapi-tls.i-mobile.co.jp.lan
      0.0.0.0 spnativeapi.i-mobile.co.jp
    + 0.0.0.0 spsvcsp-tls.i-mobile.co.jp
      0.0.0.0 ss-jp2.appiersig.com
      0.0.0.0 ss-jp2.appiersig.com.lan
      0.0.0.0 ss-sg.appiersig.com

      @@ -588,19 +811,24 @@

      0.0.0.0 ss-sg2.appiersig.com.akadns.net
      0.0.0.0 ss-use.appiersig.com
      0.0.0.0 ss-use.appiersig.com.akadns.net
    + 0.0.0.0 ssc-cms.33across.com
      0.0.0.0 ssp-bidapi.i-mobile.co.jp
      0.0.0.0 ssp.img-static.tech
      0.0.0.0 ssp.send.microad.jp
      0.0.0.0 ssp.send.microad.jp.lan
    + 0.0.0.0 sspexc-asia.taxssp.com
      0.0.0.0 ssstwo.com
      0.0.0.0 ssyoutube.com
      0.0.0.0 st.shinobi.jp
      0.0.0.0 st.shinobi.jp.lan
      0.0.0.0 stackpath.bootstrapcdn.com
      0.0.0.0 stage-e.axon.ai
    + 0.0.0.0 stage-e.axon.ai.lan
    + 0.0.0.0 stage-e.axon.ai.ts.net
      0.0.0.0 stage-e.axon.aie.axon.ai
      0.0.0.0 static-assets.sdhahs.com
      0.0.0.0 static-assets.sdhahs.com.lan
    + 0.0.0.0 static-rise.enhance.co.jp
      0.0.0.0 static-v1.va-api.net
      0.0.0.0 static.ads-twitter.com
      0.0.0.0 static.adsafeprotected.com

      @@ -608,7 +836,10 @@

      0.0.0.0 static.doubleclick.net.lan
      0.0.0.0 static.jampp.com
      0.0.0.0 static.karte.io
    + 0.0.0.0 static.smilewanted.com
      0.0.0.0 stats.g.doubleclick.net
    + 0.0.0.0 stjp.image-qoo10.jp
    + 0.0.0.0 storage.buzzsprout.com
      0.0.0.0 store-visit-to-haas.east.edge.storage-yahoo.jp
      0.0.0.0 store-visit-to-haas.east.edge.storage-yahoo.jp.lan
      0.0.0.0 sub.girlslab-info.net

      @@ -621,23 +852,34 @@

      0.0.0.0 sync.adkernel.com
      0.0.0.0 sync.adkernel.com.lan
      0.0.0.0 sync.admanmedia.com
    + 0.0.0.0 sync.dsp.reemo-ad.jp
      0.0.0.0 sync.im-apps.net
      0.0.0.0 sync.intentiq.com
      0.0.0.0 sync.logly.co.jp
    + 0.0.0.0 sync.richaudience.com
      0.0.0.0 sync6.im-apps.net
      0.0.0.0 sync6.im-apps.net.lan
    + 0.0.0.0 syndicatedsearch.goog.lan
    + 0.0.0.0 syndicatedsearch.goog.ts.net
      0.0.0.0 t-odx.op-mobile.opera.com
      0.0.0.0 t.adclr.jp
      0.0.0.0 t.adx.opera.com
      0.0.0.0 t.adx.opera.com.lan
    + 0.0.0.0 t.seenthis.se
    + 0.0.0.0 tadata.afafb.com
    + 0.0.0.0 tadata.afafb.com.lan
    + 0.0.0.0 tagan.adlightning.com
      0.0.0.0 tags.rd.linksynergy.com
    + 0.0.0.0 tags.srv.stackadapt.com
      0.0.0.0 td.doubleclick.net
      0.0.0.0 thumbnail.smartnews-ads.com
      0.0.0.0 tiger.clickhubs.com
      0.0.0.0 timecheck.moduleapps.com
      0.0.0.0 timecheck.moduleapps.com.lan
    + 0.0.0.0 timecheck.moduleapps.com.ts.net
      0.0.0.0 timedomaintech.datasink.sensorsdata.cn
      0.0.0.0 tivan.naver.com
    + 0.0.0.0 tlx.3lift.com
      0.0.0.0 torimochi.line-apps.com
      0.0.0.0 tp.adx.opera.com
      0.0.0.0 tr.acobt.tech

      @@ -646,15 +888,24 @@

      0.0.0.0 track-us.bidease.com
      0.0.0.0 track.adform.net
      0.0.0.0 track.adform.net.lan
    + 0.0.0.0 track.analytics-data.io.lan
    + 0.0.0.0 track.analytics-data.io.ts.net
    + 0.0.0.0 track.hubspot.com
    + 0.0.0.0 track.lacunads.com
      0.0.0.0 tracker.maticooads.com
    + 0.0.0.0 tracking-apac.tmbid.com
      0.0.0.0 tracking.aws.judge.me
      0.0.0.0 tracking.isappcloud.com
    + 0.0.0.0 tracks.liftyad.xyz
      0.0.0.0 trk.atomex.net
      0.0.0.0 ts.amazon-adsystem.com
      0.0.0.0 ts.foisonad.com
      0.0.0.0 tsuruhahdapp-proxy.moduleapps.com
    + 0.0.0.0 tus.foisonad.com
      0.0.0.0 uct.service.usercentrics.eu
      0.0.0.0 uh.nakanohito.jp
    + 0.0.0.0 ums.acuityplatform.com
    + 0.0.0.0 uncn.jp
      0.0.0.0 unified.adsafeprotected.com
      0.0.0.0 universe.send.microad.jp
      0.0.0.0 ups.analytics.yahoo.com

      @@ -666,9 +917,12 @@

      0.0.0.0 user-profile.isappcloud.com
      0.0.0.0 users.popinfo.jp
      0.0.0.0 ut.rd.linksynergy.com
    + 0.0.0.0 v.adsrvr.org
      0.0.0.0 v1-videocdn.gjhyss.com
      0.0.0.0 vad-bid.adsrvr.org
      0.0.0.0 vam-bid.adsrvr.org
    + 0.0.0.0 vast.doubleverify.com.ts.net
    + 0.0.0.0 vastevent.startappservice.com
      0.0.0.0 vc-brain.ndcpp-os.com
      0.0.0.0 vc-mirror.ndcpp-os.com
      0.0.0.0 vfw.amazon-adsystem.com

      @@ -687,6 +941,7 @@

      0.0.0.0 view.adjust.com
      0.0.0.0 view.adjust.com.lan
      0.0.0.0 vimp.u.send.microad.jp
    + 0.0.0.0 visitor-33across.omnitagjs.com
      0.0.0.0 vogue-mode-symphony.site
      0.0.0.0 vscode-cdn.z01.azurefd.net
      0.0.0.0 vscode-unpkg-gvgaavacadd3anb4.z01.azurefd.net

      @@ -695,19 +950,37 @@

      0.0.0.0 wangmeng.online
      0.0.0.0 weather-server.allawnos.com
      0.0.0.0 weather-server.allawnos.com.lan
    + 0.0.0.0 widget.intercom.io
    + 0.0.0.0 wimg.bypass.jp
      0.0.0.0 win.eskimi.com
    + 0.0.0.0 works.gsspcln.jp
    + 0.0.0.0 ws.tapjoyads.com
    + 0.0.0.0 www.appdraft.link
      0.0.0.0 www.awxcdn.com
      0.0.0.0 www.boredpanda.com
    + 0.0.0.0 www.brainlitix.netqa-analytics.com
    + 0.0.0.0 www.buzzsprout.com
      0.0.0.0 www.cross-a.net
    + 0.0.0.0 www.datadoghq-browser-agent.com
      0.0.0.0 www.google-analytics.com
    + 0.0.0.0 www.google-analytics.com.lan
    + 0.0.0.0 www.google-analytics.com.ts.net
    + 0.0.0.0 www.googleoptimize.com
      0.0.0.0 www.googletagmanager.com
    + 0.0.0.0 www.googletagmanager.com.ts.net
      0.0.0.0 www.npttech.com
    + 0.0.0.0 www.qoo10.jp
    + 0.0.0.0 www.roomloft.net
    + 0.0.0.0 www.thinkcrate.net
    + 0.0.0.0 www.tidysuite.netrtb.mfadsrvr.com
      0.0.0.0 wwwc.netcrew-analysis.jp
    + 0.0.0.0 x.everestop.io
      0.0.0.0 x9.shinobi.jp
      0.0.0.0 xa.shinobi.jp
      0.0.0.0 yads.c.yimg.jp
      0.0.0.0 yads.c.yimg.jp.lan
      0.0.0.0 yads.yjtag.yahoo.co.jp
    + 0.0.0.0 yicha.jp
      0.0.0.0 yj-a.p.adnxs.com
      0.0.0.0 yj.p.adnxs.com
      0.0.0.0 youngle.techgdl.youngle.tech

      @@ -722,12 +995,16 @@

      /image[0-9].pubmatic.com/
      ||*.sdk-hb.smaato.net
      0.0.0.0 546001125.collect.igodigital.com
    + 0.0.0.0 684d0d44.akstat.io
    + 0.0.0.0 684d0d4b.akstat.io
      0.0.0.0 a.teads.tv
      0.0.0.0 a.teads.tv.edgekey.net
      0.0.0.0 a.teads.tv.lan
      0.0.0.0 accdn.lpsnmedia.net
      0.0.0.0 ad-delivery.net
      0.0.0.0 ad.jp.ap.valuecommerce.com
    + 0.0.0.0 adclick.startappservice.com
    + 0.0.0.0 adimpression.startappservice.com
      0.0.0.0 adrta.com
      0.0.0.0 ads.adingo.jp
      0.0.0.0 ads.mozilla.org

      @@ -737,14 +1014,12 @@

      0.0.0.0 ads.rubiconproject.com.lan
      0.0.0.0 ads.rubiconproject.com.ts.net
      0.0.0.0 ads.stickyadstv.com
      0.0.0.0 adx.ads.vungle.com
      0.0.0.0 aml.valuecommerce.com
      0.0.0.0 aml.valuecommerce.com.lan
      0.0.0.0 amplify.outbrain.com
      0.0.0.0 analytics-tcp.mintegral.net.lan
    + 0.0.0.0 ap.lijit.com
      0.0.0.0 ap.srv.stackadapt.com
      0.0.0.0 ap.srv.stackadapt.com.lan
      0.0.0.0 apac-jp-sync.bidswitch.net

      @@ -760,10 +1035,6 @@

      0.0.0.0 api.superwall.me
      0.0.0.0 api.tradplusad.com
      0.0.0.0 apis.usonar.jp
      0.0.0.0 apps.rokt.com
      0.0.0.0 article.squadbeyond.com
      0.0.0.0 as.jivox.com

      @@ -799,6 +1070,8 @@

      0.0.0.0 cdn-kddi-prod.adobecqms.net
      0.0.0.0 cdn-lb.vungle.com
      0.0.0.0 cdn-lb.vungle.com.lan
    + 0.0.0.0 cdn-lb.vungle.com.ts.net
    + 0.0.0.0 cdn.browsiprod.com
      0.0.0.0 cdn.cookie.sync.usonar.jp
      0.0.0.0 cdn.doubleverify.com
      0.0.0.0 cdn.doubleverify.com.lan

      @@ -816,9 +1089,6 @@

      0.0.0.0 cf.vast.doubleverify.com
      0.0.0.0 cf.vast.doubleverify.com.cdn.cloudflare.net
      0.0.0.0 chartbeat.net
      0.0.0.0 cm.creativecdn.com
      0.0.0.0 cm.everesttech.net
      0.0.0.0 cm.smadex.com

      @@ -851,9 +1121,6 @@

      0.0.0.0 dalb.valuecommerce.com
      0.0.0.0 dalc.valuecommerce.com
      0.0.0.0 dalc.valuecommerce.com.lan
      0.0.0.0 displayf-tm.everesttech.net
      0.0.0.0 dl.listdl.com
      0.0.0.0 dossier.chartboost.com

      @@ -884,20 +1151,16 @@

      0.0.0.0 f.creativecdn.com
      0.0.0.0 fastlane.rubiconproject.com
      0.0.0.0 fastlane.rubiconproject.com.lan
      0.0.0.0 file.mysquadbeyond.com
      0.0.0.0 firebase-settings.crashlytics.com
      0.0.0.0 firebase-settings.crashlytics.com.lan
      0.0.0.0 firebase-settings.crashlytics.com.ts.net
      0.0.0.0 format.prod.cloud.ogury.io
      0.0.0.0 games.tresensa.com
      0.0.0.0 geo-tracker.smadex.com
      0.0.0.0 geoclue.smaato.net
      0.0.0.0 geolocation.onetrust.com
      0.0.0.0 ghent-gce-jp.bidswitch.net
      0.0.0.0 got.asia-se1gcp1.pubnative.net
      0.0.0.0 got.us-east4gcp1.pubnative.net
      0.0.0.0 graph-fallback.instagram.com

      @@ -906,6 +1169,7 @@

      0.0.0.0 graph.instagram.com.ts.net
      0.0.0.0 grid.bidswitch.net
      0.0.0.0 groundcontrol.rendering.sharethrough.com
    + 0.0.0.0 gtrace.mediago.io
      0.0.0.0 hblg.media.net
      0.0.0.0 hblg.media.net.lan
      0.0.0.0 hbopenbid-nrt10.pubmatic.com

      @@ -915,10 +1179,10 @@

      0.0.0.0 hbx.media.net
      0.0.0.0 htlb.casalemedia.com
      0.0.0.0 htlb.casalemedia.com.lan
      0.0.0.0 i.w55c.net
      0.0.0.0 i.w55c.net.lan
      0.0.0.0 id-ap.piano.io
    + 0.0.0.0 id.a-mx.com
      0.0.0.0 id.crwdcntrl.net
      0.0.0.0 id.rlcdn.com
      0.0.0.0 idsync.rlcdn.com

      @@ -937,7 +1201,10 @@

      0.0.0.0 js.hs-scripts.com
      0.0.0.0 js.hsforms.net
      0.0.0.0 js.slvrbullet.com
    + 0.0.0.0 kefirgames.helpshift.com
      0.0.0.0 l.evidon.com
    + 0.0.0.0 lbs.eu-1-id5-sync.com
    + 0.0.0.0 ldoe-analytics.kefirgames.ru.lan
      0.0.0.0 libs.outbrain.com
      0.0.0.0 link.rubiconproject.com
      0.0.0.0 live.chartboost.com

      @@ -947,6 +1214,7 @@

      0.0.0.0 log.yshp.r-oo.valuecommerce.com
      0.0.0.0 logs.ads.vungle.com
      0.0.0.0 logs.ads.vungle.com.lan
    + 0.0.0.0 logs.ads.vungle.com.ts.net
      0.0.0.0 logsdk.kwai-pro.com
      0.0.0.0 lpcdn.lpsnmedia.net
      0.0.0.0 lyr.pubmatic.com

      @@ -958,13 +1226,6 @@

      0.0.0.0 mcdp-sngdc1.outbrain.com
      0.0.0.0 mcdp-wndc1.outbrain.com
      0.0.0.0 mcdp-wndc1.outbrain.com.lan
      0.0.0.0 media.grid.bidswitch.net
      0.0.0.0 medias.cloud.ogury.io
      0.0.0.0 micro.rubiconproject.com

      @@ -979,20 +1240,11 @@

      0.0.0.0 mv.outbrain.com
      0.0.0.0 navvy.media.net
      0.0.0.0 new.ads.vungle.com
      0.0.0.0 odb.outbrain.com
      0.0.0.0 ow.pubmatic.com
      0.0.0.0 ow.pubmatic.com.lan
      0.0.0.0 p.teads.tv
      0.0.0.0 paid.outbrain.com
      0.0.0.0 pix.adrta.com
      0.0.0.0 pixel-apac.rubiconproject.com
      0.0.0.0 pixel-apac.rubiconproject.com.lan

      @@ -1053,7 +1305,6 @@

      0.0.0.0 secure-assets.rubiconproject.com
      0.0.0.0 settings.crashlytics.com
      0.0.0.0 settings.crashlytics.com.lan
      0.0.0.0 showads-nrt10.pubmatic.com
      0.0.0.0 simage2.pubmatic.com
      0.0.0.0 sin.creativecdn.com

      @@ -1078,9 +1329,6 @@

      0.0.0.0 static.chartbeat.com.lan
      0.0.0.0 statics.creativecdn.com
      0.0.0.0 statsf-tm.everesttech.net
      0.0.0.0 sync-tm.everesttech.net
      0.0.0.0 sync-tm.everesttech.net.lan
      0.0.0.0 sync.1rx.io

      @@ -1136,7 +1384,6 @@

      0.0.0.0 videoevents.outbrain.com
      0.0.0.0 videoexternalapi.outbrain.com
      0.0.0.0 videoexternalapi.outbrain.com.lan
      0.0.0.0 vita.pstatic.net
      0.0.0.0 vpaid.doubleverify.com
      0.0.0.0 vt.outbrain.com

      @@ -1280,6 +1527,7 @@

      0.0.0.0 pancake.apple.com
      0.0.0.0 push.apple.com
      0.0.0.0 sb.music.apple.com
    + 0.0.0.0 tr.iadsdk.apple.com

      # [ByteDance (tracker)]
      /p[0-9]*-ad.byteoversea.com/

      @@ -1304,7 +1552,6 @@

      0.0.0.0 api16-log-my.pangle.io
      0.0.0.0 api16-log-sg2.pangle.io.ts.net
      0.0.0.0 api16-log-va.pangle.io
      0.0.0.0 api39-sg.gts.byteoversea.net
      0.0.0.0 api39-va.gts.byteoversea.net
      0.0.0.0 api39.gtm.byteoversea.net

      @@ -1729,6 +1976,7 @@

      0.0.0.0 frontier.tiktokv.com
      0.0.0.0 frontier.tiktokv.com.lan
      0.0.0.0 gecko-sg.tiktokv.com
    + 0.0.0.0 gecko-sg.tiktokv.com.lan
      0.0.0.0 i.isnssdk.com
      0.0.0.0 i.isnssdk.com.lan
      0.0.0.0 image-sg.tiktokv.com

      @@ -1774,6 +2022,8 @@

      0.0.0.0 p19-heycan-sign-va.ibyteimg.com
      0.0.0.0 p19-push-sign-va.ibyteimg.com
      0.0.0.0 p21-ad-sg.ibyteimg.com
    + 0.0.0.0 pangolin16.sgsnssdk.com
    + 0.0.0.0 pangolin16.sgsnssdk.com.ts.net
      0.0.0.0 pitaya-sg.tiktokv.com
      0.0.0.0 pitaya-sg.tiktokv.com.lan
      0.0.0.0 pitaya.tiktokv.com

      @@ -1937,7 +2187,6 @@

      0.0.0.0 resolver.msg.global.xiaomi.net
      0.0.0.0 resolver.msg.global.xiaomi.net.lan
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com.lan
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com.ts.net
      0.0.0.0 sdkconfig.intl.xiaomi.com

      @@ -2040,6 +2289,7 @@

      0.0.0.0 edgw.adingo.jp
      0.0.0.0 er.fivecdm.com
      0.0.0.0 er.fivecdm.com.lan
    + 0.0.0.0 er.fivecdm.com.ts.net
      0.0.0.0 eu-u.openx.net
      0.0.0.0 fledge.as.criteo.com
      0.0.0.0 fledge.criteo.com
    ```

## Commit: [4de47df](https://github.com/virtualitypage/AdGuardHome_Filters/commit/4de47df08c6a0ed38a1ec7d229a0f7d73d6f3fea) - 2025-11-11

### Date

- 2025/11/11 20:38:43

### Change

- reject/Reject_domain.txt
    ```yaml
    BEFORE:
      # References: none
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/reject/Reject_domain.txt
      #
    - # Last modified: 31 August 2025
      #

      # [拒否リクエスト]

      @@ -734,6 +734,8 @@

      0.0.0.0 ads.pubmatic.com
      0.0.0.0 ads.pubmatic.com.lan
      0.0.0.0 ads.rubiconproject.com
      0.0.0.0 ads.stickyadstv.com
      0.0.0.0 adx-f.ads.heytapmobile.com
      0.0.0.0 adx-f.ads.heytapmobile.com.lan

      @@ -770,6 +772,7 @@

      0.0.0.0 assets-v2.article.squadbeyond.com
      0.0.0.0 assets.jivox.com
      0.0.0.0 assets.mintegral.com.lan
      0.0.0.0 at.outbrain.com
      0.0.0.0 at.outbrain.com.lan
      0.0.0.0 at.teads.tv

      @@ -799,6 +802,7 @@

      0.0.0.0 cdn.cookie.sync.usonar.jp
      0.0.0.0 cdn.doubleverify.com
      0.0.0.0 cdn.doubleverify.com.lan
      0.0.0.0 cdn.krxd.net
      0.0.0.0 cdn.krxd.net.lan
      0.0.0.0 cdn.liftoff-creatives.io

      @@ -824,6 +828,7 @@

      0.0.0.0 collector.tracking.io.lan
      0.0.0.0 config.ads.vungle.com
      0.0.0.0 config.ads.vungle.com.lan
      0.0.0.0 connect.tapjoy.com
      0.0.0.0 connect.tapjoy.com.lan
      0.0.0.0 content-static.pstatic.net

      @@ -859,6 +864,7 @@

      0.0.0.0 dsum-sec.casalemedia.com.lan
      0.0.0.0 dsum.casalemedia.com
      0.0.0.0 dsum.casalemedia.com.lan
      0.0.0.0 e.crashlytics.com
      0.0.0.0 e.crashlytics.com.lan
      0.0.0.0 east.srv.stackadapt.com

      @@ -882,6 +888,7 @@

      0.0.0.0 file.mysquadbeyond.com
      0.0.0.0 firebase-settings.crashlytics.com
      0.0.0.0 firebase-settings.crashlytics.com.lan
      0.0.0.0 format.prod.cloud.ogury.io
      0.0.0.0 games-community-gl.heytapmobile.com
      0.0.0.0 games-community-gl.heytapmobile.com.lan

      @@ -892,9 +899,11 @@

      0.0.0.0 ghent-gce-jp.bidswitch.net
      0.0.0.0 global-search-gl.heytapmobile.com
      0.0.0.0 got.asia-se1gcp1.pubnative.net
      0.0.0.0 graph-fallback.instagram.com
      0.0.0.0 graph.instagram.com
      0.0.0.0 graph.instagram.com.lan
      0.0.0.0 grid.bidswitch.net
      0.0.0.0 groundcontrol.rendering.sharethrough.com
      0.0.0.0 hblg.media.net

      @@ -922,9 +931,15 @@

      0.0.0.0 ipv6.adrta.com
      0.0.0.0 itag.valuecommerce.com
      0.0.0.0 itrack2.valuecommerce.com
      0.0.0.0 js.slvrbullet.com
      0.0.0.0 l.evidon.com
      0.0.0.0 libs.outbrain.com
      0.0.0.0 live.chartboost.com
      0.0.0.0 live.chartboost.com.lan
      0.0.0.0 log.outbrainimg.com

      @@ -982,6 +997,7 @@

      0.0.0.0 pixel-apac.rubiconproject.com
      0.0.0.0 pixel-apac.rubiconproject.com.lan
      0.0.0.0 pixel-eu.rubiconproject.com
      0.0.0.0 pixel-us-east.rubiconproject.com
      0.0.0.0 pixel-us-west.rubiconproject.com
      0.0.0.0 pixel.rubiconproject.com

      @@ -1014,6 +1030,7 @@

      0.0.0.0 r.casalemedia.com.lan
      0.0.0.0 reports.crashlytics.com
      0.0.0.0 reports.crashlytics.com.lan
      0.0.0.0 rpc.tapjoy.com
      0.0.0.0 rpc.tapjoy.com.lan
      0.0.0.0 rtb-csync-apac1.smartadserver.com

      @@ -1043,6 +1060,7 @@

      0.0.0.0 sin.creativecdn.com.lan
      0.0.0.0 spadsync.com
      0.0.0.0 spadsync.com.lan
      0.0.0.0 srv.stackadapt.com
      0.0.0.0 ssbsync-apac1.smartadserver.com
      0.0.0.0 ssbsync-global.smartadserver.com

      @@ -1135,6 +1153,7 @@

      0.0.0.0 x.bidswitch.net
      0.0.0.0 x.bidswitch.net.lan
      0.0.0.0 x.bidswitch.netghent-gce-jp.bidswitch.net
      0.0.0.0 zem.outbrainimg.com

      # [Adjust と連携されたアドネットワーク]

      @@ -1188,24 +1207,42 @@

      0.0.0.0 gcdsdk.appsflyersdk.com
      0.0.0.0 impression.appsflyer.com
      0.0.0.0 impression.appsflyer.com.lan
      0.0.0.0 inapps.appsflyer.com
      0.0.0.0 inapps.appsflyer.com.lan
      0.0.0.0 inapps.appsflyersdk.com
      0.0.0.0 jtlbyt-adrevenue.appsflyersdk.com
      0.0.0.0 jtlbyt-adrevenue.appsflyersdk.com.lan
      0.0.0.0 launches.appsflyer.com
      0.0.0.0 launches.appsflyersdk.com
      0.0.0.0 launches.appsflyersdk.com.lan
      0.0.0.0 luakl2-adrevenue.appsflyersdk.com
      0.0.0.0 luakl2-impression.appsflyersdk.com
      0.0.0.0 orspid-adrevenue.appsflyersdk.com
      0.0.0.0 privacy-sandbox.appsflyersdk.com
      0.0.0.0 qbhozv-gcdsdk.appsflyersdk.com
      0.0.0.0 qkjbfq-gcdsdk.appsflyersdk.com
      0.0.0.0 register.appsflyer.com
      0.0.0.0 statgw.devtodev.com.lan
      0.0.0.0 tys9m3-dlsdk.appsflyersdk.com
      0.0.0.0 upj2lp-pia.appsflyersdk.com
      0.0.0.0 viap.appsflyersdk.com
      0.0.0.0 wa.appsflyer.com
      0.0.0.0 websdk.appsflyer.com

      @@ -1252,15 +1289,31 @@

      /v[0-9]*-ad.byteoversea.com/
      /vas-alisg[0-9]*.byteoversea.com/
      0.0.0.0 api.service.kix1a.g.byteoversea.net
      0.0.0.0 api16-access-ttp.tiktokpangle-b.us.lan
      0.0.0.0 api16-access-wf-sg.pangle.io.lan
      0.0.0.0 api39-sg.gts.byteoversea.net
      0.0.0.0 api39-va.gts.byteoversea.net
      0.0.0.0 api39.gtm.byteoversea.net
      0.0.0.0 frontier.byteoversea.com
      0.0.0.0 frontier.byteoversea.com.lan
      0.0.0.0 gecko-pangle-sg.byteoversea.com
      0.0.0.0 gecko-pangle-sg.byteoversea.com.lan
      0.0.0.0 gecko-sg.byteoversea.com
      0.0.0.0 gecko-sg.byteoversea.com.lan
      0.0.0.0 i.byteoversea.com

      @@ -1279,15 +1332,20 @@

      0.0.0.0 sf16-static.i18n-pglstatp.com.lan
      0.0.0.0 sf19-static.i18n-pglstatp.com
      0.0.0.0 sf19-static.i18n-pglstatp.com.lan
      0.0.0.0 sgali-mcs.byteoversea.com
      0.0.0.0 starling-sg.byteoversea.com
      0.0.0.0 tnc16-useast1a.byteoversea.com
      0.0.0.0 tnc16-useast1a.byteoversea.com.lan
      0.0.0.0 vcs-sg.byteintl.com
      0.0.0.0 vcs-sg.byteintl.com.lan

      # [dbankcloud]
      0.0.0.0 api-dra.theme.dbankcloud.cn
      0.0.0.0 api-dra.theme.dbankcloud.com
      0.0.0.0 configdownload-dre.dbankcdn.com
      0.0.0.0 connect-dra.dbankcloud.cn

      @@ -1297,34 +1355,50 @@

      0.0.0.0 dnkeeper.platform.dbankcloud.com
      0.0.0.0 dnkeeper.platform.dbankcloud.com.lan
      0.0.0.0 events-dra.op.dbankcloud.cn
      0.0.0.0 events-dra.op.dbankcloud.com
      0.0.0.0 events-dra.op.dbankcloud.com.lan
      0.0.0.0 grs.dbankcloud.asia
      0.0.0.0 grs.dbankcloud.cn
      0.0.0.0 grs.dbankcloud.cn.lan
      0.0.0.0 grs.dbankcloud.com
      0.0.0.0 grs.dbankcloud.eu
      0.0.0.0 grs.dbankcloud.eu.lan
      0.0.0.0 grs.platform.dbankcloud.ru
      0.0.0.0 grs.platform.dbankcloud.ru.lan
      0.0.0.0 h5hosting.dbankcdn.com
      0.0.0.0 h5hosting.dbankcdn.com.lan
      0.0.0.0 map-dra.platform.dbankcloud.cn
      0.0.0.0 map-dra.platform.dbankcloud.com
      0.0.0.0 openlocation-dra.platform.dbankcloud.com
      0.0.0.0 openlocation-dra.platform.dbankcloud.com.lan
      0.0.0.0 pushtrs6.push.dbankcloud.com
      0.0.0.0 sdkserver-dra.op.dbankcloud.cn
      0.0.0.0 sdkserver-dra.op.dbankcloud.com
      0.0.0.0 sdkserver-dra.op.dbankcloud.com.lan
      0.0.0.0 store-dra.hispace.dbankcloud.com
      0.0.0.0 tsms-dra.security.dbankcloud.cn
      0.0.0.0 tsms-dra.security.dbankcloud.cn.lan
      0.0.0.0 tsms-dra.security.dbankcloud.com
      0.0.0.0 videocontent-dra.himovie.dbankcloud.com
      0.0.0.0 videocontent-dra.himovie.dbankcloud.com.lan
      0.0.0.0 weather-dre.weather.dbankcloud.com
      0.0.0.0 weather-dre.weather.dbankcloud.com.lan

      # [facebook]
      /ep[1-9].facebook.com/

      @@ -1363,6 +1437,7 @@

      0.0.0.0 z-p42-chat-e2ee-ig.facebook.com.lan

      # [huawei]
      0.0.0.0 configserver-dra.platform.hicloud.com
      0.0.0.0 configserver-dre.platform.hicloud.com.lan
      0.0.0.0 configserver.platform.hicloud.com

      @@ -1371,14 +1446,17 @@

      0.0.0.0 connect-drcn.hispace.hicloud.com
      0.0.0.0 connectivitycheck.cbg-app.huawei.com
      0.0.0.0 connectivitycheck.cbg-app.huawei.com.lan
      0.0.0.0 connectivitycheck.platform.hicloud.com
      0.0.0.0 connectivitycheck.platform.hicloud.com.lan
      0.0.0.0 dnkeeper.hicloud.com
      0.0.0.0 events-dra.op.hicloud.com
      0.0.0.0 grs.hicloud.com
      0.0.0.0 grs.hicloud.com.lan
      0.0.0.0 hwid.platform.hicloud.com
      0.0.0.0 hwid.platform.hicloud.com.lan
      0.0.0.0 metrics-dra.dt.hicloud.com
      0.0.0.0 metrics-dra.dt.hicloud.com.lan
      0.0.0.0 metrics3.data.hicloud.com

      @@ -1390,6 +1468,7 @@

      0.0.0.0 sdkserver-dre.op.hicloud.com.lan
      0.0.0.0 store.hispace.hicloud.com
      0.0.0.0 store.hispace.hicloud.com.lan

      # [inmobi (モバイル広告プラットフォーム)]
      0.0.0.0 ac.onedsp.inmobi.com

      @@ -1397,12 +1476,14 @@

      0.0.0.0 acj.onedsp.inmobi.com
      0.0.0.0 adq.w.inmobi.com
      0.0.0.0 api.cmp.inmobi.com
      0.0.0.0 b.de.inmobi.com
      0.0.0.0 b.de.inmobi.com.lan
      0.0.0.0 c-eus.w.inmobi.com
      0.0.0.0 cmp.inmobi.com
      0.0.0.0 config.inmobi.com
      0.0.0.0 config.inmobi.com.lan
      0.0.0.0 dspbeacons.error.ihasdsp.inmobi.com
      0.0.0.0 dspbeacons.error.ihasdsp.inmobi.com.lan
      0.0.0.0 dspbeacons.ihasdsp.inmobi.com

      @@ -1477,8 +1558,11 @@


      # [onelink (associated with AppsFlyer)]
      0.0.0.0 go.onelink.me
      0.0.0.0 gravityapp.onelink.me
      0.0.0.0 impressions.onelink.me
      0.0.0.0 paypay.onelink.me
      0.0.0.0 shortswave.onelink.me
      0.0.0.0 snssdk1180.onelink.me

      @@ -1518,6 +1602,7 @@

      0.0.0.0 st001015pinterest.instabug.com
      0.0.0.0 trk.pinterest.com
      0.0.0.0 trk.pinterest.com.lan
      0.0.0.0 trk2.pinterest.com

      # [qualcomm]

      @@ -1552,6 +1637,8 @@

      /mssdk[0-9]*-normal-alisg.tiktokv.com/
      /oec[0-9]*-normal-alisg.tiktokv.com/
      /p[0-9]*-amd-va.tiktokcdn.com/
      /p[0-9]*-h1-sign-sg.ibyteimg.com/
      /p[0-9]*-heycan-img-sign-sg.ibyteimg.com/
      /p[0-9]*-sg.tiktokcdn.com.lan/

      @@ -1560,6 +1647,8 @@

      /p[0-9]*-sign.tiktokcdn-us.com/
      /p[0-9]*-tiktokcdn-com.akamaized.net/
      /p[0-9]*-tiktokyoyo-va.ibyteimg.com/
      /p[0-9]*-useast2a.tiktokcdn.com/
      /p[0-9]*-vimo-sg.ibyteimg.com/
      /p[0-9]*-webcast.tiktokcdn.com/

      @@ -1668,6 +1757,7 @@

      0.0.0.0 p16-heycan-sign-va.ibyteimg.com
      0.0.0.0 p16-lp-sg.ibyteimg.com
      0.0.0.0 p16-push-sign-va.ibyteimg.com
      0.0.0.0 p16-tikcast-game-sign-sg.ibyteimg.com
      0.0.0.0 p16-tiktok-dm-sticker-sign-sg.ibyteimg.com
      0.0.0.0 p16-tiktok-dm-sticker-sign-va.ibyteimg.com

      @@ -1710,8 +1800,10 @@

      0.0.0.0 tnc0-normal-my.tiktokv.com.lan
      0.0.0.0 tnc16-alisg.isnssdk.com
      0.0.0.0 tnc16-alisg.isnssdk.com.lan
      0.0.0.0 tnc16-useast1a.isnssdk.com
      0.0.0.0 tnc16-useast1a.isnssdk.com.lan
      0.0.0.0 tos-quic-kix1b.tiktokcdn.com^$client=~192.168.8.117
      0.0.0.0 vcs-sg.tiktokv.com
      0.0.0.0 vcs-sg.tiktokv.com.lan

      @@ -1724,6 +1816,7 @@

      ||assets-*.lunalabs.io
      0.0.0.0 a-adq.mediation.unity3d.com
      0.0.0.0 ae.iads.unity3d.com
      0.0.0.0 aps-attribution.unityads.unity3d.com
      0.0.0.0 assets.lunalabs.io
      0.0.0.0 auction-load.unityads.unity3d.com

      @@ -1740,26 +1833,36 @@

      0.0.0.0 config.uca.cloud.unity3d.com
      0.0.0.0 configv2.unityads.unity3d.com
      0.0.0.0 configv2.unityads.unity3d.com.lan
      0.0.0.0 content.offerwall.unity3d.com
      0.0.0.0 events.mz.unity3d.com
      0.0.0.0 gateway.unityads.unity3d.com
      0.0.0.0 gateway.unityads.unity3d.com.lan
      0.0.0.0 gw-ext.mediation.unity3d.com
      0.0.0.0 gw-is.iads.unity3d.com
      0.0.0.0 gw-rv.iads.unity3d.com
      0.0.0.0 gw-rv.iads.unity3d.com.lan
      0.0.0.0 gw.mediation.unity3d.com
      0.0.0.0 gw.mediation.unity3d.com.lan
      0.0.0.0 hbevents-public.mz.unity3d.com
      0.0.0.0 html-uap.iads.unity3d.com
      0.0.0.0 httpkafka.unityads.unity3d.com
      0.0.0.0 httpkafka.unityads.unity3d.com.lan
      0.0.0.0 i-adq.mediation.unity3d.com
      0.0.0.0 i-adq.mediation.unity3d.com.lan
      0.0.0.0 i-sdk.mediation.unity3d.com
      0.0.0.0 i-sdk.mediation.unity3d.com.lan
      0.0.0.0 icon-uap.iads.unity3d.com
      0.0.0.0 img-dyn-uap.iads.unity3d.com
      0.0.0.0 o-adq.mediation.unity3d.com
      0.0.0.0 o-iab-imp-counters.mediation.unity3d.com
      0.0.0.0 o-iab-notifications.mediation.unity3d.com

      @@ -1767,13 +1870,19 @@

      0.0.0.0 o-pxt.iads.unity3d.com
      0.0.0.0 o-sdk.mediation.unity3d.com
      0.0.0.0 o-sdk.mediation.unity3d.com.lan
      0.0.0.0 o.iads.unity3d.com
      0.0.0.0 o.iads.unity3d.com.lan
      0.0.0.0 o.isx.unity3d.com
      0.0.0.0 perf-events.cloud.unity3d.com
      0.0.0.0 publisher-event.unityads.unity3d.com
      0.0.0.0 scar.unityads.unity3d.com
      0.0.0.0 scar.unityads.unity3d.com.lan
      0.0.0.0 thind.unityads.unity3d.com
      0.0.0.0 vid-uap.iads.unity3d.com
      0.0.0.0 w.isx.unity3d.com

      @@ -1786,6 +1895,7 @@

      0.0.0.0 api.account.xiaomi.com
      0.0.0.0 api.account.xiaomi.com.lan
      0.0.0.0 api.ad.intl.xiaomi.com
      0.0.0.0 api.aurogon.intl.miui.com
      0.0.0.0 api.sec.intl.miui.com
      0.0.0.0 api.video.intl.xiaomi.com

      @@ -1804,7 +1914,10 @@

      0.0.0.0 connect.intl.rom.miui.com.lan
      0.0.0.0 find.api.micloud.xiaomi.net
      0.0.0.0 find.api.micloud.xiaomi.net.lan
      0.0.0.0 findapi.micloud.xiaomi.net
      0.0.0.0 flash.sec.intl.miui.com
      0.0.0.0 gallery.market.xiaomi.com
      0.0.0.0 global.market.xiaomi.com

      @@ -1814,15 +1927,19 @@

      0.0.0.0 jupiter.intl.sys.miui.com
      0.0.0.0 mcc-intl.inf.miui.com
      0.0.0.0 mcc-intl.inf.miui.com.lan
      0.0.0.0 mcc.intl.inf.miui.com
      0.0.0.0 mcc.intl.inf.miui.com.lan
      0.0.0.0 mqs-log.miui.com
      0.0.0.0 pi.ias.xiaomi.com
      0.0.0.0 privacy.api.intl.miui.com
      0.0.0.0 resolver.msg.global.xiaomi.net
      0.0.0.0 resolver.msg.global.xiaomi.net.lan
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com.lan
      0.0.0.0 sdkconfig.intl.xiaomi.com
      0.0.0.0 sdkconfig.intl.xiaomi.com.lan
      0.0.0.0 sdkconfig.xiaomi.com

      @@ -1843,6 +1960,7 @@

      0.0.0.0 update.intl.miui.com
      0.0.0.0 weatherapi.intl.xiaomi.com
      0.0.0.0 weatherapi.intl.xiaomi.com.lan

      # [その他 (広告・追跡)]
      # https://btonews.blog.fc2.com/blog-entry-410.html

      @@ -1861,10 +1979,13 @@

      0.0.0.0 accuweather-d.openx.net
      0.0.0.0 ad2.fivecdm.com
      0.0.0.0 ad2.fivecdm.com.lan
      0.0.0.0 adchk.fivecdm.com
      0.0.0.0 adchk.fivecdm.com.lan
      0.0.0.0 adgen.socdm.com
      0.0.0.0 ads.as.criteo.com
      0.0.0.0 adserver.cxad.cxense.com
      0.0.0.0 andromeda.iad-01.braze.com
      0.0.0.0 apc.socdm.com

      @@ -1873,6 +1994,7 @@

      0.0.0.0 api.karte.io
      0.0.0.0 appconf.rfp.fout.jp
      0.0.0.0 appconf.rfp.fout.jp.lan
      0.0.0.0 aw.dw.impact-ad.jp
      0.0.0.0 b.karte.io
      0.0.0.0 bc2.fivecdm.com

      @@ -1910,6 +2032,7 @@

      0.0.0.0 d.socdm.com.lan
      0.0.0.0 dad.ladsp.com
      0.0.0.0 dis.criteo.com
      0.0.0.0 dsp.fout.jp
      0.0.0.0 dsp.fout.jp.lan
      0.0.0.0 ecr.ladsp.com

      @@ -1925,6 +2048,8 @@

      0.0.0.0 frtn.socdm.com
      0.0.0.0 g2.gumgum.com
      0.0.0.0 g2.gumgum.com.lan
      0.0.0.0 gdn.socdm.com
      0.0.0.0 genieejapan-d.openx.net
      0.0.0.0 google-bidout-d.openx.net

      @@ -1960,6 +2085,7 @@

      0.0.0.0 log.fivecdm.com
      0.0.0.0 ly.my.sentry.io
      0.0.0.0 ly.my.sentry.io.lan
      0.0.0.0 match.taboola.com
      0.0.0.0 measurement-api.criteo.com
      0.0.0.0 metrics.brightcove.com

      @@ -1972,6 +2098,7 @@

      0.0.0.0 ntjp.mieru-ca.com
      0.0.0.0 nttresonant-d.openx.net
      0.0.0.0 oajs.openx.net
      0.0.0.0 opps.taboola.com
      0.0.0.0 p1cluster.cxense.com
      0.0.0.0 pa.openx.net

      @@ -1988,6 +2115,8 @@

      0.0.0.0 px.ladsp.com
      0.0.0.0 rtb.gumgum.com
      0.0.0.0 rtb.jp2.as.criteo.com
      0.0.0.0 rtb.openx.net
      0.0.0.0 rtb.openx.net.lan
      0.0.0.0 rubicon.socdm.com

      @@ -2066,6 +2195,11 @@

      0.0.0.0 loadm.exelator.com
      0.0.0.0 loadus.exelator.com

      # [bitdefender アンチウイルス検知]
      # https://answers.microsoft.com/en-us/windows/forum/all/sudden-threat-from-antivirus-doing-nothing/a8e09462-36f9-4acb-b178-3005d731148a
      0.0.0.0 cadmus.script.ac
    ```

    ```yaml
    AFTER:
      # References: none
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/reject/Reject_domain.txt
      #
    + # Last modified: 11 November 2025
      #

      # [拒否リクエスト]

      @@ -734,6 +734,8 @@

      0.0.0.0 ads.pubmatic.com
      0.0.0.0 ads.pubmatic.com.lan
      0.0.0.0 ads.rubiconproject.com
    + 0.0.0.0 ads.rubiconproject.com.lan
    + 0.0.0.0 ads.rubiconproject.com.ts.net
      0.0.0.0 ads.stickyadstv.com
      0.0.0.0 adx-f.ads.heytapmobile.com
      0.0.0.0 adx-f.ads.heytapmobile.com.lan

      @@ -770,6 +772,7 @@

      0.0.0.0 assets-v2.article.squadbeyond.com
      0.0.0.0 assets.jivox.com
      0.0.0.0 assets.mintegral.com.lan
    + 0.0.0.0 assets.mintegral.com.ts.net
      0.0.0.0 at.outbrain.com
      0.0.0.0 at.outbrain.com.lan
      0.0.0.0 at.teads.tv

      @@ -799,6 +802,7 @@

      0.0.0.0 cdn.cookie.sync.usonar.jp
      0.0.0.0 cdn.doubleverify.com
      0.0.0.0 cdn.doubleverify.com.lan
    + 0.0.0.0 cdn.doubleverify.com.ts.net
      0.0.0.0 cdn.krxd.net
      0.0.0.0 cdn.krxd.net.lan
      0.0.0.0 cdn.liftoff-creatives.io

      @@ -824,6 +828,7 @@

      0.0.0.0 collector.tracking.io.lan
      0.0.0.0 config.ads.vungle.com
      0.0.0.0 config.ads.vungle.com.lan
    + 0.0.0.0 config.ads.vungle.com.ts.net
      0.0.0.0 connect.tapjoy.com
      0.0.0.0 connect.tapjoy.com.lan
      0.0.0.0 content-static.pstatic.net

      @@ -859,6 +864,7 @@

      0.0.0.0 dsum-sec.casalemedia.com.lan
      0.0.0.0 dsum.casalemedia.com
      0.0.0.0 dsum.casalemedia.com.lan
    + 0.0.0.0 dts.startappservice.com
      0.0.0.0 e.crashlytics.com
      0.0.0.0 e.crashlytics.com.lan
      0.0.0.0 east.srv.stackadapt.com

      @@ -882,6 +888,7 @@

      0.0.0.0 file.mysquadbeyond.com
      0.0.0.0 firebase-settings.crashlytics.com
      0.0.0.0 firebase-settings.crashlytics.com.lan
    + 0.0.0.0 firebase-settings.crashlytics.com.ts.net
      0.0.0.0 format.prod.cloud.ogury.io
      0.0.0.0 games-community-gl.heytapmobile.com
      0.0.0.0 games-community-gl.heytapmobile.com.lan

      @@ -892,9 +899,11 @@

      0.0.0.0 ghent-gce-jp.bidswitch.net
      0.0.0.0 global-search-gl.heytapmobile.com
      0.0.0.0 got.asia-se1gcp1.pubnative.net
    + 0.0.0.0 got.us-east4gcp1.pubnative.net
      0.0.0.0 graph-fallback.instagram.com
      0.0.0.0 graph.instagram.com
      0.0.0.0 graph.instagram.com.lan
    + 0.0.0.0 graph.instagram.com.ts.net
      0.0.0.0 grid.bidswitch.net
      0.0.0.0 groundcontrol.rendering.sharethrough.com
      0.0.0.0 hblg.media.net

      @@ -922,9 +931,15 @@

      0.0.0.0 ipv6.adrta.com
      0.0.0.0 itag.valuecommerce.com
      0.0.0.0 itrack2.valuecommerce.com
    + 0.0.0.0 js.appboycdn.com
    + 0.0.0.0 js.hs-analytics.net
    + 0.0.0.0 js.hs-banner.com
    + 0.0.0.0 js.hs-scripts.com
    + 0.0.0.0 js.hsforms.net
      0.0.0.0 js.slvrbullet.com
      0.0.0.0 l.evidon.com
      0.0.0.0 libs.outbrain.com
    + 0.0.0.0 link.rubiconproject.com
      0.0.0.0 live.chartboost.com
      0.0.0.0 live.chartboost.com.lan
      0.0.0.0 log.outbrainimg.com

      @@ -982,6 +997,7 @@

      0.0.0.0 pixel-apac.rubiconproject.com
      0.0.0.0 pixel-apac.rubiconproject.com.lan
      0.0.0.0 pixel-eu.rubiconproject.com
    + 0.0.0.0 pixel-eu.rubiconproject.com.lan
      0.0.0.0 pixel-us-east.rubiconproject.com
      0.0.0.0 pixel-us-west.rubiconproject.com
      0.0.0.0 pixel.rubiconproject.com

      @@ -1014,6 +1030,7 @@

      0.0.0.0 r.casalemedia.com.lan
      0.0.0.0 reports.crashlytics.com
      0.0.0.0 reports.crashlytics.com.lan
    + 0.0.0.0 reports.crashlytics.com.ts.net
      0.0.0.0 rpc.tapjoy.com
      0.0.0.0 rpc.tapjoy.com.lan
      0.0.0.0 rtb-csync-apac1.smartadserver.com

      @@ -1043,6 +1060,7 @@

      0.0.0.0 sin.creativecdn.com.lan
      0.0.0.0 spadsync.com
      0.0.0.0 spadsync.com.lan
    + 0.0.0.0 spadsync.com.ts.net
      0.0.0.0 srv.stackadapt.com
      0.0.0.0 ssbsync-apac1.smartadserver.com
      0.0.0.0 ssbsync-global.smartadserver.com

      @@ -1135,6 +1153,7 @@

      0.0.0.0 x.bidswitch.net
      0.0.0.0 x.bidswitch.net.lan
      0.0.0.0 x.bidswitch.netghent-gce-jp.bidswitch.net
    + 0.0.0.0 yield-manager.browsiprod.com
      0.0.0.0 zem.outbrainimg.com

      # [Adjust と連携されたアドネットワーク]

      @@ -1188,24 +1207,42 @@

      0.0.0.0 gcdsdk.appsflyersdk.com
      0.0.0.0 impression.appsflyer.com
      0.0.0.0 impression.appsflyer.com.lan
    + 0.0.0.0 impression.appsflyer.com.ts.net
      0.0.0.0 inapps.appsflyer.com
      0.0.0.0 inapps.appsflyer.com.lan
      0.0.0.0 inapps.appsflyersdk.com
    + 0.0.0.0 jarlio.inapps.appsflyersdk.com
    + 0.0.0.0 jarlio.launches.appsflyersdk.com
    + 0.0.0.0 jarlio.launches.appsflyersdk.com.lan
    + 0.0.0.0 jarlio.launches.appsflyersdk.com.ts.net
      0.0.0.0 jtlbyt-adrevenue.appsflyersdk.com
      0.0.0.0 jtlbyt-adrevenue.appsflyersdk.com.lan
      0.0.0.0 launches.appsflyer.com
      0.0.0.0 launches.appsflyersdk.com
      0.0.0.0 launches.appsflyersdk.com.lan
    + 0.0.0.0 launches.appsflyersdk.com.ts.net
      0.0.0.0 luakl2-adrevenue.appsflyersdk.com
      0.0.0.0 luakl2-impression.appsflyersdk.com
      0.0.0.0 orspid-adrevenue.appsflyersdk.com
    + 0.0.0.0 otpi0g-dlsdk.appsflyersdk.com
      0.0.0.0 privacy-sandbox.appsflyersdk.com
      0.0.0.0 qbhozv-gcdsdk.appsflyersdk.com
    + 0.0.0.0 qkdasj-adrevenue.appsflyersdk.com
      0.0.0.0 qkjbfq-gcdsdk.appsflyersdk.com
      0.0.0.0 register.appsflyer.com
    + 0.0.0.0 snjqhu-dlsdk.appsflyersdk.com
      0.0.0.0 statgw.devtodev.com.lan
    + 0.0.0.0 tfqwb2-register.appsflyersdk.com
      0.0.0.0 tys9m3-dlsdk.appsflyersdk.com
    + 0.0.0.0 upj2lp-inapps.appsflyersdk.com
    + 0.0.0.0 upj2lp-inapps.appsflyersdk.com.lan
    + 0.0.0.0 upj2lp-launches.appsflyersdk.com
    + 0.0.0.0 upj2lp-launches.appsflyersdk.com.lan
      0.0.0.0 upj2lp-pia.appsflyersdk.com
    + 0.0.0.0 vd8qif.adrevenue.appsflyersdk.com
    + 0.0.0.0 vd8qif.conversions.appsflyersdk.com
    + 0.0.0.0 vd8qif.inapps.appsflyersdk.com
    + 0.0.0.0 vd8qif.launches.appsflyersdk.com
      0.0.0.0 viap.appsflyersdk.com
      0.0.0.0 wa.appsflyer.com
      0.0.0.0 websdk.appsflyer.com

      @@ -1252,15 +1289,31 @@

      /v[0-9]*-ad.byteoversea.com/
      /vas-alisg[0-9]*.byteoversea.com/
      0.0.0.0 api.service.kix1a.g.byteoversea.net
    + 0.0.0.0 api16-access-gcp.pangle-b.ioio.ts.net
    + 0.0.0.0 api16-access-sg.pangle.io.ts.net
    + 0.0.0.0 api16-access-ttp-b.tiktokpangle-b.us.ts.net
    + 0.0.0.0 api16-access-ttp-b.tiktokpangle.us.ts.net
      0.0.0.0 api16-access-ttp.tiktokpangle-b.us.lan
    + 0.0.0.0 api16-access-ttp.tiktokpangle-b.us.ts.net
    + 0.0.0.0 api16-access-ttp.tiktokpangle.us.ts.net
    + 0.0.0.0 api16-access-wf-sg.pangle.io
      0.0.0.0 api16-access-wf-sg.pangle.io.lan
    + 0.0.0.0 api16-event-sg.pangle.io
    + 0.0.0.0 api16-event-va.pangle.io.lan
    + 0.0.0.0 api16-event-va.pangle.io.ts.net
    + 0.0.0.0 api16-log-my.pangle.io
    + 0.0.0.0 api16-log-sg2.pangle.io.ts.net
    + 0.0.0.0 api16-log-va.pangle.io
    + 0.0.0.0 api16-log-va.pangle.io
      0.0.0.0 api39-sg.gts.byteoversea.net
      0.0.0.0 api39-va.gts.byteoversea.net
      0.0.0.0 api39.gtm.byteoversea.net
    + 0.0.0.0 ether-pack-va.pangle.io
      0.0.0.0 frontier.byteoversea.com
      0.0.0.0 frontier.byteoversea.com.lan
      0.0.0.0 gecko-pangle-sg.byteoversea.com
      0.0.0.0 gecko-pangle-sg.byteoversea.com.lan
    + 0.0.0.0 gecko-pangle-sg.byteoversea.com.ts.net
      0.0.0.0 gecko-sg.byteoversea.com
      0.0.0.0 gecko-sg.byteoversea.com.lan
      0.0.0.0 i.byteoversea.com

      @@ -1279,15 +1332,20 @@

      0.0.0.0 sf16-static.i18n-pglstatp.com.lan
      0.0.0.0 sf19-static.i18n-pglstatp.com
      0.0.0.0 sf19-static.i18n-pglstatp.com.lan
    + 0.0.0.0 sf19-static.i18n-pglstatp.com.ts.net
      0.0.0.0 sgali-mcs.byteoversea.com
    + 0.0.0.0 ssdk-sg.pangle.io.ts.net
      0.0.0.0 starling-sg.byteoversea.com
      0.0.0.0 tnc16-useast1a.byteoversea.com
      0.0.0.0 tnc16-useast1a.byteoversea.com.lan
    + 0.0.0.0 tnc16-useast1a.byteoversea.com.ts.net
      0.0.0.0 vcs-sg.byteintl.com
      0.0.0.0 vcs-sg.byteintl.com.lan

      # [dbankcloud]
      0.0.0.0 api-dra.theme.dbankcloud.cn
    + 0.0.0.0 api-dra.theme.dbankcloud.cn.lan
    + 0.0.0.0 api-dra.theme.dbankcloud.cn.ts.net
      0.0.0.0 api-dra.theme.dbankcloud.com
      0.0.0.0 configdownload-dre.dbankcdn.com
      0.0.0.0 connect-dra.dbankcloud.cn

      @@ -1297,34 +1355,50 @@

      0.0.0.0 dnkeeper.platform.dbankcloud.com
      0.0.0.0 dnkeeper.platform.dbankcloud.com.lan
      0.0.0.0 events-dra.op.dbankcloud.cn
    + 0.0.0.0 events-dra.op.dbankcloud.cn.lan
    + 0.0.0.0 events-dra.op.dbankcloud.cn.ts.net
      0.0.0.0 events-dra.op.dbankcloud.com
      0.0.0.0 events-dra.op.dbankcloud.com.lan
    + 0.0.0.0 events-dra.op.dbankcloud.com.ts.net
      0.0.0.0 grs.dbankcloud.asia
    + 0.0.0.0 grs.dbankcloud.asia.ts.net
      0.0.0.0 grs.dbankcloud.cn
      0.0.0.0 grs.dbankcloud.cn.lan
    + 0.0.0.0 grs.dbankcloud.cn.ts.net
      0.0.0.0 grs.dbankcloud.com
    + 0.0.0.0 grs.dbankcloud.com.ts.net
      0.0.0.0 grs.dbankcloud.eu
      0.0.0.0 grs.dbankcloud.eu.lan
    + 0.0.0.0 grs.dbankcloud.eu.ts.net
      0.0.0.0 grs.platform.dbankcloud.ru
      0.0.0.0 grs.platform.dbankcloud.ru.lan
    + 0.0.0.0 grs.platform.dbankcloud.ru.ts.net
      0.0.0.0 h5hosting.dbankcdn.com
      0.0.0.0 h5hosting.dbankcdn.com.lan
    + 0.0.0.0 h5hosting.dbankcdn.com.ts.net
      0.0.0.0 map-dra.platform.dbankcloud.cn
      0.0.0.0 map-dra.platform.dbankcloud.com
      0.0.0.0 openlocation-dra.platform.dbankcloud.com
      0.0.0.0 openlocation-dra.platform.dbankcloud.com.lan
    + 0.0.0.0 openlocation-dra.platform.dbankcloud.com.ts.net
      0.0.0.0 pushtrs6.push.dbankcloud.com
    + 0.0.0.0 pushtrs6.push.dbankcloud.com.ts.net
      0.0.0.0 sdkserver-dra.op.dbankcloud.cn
      0.0.0.0 sdkserver-dra.op.dbankcloud.com
      0.0.0.0 sdkserver-dra.op.dbankcloud.com.lan
      0.0.0.0 store-dra.hispace.dbankcloud.com
      0.0.0.0 tsms-dra.security.dbankcloud.cn
      0.0.0.0 tsms-dra.security.dbankcloud.cn.lan
    + 0.0.0.0 tsms-dra.security.dbankcloud.cn.ts.net
      0.0.0.0 tsms-dra.security.dbankcloud.com
      0.0.0.0 videocontent-dra.himovie.dbankcloud.com
      0.0.0.0 videocontent-dra.himovie.dbankcloud.com.lan
      0.0.0.0 weather-dre.weather.dbankcloud.com
      0.0.0.0 weather-dre.weather.dbankcloud.com.lan
    + 0.0.0.0 weather-dre.weather.dbankcloud.com.ts.net
    +
    + # [Epsilon (direct marketing services)]
    + 0.0.0.0 inmobi-match.dotomi.com

      # [facebook]
      /ep[1-9].facebook.com/

      @@ -1363,6 +1437,7 @@

      0.0.0.0 z-p42-chat-e2ee-ig.facebook.com.lan

      # [huawei]
    + 0.0.0.0 conf-dra.cloud.hicloud.com
      0.0.0.0 configserver-dra.platform.hicloud.com
      0.0.0.0 configserver-dre.platform.hicloud.com.lan
      0.0.0.0 configserver.platform.hicloud.com

      @@ -1371,14 +1446,17 @@

      0.0.0.0 connect-drcn.hispace.hicloud.com
      0.0.0.0 connectivitycheck.cbg-app.huawei.com
      0.0.0.0 connectivitycheck.cbg-app.huawei.com.lan
    + 0.0.0.0 connectivitycheck.cbg-app.huawei.com.ts.net
      0.0.0.0 connectivitycheck.platform.hicloud.com
      0.0.0.0 connectivitycheck.platform.hicloud.com.lan
      0.0.0.0 dnkeeper.hicloud.com
      0.0.0.0 events-dra.op.hicloud.com
      0.0.0.0 grs.hicloud.com
      0.0.0.0 grs.hicloud.com.lan
    + 0.0.0.0 grs.hicloud.com.ts.net
      0.0.0.0 hwid.platform.hicloud.com
      0.0.0.0 hwid.platform.hicloud.com.lan
    + 0.0.0.0 logbak.hicloud.com
      0.0.0.0 metrics-dra.dt.hicloud.com
      0.0.0.0 metrics-dra.dt.hicloud.com.lan
      0.0.0.0 metrics3.data.hicloud.com

      @@ -1390,6 +1468,7 @@

      0.0.0.0 sdkserver-dre.op.hicloud.com.lan
      0.0.0.0 store.hispace.hicloud.com
      0.0.0.0 store.hispace.hicloud.com.lan
    + 0.0.0.0 store.hispace.hicloud.com.ts.net

      # [inmobi (モバイル広告プラットフォーム)]
      0.0.0.0 ac.onedsp.inmobi.com

      @@ -1397,12 +1476,14 @@

      0.0.0.0 acj.onedsp.inmobi.com
      0.0.0.0 adq.w.inmobi.com
      0.0.0.0 api.cmp.inmobi.com
    + 0.0.0.0 api.w.inmobi.com
      0.0.0.0 b.de.inmobi.com
      0.0.0.0 b.de.inmobi.com.lan
      0.0.0.0 c-eus.w.inmobi.com
      0.0.0.0 cmp.inmobi.com
      0.0.0.0 config.inmobi.com
      0.0.0.0 config.inmobi.com.lan
    + 0.0.0.0 config.inmobi.com.ts.net
      0.0.0.0 dspbeacons.error.ihasdsp.inmobi.com
      0.0.0.0 dspbeacons.error.ihasdsp.inmobi.com.lan
      0.0.0.0 dspbeacons.ihasdsp.inmobi.com

      @@ -1477,8 +1558,11 @@


      # [onelink (associated with AppsFlyer)]
      0.0.0.0 go.onelink.me
    + 0.0.0.0 goodnovel.onelink.me
      0.0.0.0 gravityapp.onelink.me
      0.0.0.0 impressions.onelink.me
    + 0.0.0.0 nikke.onelink.me
    + 0.0.0.0 ovenbreak.onelink.me
      0.0.0.0 paypay.onelink.me
      0.0.0.0 shortswave.onelink.me
      0.0.0.0 snssdk1180.onelink.me

      @@ -1518,6 +1602,7 @@

      0.0.0.0 st001015pinterest.instabug.com
      0.0.0.0 trk.pinterest.com
      0.0.0.0 trk.pinterest.com.lan
    + 0.0.0.0 trk.pinterest.com.ts.net
      0.0.0.0 trk2.pinterest.com

      # [qualcomm]

      @@ -1552,6 +1637,8 @@

      /mssdk[0-9]*-normal-alisg.tiktokv.com/
      /oec[0-9]*-normal-alisg.tiktokv.com/
      /p[0-9]*-amd-va.tiktokcdn.com/
    + /p[0-9]*-capcut-sign-sg.ibyteimg.com.ts.net/
    + /p[0-9]*-common-sign-useastred.tiktokcdn-eu.com/
      /p[0-9]*-h1-sign-sg.ibyteimg.com/
      /p[0-9]*-heycan-img-sign-sg.ibyteimg.com/
      /p[0-9]*-sg.tiktokcdn.com.lan/

      @@ -1560,6 +1647,8 @@

      /p[0-9]*-sign.tiktokcdn-us.com/
      /p[0-9]*-tiktokcdn-com.akamaized.net/
      /p[0-9]*-tiktokyoyo-va.ibyteimg.com/
    + /p[0-9]*-ulike-sg.ibyteimg.com.lan/
    + /p[0-9]*-ulike-sg.ibyteimg.com.ts.net/
      /p[0-9]*-useast2a.tiktokcdn.com/
      /p[0-9]*-vimo-sg.ibyteimg.com/
      /p[0-9]*-webcast.tiktokcdn.com/

      @@ -1668,6 +1757,7 @@

      0.0.0.0 p16-heycan-sign-va.ibyteimg.com
      0.0.0.0 p16-lp-sg.ibyteimg.com
      0.0.0.0 p16-push-sign-va.ibyteimg.com
    + 0.0.0.0 p16-seeyou-sg.ibyteimg.com
      0.0.0.0 p16-tikcast-game-sign-sg.ibyteimg.com
      0.0.0.0 p16-tiktok-dm-sticker-sign-sg.ibyteimg.com
      0.0.0.0 p16-tiktok-dm-sticker-sign-va.ibyteimg.com

      @@ -1710,8 +1800,10 @@

      0.0.0.0 tnc0-normal-my.tiktokv.com.lan
      0.0.0.0 tnc16-alisg.isnssdk.com
      0.0.0.0 tnc16-alisg.isnssdk.com.lan
    + 0.0.0.0 tnc16-alisg.isnssdk.com.ts.net
      0.0.0.0 tnc16-useast1a.isnssdk.com
      0.0.0.0 tnc16-useast1a.isnssdk.com.lan
    + 0.0.0.0 tnc16-useast1a.isnssdk.com.ts.net
      0.0.0.0 tos-quic-kix1b.tiktokcdn.com^$client=~192.168.8.117
      0.0.0.0 vcs-sg.tiktokv.com
      0.0.0.0 vcs-sg.tiktokv.com.lan

      @@ -1724,6 +1816,7 @@

      ||assets-*.lunalabs.io
      0.0.0.0 a-adq.mediation.unity3d.com
      0.0.0.0 ae.iads.unity3d.com
    + 0.0.0.0 ae.iads.unity3d.com.ts.net
      0.0.0.0 aps-attribution.unityads.unity3d.com
      0.0.0.0 assets.lunalabs.io
      0.0.0.0 auction-load.unityads.unity3d.com

      @@ -1740,26 +1833,36 @@

      0.0.0.0 config.uca.cloud.unity3d.com
      0.0.0.0 configv2.unityads.unity3d.com
      0.0.0.0 configv2.unityads.unity3d.com.lan
    + 0.0.0.0 configv2.unityads.unity3d.com.ts.net
      0.0.0.0 content.offerwall.unity3d.com
      0.0.0.0 events.mz.unity3d.com
      0.0.0.0 gateway.unityads.unity3d.com
      0.0.0.0 gateway.unityads.unity3d.com.lan
    + 0.0.0.0 gateway.unityads.unity3d.com.ts.net
      0.0.0.0 gw-ext.mediation.unity3d.com
      0.0.0.0 gw-is.iads.unity3d.com
      0.0.0.0 gw-rv.iads.unity3d.com
      0.0.0.0 gw-rv.iads.unity3d.com.lan
      0.0.0.0 gw.mediation.unity3d.com
      0.0.0.0 gw.mediation.unity3d.com.lan
    + 0.0.0.0 gw1.mediation.unity3d.com
    + 0.0.0.0 gw1.mediation.unity3d.com.lan
    + 0.0.0.0 gw1.mediation.unity3d.com.ts.net
      0.0.0.0 hbevents-public.mz.unity3d.com
    + 0.0.0.0 hbevents-public.mz.unity3d.com.lan
    + 0.0.0.0 hbevents-public.mz.unity3d.com.ts.net
      0.0.0.0 html-uap.iads.unity3d.com
      0.0.0.0 httpkafka.unityads.unity3d.com
      0.0.0.0 httpkafka.unityads.unity3d.com.lan
      0.0.0.0 i-adq.mediation.unity3d.com
      0.0.0.0 i-adq.mediation.unity3d.com.lan
    + 0.0.0.0 i-adq.mediation.unity3d.com.ts.net
      0.0.0.0 i-sdk.mediation.unity3d.com
      0.0.0.0 i-sdk.mediation.unity3d.com.lan
    + 0.0.0.0 i-sdk.mediation.unity3d.com.ts.net
      0.0.0.0 icon-uap.iads.unity3d.com
      0.0.0.0 img-dyn-uap.iads.unity3d.com
    + 0.0.0.0 img-uap.iads.unity3d.com
      0.0.0.0 o-adq.mediation.unity3d.com
      0.0.0.0 o-iab-imp-counters.mediation.unity3d.com
      0.0.0.0 o-iab-notifications.mediation.unity3d.com

      @@ -1767,13 +1870,19 @@

      0.0.0.0 o-pxt.iads.unity3d.com
      0.0.0.0 o-sdk.mediation.unity3d.com
      0.0.0.0 o-sdk.mediation.unity3d.com.lan
    + 0.0.0.0 o-sdk.mediation.unity3d.com.ts.net
      0.0.0.0 o.iads.unity3d.com
      0.0.0.0 o.iads.unity3d.com.lan
    + 0.0.0.0 o.iads.unity3d.com.ts.net
      0.0.0.0 o.isx.unity3d.com
      0.0.0.0 perf-events.cloud.unity3d.com
      0.0.0.0 publisher-event.unityads.unity3d.com
    + 0.0.0.0 qa-analytics.unity3d.com
    + 0.0.0.0 qa-analytics.unity3d.com.lan
    + 0.0.0.0 qa-analytics.unity3d.com.ts.net
      0.0.0.0 scar.unityads.unity3d.com
      0.0.0.0 scar.unityads.unity3d.com.lan
    + 0.0.0.0 scar.unityads.unity3d.com.ts.net
      0.0.0.0 thind.unityads.unity3d.com
      0.0.0.0 vid-uap.iads.unity3d.com
      0.0.0.0 w.isx.unity3d.com

      @@ -1786,6 +1895,7 @@

      0.0.0.0 api.account.xiaomi.com
      0.0.0.0 api.account.xiaomi.com.lan
      0.0.0.0 api.ad.intl.xiaomi.com
    + 0.0.0.0 api.ad.intl.xiaomi.com.lan
      0.0.0.0 api.aurogon.intl.miui.com
      0.0.0.0 api.sec.intl.miui.com
      0.0.0.0 api.video.intl.xiaomi.com

      @@ -1804,7 +1914,10 @@

      0.0.0.0 connect.intl.rom.miui.com.lan
      0.0.0.0 find.api.micloud.xiaomi.net
      0.0.0.0 find.api.micloud.xiaomi.net.lan
    + 0.0.0.0 find.api.micloud.xiaomi.net.ts.net
      0.0.0.0 findapi.micloud.xiaomi.net
    + 0.0.0.0 findapi.micloud.xiaomi.net.lan
    + 0.0.0.0 findapi.micloud.xiaomi.net.ts.net
      0.0.0.0 flash.sec.intl.miui.com
      0.0.0.0 gallery.market.xiaomi.com
      0.0.0.0 global.market.xiaomi.com

      @@ -1814,15 +1927,19 @@

      0.0.0.0 jupiter.intl.sys.miui.com
      0.0.0.0 mcc-intl.inf.miui.com
      0.0.0.0 mcc-intl.inf.miui.com.lan
    + 0.0.0.0 mcc-intl.inf.miui.com.ts.net
      0.0.0.0 mcc.intl.inf.miui.com
      0.0.0.0 mcc.intl.inf.miui.com.lan
    + 0.0.0.0 mcc.intl.inf.miui.com.ts.net
      0.0.0.0 mqs-log.miui.com
      0.0.0.0 pi.ias.xiaomi.com
      0.0.0.0 privacy.api.intl.miui.com
      0.0.0.0 resolver.msg.global.xiaomi.net
      0.0.0.0 resolver.msg.global.xiaomi.net.lan
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com
    + 0.0.0.0 sdkconfig.ad.intl.xiaomi.com
      0.0.0.0 sdkconfig.ad.intl.xiaomi.com.lan
    + 0.0.0.0 sdkconfig.ad.intl.xiaomi.com.ts.net
      0.0.0.0 sdkconfig.intl.xiaomi.com
      0.0.0.0 sdkconfig.intl.xiaomi.com.lan
      0.0.0.0 sdkconfig.xiaomi.com

      @@ -1843,6 +1960,7 @@

      0.0.0.0 update.intl.miui.com
      0.0.0.0 weatherapi.intl.xiaomi.com
      0.0.0.0 weatherapi.intl.xiaomi.com.lan
    + 0.0.0.0 weatherapi.intl.xiaomi.com.ts.net

      # [その他 (広告・追跡)]
      # https://btonews.blog.fc2.com/blog-entry-410.html

      @@ -1861,10 +1979,13 @@

      0.0.0.0 accuweather-d.openx.net
      0.0.0.0 ad2.fivecdm.com
      0.0.0.0 ad2.fivecdm.com.lan
    + 0.0.0.0 ad2.fivecdm.com.ts.net
      0.0.0.0 adchk.fivecdm.com
      0.0.0.0 adchk.fivecdm.com.lan
    + 0.0.0.0 adchk.fivecdm.com.ts.net
      0.0.0.0 adgen.socdm.com
      0.0.0.0 ads.as.criteo.com
    + 0.0.0.0 ads.as.criteo.com.ts.net
      0.0.0.0 adserver.cxad.cxense.com
      0.0.0.0 andromeda.iad-01.braze.com
      0.0.0.0 apc.socdm.com

      @@ -1873,6 +1994,7 @@

      0.0.0.0 api.karte.io
      0.0.0.0 appconf.rfp.fout.jp
      0.0.0.0 appconf.rfp.fout.jp.lan
    + 0.0.0.0 appconf.rfp.fout.jp.ts.net
      0.0.0.0 aw.dw.impact-ad.jp
      0.0.0.0 b.karte.io
      0.0.0.0 bc2.fivecdm.com

      @@ -1910,6 +2032,7 @@

      0.0.0.0 d.socdm.com.lan
      0.0.0.0 dad.ladsp.com
      0.0.0.0 dis.criteo.com
    + 0.0.0.0 display.bidder.taboola.com
      0.0.0.0 dsp.fout.jp
      0.0.0.0 dsp.fout.jp.lan
      0.0.0.0 ecr.ladsp.com

      @@ -1925,6 +2048,8 @@

      0.0.0.0 frtn.socdm.com
      0.0.0.0 g2.gumgum.com
      0.0.0.0 g2.gumgum.com.lan
    + 0.0.0.0 gat.jp2.as.criteo.com.lan
    + 0.0.0.0 gat.jp2.as.criteo.com.ts.net
      0.0.0.0 gdn.socdm.com
      0.0.0.0 genieejapan-d.openx.net
      0.0.0.0 google-bidout-d.openx.net

      @@ -1960,6 +2085,7 @@

      0.0.0.0 log.fivecdm.com
      0.0.0.0 ly.my.sentry.io
      0.0.0.0 ly.my.sentry.io.lan
    + 0.0.0.0 ly.my.sentry.io.ts.net
      0.0.0.0 match.taboola.com
      0.0.0.0 measurement-api.criteo.com
      0.0.0.0 metrics.brightcove.com

      @@ -1972,6 +2098,7 @@

      0.0.0.0 ntjp.mieru-ca.com
      0.0.0.0 nttresonant-d.openx.net
      0.0.0.0 oajs.openx.net
    + 0.0.0.0 one.adingo.jp
      0.0.0.0 opps.taboola.com
      0.0.0.0 p1cluster.cxense.com
      0.0.0.0 pa.openx.net

      @@ -1988,6 +2115,8 @@

      0.0.0.0 px.ladsp.com
      0.0.0.0 rtb.gumgum.com
      0.0.0.0 rtb.jp2.as.criteo.com
    + 0.0.0.0 rtb.jp2.as.criteo.com.lan
    + 0.0.0.0 rtb.jp2.as.criteo.com.ts.net
      0.0.0.0 rtb.openx.net
      0.0.0.0 rtb.openx.net.lan
      0.0.0.0 rubicon.socdm.com

      @@ -2066,6 +2195,11 @@

      0.0.0.0 loadm.exelator.com
      0.0.0.0 loadus.exelator.com

    + # https://uirusu.jp/moatads-%E3%82%A6%E3%82%A3%E3%83%AB%E3%82%B9/
    + 0.0.0.0 z.moatads.com
    + 0.0.0.0 z.moatads.com.lan
    + 0.0.0.0 z.moatads.com.ts.net
    +
      # [bitdefender アンチウイルス検知]
      # https://answers.microsoft.com/en-us/windows/forum/all/sudden-threat-from-antivirus-doing-nothing/a8e09462-36f9-4acb-b178-3005d731148a
      0.0.0.0 cadmus.script.ac
    ```

## Commit: [d4b9bbe](https://github.com/virtualitypage/AdGuardHome_Filters/commit/d4b9bbeec98be783c0b33d8e749b51a947fce02b) - 2025-09-15

### Date

- 2025/09/15 21:25:56

### Change

- accept/Restricted_domain.txt
    ```yaml
    BEFORE:
      # References: querylog
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/accept/Restricted_domain.txt
      #
    - # Last modified: 13 July 2025
      #

      # [Restricted Domain]
      @@||ai-api.simeji.me^$client=192.168.8.117
      @@||aityping.simeji.me^$client=192.168.8.117
      @@||api-pinterest-com-eip-akadns-net.pinterest.com^$client=192.168.8.117
      @@||api.pinterest.com.getcacheddhcpresultsforcurrentconfig^$client=192.168.8.117
      @@||api.pinterest.com.lan^$client=192.168.8.117
      @@||api.pinterest.com^$client=192.168.8.117
      @@||api.simeji.me^$client=192.168.8.117
      @@||appdump.nie.easebar.com^$client=192.168.8.117
      @@||applog.matrix.easebar.com^$client=192.168.8.117
      @@||applogsg.matrix.netease.com^$client=192.168.8.117
      @@||audiostatlog.cc.easebar.com^$client=192.168.8.117
      @@||buddy.simeji.me^$client=192.168.8.117
      @@||c2pa-cloud-server-sg.tiktokv.com^$client=192.168.8.117
      @@||cdn.dev.mirrativ.com^$client=192.168.8.117
      @@||cdn.mirrativ.com.lan^$client=192.168.8.117
      @@||cdn.mirrativ.com^$client=192.168.8.117
      @@||clog.mirrativ.com.lan^$client=192.168.8.117
      @@||clog.mirrativ.com^$client=192.168.8.117
      @@||cloud.simeji.me^$client=192.168.8.117
      @@||data-detect.nie.easebar.com^$client=192.168.8.117
      @@||dns.update.easebar.com^$client=192.168.8.117
      @@||drpf-h55na.proxima.nie.easebar.com^$client=192.168.8.117
      @@||edge-*.mirrativ.com^$client=192.168.8.117
      @@||feedback-sg.tiktokv.com^$client=192.168.8.117
      @@||g0-06.gsf.easebar.com^$client=192.168.8.117
      @@||g0.gsf.easebar.com^$client=192.168.8.117
      @@||gate.push.x.easebar.com^$client=192.168.8.117
      @@||h55jp.gmsdk.gameyw.easebar.com^$client=192.168.8.117
      @@||h55na.appdump.nie.easebar.com^$client=192.168.8.117
      @@||h55na.gph.easebar.com^$client=192.168.8.117
      @@||h55na.update.easebar.com^$client=192.168.8.117
      @@||hls-cdn*.mirrativ.com^$client=192.168.8.117
      @@||i.pinimg.com.lan^$client=192.168.8.117
      @@||i.pinimg.com^$client=192.168.8.117
      @@||idv.fp.ps.easebar.com^$client=192.168.8.117
      @@||impression.update.easebar.com^$client=192.168.8.117
      @@||inneraudioms.cc.easebar.com^$client=192.168.8.117
      @@||jp.pinterest.com^$client=192.168.8.117
      @@||lf-main-gecko-source.tiktokcdn.com^$client=192.168.8.117
      @@||lf-videocut-ug-hybird.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-geckocdn.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-pitayacdn.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-tiktok-im-scp.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-tos-files.tiktokcdn.com^$client=192.168.8.117
      @@||mcount.easebar.com^$client=192.168.8.117
      @@||mcs-sg.tiktokv.com^$client=192.168.8.117
      @@||mgbsdkjp.matrix.easebar.com^$client=192.168.8.117
      @@||mirrativ.wraptas.site^$client=192.168.8.117
      @@||msg.simeji.me^$client=192.168.8.117
      @@||netease-publish-v.w.alikunlun.com^$client=192.168.8.117
      @@||netease-publish-web.w.alikunlun.com^$client=192.168.8.117
      @@||netlink-sigma.proxima.nie.easebar.com^$client=192.168.8.117
      @@||nie.res.netease.com^$client=192.168.8.117
      @@||online.mirrativ.com^$client=192.168.8.117
      @@||online2.dev.mirrativ.com^$client=192.168.8.117
      @@||p*-music-useast8.tiktokcdn-us.com^$client=192.168.8.117
      @@||p*-pu-sign-ie.tiktokcdn-eu.com^$client=192.168.8.117
      @@||p*-pu-sign-no.tiktokcdn-eu.com^$client=192.168.8.117

      @@ -79,10 +152,20 @@

      @@||p*-ug-incentive-va.tiktokcdn.com.lan^$client=192.168.8.117
      @@||p*-ug-incentive-va.tiktokcdn.com^$client=192.168.8.117
      @@||p*.tiktokcdn.com^$client=192.168.8.117
      @@||p16-music-useast8.tiktokcdn-us.com^$client=192.168.8.117
      @@||pharos.easebar.com^$client=192.168.8.117
      @@||pimg.easebar.com^$client=192.168.8.117
      @@||play.google.com^$client=192.168.8.117
      @@||pull*-expt.fcdn.eu.tiktokcdn.com.lan^$client=192.168.8.117
      @@||pull*-expt.fcdn.eu.tiktokcdn.com^$client=192.168.8.117
      @@||pull*.eu.tiktokcdn.com.lan^$client=192.168.8.117

      @@ -95,49 +178,94 @@

      @@||pull*.tiktokcdn-eu.com^$client=192.168.8.117
      @@||pull*.tiktokcdn.com.lan^$client=192.168.8.117
      @@||pull*.tiktokcdn.com^$client=192.168.8.117
      @@||push-rtmp*.fcdn.eu.tiktokcdn.com^$client=192.168.8.117
      @@||push-rtmp*.tiktokcdn-eu.com^$client=192.168.8.117
      @@||push-rtmp*.tiktokcdn.com.lan^$client=192.168.8.117
      @@||push-rtmp*.tiktokcdn.com^$client=192.168.8.117
      @@||research.easebar.com^$client=192.168.8.117
      @@||s.pinimg.com.lan^$client=192.168.8.117
      @@||s.pinimg.com^$client=192.168.8.117
      @@||sdk-os.mpsdk.easebar.com^$client=192.168.8.117
      @@||sf-i18n-resources.tiktokcdn.com.ttdns2.com^$client=192.168.8.117
      @@||sf-static.tiktokcdn.com^$client=192.168.8.117
      @@||sf*-geckocdn.tiktokcdn.com^$client=192.168.8.117
      @@||sf*-ies-music.tiktokcdn.com^$client=192.168.8.117
      @@||sf*m-geckocdn.tiktokcdn.com^$client=192.168.8.117
      @@||share.easebar.com^$client=192.168.8.117
      @@||sigma-buriedpoint-opd.proxima.nie.easebar.com^$client=192.168.8.117
      @@||sigma-pharosv3-pathn.proxima.nie.easebar.com^$client=192.168.8.117
      @@||sigma-statistics-push.proxima.nie.easebar.com^$client=192.168.8.117
      @@||speed.mirrativ.com^$client=192.168.8.117
      @@||starling-sg.tiktokv.com^$client=192.168.8.117
      @@||static-ime.simeji.me^$client=192.168.8.117
      @@||static.easebar.com^$client=192.168.8.117
      @@||statis.simeji.me^$client=192.168.8.117
      @@||survey-ovs.fp.ps.easebar.com^$client=192.168.8.117
      @@||tnc-boot.tiktokv.com^$client=192.168.8.117
      @@||tnc*-normal-my.tiktokv.com^$client=192.168.8.117
      @@||tos-quic-kix1b.tiktokcdn.com^$client=192.168.8.117
      @@||translate.mpsdk.easebar.com^$client=192.168.8.117
      @@||twiman.net^$client=192.168.8.117
      @@||unisdk.proxima.nie.easebar.com^$client=192.168.8.117
      @@||unisdk.update.easebar.com^$client=192.168.8.117
      @@||v*-cla.tiktokcdn.com^$client=192.168.8.117
      @@||v*-coin.tiktokcdn.com^$client=192.168.8.117
      @@||v*-jp.tiktokcdn.com.lan^$client=192.168.8.117
      @@||v*-jp.tiktokcdn.com^$client=192.168.8.117
      @@||v*.tiktokcdn.com^$client=192.168.8.117
      @@||v16-webapp-prime.tiktok.com^$client=192.168.8.117
      @@||webcast.tiktok.com.ttdns2.com^$client=192.168.8.117
      @@||who.nie.easebar.com^$client=192.168.8.117
      @@||whoami.nie.netease.com^$client=192.168.8.117
      @@||ws.speed.mirrativ.com^$client=192.168.8.117
      @@||www.identityvgame.com^$client=192.168.8.117
      @@||www.mirrativ.com.lan^$client=192.168.8.117
      @@||www.mirrativ.com^$client=192.168.8.117
      @@||www.pinterest.com^$client=192.168.8.117
      @@||www.tiktok.com^$client=192.168.8.117
      @@||xyq-service.easebar.com^$client=192.168.8.117
    ```

    ```yaml
    AFTER:
      # References: querylog
      # definition: https://virtualitypage.github.io/AdGuardHome_Filters/accept/Restricted_domain.txt
      #
    + # Last modified: 15 September 2025
      #

      # [Restricted Domain]
    + @@||accountinformation.roblox.com^$client=192.168.8.117
    + @@||accountsettings.roblox.com^$client=192.168.8.117
      @@||ai-api.simeji.me^$client=192.168.8.117
      @@||aityping.simeji.me^$client=192.168.8.117
    + @@||ams*.roblox.com^$client=192.168.8.117
      @@||api-pinterest-com-eip-akadns-net.pinterest.com^$client=192.168.8.117
      @@||api.pinterest.com.getcacheddhcpresultsforcurrentconfig^$client=192.168.8.117
      @@||api.pinterest.com.lan^$client=192.168.8.117
      @@||api.pinterest.com^$client=192.168.8.117
      @@||api.simeji.me^$client=192.168.8.117
    + @@||apis.rbxcdn.com^$client=192.168.8.117
    + @@||apis.roblox.com^$client=192.168.8.117
      @@||appdump.nie.easebar.com^$client=192.168.8.117
      @@||applog.matrix.easebar.com^$client=192.168.8.117
    + @@||applogsg.matrix.netease.com.lan^$client=192.168.8.117
      @@||applogsg.matrix.netease.com^$client=192.168.8.117
    + @@||arkoselabs.roblox.com^$client=192.168.8.117
    + @@||assetdelivery.roblox.com^$client=192.168.8.117
    + @@||assetgame.roblox.com^$client=192.168.8.117
    + @@||atl*.roblox.com^$client=192.168.8.117
      @@||audiostatlog.cc.easebar.com^$client=192.168.8.117
    + @@||auth.roblox.com^$client=192.168.8.117
    + @@||avatar.roblox.com^$client=192.168.8.117
    + @@||badges.roblox.com^$client=192.168.8.117
    + @@||bom*.roblox.com^$client=192.168.8.117
      @@||buddy.simeji.me^$client=192.168.8.117
      @@||c2pa-cloud-server-sg.tiktokv.com^$client=192.168.8.117
    + @@||catalog.roblox.com^$client=192.168.8.117
    + @@||cdg*.roblox.com^$client=192.168.8.117
      @@||cdn.dev.mirrativ.com^$client=192.168.8.117
      @@||cdn.mirrativ.com.lan^$client=192.168.8.117
      @@||cdn.mirrativ.com^$client=192.168.8.117
    + @@||client-telemetry.roblox.com^$client=192.168.8.117
    + @@||clientsettings.roblox.com^$client=192.168.8.117
    + @@||clientsettingscdn.roblox.com^$client=192.168.8.117
      @@||clog.mirrativ.com.lan^$client=192.168.8.117
      @@||clog.mirrativ.com^$client=192.168.8.117
      @@||cloud.simeji.me^$client=192.168.8.117
    + @@||contacts.roblox.com^$client=192.168.8.117
    + @@||css.rbxcdn.com^$client=192.168.8.117
      @@||data-detect.nie.easebar.com^$client=192.168.8.117
    + @@||dfw*.roblox.com^$client=192.168.8.117
      @@||dns.update.easebar.com^$client=192.168.8.117
      @@||drpf-h55na.proxima.nie.easebar.com^$client=192.168.8.117
    + @@||economy.roblox.com^$client=192.168.8.117
    + @@||ecsv2.roblox.com^$client=192.168.8.117
      @@||edge-*.mirrativ.com^$client=192.168.8.117
    + @@||edge-term4-fra4.roblox.com^$client=192.168.8.117
    + @@||edge-term4-nrt2.roblox.com^$client=192.168.8.117
    + @@||editor-api-sg.capcut.com.lan^$client=~192.168.8.117
    + @@||editor32-normal-mya.capcutapi.com.lan^$client=192.168.8.117
    + @@||editor32-normal-sg.capcutapi.com.lan^$client=~192.168.8.117
    + @@||ephemeralcounters.api.roblox.com^$client=192.168.8.117
    + @@||feed16-normal-mya.capcutapi.com^$client=192.168.8.117
    + @@||feed16-normal-sg.capcutapi.com.lan^$client=~192.168.8.117
    + @@||feed16-normal-sg.capcutapi.com^$client=~192.168.8.117
    + @@||feed32-normal-mya.capcutapi.com.ts.net^$client=192.168.8.117
    + @@||feed32-normal-sg.capcutapi.com.lan^$client=~192.168.8.117
      @@||feedback-sg.tiktokv.com^$client=192.168.8.117
    + @@||followings.roblox.com^$client=192.168.8.117
    + @@||fra*.roblox.com^$client=192.168.8.117
    + @@||friends.roblox.com^$client=192.168.8.117
    + @@||fts.rbxcdn.com^$client=192.168.8.117
      @@||g0-06.gsf.easebar.com^$client=192.168.8.117
    + @@||g0.gsf.easebar.com.lan^$client=192.168.8.117
      @@||g0.gsf.easebar.com^$client=192.168.8.117
    + @@||gameinternationalization.roblox.com^$client=192.168.8.117
    + @@||gamejoin.roblox.com^$client=192.168.8.117
    + @@||games.roblox.com^$client=192.168.8.117
      @@||gate.push.x.easebar.com^$client=192.168.8.117
    + @@||gecko-sg.capcutapi.com.lan^$client=~192.168.8.117
    + @@||gold.roblox.com^$client=192.168.8.117
    + @@||groups.roblox.com^$client=192.168.8.117
    + @@||gru*.roblox.com^$client=192.168.8.117
      @@||h55jp.gmsdk.gameyw.easebar.com^$client=192.168.8.117
      @@||h55na.appdump.nie.easebar.com^$client=192.168.8.117
      @@||h55na.gph.easebar.com^$client=192.168.8.117
      @@||h55na.update.easebar.com^$client=192.168.8.117
      @@||hls-cdn*.mirrativ.com^$client=192.168.8.117
    + @@||hls-cdn26.mirrativ.com.lan^$client=192.168.8.117
    + @@||hls-segments.rbxcdn.com^$client=192.168.8.117
    + @@||i-sg.capcutapi.com.lan^$client=~192.168.8.117
      @@||i.pinimg.com.lan^$client=192.168.8.117
      @@||i.pinimg.com^$client=192.168.8.117
    + @@||iad*.roblox.com^$client=192.168.8.117
      @@||idv.fp.ps.easebar.com^$client=192.168.8.117
    + @@||images.rbxcdn.com^$client=192.168.8.117
      @@||impression.update.easebar.com^$client=192.168.8.117
      @@||inneraudioms.cc.easebar.com^$client=192.168.8.117
    + @@||inventory.roblox.com^$client=192.168.8.117
      @@||jp.pinterest.com^$client=192.168.8.117
    + @@||js.rbxcdn.com^$client=192.168.8.117
    + @@||lax*.roblox.com^$client=192.168.8.117
      @@||lf-main-gecko-source.tiktokcdn.com^$client=192.168.8.117
      @@||lf-videocut-ug-hybird.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-geckocdn.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-pitayacdn.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-tiktok-im-scp.tiktokcdn.com^$client=192.168.8.117
      @@||lf*-tos-files.tiktokcdn.com^$client=192.168.8.117
    + @@||lf16-web-buz.capcut.com^$client=~192.168.8.117
    + @@||lga*.roblox.com^$client=192.168.8.117
    + @@||lhr*.roblox.com^$client=192.168.8.117
    + @@||lms.roblox.com^$client=192.168.8.117
    + @@||locale.roblox.com^$client=192.168.8.117
    + @@||log-sg.capcutapi.com.lan^$client=~192.168.8.117
      @@||mcount.easebar.com^$client=192.168.8.117
      @@||mcs-sg.tiktokv.com^$client=192.168.8.117
    + @@||mediation-gab-normal-sg.capcutapi.com.lan^$client=192.168.8.117
    + @@||metrics.roblox.com^$client=192.168.8.117
      @@||mgbsdkjp.matrix.easebar.com^$client=192.168.8.117
    + @@||mia*.roblox.com^$client=192.168.8.117
      @@||mirrativ.wraptas.site^$client=192.168.8.117
    + @@||mon-boot.capcutapi.com.lan^$client=~192.168.8.117
    + @@||mon-sg.capcutapi.com.lan^$client=~192.168.8.117
    + @@||mon-sg.capcutapi.com^$client=~192.168.8.117
      @@||msg.simeji.me^$client=192.168.8.117
    + @@||mssdk-sg.capcutapi.com.lan^$client=~192.168.8.117
    + @@||ncs.roblox.com^$client=192.168.8.117
      @@||netease-publish-v.w.alikunlun.com^$client=192.168.8.117
      @@||netease-publish-web.w.alikunlun.com^$client=192.168.8.117
    + @@||netlink-sigma.proxima.nie.easebar.com.lan^$client=192.168.8.117
      @@||netlink-sigma.proxima.nie.easebar.com^$client=192.168.8.117
      @@||nie.res.netease.com^$client=192.168.8.117
    + @@||notifications.roblox.com^$client=192.168.8.117
    + @@||nrt*.roblox.com^$client=192.168.8.117
      @@||online.mirrativ.com^$client=192.168.8.117
      @@||online2.dev.mirrativ.com^$client=192.168.8.117
    + @@||ord*.roblox.com^$client=192.168.8.117
      @@||p*-music-useast8.tiktokcdn-us.com^$client=192.168.8.117
      @@||p*-pu-sign-ie.tiktokcdn-eu.com^$client=192.168.8.117
      @@||p*-pu-sign-no.tiktokcdn-eu.com^$client=192.168.8.117

      @@ -79,10 +152,20 @@

      @@||p*-ug-incentive-va.tiktokcdn.com.lan^$client=192.168.8.117
      @@||p*-ug-incentive-va.tiktokcdn.com^$client=192.168.8.117
      @@||p*.tiktokcdn.com^$client=192.168.8.117
    + @@||p0-artist-brand-img-private-sg.capcutapi.com^$client=~192.168.8.117
    + @@||p16-capcut-sg.ibyteimg.com^$client=~192.168.8.117
    + @@||p16-capcut-va.ibyteimg.com^$client=~192.168.8.117
      @@||p16-music-useast8.tiktokcdn-us.com^$client=192.168.8.117
    + @@||p19-capcut-sg.ibyteimg.com^$client=~192.168.8.117
    + @@||passport16-normal-sg.capcutapi.com^$client=~192.168.8.117
    + @@||passport32-normal-sg.capcutapi.com.lan^$client=~192.168.8.117
      @@||pharos.easebar.com^$client=192.168.8.117
      @@||pimg.easebar.com^$client=192.168.8.117
    + @@||pitaya-sg.capcutapi.com.lan^$client=~192.168.8.117
      @@||play.google.com^$client=192.168.8.117
    + @@||premiumfeatures.roblox.com^$client=192.168.8.117
    + @@||presence.roblox.com^$client=192.168.8.117
    + @@||privatemessages.roblox.com^$client=192.168.8.117
      @@||pull*-expt.fcdn.eu.tiktokcdn.com.lan^$client=192.168.8.117
      @@||pull*-expt.fcdn.eu.tiktokcdn.com^$client=192.168.8.117
      @@||pull*.eu.tiktokcdn.com.lan^$client=192.168.8.117

      @@ -95,49 +178,94 @@

      @@||pull*.tiktokcdn-eu.com^$client=192.168.8.117
      @@||pull*.tiktokcdn.com.lan^$client=192.168.8.117
      @@||pull*.tiktokcdn.com^$client=192.168.8.117
    + @@||pulsar.roblox.com^$client=192.168.8.117
      @@||push-rtmp*.fcdn.eu.tiktokcdn.com^$client=192.168.8.117
      @@||push-rtmp*.tiktokcdn-eu.com^$client=192.168.8.117
      @@||push-rtmp*.tiktokcdn.com.lan^$client=192.168.8.117
      @@||push-rtmp*.tiktokcdn.com^$client=192.168.8.117
    + @@||r.res.easebar.com^$client=192.168.8.117
    + @@||realtime-signalr.roblox.com^$client=192.168.8.117
      @@||research.easebar.com^$client=192.168.8.117
      @@||s.pinimg.com.lan^$client=192.168.8.117
      @@||s.pinimg.com^$client=192.168.8.117
    + @@||sc*.rbxcdn.com^$client=192.168.8.117
    + @@||sc0.rbxcdn.com^$client=192.168.8.117
    + @@||sc0ak.rbxcdn.com^$client=192.168.8.117
    + @@||sc0aws.rbxcdn.com^$client=192.168.8.117
      @@||sdk-os.mpsdk.easebar.com^$client=192.168.8.117
    + @@||sdksggcp32-normal.evercloud.capcutapi.com^$client=~192.168.8.117
    + @@||sea*.roblox.com^$client=192.168.8.117
    + @@||sf-fe.capcut.com^$client=~192.168.8.117
      @@||sf-i18n-resources.tiktokcdn.com.ttdns2.com^$client=192.168.8.117
      @@||sf-static.tiktokcdn.com^$client=192.168.8.117
      @@||sf*-geckocdn.tiktokcdn.com^$client=192.168.8.117
      @@||sf*-ies-music.tiktokcdn.com^$client=192.168.8.117
      @@||sf*m-geckocdn.tiktokcdn.com^$client=192.168.8.117
    + @@||sf16-web-login-neutral.capcutstatic.com^$client=~192.168.8.117
    + @@||sf16-web-music.capcutstatic.com^$client=~192.168.8.117
    + @@||sf16-web-tos-buz.capcutcdn-us.com^$client=~192.168.8.117
    + @@||sf19-web-music.capcutstatic.com^$client=~192.168.8.117
      @@||share.easebar.com^$client=192.168.8.117
      @@||sigma-buriedpoint-opd.proxima.nie.easebar.com^$client=192.168.8.117
    + @@||sigma-orbitv3-impression.proxima.nie.easebar.com^$client=192.168.8.117
      @@||sigma-pharosv3-pathn.proxima.nie.easebar.com^$client=192.168.8.117
      @@||sigma-statistics-push.proxima.nie.easebar.com^$client=192.168.8.117
    + @@||silver.roblox.com^$client=192.168.8.117
    + @@||sin*.roblox.com^$client=192.168.8.117
      @@||speed.mirrativ.com^$client=192.168.8.117
    + @@||starling-normal-sg.capcutapi.com^$client=~192.168.8.117
      @@||starling-sg.tiktokv.com^$client=192.168.8.117
      @@||static-ime.simeji.me^$client=192.168.8.117
      @@||static.easebar.com^$client=192.168.8.117
    + @@||static.rbxcdn.com^$client=192.168.8.117
      @@||statis.simeji.me^$client=192.168.8.117
      @@||survey-ovs.fp.ps.easebar.com^$client=192.168.8.117
    + @@||syd*.roblox.com^$client=192.168.8.117
    + @@||t2.rbxcdn.com^$client=192.168.8.117
    + @@||thumbnails.roblox.com^$client=192.168.8.117
    + @@||tnc-boot.capcutapi.com^$client=~192.168.8.117
      @@||tnc-boot.tiktokv.com^$client=192.168.8.117
      @@||tnc*-normal-my.tiktokv.com^$client=192.168.8.117
      @@||tos-quic-kix1b.tiktokcdn.com^$client=192.168.8.117
    + @@||tr.rbxcdn.com^$client=192.168.8.117
    + @@||tracing.roblox.com^$client=192.168.8.117
    + @@||trades.roblox.com^$client=192.168.8.117
      @@||translate.mpsdk.easebar.com^$client=192.168.8.117
    + @@||tt-gecko-sg.capcutapi.com.lan^$client=~192.168.8.117
    + @@||tt-gecko-sg.capcutapi.com^$client=~192.168.8.117
      @@||twiman.net^$client=192.168.8.117
    + @@||twostepverification.roblox.com^$client=192.168.8.117
      @@||unisdk.proxima.nie.easebar.com^$client=192.168.8.117
      @@||unisdk.update.easebar.com^$client=192.168.8.117
    + @@||us-central-origin-px.roblox.com^$client=192.168.8.117
    + @@||usermoderation.roblox.com^$client=192.168.8.117
    + @@||users.roblox.com^$client=192.168.8.117
      @@||v*-cla.tiktokcdn.com^$client=192.168.8.117
      @@||v*-coin.tiktokcdn.com^$client=192.168.8.117
      @@||v*-jp.tiktokcdn.com.lan^$client=192.168.8.117
      @@||v*-jp.tiktokcdn.com^$client=192.168.8.117
      @@||v*.tiktokcdn.com^$client=192.168.8.117
    + @@||v16-vod.capcutvod.com.lan^$client=192.168.8.117
    + @@||v16-vod.capcutvod.com.ts.net^$client=192.168.8.117
      @@||v16-webapp-prime.tiktok.com^$client=192.168.8.117
    + @@||vcs-sg.capcutapi.com.lan^$client=~192.168.8.117
    + @@||video-sg.capcutshare.com^$client=192.168.8.117
    + @@||voice.roblox.com^$client=192.168.8.117
    + @@||webblox.roblox.com^$client=192.168.8.117
      @@||webcast.tiktok.com.ttdns2.com^$client=192.168.8.117
      @@||who.nie.easebar.com^$client=192.168.8.117
    + @@||whoami.nie.easebar.com.lan^$client=192.168.8.117
    + @@||whoami.nie.easebar.com^$client=192.168.8.117
      @@||whoami.nie.netease.com^$client=192.168.8.117
      @@||ws.speed.mirrativ.com^$client=192.168.8.117
    + @@||www.capcut.com^$client=~192.168.8.117
    + @@||www.capcut.net^$client=~192.168.8.117
      @@||www.identityvgame.com^$client=192.168.8.117
      @@||www.mirrativ.com.lan^$client=192.168.8.117
      @@||www.mirrativ.com^$client=192.168.8.117
    + @@||www.neteasegamer.com^$client=192.168.8.117
      @@||www.pinterest.com^$client=192.168.8.117
    + @@||www.roblox.com^$client=192.168.8.117
      @@||www.tiktok.com^$client=192.168.8.117
    + @@||xyq-service-gcp.easebar.com^$client=192.168.8.117
      @@||xyq-service.easebar.com^$client=192.168.8.117
    ```

## Commit: [e3dfc49](https://github.com/virtualitypage/AdGuardHome_Filters/commit/e3dfc49daf09e40ed648cf2c36081711c06f53c7) - first commit

### Date

- 2025/08/31 18:35:23

### Add

- CommitLog.md
- README.md
- accept/Accept_domain.txt
- accept/Accept_PBAds.txt
- accept/Restricted_domain.txt
- reject/Reject_domain.txt
- reject/Reject_link.txt
- reject/Reject_PhishingSite.txt
- reject/Reject_ScamSite.txt