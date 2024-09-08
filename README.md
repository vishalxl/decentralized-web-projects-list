# Decentralized Web Projects
A list of all projects that aim to make the web more decentralized

# Decentralized Social Networks 

| # |   Project Name  |  Open Source |  Description                 |  Design           | Status       |  Link(s)|
|-|:----------------|:------------:|:-------------------------------|-------------------|--------------|--------|
|1| [Mastodon](https://joinmastodon.org/)[^1]    | Yes | SN[^2], most widely used, part of Fediverse[^3] |Federated server, uses ActivityPub| Functional|  [site](https://joinmastodon.org/) |
|2| [Diaspora](https://diasporafoundation.org)| Yes | SN. widely used, part of Fediverse  |Federated server, uses ActivityPub| Functional |  [site](https://diasporafoundation.org)|
|3| [Secure Scuttlebutt](https://scuttlebutt.nz)| Yes |SN, Mesh, p2p, widely used |Mesh, p2p|Functional    |[site](https://scuttlebutt.nz), [Another version, Manyverse](https://www.manyver.se/), [SSB Protocol guide](https://ssbc.github.io/scuttlebutt-protocol-guide)|
|4|Clients of [Matrix](https://matrix.org/) Open Standard|Yes|Chat - Real time communication over TCP/IP, widely used|Interconnected Distributed servers; clients that use them|Functional; bridges for Gitter, XMPP|[site](https://matrix.org/)|
|5| [Retroshare](https://retroshare.cc)   | Yes          |SN, File sharing    |Mesh, p2p          |Functional but breaking, no maintenance|[site](https://retroshare.cc), [Github](https://github.com/RetroShare/RetroShare)|
|6| [Aether](https://getaether.net)| Yes  |Reddit like SN |Flood mesh, p2p  |Functional    |[site and about info](https://getaether.net/about-contact/) |
|7|[Movim](https://github.com/movim/movim)| Yes|SN| Based on XMPP |Functional, in development|[site](https://movim.eu/), [Github](https://github.com/movim/movim)|
|8| [SOLID](https://solidproject.org)| Yes|Data store model, led by Tim Berners Lee|Data store pods     |In development| [site](https://solidproject.org) |
|9|[Nostr](https://github.com/nostr-protocol/nostr)|Yes|SN, chat          |Websocket relays, schnorr sigs  |Functional, in Development|[Intro to Nostr](https://github.com/nostr-protocol/nostr), [Awesome Nostr List](https://github.com/aljazceru/awesome-nostr), [NIP](https://github.com/nostr-protocol/nips), client [list](https://github.com/vishalxl/Nostr-Clients-Features-List)|


# Other Decentralized Projects
| # |   Project Name  |  Open Source |  Description                 |  Design           | Status       |  Link(s)|
|-|:----------------|:------------:|:-------------------------------|-------------------|--------------|--------|
|1|[Iroh](https://www.iroh.computer/)|Yes| Distributed apps, using p2p data share| Documents, Blobs, Gossip, & Networking| Has tools, and basic applications such as [dumppipe](https://www.dumbpipe.dev/) and [sendme](https://github.com/n0-computer/sendme); [short video on sendme use](https://twitter.com/iroh_n0/status/1737854297122197741); example [issue](https://github.com/n0-computer/iroh/issues/2317)|  [Iroh Github](https://github.com/n0-computer/iroh)|
|2|[PeerTube](https://joinpeertube.org)|Yes|Federated video solution, part of Fediverse |Uses ActivityPub, federated servers | Functional| [site](https://joinpeertube.org/), [BitcoinTV - an instance of PeerTube](https://bitcointv.com)|
|3|[Keet](https://keet.io/)|to be open-source released in Dec'22|p2p video call app| | live, released in Aug 2022| [annoucnement](https://bitcoinmagazine.com/technical/keet-the-decentralized-communications-app)|
|4|[Wildland](https://wildland.io) |Yes  |Distributed storage, Data ownership, distributed file system(s)   |One con is that they seem to have integrated a token(eth) into their system|In development, Beta| [site](https://wildland.io), [introduction to Wildland](https://golem.foundation/2020/04/09/wildland.html)|
|5|[Magic Wormhole](https://github.com/magic-wormhole/magic-wormhole) |Yes          |File transfer/sharing application, open source, and a website| Uses a mailbox server to connect two endpoints| Functional | [Github](https://github.com/magic-wormhole/magic-wormhole), [docs](https://magic-wormhole.readthedocs.io/en/latest/), [file transfer site](https://wormhole.app/)|
|6|[GNUnet](https://www.gnunet.org) stack |Yes |Collection of applications|Tech stack with file system, VPN support| Functional| [how to use](https://www.gnunet.org/en/use.html), tool [Anastasis](https://anastasis.lu/en/index.html) for password recovery|
|7|[Dark Crystal](https://darkcrystal.pw/)| Yes | Allows safeguarding your private key(s) by sharing them among number of other individuals you trust| Like Anastasis;  shamir secret sharing and similar techniques| In development, being used by Secure Scuttlebutt apps| [Protocol spec](https://darkcrystal.pw/protocol-specification/)
|8|[Earthstar](https://earthstar-project.org/) | Yes| private, distributed, offline-first applications | Shares (shared folder), replicas (copy of share), Documents (describe shares data), keypairs (start with 4 letters)| In development | [How Earthstar works](https://earthstar-project.org/docs/how-it-works)| 
|9|[p2panda](https://p2panda.org/)| Yes | build local-first websites, mobile- and desktop applications | Rust and JS [sdk](https://p2panda.org/sdks/)  | in development, [network node called aquadoggo](https://github.com/p2panda/aquadoggo/), [roadmap](https://p2panda.org/about/roadmap) | [History of p2panda](https://p2panda.org/about/history)

# Technology Stacks

|#| Name           | Other related technologies | Main driver |  Users      |
|-|----------------|----------------------------|-------------|-------------|
|1|[WEB5](https://developer.tbd.website/projects/web5/)[^4][^5] |DID, "Control your identity, Control your Data" |Jack Dorsey's Block Inc    |In development|
|2|[ActivityPub](https://en.wikipedia.org/wiki/ActivityPub)     |Based on Pump.io's ActivityPump protocol, applications using it are called Fediverse | W3C            | Mastodon, NextCloud |
|3|[WebRTC](https://webrtc.org)|Communication, p2p, browser to browser comm, WebTorrent uses it |Supported by Apple, Google, Microsoft and Mozilla| WebRTC.org |


## Document History

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
