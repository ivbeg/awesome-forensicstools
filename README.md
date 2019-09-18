# Awesome list of digital forensic tools [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Collection of digital forensics tools for verification, investigations, diagnostics and so on.
Composed from: Bellingcat's Digital Forensics Tools list https://docs.google.com/document/d/1BfLPJpRtyq4RFtHJoNpvWQjmGnyVkfE2HYoICKOGguA, Forensics Wiki http://www.forensicswiki.org
and assorted collections of forensic resources online.

All contributions welcome. Please propose changes using github issue https://github.com/ivbeg/awesome-forensictools/issues or by direct writing pull request.

### Table of contents / Содержание
* [Collections](#collections-of-tools)
* [Satellite and mapping services](#satellite-and-mapping-services)
* [Geobased searches](#geobased-searches)
* [Documents metadata](#documents-metadata)
* [Images, videos and metadata](#images-videos-metadata)
* [Social media](#social-media)
* [Transport](#transport)
* [Date and time](#date-and-time)
* [Archiving](#archiving)
* [Miscellaneous](#miscellaneous)
* [Guides and handbooks](#guides-and-handbooks)
* [Data visualization](#data-visualization)
* [Online security and privacy](#online-security-and-privacy)
* [List of sources per country](#list-of-sources-per-country)


# Collections of tools
- OSINT Tools [osintframework.com](http://osintframework.com) - huge collection of open source intelligence tools

# Satellite and mapping services

-   Bing Maps, satellite and mapping service, has more recent and
    sharper imagery than Google in several areas such as Iraq,
    [bing.com/maps](https://www.bing.com/maps/)
-   Date of the Bing imagery? Check:
    [mvexel.dev.openstreetmap.org/bing](http://mvexel.dev.openstreetmap.org/bing/) 
-   conversion of coordinates, convert geographic coordinates between
    different notation styles,
    [synnatschke.de/geo-tools/coordinate-converter.php](http://www.synnatschke.de/geo-tools/coordinate-converter.php) 
-   DigitalGlobe, paid satellite imagery, but preview available for free
    via the catalogus,
    [browse.digitalglobe.com/imagefinder](https://browse.digitalglobe.com/imagefinder/main.jsp;jsessionid%3D211D96095DB2313696B02534E7F62D64?) 
-   Geograph, georeferenced
    images, [geograph.org](http://www.geograph.org) 
-   GeoNames, an online database of (various spellings of) locations
    names,
    [geonames.org](http://www.geonames.org)
-   Google Earth Pro,
    [google.com/earth/download/gep/agree.html](https://www.google.com/earth/download/gep/agree.html) 
-   Bing Maps satellite imagery layer:
    [ge-map-overlays.appspot.com/bing-maps/aerial](http://ge-map-overlays.appspot.com/bing-maps/aerial) 
-   Google Maps,
    [maps.google.com](http://maps.google.com) 
-   HERE WeGo, mapping service which includes more recent satellite
    imagery from e.g. Iraq,
    [wego.here.com](https://wego.here.com) 
-   Mapillary, crowdsourced street-level photos,
    [mapillary.com](https://www.mapillary.com)
-   OpenStreetCam,[ ](https://www.mapillary.com)crowdsourced
    street-level
    photos, [openstreetcam.org](https://www.openstreetcam.org) 
-   OpenStreetMap,
    [openstreetmap.org](http://www.openstreetmap.org/) 
-   Panoramio,
    [panoramio.com](http://www.panoramio.com) (no
    longer available)
-   Sentinel Playground,
    [apps.sentinel-hub.com/sentinel-playground](http://apps.sentinel-hub.com/sentinel-playground)      
-   TerraServer, also a commercial company selling satellite imagery,
    but previews available:
    [terraserver.com](http://www.terraserver.com)
-   Wikimapia, crowdsourced information related to geographic locations,
    works like Google Maps but possibility to switch between Google,
    Bing, OSM, etc.,
    [wikimapia.org](http://www.wikimapia.org)
-   Yandex Maps,
    [yandex.ru](http://www.yandex.ru) 


# Geobased searches
-   (\$) Echosec, [echosec.net](http://www.echosec.net) (Instagram,
    Twitter, VK, Foursquare)
-   LiveUAmap, aggregated open source information,
    [liveuamap.com](http://www.liveuamap.com) 
-   Afghanistan:
    [afghanistan.liveuamap.com](https://afghanistan.liveuamap.com) 
-   Islamic State:
    [isis.liveuamap.com](http://isis.liveuamap.com) 
-   Syria:
    [syria.liveuamap.com](http://syria.liveuamap.com) 
-   Ukraine:
    [ukraine.liveuamap.com](http://ukraine.liveuamap.com) 
-   Venezuela: venezuela.liveuamap.com
-   (\$) WarWire,
    [warwire.net](http://www.warwire.net) (Twitter,
    Instagram, VK, YouTube)
-   Yomapic,
    [yomapic.com](http://www.yomapic.com)
## Geobased search on:

-   YouTube [youtube.github.io/geo-search-tool/search.html](http://youtube.github.io/geo-search-tool/search.html)
-   Twitter insert this is search box:
    geocode:[coordinates],[radius-km], for example:
    geocode:36.222285,43.998233,2km (only works with km, so 500m =
    0.5km)

# Documents metadata
- Hachoir3 [https://github.com/haypo/hachoir3] (https://github.com/haypo/hachoir3). Python library for metadata extraction from binary streams including MS Office documents
- Forensic wiki [list of metadata extractors](http://www.forensicswiki.org/wiki/Document_Metadata_Extraction)
- Metadata extractor [github](https://github.com/drewnoakes/metadata-extractor)

# Images, videos and metadata
## Image and videos tools
-   Amnesty YouTube Dataviewer, Reverse image (still of video) search
    and exact uploading time,
    [amnestyusa.org/sites/default/custom-scripts/citizenevidence](http://www.amnestyusa.org/sites/default/custom-scripts/citizenevidence/)
-   reverse image search
-   Google Reverse Image Search,
    [images.google.com](http://images.google.com) (also
    available as Chrome and Firefox add-on)
-   TinEye,
    [tineye.com](http://www.tineye.com) 
-   Yandex, be aware that sometimes Russia’s Yandex has better results
    ([example](https://twitter.com/trbrtc/status/900708029389307904)
    than Google’s reverse image search,
    [yandex.com/images](https://yandex.com/images/) 

## Foto/video metadata (EXIF and e.t.c.)
-   Jeffrey's Image Metadata Viewer, to view the metadata of (online)
    photos,
    [exif.regex.info/exif.cgi](http://exif.regex.info/exif.cgi) 
-   Irfanview,
    [irfanview.com](https://irfanview.com)
-   Foca. Metadata extraction tool [elevenpaths.com](https://www.elevenpaths.com/labstools/foca/index.html)
- [Goofile](https://tools.kali.org/information-gathering/goofile). Download and extract metadata
- Splunk and Metadata automation. [Splunk](https://blog.sweepatic.com/metadata-hackers-best-friend/)
-   Foto
    Forensics,[fotoforensics.com](http://fotoforensics.com)        
-   Image Forensics,
    [https://29a.ch/photo-forensics/\#level-sweep](https://29a.ch/photo-forensics/%23level-sweep)
-   InVID, verification plugin to help journalists verify images and
    videos and debunk fake news,
    [invid-project.eu]http://www.invid-project.eu/invid-releases-fake-video-news-debunker-firefox-provides-code-open-source-mit-licence/) (plugins
    for
    [Chrome](https://goo.gl/Fo8i73) and
    Firefox
    ([Windows](http://www.invid-project.eu/wp-content/uploads/2017/07/fake_video_news_debunker_by_invid-0.55-anfx-windows.zip),
    [Mac OS
    X](http://www.invid-project.eu/wp-content/uploads/2017/07/InVID-verification-ext-v0.54fx-mac.zip),
    [Linux](http://www.invid-project.eu/wp-content/uploads/2017/07/InVID-verification-ext-v0.54fx-linux.zip).

## Guides
-   First Draft News,
    [firstdraftnews.com/resource/visual-verification-guide-photos](https://firstdraftnews.com/resource/visual-verification-guide-photos) 


# Social media

## Multiple social networks
-   NacheChk. Same name check over dozens of social networks [namechk.com](https://namechk.com/)

## Facebook
-   Facebook Scanner, automatically advanced searched for Facebook
    profiles, [stalkscan.com](http://stalkscan.com/)
-   Facebook Search Tool, find accounts by name, email, screen name and
    phone,
    [netbootcamp.org/facebook.html](http://netbootcamp.org/facebook.html) 
-   Lookup-ID, another very complete Facebook search tool,
    [lookup-id.com](http://lookup-id.com/)
-   Facebook Graph tips, automatically advanced searches for Facebook
    profiles,
    [graph.tips](http://graph.tips/beta) 
-   Facebook Livemap, live broadcasts around the world, mapped on the
    world,
    [facebook.com/livemap](https://www.facebook.com/livemap/) 
-   Facebook Video Downloader Online, for downloading Facebook videos,
    [fbdown.net](http://www.fbdown.net/)
-   Facebook search tool, advanced search tool for Facebook profiles,
    [http://inteltechniques.com/osint/menu.facebook.html](http://inteltechniques.com/osint/menu.facebook.html) 
-   peoplefindThor, advanced search tool for Facebook profiles,
    [peoplefindthor.dk](https://peoplefindthor.dk)

## LinkedIn

-   Socilab, allows users to visualise and analyse your own LinkedIn
    network,
    [socilab.com](http://socilab.com/%23home) 

## Snapchat
-   Snap Map, a searchable map of geotagged snaps, via the mobile
    application, read
    [here](https://techcrunch.com/2017/06/21/snap-map/) how.

## Tumblr

-   Tumblr Originals, find posts uploaded by the account, thus excluding
    reblogs,
    [studiomoh.com/fun/tumblr\_originals](http://www.studiomoh.com/fun/tumblr_originals) 

## Twitter

-   advanced search,
    [twitter.com/search-advanced](https://twitter.com/search-advanced)
-   [C](https://twitter.com/search-advanced),
    [tweetbeaver.com/index.php](https://tweetbeaver.com/index.php)

### Geobased searches

-   On Twitter, insert this is search box:
    geocode:[coordinates],[radius-km], for example:
    geocode:36.222285,43.998233,2km
-   Onemilliontweetmap, maps tweets per location up to 6hrs old, and has
    a keyword search option,
    [onemilliontweetmap.com](http://onemilliontweetmap.com/) 

-   Union Metrics, find the reach of tweets,
    [tweetreach.com/](https://tweetreach.com/) 

### Advanced Search Operators:

-   term1 term2 - tweets with both term1 and term2 in any order (e.g.
    twitter metrics)
-   term1 OR term2 - tweets with either term1 or term2 (e.g. analytics
    OR metrics)
-   “term1 term2” - tweets with the phrase “term1 term2” (e.g. "twitter
    metrics")
-   term1 -term2 - tweets with term1 but not term2 (e.g. twitter
    -facebook)
-   @username - tweets mentioning or RTing a specific user (e.g.
    @unionmetrics)
-   from:username - tweets from a specific Twitter user (e.g.
    from:unionmetrics)
-   since:YYYY-MM-DD - tweets after a specific date in UTC (e.g.
    since:2017-03-30)
-   until:YYYY-MM-DD - tweets before a specific date in UTC (e.g.
    until:2017-03-30)

## YouTube
-   Amnesty YouTube Dataviewer, Reverse image (still of video) search
    and exact uploading time,
    [amnestyusa.org/sites/default/custom-scripts/citizenevidence](http://www.amnestyusa.org/sites/default/custom-scripts/citizenevidence/)

# Transport
## Aircraft

-   OpenSky. Free aircraft tracking project [opensky-network.org](https://opensky-network.org/)
-   ADS-B Exchange Global Radar, which also includes a number of
    [military
    aircraft](https://www.adsbexchange.com/airborne-military-aircraft/),
    [global.adsbexchange.com/VirtualRadar/mobile.html](https://global.adsbexchange.com/VirtualRadar/mobile.html)
-   Flightradar24, to track (mostly) civilian aircraft currently in the
    air around the world, archive goes 12 months back but (\$),
     [flightradar24.com](https://www.flightradar24.com/)
-   RadarBox, worldwide coverage, includes private and military jets,
    [radarbox24.com](https://www.radarbox24.com)
-   FlightView, [flightview.com](https://www.flightview.com/)

## Boats

-   MarineTraffic,
    [marinetraffic.com](https://www.marinetraffic.com/) 
-   VesselFinder,
    [vesselfinder.com](https://www.vesselfinder.com/) 
-   Fleet Min, [fleetmon.com](https://www.fleetmon.com/)

## Trains

-   France, full interactive map of the French railway system with live
    positions of trains, plus accuracy of schedule,
    [raildar.fr/\#lat=46.810&lng=6.880&zoom=6](http://www.raildar.fr/%23lat%3D46.810%26lng%3D6.880%26zoom%3D6)
-   Germany, full interactive map of current positions of Deutsche
    Bahn railway network,
    apps-bahn.de/bin/livemap/query-livemap.exe/dn?L=vs\_livefahrplan&livemap
     
-   Netherlands, full interactive map of the Dutch railway system,
    including live positions of trains,
    [http://spoorkaart.mwnn.nl](http://spoorkaart.mwnn.nl/) 

## Misc

-   WikiRoutes, public transport database,
    [wikiroutes.info](http://wikiroutes.info)

# Date and time
-   SunCalc, to make an approximation of the time of the day based on
    shadows,
    [suncalc.net](http://suncalc.net) 
-   Weather,
    [wolframalpha.com](http://www.wolframalpha.com) 


## Whois, IP lookups, website analysis
-   [Censys](https://censys.io/)
-   Central Ops, [CentralOps](http://centralops.net/)
-   Certificate search, [crt.sh](https://crt.sh) 
-   Complete DNS, historical DNS records,[completedns.com/dns-history](https://completedns.com/dns-history) 
-   BuildWith. Online database of web technologies used on website [buildwith.com](http://builtwith.com)
-   Domain Tools,[DomainTools](http://www.domaintools.com/)
-   IXMaps,[IXMaps](https://www.ixmaps.ca/explore.php)
-   [Network-Tools](http://network-tools.com/)
-   [Open Site Explorer](http://www.opensiteexplorer.org/)

##   People search
-   Peekyou,
    [peekyou.com](http://peekyou.com) 
-   Pipl, the world largest people search engine, find persons behind an e-mail address, social media username, or phone number,  [pipl.com](https://pipl.com/)
-   Yasni, [yasni.com](http://www.yasni.com/)
-   Zaba Search, only US, [zabasearch.com](http://www.zabasearch.com/)
-   [publicrecords.searchsystems.net](http://www.publicrecords.searchsystems.net)
-   [cemetery.canadagenweb.org/search.html](http://cemetery.canadagenweb.org/search.html)
-   [opencorporates.com](https://opencorporates.com/)

## Networks
-   [Robtex](https://www.robtex.com/)
-   [BGPView](https://bgpview.io/) to find networks and it's prefixes
-   [SearchIRC](http://search.mibbit.com/)
-   [Shodan Computer Search](http://www.shodanhq.com/)
-   [Utrace](http://en.utrace.de/)
-   [ViewDNS](http://viewdns.info/)
-   [D](http://whois.icann.org), [research.dnstrails.com](http://research.dnstrails.com)
-   [SpyOnWeb](http://research.dnstrails.com/)[,to retrieve websites by their Trackingcodes,](http://research.dnstrails.com/) 
-   Whois, for domain search and information, [whois.net](http://www.whois.net) or [whois.icann.org](http://whois.icann.org)

# Archiving
-   Archive.is, let’s you archive any webpage.
-   Let’s say you want to look whether old IS reports were archived, use
    a Google advanced search: make an \<IS search term\> justpaste.it
    site:archive.is and perhaps the site has been archived.

-   CachedView.com, Google Cached Pages for any web site. It is the
    ultimate internet cache.
-   Gruber, slideshare downloader,
    [http://grub.cballenar.me/](http://grub.cballenar.me/)
-   Historic Breach Database List,
    [https://publicdbhost.dmca.gripe/random/](https://publicdbhost.dmca.gripe/random/)
-   Wayback Machine, which archives websites
    [archive.org/web/web.php](http://archive.org/web/web.php) 

-   Download an entire website from the Wayback Machine,
    [github.com/hartator/wayback-machine-downloader](https://github.com/hartator/wayback-machine-downloader)

# Miscellaneous
-   Check for collaborative fact-checking, [checkmedia.org](http://www.checkdesk.org) 

-   Link to [user
    guide](https://drive.google.com/drive/u/1/folders/0B8ssHSpx1n0qcW9TYnNuYmx1VWc)
-   Bellingcat’s [Check team](https://checkmedia.org/)

-   Document Redaction, useful for removing potentially harmful content
    in Pdfs before viewing, like traceback,
    [github.com/firstlookmedia/pdf-redact-tools](https://github.com/firstlookmedia/pdf-redact-tools)
-   Geo IP Tool, check your own IP, handy to check if your VPN is
    working,
    [geoiptool.com](https://geoiptool.com)
-   Google Search Operators, such as searching for a specific filetype
    (e.g. PDF) or on a specific website,
    [googleguide.com/advanced\_operators\_](http://www.googleguide.com/advanced_operators_reference.html) 

-   Insecam, network live IP video cameras directory,
    [insecam.org/en/](http://www.insecam.org/en/) 
-   Knight Lab, make an interactive timeline of events,
    [timeline.knightlab.com](https://timeline.knightlab.com) 
-   LittleSis, a database of who-knows-who at the heights of business
    and government,
    [littlesis.org](http://littlesis.org/)
-   Lumen, the Lumen database collects and analyses legal complaints and
    requests for removal of online materials, helping Internet users to
    know their rights and understand the law. These data enables us to
    study the prevalence of legal threats and let Internet users see the
    source of content removals,
    [lumendatabase.org](https://lumendatabase.org/) 
-   Maltego tool,
    [paterva.com/web7](https://www.paterva.com/web7/)
-   Montage for collaborative working,
    [montage.storyful.com](https://montage.storyful.com/welcome?next%3D%252Fmy-projects)
-   OpenCorporates, database of companies in the world,         
-   People tracer,
    [peopletracer.co.uk](http://www.peopletracer.co.uk) 
-   Research sidekick Hunch.ly,
    [hunch.ly](http://www.hunch.ly/)
-   Visual Investigative Scenarios (VIS), a
    tool,[ ](https://vis.occrp.org/)
-   Wolfram Alpha, for any question and a computer-generated answer,
    [wolframalpha.com](http://www.wolframalpha.com) 
-   Zoopla, Search for property with the UK's leading resource. Browse
    houses and flats for sale and to rent, and find estate agents in any
    area,
    [zoopla.co.uk](https://www.zoopla.co.uk/) 

# Guides and handbooks
-   Bellingcat’s resources,
    [www.bellingcat.com/category/resources/how-tos](http://www.bellingcat.com/category/resources/how-tos/),
    for example:
-   [E](http://verificationhandbook.com/)e,
    a project by the Tactical Tech Collective,
     [exposingtheinvisible.org](https://exposingtheinvisible.org)

-   Includes multiple guides (website data scraping, Google Dorking
    etc.), resource links, and examples of successful investigations in
    various fields

-   First Draft News’ resources, some of which have been written by
    Bellingcat members,
    [firstdraftnews.com/resources](https://firstdraftnews.com/resources/),
    for example:

-   [How to Get Started in Online
    Investigations](https://firstdraftnews.com/how-to-get-started-in-online-investigations-with-open-source-intelligence-osint/)

-   The Verification Handbook (PDF) is a great place to go,
    [verificationhandbook.com](http://verificationhandbook.com/)

## Weapons

-   Open guide called “Itrace” by Conflict Armament Research, lots of
    information on different kinds of munitions and weapons presented
    graphically on a map format,
    [itrace.conflictarm.com](http://itrace.conflictarm.com/Home/Login) 

# Data visualization
-   DataBasic.io, web tools for beginners that introduce concepts of
    working with data,
     [databasic.io/en](https://www.databasic.io/en/) 
-   DataWrapper, easy to use chart and mapping tool,
    [datawrapper.de](https://www.datawrapper.de/) 
-   Google Fusion Tables, fusiontables.google.com  
-   Maptia,
    [maptia.com](https://maptia.com) 
-   Visual investigative
    scenarios, [vis.occrp.org](https://vis.occrp.org) 
-   RAWGraphs, free webtool to quickly visualize your data,
    [app.rawgraphs.io](http://app.rawgraphs.io/)

# Online security and privacy
-   Check for every digital service you use whether you have enabled two
    factor authentication (2FA),
    [twofactorauth.org](https://twofactorauth.org/) 
-   Security in a box guide:
    [https://securityinabox.org/en/](https://securityinabox.org/en/) 

# Search engines which protect privacy
-   DuckDuckGo, Internet search engine, protecting privacy,
    [duckduckgo.com](https://duckduckgo.com)
-   Qwant, Internet search engine, protecting privacy,
    [qwant.com](http://www.qwant.com) 

# List of sources per country

## Iraq

-   Provinces of the so-called Islamic State,
    [umap.openstreetmap.fr](http://umap.openstreetmap.fr/en/map/islamic-state-claimed-provinces-map_29647%236/32.880/45.242)

## Russia

- SearchFace. Face search services for Vkontakte [searchface.ru](http://searchface.ru/)

### OSINT guides

- How to use google and other online instruments to [analyze person accounts](https://habr.com/ru/company/echelon/blog/321754/). Russian language
- How to use social networks [API for OSINT purposes](https://habr.com/ru/company/xakep/blog/254129/)

## Syria

-   Opposition media, see this excellent list compiled by Noor Nahas of
    multimedia sources from Syrian opposition groups,
    [reddit.com](https://www.reddit.com/r/syriancivilwar/comments/4km13m/free_syrian_media_opposition_activists_and/)
-   Provinces of the so-called Islamic State,
    [umap.openstreetmap.fr](http://umap.openstreetmap.fr/en/map/islamic-state-claimed-provinces-map_29647%236/32.880/45.242)
