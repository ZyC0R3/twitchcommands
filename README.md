### Subs Count Command
!addcom -cd=5 !subs $(twitch $(channel) "{{displayName}} has {{subscriberCount}} subscribers.")

### Follower Count Command
!addcom !followers $(twitch $(channel) "{{displayName}} has {{followers}} followers")

### Shoutout Command.
!addcom !so $(twitch $(touser) "Give {{displayName}} a follow at {{url}} they were last playing {{game}}")

### Gift 2 Subs Command
!addcom !bounty Destiny's Official Extension has a NEW Weekly Bounty, GIFT 2 SUBS in order to unlock rewards. YOU MUST HAVE YOUR BUNGIE ACCOUNT AND TWITCH LINKED FIRST! Once you have gifted two (ANONYMOUS SUBS WON'T COUNT), you should have a popup on your screen saying you've completed the bounty. Head to Amanda Holiday in the Tower to claim your rewards. (Chrome might have issues, double check in another browser) CHECK THIS IF YOU HAVE MORE ISSUES https://www.bungie.net/en/Help/Article/48844

### Uptime Command
!addcom !uptime Stream uptime: $(twitch $(channel) "{{uptimeLength}}")

### Party Command
!addcom !Party $(twitch $(channel) " Me and {{viewers}} are having a party")

### Customer Countdown
!addcom !countdown: $(countdown Dec 25 2020 12:00:00 AM EST)

### Gift Bounty Help
!addcom !bountyhelp Viewers who encounter issues with bounty progress after purchasing gift subs should refresh the stream they are currently viewing. If progress is still not counted please follow this link and fill out the Gift Sub Contact Form. https://www.bungie.net/en/Support/Troubleshoot?oid=48947

### Gift Bounty Mobile Help
!addcom !mobilebounty FOR THE BOUNTY ON MOBILE: Link your Bungie account with your Twitch Account go to Bungie.net > My Account > Twitch > Settings > Accounts & Linking, AFTER THAT go to https://sjc.go.twitch.tv/Gladd - Log in, and turn your mobile sideways and collapse chat to open the extension. DO NOT GIFT ANONYMOUSLY, CHECK THIS IF YOU HAVE MORE ISSUES https://www.bungie.net/en/Help/Article/48844

### Destiny Update Help
!addcom !updategame If you are having problems or if destiny is saying "game is at capacity" Close your game, and make sure steam is closed, open steam and it should start to update. if this does not work close steam and make sure it is closed from task manager, open it again and it will start to download. If this still does not work, right-click destiny and go "Properties" then go to "Local Files" and Verify files, this will say it needs to update and force the update to start.

### BRB Command
!addcom !brb (USERNAME) is currently taking a short break and should return shortly. Please standy and hang in chat and listen to some tunes. Don't forget to smash that follow button if you havent already!

### Countdown to Weekly Reset
!addcom !reset Time until next reset: $(countdown $(eval h=17+0;n=new Date();s=new Date(Date.UTC(n.getUTCFullYear(),n.getUTCMonth(),n.getUTCDate()+(2-n.getUTCDay())%7,(h%24+24)%24));if(s<n)s.setDate(s.getDate()+7);s.toLocaleTimeString("en-US",{hour12:true,month:"numeric",day:"numeric",year:"numeric"}).replace(/\//g," ").replace(/,/g,"").replace(/(?=\b\d\b)/g,"0")+" "+Intl.DateTimeFormat().resolvedOptions().timeZone))

### Lurk Command
!addcom !lurk $(user) is lurking in the shadows but still showing the love.

### Bits Command
!addcom !bits	Bits are a currency on Twitch that are the equivalent to one cent. ($.01) Don't forget that you can support the stream without spending a penny by earning bits from watching ads, and then donating them to the stream!

### Dungeon Report
!addcom !dr wanna see my dungeon.report? https://dungeon.report/

### Join Command
!addcom !join My Join code is ??????????????????

### Steam Code Command
!addcom !steam My Steam code is ?????????

### Prime Command 
!addcom !prime Don't forget you can use your Amazon prime/Twitch prime membership to sub for free!
