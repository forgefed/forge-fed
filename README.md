# ForgeFed - Federation Protocol for Forge Services

ForgeFed is a federation protocol extending the W3C's [ActivityPub][activity-pub] protocol to provide a uniform server-to-server API for interoperability between networked version control services, with limited pub/sub access for messaging and notifications to and from the larger fediverse. It allows users of any ForgeFed-compliant service to interact with other ForgeFed-compliant forge services, without being a registered user of that foreign service, just as if they were. In this way, users that choose to self-host have the additional benefit/responsibility of fully controlling of their own authentication/identity and their own data.

All of the most common user interactions are supported such as: cloning/forking, merge-requests/patches, bug-reports/code-review, subscriptions/favorites with VCS-agnostic, service-agnostic, and client-agnostic genericity.


## Work-group Collaboration

The formal work-group and associated development discussions are conducted openly on the [ForgeFed Community Forum][feneas-forum] on the FeNeAs website; with informal, real-time Collaboration often taking place on the #peers IRC channel on freenode. Everyone is invited to participate in either venue. Before posting, please read [this primer][overview] for a brief overview of the project motivation and goals.

The artifacts produced by this work-group are still in the early stages; and there is still much work to do, and ample design-space for discussion and contributions. In order to be most widely adopted, we strive to assemble the most diverse and representative group of stake-holders including: users, implementers, and various domain experts. Anyone who is experienced with working on an existing forge or a federated "social" service, or who is planning to implement new ones, and anyone with experience in writing technical specification documents, or has UX expertise is encouraged to join the work-group and/or contribute artifacts. Please submit any tangible contributions (artwork, software, documentation) and technical critique regarding the published artifacts to the [ForgeFed issue tracker][notabug-issues] and [ForgeFed wiki][notabug-wiki] on NotABug, or the [ForgeFed mirror on Pagure][pagure-mirror].


### Projects participating in the discussions have included:

* [Federated Networks Association][feneas]
* [Git-Dit][git-dit]
* [GitLab][gitlab]
* [GitTea][gittea]
* [Gogs][gogs]
* [NotABug][notabug]
* [Pagure][pagure]
* [Peers Community][peers]
* [SocialHome][socialhome]
* [sr.ht][srht]
* [Vervis][vervis]


## License

All artifacts produced by the ForgeFed work-group are freely available under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication][cc0]. All contributions to the wiki must also be offered freely as such.


[activity-pub]:    https://www.w3.org/TR/activitypub/
[mail-archive]:    https://framalistes.org/sympa/arc/git-federation
[feneas]:          https://feneas.org
[vervis]:          https://dev.angeley.es/s/fr33domlover/r/vervis
[notabug-repo]:    https://notabug.org/peers/forgefed/
[feneas-forum]:    https://talk.feneas.org/c/forgefed
[overview]:        https://notabug.org/peers/forgefed/src/master/doc/README.md
[notabug-issues]:  https://notabug.org/peers/forgefed/issues
[notabug-wiki]:    https://notabug.org/peers/forgefed/wiki
[pagure-mirror]:   https://pagure.io/forge-fed/forge-fed
[git-dit]:         https://github.com/neithernut/git-dit
[gitlab]:          https://about.gitlab.com/
[gittea]:          https://gitea.io/en-us/
[go-fed]:          http://go-fed.org/
[gogs]:            https://gogs.io/
[notabug]:         https://notabug.org/
[pagure]:          https://pagure.io/
[peers]:           https://peers.community/
[socialhome]:      https://socialhome.network/
[srht]:            https://meta.sr.ht/
[cc0]:             https://creativecommons.org/publicdomain/zero/1.0/
