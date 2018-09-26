# MadLibby
Mad-libs via Twitch Chat! We built this Twitch-integrated chat story writer live on Twitch!

## Instafluff ##
> *Come and hang out with us at the Comfiest Corner on Twitch!*

> https://twitch.tv/instafluff

> https://twitter.com/instafluffTV

## Credits ##
Thank you to all the participants of this project!

**pipskidoodle, Instafluff, RebelRoxie, SirBillPaxton, MacabreMan2, where_is_laughingman, Instafriend, That_MS_Gamer, MrWaffle268, jellydance, Sundance_kid88, neniltheelf, Tiny__Toes, malfunct, Deitypotato, Liayda, sethorizer, Amarogine, BountyHunterLani, Zoraketh, DevMerlin, Mikeystea, DEAD_P1XL, BungalowGlow, DrJavaSaurus, mallesbixie, tsmilesxd, QeraiX, LANiD, Xynal, sasha_ebalo, InSanityParty, MoroGoddess, NiecyRed, ccjmne, Neo_TA, sciondragons, TheSkiDragon, momokohyhy, kaisuke, CaseyGeske, HeyOhKei, kingswerv, clubhouse13, LoonyLizard, GeoRevilo, AmazingPexer, TheArtisticBallistic, Poolpourri, wietlol, Flippo13, vic_likadabooty, MsKait, Kisa__d1_1b, 에메이, MisterHex**

## Instructions ##

1. Install NodeJS - [https://nodejs.org/en/](https://nodejs.org/en/)
2. Open the directory in a Command Prompt/Terminal
3. Install Dependencies: `npm install`
4. Get a Twitch Chat OAuth Password Token - [http://twitchapps.com/tmi/](http://twitchapps.com/tmi/)
4. Create a file named `.env` that looks like this:
```javascript
PORT=8000
TWITCHUSER=[YOUR-USERNAME-HERE]
OAUTH=[YOUR-OAUTH-PASS HERE] # e.g. OAUTH=oauth:kjh12bn1hsj78445234
```
5. Run Server: `npm start`
6. View the webpage from your web browser! [http://localhost:8000](http://localhost:8000)
