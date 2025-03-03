# Filterlist uBo

Build-in

![image](https://github.com/user-attachments/assets/44fa89e0-152f-4bc0-81b6-45a1310b877f)

+ Ads
  + EasyList

+ Privacy
  + [EasyPrivacy](https://easylist.to/)
  + [AdGuard Tracking Protection](https://github.com/AdguardTeam/AdguardFilters#adguard-filters)

+ Maleware protection 1/2
  + [Online Maliciouse URL Blocklist](https://gitlab.com/malware-filter/urlhaus-filter#malicious-url-blocklist)

+ Cookie notice
  + Easlist/uBO Cookienotice 2/2

+ Annoyances
  + Easlist - Annoyances 4/4
 
+ uBlock filters
  + Annoyancses    
 
+ Region
  + Easylist Germany

+ Custom
  + [FMHY Unsage sites](https://github.com/fmhy/FMHYFilterlist)
  + [Yokoffing filterlist](https://github.com/yokoffing/filterlists)
  + [Actually Legitimate URL Shortener Tool](https://github.com/DandelionSprout/adfilt/blob/master/LegitimateURLShortener.txt)
  + [Browse websites without logging in](https://github.com/DandelionSprout/adfilt/blob/master/BrowseWebsitesWithoutLoggingIn.txt)
  + [Dandelion Sprout's Anti-Malware List](https://github.com/DandelionSprout/adfilt/blob/master/Dandelion%20Sprout's%20Anti-Malware%20List.txt)

 

+ removed Youtube Shorts and Mixes

```! YT Homepage and Subscriptions - Hide the Shorts section
youtube.com##[is-shorts]
! YT Menu - Hide the Shorts button
www.youtube.com###guide [title="Shorts"], .ytd-mini-guide-entry-renderer[title="Shorts"]
! YT Search - Hide Shorts
www.youtube.com##ytd-search ytd-video-renderer:has([overlay-style="SHORTS"])
! YT Search, Channels and Sidebar or below the player - Hide the Shorts sections
www.youtube.com##ytd-reel-shelf-renderer
! YT Channels - Hide the Shorts tab
www.youtube.com##[tab-title="Shorts"]
! YT Subscriptions - Hide Shorts - Grid View
www.youtube.com##ytd-browse[page-subtype="subscriptions"] ytd-grid-video-renderer:has([overlay-style="SHORTS"])
! YT Subscriptions - Hide Shorts - List View
www.youtube.com##ytd-browse[page-subtype="subscriptions"] ytd-video-renderer:has([overlay-style="SHORTS"])
! YT Subscriptions - New Layout - Hide Shorts
www.youtube.com##ytd-browse[page-subtype="subscriptions"] ytd-rich-item-renderer:has([overlay-style="SHORTS"])
! YT Sidebar - Hide Shorts
www.youtube.com###related ytd-compact-video-renderer:has([overlay-style="SHORTS"])

! YT Mobile - Hide the Shorts Menu button
m.youtube.com##ytm-pivot-bar-item-renderer:has(>.pivot-shorts)
! YT Mobile - Hide the Shorts sections
m.youtube.com##ytm-reel-shelf-renderer
! YT Mobile - Hide Shorts in search results
m.youtube.com##ytm-search ytm-video-with-context-renderer:has([data-style="SHORTS"])
! YT Mobile - Hide the Shorts button on Channels
m.youtube.com##[tab-title="Shorts"]

! Removes Mixes from the Main Page
youtube.com##ytd-rich-item-renderer:has(#video-title-link[title*="Mix"][href$="start_radio=1"])
! Removes Mixes from the right side panel
youtube.com##ytd-compact-radio-renderer
! Removes Mixes from search results
youtube.com##ytd-radio-renderer
