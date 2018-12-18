---
title: Malicious Software
description: Common Scams
priority: 10
date_published: '2018-03-12'
date_modified: '2018-03-12'
---

## Malicious Software-Based Attacks

Malicious software is anything that changes the functionality of your computer for the purpose of making someone else profit in some way. Malicious software can come in many forms—from [Keyloggers](https://en.wikipedia.org/wiki/Keystroke_logging) and [Clipboard Hijackers](http://whatis.techtarget.com/definition/clipboard-hijack-attack) to [RATs](https://en.wikipedia.org/wiki/Remote_access_trojan) and [Trojans](https://en.wikipedia.org/wiki/Trojan_horse_(computing)).

This malware can be used to steal your funds by taking your private keys (the access keys to your public addresses) and transferring your funds away.

### How Can I Mitigate This?

Users should always practice safe computing habits. Here are some useful tips:

* Do not download files from emails or websites that you don't know or trust.
* Get in the habit of running periodic antivirus / antimalware scans on your computer.
* Do not use public networks for anything related to cryptocurrency. Public networks expose your browsing habits to anyone on the network listening for them.
* Download an antivirus and firewall software for your computer.
* Do not allow others to have unmonitored access to your computer.

---

### Keyloggers

Keyloggers can be used to record your private keys / Keystore passwords / mnemonic phrases.

### Clipboard Hijackers

Clipboard Hijackers can be used for public key replacement. In this case, a bad actor's malware watches your clipboard and when it sees strings that resemble Ethereum, Bitcoin, Monero, or Litecoin public keys, it replaces the copied public key with the attacker's previously-specified public key. That way, when you go to paste it into a send box to transfer your funds to someone or some organization, you actually end up sending to the attacker.

Reference:

* [ComboJack](https://researchcenter.paloaltonetworks.com/2018/03/unit42-sure-ill-take-new-combojack-malware-alters-clipboards-steal-cryptocurrency/)
* [Cryptoshuffler](https://www.kaspersky.com/blog/cryptoshuffler-bitcoin-stealer/19976/)

---

If you don't understand any of the terms in this article, please try referencing our [Ethereum Glossary](https://support.mycrypto.com/getting-started/ethereum-glossary.html).
