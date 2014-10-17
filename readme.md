# Fronteers 2014

## Day 1
1. ### Getting nowhere with CSS best practices
	- Luchtige presentatie over wat "best practices" zijn (of wat ze net niet zijn). Iedereen heeft hier zijn eigen idee/interpretatie over & het is simpel te zeggen dat iets niet volgens best practices is opgemaakt. Het gaat niet enkel om het schrijven van de beste code, maar evengoed om het brengen van een goede experience voor de gebruiker. Het gaat niet om de mooiste website maken met de gekste animaties, het gaat om een gebruiksvriendelijke website.
	- http://topcoat.io

1. ### Making maps, the role of frontend infrastructure at Etsy
	- Het is wel eens leuk om te zien hoe absurd veel werk/code er schuilt achter een website zoals Etsy. Wel heeft men een heel aparte aanpak, iedereen kan op eender elk moment zijn code pushen naar productie. Men maakt verder geen gebruik van feature branches, maar men ontwikkelt simpelweg een feature welke meteen toegevoegd wordt aan de productie website. Ook fascinerend is de mogelijkheid om de uitrol van een nieuwe feature volledig onder controle te houden, door deze geleidelijk aan uit te rollen naar hun gebruikers.

1. ### Do we need to write markup?


1. ### Pushing the real time web forward
	- Een mooi/technisch overzicht van de verschillende methodes om het real time web te bouwen (AJAX, sockets, ...). Wel was ik persoonlijk (Tim) niet op de hoogte dat er nog zoveel bugs gepaard gingen met Websockets vandaag de dag (ook in de meest moderne browsers). Zelfs Socket.IO, een van de bekendste frameworks die hiervoor gebruikt worden, kan niet om met al deze inconsistenties & bugs.

1. ### State of the animation 2014
    - http://github.com/web-animations
    - will-change instead of translate-z(0) hack
    - Opacity & transform css animaties zijn performanter (alles wat de layout niet beïnvloed is performanter).
    - rachelnabors.com/waapi
    - Greensock, GSAP (https://greensock.com/get-started-js, https://greensock.com/gsap)
    - Presentatie was enorm visueel en mooi gebracht in een verhalende vorm, maar om dit kort samen te vatten: een revival van flash is nabij, maar dan met CSS. CSS is nog eerder beperkt in mogelijkheden (er is bijvoorbeeld geen timeline, path animations, morphing, ...), maar de oude bekenden uit het voormalige flash tijdperk zijn intussen bewust dat er nog steeds een toekomst voor complexe animaties weggelegd is. Zo bijvoorbeeld: GSAP van Greensock, het alombekende (Flash) animations framework.

1. ### 3 mini sessions about gaming in the browser
    - http://lessmilk.com
    - http://phaser.io (IE9 support with polyfill)
    - http://impactjs.com/
    - http://phoboslab.org/xibalba/ (FPS)
    - http://phoboslab.org/fronteers2014
    - Het was leuk & inspirerend om te horen hoe de persoon uit de eerste sessie zichzelf opgelegd heeft om elke week een game te maken. Startende van een doodsimpel iets, is hij intussen uitgegroeid tot iemand die steeds complexere games ontwikkeld & tevens tutorials/boeken schrijft en hiermee intussen ook zijn brood kan verdienen.
    - De derde presentatie deed me enorm fel denken aan Bert Timmermans en zijn Pokémon game (voornamelijk de map builder). Deze persoon was ook zo gefascineerd door het spel dat hij aan het maken was voor zijn 7 dagen durende build-off wedstrijd, dat hij pas één jaar later zijn project beeindigd heeft. Het was indrukwekkend om te zien wat er vandaag de dag allemaal reeds mogelijk is met gewoon wat Javascript/WebGL/Canvas.

1. ### WebRTC: a front-end perspective
	- Een introductie tot WebRTC, de mogelijkheden ervan en wat de toekomst van WebRTC te bieden heeft. Niet veel nieuws op zich, maar wel een mooi toekomstperspectief peer-2-peer toepassingen.

1. ### Offline first: faster, more fun, and more robust
	- Tal van voorbeelden gezien waarom het toch wel belangrijk kan zijn om in sommige gevallen een "offline first" aanpak te hanteren. Waaronder bijvoorbeeld Google Maps, waar het handig zou zijn om de kaarten in jouw nabije omgeving of bepaalde locaties te cachen, zodat je deze altijd kan gebruiken. Ook zou onze data, ook steeds toegankelijk moeten zijn voor ons op eender welk moment. Nog teveel moeten we telkens onze eigen data gaan ophalen van externe servers, in de plek van dat we deze logischer gewijs gewoon lokaal ter beschikking zouden moeten hebben...
    - http://hood.ie/
    - Tobias Revell

## Day 2
1. ### Making Twitter UI infrastructure
    - http://karma-runner.github.io/ vs http://visionmedia.github.io/mocha/
    - http://theintern.io/
    - http://webpack.github.io/ (also used at Instagram)
	- Webdriver api (Java, C#)
	- Webpack module bundler (http://webpack.github.io)
	- http://bem.info/

1. ### Optimizing web performance
    - Mobile first = performance first
    - Don't overdownload on mobile
    - https://developers.google.com/speed/pagespeed/insights/
    - Performance tool (webpagetest.org)
        - Test real browsers from mult. locations
        - Modify connection speeds (handy for mobile 3G testing)
        - Video capture
        - Content blocking
        - Script the session
        - Use continous integration
        - Collect tests over time
        - Free
    - Set a performance budget (in KBs). A lot of images or webfonts make you go over this budget and this way you keep it into account http://timkadlec.com/2013/01/setting-a-performance-budget/
    - Use `srcset`. `<Picture>` can be used for art direction
    - http://microjs.com/
    - https://www.npmjs.org/package/grunt-google-cdn
    - Course on Chrome Dev tool (Udacity.com/course/ud884/)
    - redbot.org (Website to check if your server has Browser Cache properly enabled)
    - http://gulpjs.com/plugins/
    - http://vanilla-js.com/
    - https://github.com/ftlabs/fastclick
    - http://perf-tooling.today/
    - Taking it easy: Network Link Conditioner http://nshipster.com/network-link-conditioner/

1. ### Animating SVGs with CSS and SMIL
    - Verschillen met html
        - Svg doesn't have a boxmodel so origin point ligt top left (0,0) so css transform-origin (50%,50%)
    - best Object tag for embed (javascript)
    - SMIL (http://www.w3.org/TR/SMIL/)
    - Interesting tutorials http://sarasoueidan.com/


1. ### This is the web platform


1. ### Using agile to bake in accessability


1. ### Choose your own JS adventure
    - http://youdontknowjs.com

1. ### Scaling op & down: evolving your testing strategies
    - http://agilemethodology.org/
    - 3 question methodology

1. ### Dream big. Think small

