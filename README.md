# Decentralized Web Projects
A list of all projects that aim to make the web more decentralized

# Decentralized Social Networks 

| # |   Project Name                             |  Open Source |  Description and  Design                             | Status       |  Link(s)|
|-|:----------------                             |:------------:|:-----------------------------------------------------|--------------|--------|
|1| [Mastodon](https://joinmastodon.org/)[^1]    | Yes          | SN[^2], most widely used, part of Fediverse[^3]; uses ActivityPub| Functional|  [site](https://joinmastodon.org/) |
|2| [Diaspora](https://diasporafoundation.org)   | Yes          | SN. widely used, part of Fediverse, uses ActivityPub | Functional |  [site](https://diasporafoundation.org)|
|3| [Secure Scuttlebutt](https://scuttlebutt.nz) | Yes          | SN, Mesh, p2p, widely used                           |Functional    |[site](https://scuttlebutt.nz), [guide](https://ssbc.github.io/scuttlebutt-protocol-guide)|
|4| [Matrix](https://matrix.org/) and Clients    |Yes           | Real time chat over TCP/IP, widely used;             |Functional; bridges for Gitter, XMPP|[site](https://matrix.org/)|
|5| [Retroshare](https://retroshare.cc)          | Yes          | SN, File sharing; Mesh, p2p                          |Functional but breaking, no maintenance|[site](https://retroshare.cc), [Github](https://github.com/RetroShare/RetroShare)|
|6| [Aether](https://getaether.net)              | Yes          |Reddit like SN; Flood mesh, p2p                       |Functional    |[site and about info](https://getaether.net/about-contact/) |
|7| [Movim](https://github.com/movim/movim)      | Yes          |SN, Based on XMPP                                     |Functional, in development|[site](https://movim.eu/), [Github](https://github.com/movim/movim)|
|8| [SOLID](https://solidproject.org)            | Yes          |Data store in pods, led by Tim Berners Lee            |In development| [site](https://solidproject.org) |
|9|[Nostr](https://github.com/nostr-protocol/nostr)|Yes         |SN, chat; Websocket relays, schnorr sigs              |Functional, in Development|[Intro](https://github.com/nostr-protocol/nostr), [Awesome Nostr List](https://github.com/aljazceru/awesome-nostr), [NIP](https://github.com/nostr-protocol/nips)|


# Other Decentralized Projects
| # |   Project Name                             |  Open Source |  Description and Design                                                       | Status            |  Link(s)|
|-|:----------------                             |:------------:|:-------------------------------------------------                      |-------------------|--------|
|1|[Iroh](https://www.iroh.computer/)            |Yes           | A framework/library; p2p ;  Documents, Blobs, Gossip, & Networking|Functional | [dumppipe](https://www.dumbpipe.dev/), [sendme](https://github.com/n0-computer/sendme); [using](https://twitter.com/iroh_n0/status/1737854297122197741); [Iroh Github](https://github.com/n0-computer/iroh)|
|2|[PeerTube](https://joinpeertube.org)          |Yes           |Federated video solution, part of Fediverse; Uses ActivityPub                  | Functional| [site](https://joinpeertube.org/), [BitcoinTV - an instance of PeerTube](https://bitcointv.com)|
|3|[Magic Wormhole](https://github.com/magic-wormhole/magic-wormhole) |Yes          |File transfer/sharing application, and a website; Uses a mailbox server to connect two endpoints| Functional | [Github](https://github.com/magic-wormhole/magic-wormhole), [docs](https://magic-wormhole.readthedocs.io/en/latest/), [file transfer site](https://wormhole.app/)|
|4|[GNUnet](https://www.gnunet.org) stack        |Yes           |Collection of applications; Tech stack with file system, VPN support| Functional| [how to use](https://www.gnunet.org/en/use.html), [Anastasis](https://anastasis.lu/en/index.html), [filesharing](https://clehaxze.tw/gemlog/2022/08-10-gnunet-file-sharing-tutorial-and-an-alternative-to-ipfs.gmi)|
|5|[Dark Crystal](https://darkcrystal.pw/)       | Yes          | Like Anastasis;  shamir secret sharing and similar techniques                  | In development, being used by Secure Scuttlebutt apps| [Protocol spec](https://darkcrystal.pw/protocol-specification/)
|6|[Earthstar](https://earthstar-project.org/)   | Yes          | private, distributed, offline-first applications ; shared folders; instantiation of [Willow](https://willowprotocol.org/index.html#willow)| In development | [How Earthstar works](https://earthstar-project.org/docs/how-it-works) | 
|7|[p2panda](https://p2panda.org/)               | Yes          | build local-first websites, mobile and desktop applications; In Rust and JS [sdk](https://p2panda.org/sdks/)  | in development, [aquadoggo](https://github.com/p2panda/aquadoggo/), [roadmap](https://p2panda.org/about/roadmap) | [History of p2panda](https://p2panda.org/about/history) |
|8| [radicle](https://radicle.xyz/)              | Yes          | p2p code collaboration stack built on Git                                    | Functional | [guides](https://radicle.xyz/guides) |
|9| [Peergos](https://peergos.org/)              | Yes          | A number of applications that interconnect, including [social network](https://peergos.org/posts/decentralized-social-media); run on your own server| Functional | [Peergos book](https://book.peergos.org/) |


# Technology Stacks

|#| Name           | Other related technologies | Main driver |  Users      |
|-|----------------|----------------------------|-------------|-------------|
|1|[AT Protocol](https://atproto.com/)  |DID, "Control your identity, Control your Data" |Non Profit. Previously called [WEB5](https://developer.tbd.website/projects/web5/)[^4][^5]    |In development, [BlueSky app](https://bsky.app/), List of [PDS's](https://blue.mackuba.eu/directory/pdses), Fediverse to BlueSky [bridge](https://fed.brid.gy/)  | 
|2|[ActivityPub](https://en.wikipedia.org/wiki/ActivityPub)     |Based on Pump.io's ActivityPump protocol, applications using it are called Fediverse | W3C            | Mastodon, NextCloud |
|3|[WebRTC](https://webrtc.org)|Communication, p2p, browser to browser comm, WebTorrent uses it |Supported by Apple, Google, Microsoft and Mozilla| WebRTC.org |
|4|[Spritely Goblins](https://spritely.institute/goblins/)|[Capn Protocol](https://capnproto.org/), is partial implementation of main standard;  |By [Spritely](https://spritely.institute/), this home page has good intro to the protocol; funded by NlNet | No usable application as of early 2025 |


## Document History

 Early 2025  - Removed Keet; added Peergos, Spritely Goblins  
 9 Sept 2024 - Mentioned Iroh, Earthstar and p2Panda; removed [GUN](https://gun.eco/), [OStatus](https://en.wikipedia.org/wiki/OStatus) and [Slashtags](https://github.com/synonymdev/slashtags)  
 6 Nov 2022 - Removed mention of abandoned project Trsst and Twister.  

[^1]: Mastodon, ActivityPub and Fediverse [explained](https://savjee.be/videos/simply-explained/mastodon-and-fediverse-explained). A different [overview](https://nerdica.net/display/84f7f58b-11196d1d6724ab77-583f6578)
[^2]: SN stands for Social Network
[^3]: One [list](https://delightful.club/delightful-fediverse-apps) of Fediverse apps
[^4]: The name 'web5' a riff/joke on 'web3', which is considered to be a VC driven scam narrative as of early 2022, used to drive shitcoin/scamcoin sales.
[^5]: Overview and [first impressions of WEB5](https://educatedguesswork.org/posts/web5-first-impressions)


## References
1. Wikipedia page for [social networking software](https://en.wikipedia.org/wiki/Comparison_of_software_and_protocols_for_distributed_social_networking)
2. [Alternative Internet list](https://github.com/redecentralize/alternative-internet)
3. [NLNet](https://nlnet.nl/project/current.html) list of projects, including Briar chat app.
4. Ecosystem overview at [Bluesky community](https://gitlab.com/bluesky-community1/decentralized-ecosystem/-/blob/master/README.md)
