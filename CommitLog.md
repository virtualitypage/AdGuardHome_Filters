# AdGuardHome_Filters Commit Log

All commits to this repository will be logged in this file.

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