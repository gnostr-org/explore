---
aliases: nostr, nostr-protocol, NIPS
created_by: fiatjaf
display_name: Nostr
github_url: https://github.com/nostr-protocol
logo: nostr.png
released: Nov 7, 2020 
short_description: nostr - Notes and Other Stuff Transmitted by Relays
topic: nostr
url: https://nostr.com
wikipedia_url: https://en.wikipedia.org/wiki/Nostr
---

### nostr - Notes and Other Stuff Transmitted by Relays

The simplest open protocol ([NIPS](https://github.com/nostr-protocol/nips)) that is able to create a censorship-resistant global "social" network once and for all.

It doesn't rely on any trusted central server, hence it is resilient. The protocol is based on cryptographic keys and signatures, so it is tamperproof, it does not rely on P2P techniques, and therefore it works.

#### Summary:

Everybody runs a client. It can be a native client, a web client, etc. To publish something, you write a post, sign it with your key and send it to multiple relays (servers hosted by someone else, or yourself). To get updates from other people, you ask multiple relays if they know anything about these other people. Anyone can run a relay. A relay is very simple and dumb. It does nothing besides accepting posts from some people and forwarding to others. Relays don't have to be trusted. Signatures are verified on the client side.


<!--

Release date based on commit:
https://github.com/nostr-protocol/nostr/commit/6158017db0b12686218113232fff175a45953e2f

-->
