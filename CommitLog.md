# AdGuardHome_Filters Commit Log

All commits to this repository will be logged in this file.

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