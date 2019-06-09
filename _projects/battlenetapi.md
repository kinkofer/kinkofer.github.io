---
layout: project
name: "Swift BattleNet API"
bannerImg: "battlenetapi_banner.png"
position: "iOS Developer"
website: "[Swift BattleNet API Github](http://github.com/kinkofer/BattleNetAPI)"
rank: 12
---


## About ##

This project is a Swift wrapper for Blizzard's Battle.Net API. It calls all the available public APIs for World of Warcraft, Star Craft II, and Diable III. The API uses OAuth to retrieve a client access token, as well as providing the OAuth required for user authentication and accessing the web services pertaining to that user.

The project is open source, and is structured to allow other developers to pull out pieces for their own use. Networking, authentication, objects, and decoding methods are all built in Swift. The example app included acts as an object viewer, drilling down into the nested objects returned by the APIs. Integration tests are included to ensure object decoding is functional, as the Blizzard documentation omits full object structure.