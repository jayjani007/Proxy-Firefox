# 🛡️ Proxy Exclusion List for Privacy & Security in Firefox
## 🚀 Introduction
This list improves privacy and security by excluding specific domains and subdomains from routing through a proxy (e.g., Burp Suite). It includes domains related to telemetry, advertising, analytics, and more helping you reduce network noise and focus only on relevant traffic.

## 📄 Description
Browsers like **Firefox** often route all traffic including telemetry, ads, and analytics through the proxy. This results in:
- Unnecessary noise
- Privacy exposure
- Bandwidth overhead
By excluding certain domains, your Burp proxy logs stay clean and relevant.

This list contains domains associated with:
- 📊 **Telemetry and analytics**  
- 🎯 **Advertising and tracking**  
- 🌐 **CDNs (Content Delivery Networks)**  
- 🔐 **Security & anti-abuse services**  
- 🧹 **Potentially unwanted traffic**  
- 📱 **Social media platforms**  
- 📦 **Miscellaneous non-targeted traffic**  

## ⚙️ Steps to Implement
1. 🔍 Open Firefox and visit: `about:config`
2. ⚠️ Click **Accept the Risk and Continue**
3. 🔎 Search: `network.proxy.no_proxies_on`
4. ✏️ If the setting exists, click the **pencil icon** and edit the value
5. ➕ If it doesn't exist:
   - Right-click → **New > String**
   - Name it `network.proxy.no_proxies_on`
6. 📝 Copy the **Domain List** from below and Paste the list of domains (comma-separated) into the field  
7. 💾 Press **Enter** or click **OK**
8. 🔄 Restart Firefox for the changes to take effect

## 📝 Domain List
```
omnireportlaunch.112.2o7.net, 8a81eebba889.cdn4.forter.com, web-sdk.aptrinsic.com, use.typekit.net, sentry.io, r11.o.lencr.org, lencr.org, r.lr-in.com, lr-in.com, privacyportal.onetrust.com, onetrust.com, passwordsleakcheck-pa.googleapis.com, p.typekit.net, typekit.net, omnireport.sc.omtrdc.net, notifier-configs.airbrake.io, airbrake.io, js-agent.newrelic.com, newrelic.com, geolocation.onetrust.com, fpt.dfp.microsoft.com, esp.aptrinsic.com, aptrinsic.com, esp-m.aptrinsic.com, dpm.demdex.net, cm.everesttech.net, everesttech.net, cdn3.forter.com, forter.com, cdn123.forter.com, cdn0.forter.com, cdn.lr-in.com, cdn.cookielaw.org, cookielaw.org, bam.nr-data.net, bam-cell.nr-data.net, api.demandbase.com, api.airbrake.io, airbrake.io, demandbase.com, amcglobal.sc.omtrdc.net, omtrdc.net, classify-client.services.mozilla.com, firefox-settings-attachments.cdn.mozilla.net, normandy.cdn.mozilla.net, addons.mozilla.org, services.addons.mozilla.org, versioncheck-bg.addons.mozilla.org, browser.events.data.msn.com, ad-delivery.net, r.bing.com, c.bing.com, login.live.com, www2.bing.com, www.msn.com, msn.com, push.services.mozilla.com, th.bing.com, img-s-msn-com.akamaized.net, srtb.msn.com, c.msn.com, incoming.telemetry.mozilla.org, ads-img.mozilla.org, esp-m.aptrinsic.com, m.adnxs.com, mem.gfx.ms, adsdk.microsoft.com, msft-ssp-apac.adnxs.com, client-side-detection.api.cx.metamask.io, px.ads.linkedin.com, snap.licdn.com, adsdkprod.azureedge.net, ads.mozilla.org, bam.nr-data.net, btloader.com, aadcdn.msauth.net, dl.edge-aicdn.net, storage.ml-cachehost.net, csp.microsoft.com, api.btloader.com, sg-api.archive-digger.com, ib.adnxs-simple.com, shftr.adnxs.net, rum.hlx.page, prodregistryv2.org, b1t-sindc1.outbrain.com, firefox.settings.services.mozilla.com, metamask.github.io, api.segment.io, rpc.blast.io, aus5.mozilla.org, content-signature-2.cdn.mozilla.net, detectportal.firefox.com, auth.openai.com, amcglobal.sc.omtrdc.net, phishing-detection.api.cx.metamask.io, fonts.googleapis.com, logincdn.msauth.net, img-getpocket.cdn.mozilla.net, use.typekit.net, p.typekit.net, safebrowsing.googleapis.com, merino.services.mozilla.com, browser-intake-datadoghq.com, gstatic.com, play.google.com, ogads-pa.clients6.google.com, region1.google-analytics.com, csp.withgoogle.com, id.google.com, prodregistryv2.org, cloudflareinsights.com, featureassets.org, cdn.oaistatic.com, ab.chatgpt.com, www.googletagmanager.com, www.googleadservices.com, static.cloudflareinsights.com, browser.events.data.microsoft.com, js.monitor.azure.com, publisher.liveperson.net, cdn-dynmedia-1.microsoft.com, wcpstatic.microsoft.com, tags.srv.stackadapt.com, qvdt3feo.com, googleads.g.doubleclick.net, images.ctfassets.net, ps.containers.piwik.pro, ps.piwik.pro, unpkg.com, ziggy.agency, code.jquery.com, www.gstatic.com, consent.google.com, fonts.gstatic.com, abs.twimg.com, accounts.google.com, assets.msn.com, app.launchdarkly.com, o.pki.goog, events.launchdarkly.com, 1.awakened.work, awakened.work, amcglobal.sc.omtrdc.net, contentsquare.net, c.contentsquare.net, cdn.cookielaw.org, js-agent.newrelic.com, mozilla-ohttp.fastly-edge.com, workspace.google.com, storage.googleapis.com, lh3.googleusercontent.com, www.google-analytics.com, ssl.google-analytics.com, analytics.google.com, feedback-pa.clients6.google.com, siteintercept.qualtrics.com, t.contentsquare.net, web-sdk.aptrinsic.com, www.recaptcha.net, zn1ldep1rtdg6qxl8-adobe.siteintercept.qualtrics.com, googlesyndication.com, www.googlesyndication.com, cloudflare.com, www.cloudflare.com, cdn.jsdelivr.net, cdn.cloudflare.com, cdnjs.cloudflare.com, abs-0.twimg.com, maxcdn.bootstrapcdn.com, cdn.amazon.com, static.cloudflareinsights.com, doubleclick.net, ads.yahoo.com, cdnssl.clicktale.net, builder-assets.unbounce.com, ad.doubleclick.net, c.go-mpulse.net, s.go-mpulse.net, go-mpulse.net, rtb-adx.com, advertising.com, unpkg.com, partner.googleadservices.com, facebook.com, twitter.com, instagram.com, linkedin.com, youtube.com, pinterest.com, www.amazon.com, www.spotify.com, www.dropbox.com, www.akamai.com, www.paypal.com, www.apple.com, www.microsoft.com, www.oracle.com, www.google.com, apis.google.com, bing.com, google.co.in, www.bing.com, x.com, api.x.com, appleid.cdn-apple.com, apple.com, www.apple.com, appleid.apple.com, mail.google.com, gmail.com, portswigger.net, enterprise.portswigger.net
```

## 🧠 How It Can Be Useful
- 🛡️ **Enhanced Privacy** - Exclude domains linked to tracking and telemetry
- 🚫 **Reduced Unwanted Traffic** - Focus Burp Suite logs on test targets only
- ⚡ **Better Performance** - Improve proxy speed by reducing irrelevant load
- 🔐 **Improved Security** - Avoid exposing sensitive data to potentially untrusted endpoints

## 💡 Note
You can edit this list anytime to match your testing goals. Remove or add domains as needed to suit your privacy or debugging preferences.

## 🧾 Explanation
The `network.proxy.no_proxies_on` setting in Firefox tells the browser to **bypass the configured proxy** for specific domains. This means requests to these domains:
- Won’t appear in Burp Suite or similar tools
- Won’t affect your proxy’s bandwidth
- Help you focus only on target-related traffic
