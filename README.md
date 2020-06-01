# OPSEC tips for the general public

It's always a good idea to properly configure your computer and smartphone, know how to securely communicate with others and how to read, write and share content while protecting your personal information. These practices are more relevant than ever.

OPSEC stands for [operations security](https://en.wikipedia.org/wiki/Operations_security), taken from wikipedia:
```
"Operations security (OPSEC) is a process that identifies critical information to determine if friendly actions can be observed by enemy intelligence."
```
In other words, OPSEC helps you share and consume information in a secure and private manner. For example sharing photos and videos with friends or reading articles on the Internet without a malicious actor (or 3rd party) knowing about it.

Here are some tips that may help you:

## On your computer
- To browse the Internet and read articles or post content, you can download [TOR](https://www.torproject.org/download/). TOR is a web browser that uses a [very cool technology](https://en.wikipedia.org/wiki/Tor_(anonymity_network)#Originating_traffic) to help you maintain your connection anonymous and hidden from 3rd parties. You can read more about it [here](https://www.torproject.org/about/history/). (Available for Windows, macOS and Linux).
- Another option is to install a [virtual private network](https://en.wikipedia.org/wiki/Virtual_private_network) or VPN and keep it on while browsing the Internet. VPNs will help you hide your [public IP](https://en.wikipedia.org/wiki/IP_address#Public_addresses) (your computer's public identification on the Internet) and prevent your [ISP](https://en.wikipedia.org/wiki/Internet_service_provider) from "looking" your traffic. (Available for Windows, macOS and Linux).
- Use "Private Browsing", "Private Window", "Incognito" modes on your browser. These modes allow you to browse the Internet in a way that would limit the traking from websites with mechanisms like [cookies](https://en.wikipedia.org/wiki/HTTP_cookie).
- Make sure the website you're connecting to is served over TLS. Some browsers use the words "secure"/"insecure", "protected"/"not protected", or a lock icon to help you visualize this. However a more effective way to check this is to make sure the domain you're visiting starts with `https://`. (Make sure it has an `s` at the end of `http`).

## On your smartphone
- When browsing the Internet, follow the same tips as with your computer.
- When sharing information, you can use end-to-end encrypted applications like [Signal](https://signal.org/en/), [Telegram](https://telegram.org/), [Wire](https://wire.com/en/), [among others](https://duckduckgo.com/?q=end+to+end+encrypted+chat+app&t=hk&ia=web). End-to-end encrypted (e2ee) applications will make sure that only the parties involved in the communication (members of a chat room) have access to the content.
- Uninstall applicationss that you may not be using. Something you might not be aware  of is that many applications track a lot of information via analytics.
    - This is specifically for iOS users, to block many of these unwanted analytics calls you can use [Guardian](https://guardianapp.com/). Guardian is an iOS firewall that will block many of these analytics libraries, (it also has other features).
- Consider removing the SIM from your phone when you're out documenting events. When your phone has cellular connectivity, it's constantly pinging the nearest cell tower to give you the best signal but this has the effect that your phone is giving away your physical location while you move around. [Read more about it](https://en.wikipedia.org/wiki/Mobile_phone_tracking).
- Remove the [EXIF data](https://en.wikipedia.org/wiki/Exif) from your photos and videos before posting them. EXIF data is the metadata attached to the media files taken from your smartphone. This metadata may include GPS coordinates, make and model of your smartphone and camera.

### Contributions
I published [this post on GitHub](https://github.com/ivRodriguezCA/opsec-tips-for-the-general-public), you can send me [PRs](https://github.com/ivRodriguezCA/opsec-tips-for-the-general-public/pulls) or create [issues](https://github.com/ivRodriguezCA/opsec-tips-for-the-general-public/issues) with suggestions for new tips and/or corrections if something I said is wrong or obsolete.

## Final thoughts
In most cases following all of the tips will help you protect your traffic faily well but event just a comination some of them will probably improve your OPSEC significantly.
There isn't a one-size-fits-all answer for OPSEC practices but the more protections you add to your stack, the harder an attacker has to work to gain access.

### Disclaimer
This is just a collection of tips and suggestions to *help* you. It's in no way an exhaustive list nor will the tips work in every single situation. Every technology has its issues and in some cases some tools my not even help at all, but something is better than nothing in this case. To be clear, **I'm not saying you'll be 100% anonymous nor 100% protected**, but these tips might help you in *some* way.
