FoBaNS Follower Based NameService
=================================

This concept was created after reading [this tweet from myEtherWallet](https://twitter.com/myetherwallet/status/867425301403324417) and realizing even more that I will not have control over walleth.eth to use for the [WALLETH project](http://walleth.org) :-( still have some small hopes for wall.eth though ;)

These are the main problems I see with the current ENS implementation:

 * who owns a domain name is determined by who has the most money
 * names are squatted (and squatting leads to reduced usefulness of the system)

To solve these problems I suggest the following alternative NameService:

 * everyone can make n mappings between a string and a NS-Record
 * mappings for each entity in the system are unique
 * Every entity can follow other entities - If a name is not in my mapping the resolver resolves the names from the entities that are followed - we can also go deeper this chain.
