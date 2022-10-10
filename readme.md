```sh
strg k #github spotlight
```

```sh
. #vs code in browser
alt #toggle menue bar
crtl shit g #source controll
crtl shift e #explorer
```

#### books

#### falls fad
[intervew mag](http://www.interviewmagazine.com/#fashion) - 
[digg mag](http://digg.com/) - 
[coub](https://coub.com/) - 
[hiddenfolks](http://hiddenfolks.com/) - 
[fact mag](http://www.factmag.com/) - 
[theaterstack](https://theartstack.com/shop) - 
[behance](https://www.behance.net/) - 
[tewan](http://tewan.diem.cl/webspace/canvasexperiment/) - 
[verge mag](http://www.theverge.com/) - 
[buzzart mag](https://bbuzzart.com/discover) - 
[wired mag](https://www.wired.com/) - 
[applemusic](https://beta.music.apple.com/for-you) - 
[liyricallemo](https://lyricallemonade.com/) - 
[dakar](https://www.dakar.com/en) - 
[closcosta](http://www.carloscosta.me/) - 
[coin](https://projects.playables.net/coin/) - 
[ny mag](http://www.newyorker.com/) - 
[garinwood](http://www.garinwood.com/) - 
[unsplach](https://unsplash.com/) - 
[efianugrah](https://erfianugrah.com/) - 
[mvsm](http://mvsm.com/) - 
[abelton](https://learningmusic.ableton.com/) - 
[falling](http://www.fallingfalling.com/) - 
[playkids](http://playkids.ch/presskit/) - 
[adobe](https://stock.adobe.com/de/) - 
[petertarka](https://petertarka.com/) - 
[twigl](https://twigl.app/) - 
[hypbeast mag](https://hypebeast.com/) - 
[mavfarm](https://mav.farm/) - 
[pime<es](https://pimeyes.com/en) - 
[brunosimons](https://bruno-simon.com/) - 
[samsweetsounds](http://samsayssweetsounds.com/) - 
[issdock](https://iss-sim.spacex.com/) - 
[pinewoodphysics](http://pinewoodphysics.com/index.html) - 
[chromexperiments](https://experiments.withgoogle.com/collection/chrome) - 
[win](http://www.windows93.net/) - 
[oeis](https://oeis.org/) - 
[takitamblog](https://takitamblog.tk/skrypty/Tupper/) - 
[cvldemo](https://cvl-demos.cs.nott.ac.uk/vrn/) - 
[tng](https://www.tng-project.org/explore/) - 
[qzsattelite](https://qz.com/296941/interactive-graphic-every-active-satellite-orbiting-earth/) - 
[quantum mag](https://www.quantamagazine.org/) - 
[aim93](https://www.aim93.com/) - 
[4chan](http://www.4chan.org/) - 
[galleriesnow](https://www.galleriesnow.net/) - 
[follower](https://follower.today/#apply) - 
[flicker](https://www.flickr.com/) - 
[avasession](https://ava-sessions.com/) - 
[wahtif](http://what-if.xkcd.com/) - 
[futurism mag](http://futurism.com/) - 
[zunzun](http://zunzun.com/) - 
[99invis](https://99percentinvisible.org/) - 
[boldmatic](https://boldomatic.com/) - 
[tumblr](https://www.tumblr.com/dashboard) - 
[gentle](http://ekrivoruchko.com/gentlebrain/)

#### para
[dhv](https://www.dhv.de/wetter/) - 
[dhv geo](http://www.dhv.de/db2/geosearch.php) - 
[paraearth](https://paraglidingearth.com/) - 
[windy](https://www.windy.com/) - 
[paragildabel](https://paraglidable.com/mobile.html) - 
[weather](https://weather.com/weather/hourbyhour/l/GMXX0087:1:GM) - 
[yamg](https://www.zamg.ac.at/cms/de/wetter/wetterkarte) - 
[radar](https://weather.com/weather/radar/interactive/) - 
[darksky](https://darksky.net/) - 
[earth](https://earth.nullschool.net/)

#### nützlich
`javascript:(function()%7Bdocument.getElementsByTagName(%22Input%22)%5B0%5D.setAttribute(%22style%22,%20%22outline:%20none;%20font-size:%2021px;%22);%C2%A0let%20v=%20document.querySelector('video');%C2%A0v.addEventListener('webkitpresentationmodechanged',(e)=%3Ee.stopPropagation(),%20true);%C2%A0setTimeout(()=%3Ev.webkitSetPresentationMode('picture-in-picture'),%203000);completion()%7D)();` - 
[vpngate](https://www.vpngate.net/en/) 


#### [ff](https://www.mozilla.org/en-US/firefox/new/)
[userchrome.css](https://github.com/crbyxwpzfl/ff/blob/main/userChrome.css)
```sh
about:support #open url to find profile folder
\Mozilla\Firefox\Profiles\...\chrome\userChrome.css #put userChrome.css here
about:config toolkit.legacyUserProfileCustomizations.stylesheets = true #to load userChrome
about:config browser.backspace_action = 0 #for backspace back
```
general
```sh
Alt # drop address bar while address bar showing navigate invisible menues via arrow keys
    # to use element click and hit alt again
Strg Tab #switch tabs
```

#### [tridactyl](https://github.com/tridactyl/tridactyl)
setup
```sh
:colourscheme --url https://crbyxwpzfl.github.io/ff/theme.css theme #remeber to host githubpages from master baranch before in repo settings
:unbind . #make . for github work
:unbind <C-f> #make search page use ff inernal search
:unbind <C-b> #let strg b open bookmarks pane
:set hintchars hjklasdgyuiopqwertnmzxcvb  #exclude f
:bind --mode=normal f hint -J*  #bind f to hint all except js
:set hintchars 0123456789 #set hintchars so one can type with next setting
:set hintfiltermode vimperator-refow #type to naeeow down hints
:set modeindicatormodes {"normal":"false", "hint":"false"} #hide moe indicator
:setnull searchurls.github  #disable github seach
```
general
```sh
b #show tabs<br>
o #open in same tab<br>
t #open in new tab<br>
O #show current link<br>
hjkl #move
f #clik link
Shift hl #back forward
Shift jk #tabs cycle
d #clsoe tab
```

#### vscode in github
[settings.json](https://github.com/crbyxwpzfl/ff/blob/main/settings.json)
```sh
crtl , #to open settings then click upper right button and paste settings.json
```
general
```sh
. #vs code in browser
alt #toggle menue bar
crtl shit g #source controll
crtl shift e #explorer
```

#### [ublock origin](https://github.com/gorhill/uBlock)
```sh
# in settings uncheck make use of context menue when appropiate
```

#### [icloud bokmarks](https://addons.mozilla.org/en-US/firefox/addon/icloud-bookmarks)
requires windows [icloud app](https://www.microsoft.com/store/apps/9PKTQ5699M62)


