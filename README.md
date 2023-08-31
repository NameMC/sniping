```
███████╗███╗   ██╗██╗██████╗ ██╗███╗   ██╗ ██████╗ 
██╔════╝████╗  ██║██║██╔══██╗██║████╗  ██║██╔════╝ 
███████╗██╔██╗ ██║██║██████╔╝██║██╔██╗ ██║██║  ███╗
╚════██║██║╚██╗██║██║██╔═══╝ ██║██║╚██╗██║██║   ██║
███████║██║ ╚████║██║██║     ██║██║ ╚████║╚██████╔╝
 ╚══════╝╚═╝  ╚═══╝╚═╝╚═╝     ╚═╝╚═╝  ╚═══╝ ╚═════╝ 
```
# **I. Introduction**

Around a year ago I made a [Minecraft sniping guide](https://github.com/NameMC/BASIC-SNIPING-GUIDE). Considering the vast changes that have happened in the past year, I believe a revised version was necessary. I strongly advise you do not waste your time reading the older guide——if you were considering doing so——as it's very outdated. This guide (the one you're reading!) contains relevant information regarding the current state of sniping and how to obtain usernames through sniping. Unlike my previous guide, I intend for this one to be much more concise, and I will not include a glossary because it's too time consuming to make. I doubt anyone greatly benefited from that section either, so an updated version will not be made. If you have any questions, they should be taken to the [3NAME Discord Server](https://discord.gg/3name-community-609961212058271755) or the [McSniperGO Discord Server](https://discord.gg/mcsnipergo-734794891258757160).

-------------------------------------------

# **II. Frequently Asked Questions**

I've seen these questions asked numerous times. If you're just getting involved with name sniping, chances are, one of these questions is of interest to you. I would also consider reading this section before investing time and money in sniping because it may not be worth it for you.

### ➤ Should I use an autoclicker to snipe?

No, this will not work. There's a reason nobody does this; you can only send so many name-change requests before being rate-limited. Past that threshold, any outgoing requests will be null. Please view `Section IV` for more information regarding the rate-limit.

### ➤ What's an interval? Why are there two different times displayed on NameMC/3NAME?

An interval defines the start or end of a duration when something happens. In this case, the two intervals define when the name will become available, which is after the first interval and before the second interval (between the intervals). This is also called the "drop time". There is no way to know the exact drop time of the name unless you changed the name yourself and documented the time. For sniping, this means sending *constant* requests throughout the entire interval in hopes of being the first person to claim the name. More about this in `Section III`.

### ➤ Do I need a bot to snipe?

*Absolutely*. If you don't have a bot, you will not get a 3-character name or any desirable username. If you want to snipe a name that has very little views, you may be able to obtain it. However, for any names that are considered "desirable", a bot is *absolutely necessary* to snipe the name. For your convenience, I have included a free, open-source sniping bot which is available for you to download and use in `Section ?`. If you don't want to / can't use a bot, **do not waste your time trying to snipe. You will not get a desirable name. Period. Trust me when I say it's impossible to do so.**

### ➤ I see some available 3-character names like PLQ, U40, and DLK. Why aren't people claiming them?

These names are blocked. There used to be hundreds of blocked 3-character names and there even used to be the ability to block names (temporarily) at will. This is no longer possible. It's incredibly unlikely any names that are blocked now will be unblocked in the future. Don't waste your time trying to auto-claim blocked 3-character names (people have bots for those too!). Focus on names that are dropping instead.

### ➤ Every time a 3-character name drops, a new account claims it. How?

The most common method of sniping at the moment is Game Pass (abbreviated as GP) sniping. Game Pass accounts are relatively inexpensive (people purchase them for $0.10 each). This means snipers can buy hundreds——sometimes thousands——of these accounts in bulk to snipe with. This is covered more in detail in `Section IV`.

### ➤ Am I able to get a 3-character name for free?

No. You will need a Minecraft: Java Edition account to claim a 3-character name. To snipe one though, you would need over 100 accounts——more about this in `Section V`. You have to be very lucky to get a 3-character name by means other than sniping. It's statistically improbable that a 3-character account gets deleted and that you happen to claim it before an auto-claim bot does.

## Conclusion
Be sure to read all the FAQs above before proceeding to later sections. In summary, you should expect to spend **hundreds of dollars for accounts and residential proxies to snipe with** and **tens, maybe hundreds of hours** on perfecting your sniping technique. If you don't have the time nor money to get a sniper up and running, **do not waste your time sniping through alternative methods**. I am saying this for your sake, not mine (I don't even snipe anymore!): You will not get a 3-character name, "semi-OG", or "OG" name by using only 1 account to snipe with. Also, it's impossible to snipe one without a bot. So, don't bother "hand-sniping". 

## TL;DR

- You will not get a 3-character name without a using bot.
- You will not get a 3-character name without spending money.
- You will not get a 3-character name without using multiple accounts to snipe.
- You will not get a 3-character name by sniping at *one* of the intervals. You must send requests **every second** between the two intervals.

-------------------------------------------

# **III. Intervals**

The idea of intervals seems to stump most sniping beginners. This feature is relatively new in the history of sniping. On September 13, 2022, Mojang [made the username history API private](https://help.minecraft.net/hc/en-us/articles/8969841895693-Username-History-API-Removal-FAQ-). This made it impossible for 3rd-party sites like NameMC, 3NAME, Laby, etc. to access your name history. Instead, these websites have resorted to using their own databases, which allow for the continuity of name history, albeit less accurate than before. One of those inaccuracies is deriving the precise time a username is changed. Since the API is private, NameMC/3NAME/Laby cannot fetch the change time from the API and must instead create two intervals when the name might drop. The username in question will always free up between these two intervals. Depending on the frequency of updates on the name's profile, the interval range can be shorter or longer. This means accounts that have less active viewers will have greater interval durations if they decide to change their name.

-------------------------------------------

# **IV. Rate-limit**

The rate-limit is the premise to all other facets of sniping. Knowing how to work around the rate-limit is key to multi-account sniping. Let's talk about the restrictions the rate-limit places on you:

- For accounts with "unset" usernames (newly redeemed gift card with no name, Game Pass acount with no name, etc.) the rate-limit is 20 requests per minute. You should space out your name change requests by 3 seconds.
- For accounts that already have a set username, the ratelimit is 6 requests per minute. You should space out your name change requests by 10 seconds.

- Recap: Use a `3 second` delay between requests on accounts without a username set and use a `10 second` delay between requests on accounts with a username already set.

As you can see, there's a visible advantage to using accounts with unset usernames. As we discussed in the FAQ section, many people utilize hundreds of Game Pass accounts to snipe with for this very reason. Game Pass accounts have unset names (until you put something on it) and they're very cheap to buy in bulk. The drawback to using Game Pass accounts is that they expire after 1 month. Sometimes the subscription is longer, depending on the supplier that you purchase Game Pass accounts from. Despite this, **whatever name is set on the Game Pass account remains on that account forever**. This means you can snipe something, have the Game Pass expire, and still have the name reserved on that account. Most people will opt for adding a gift card to the account so it's a fully premium Minecraft account. This is only one of the routes you can take, though. The second route is described in detail in `Section ?`.

Another option is using gift card accounts with unset names to snipe with. This is a very expensive method, so I would strongly advise against this. Most Minecraft gift cards can be purchased for $10.00 (I will not tell you where!), meaning gift card sniping is 100 times more expensive than Game Pass sniping. You also don't have the option to delete transfer the name on the gift card as you would with a Game Pass account (see `Section VI`).

Lastly, you have the option to snipe with accounts that already have a set username. This will substantially decrease your likelihood of a successful snipe. If you have thousands of accounts of this caliber, it's possible; otherwise, don't bother. 

-------------------------------------------

# **V. Multiple Account Sniping**

In order to be a prolific sniper, you'll need residential proxies to send requests from more than one account at once.

-------------------------------------------

# **VI. Delete Transferring**

Alternatively, you can "delete transfer" the name on a Game Pass account to another account, such as a Minecon Cape account or a main account. This makes Game Pass accounts highly sought after because OGs, semi-OGs, and 3-character names can be moved to cape accounts or to your personal account. Most people don't want to spend hundreds of dollars and hundreds of hours setting up a name sniper, so instead, they just buy a 3-character name off a sniper for $35. The price may vary depending on how desirable the name is, however, $35 is a good baseline to start from. If you choose to delete transfer the 3-character name to your main account, this doesn't actually violate the EULA or TOS because the account the name is being swapped to is your own, personal, legitimate account. The Game Pass account that the 3-character name was originally on is violating the EULA/TOS, but you won't need the account after transferring the name. 

Technically you can also delete a gift card account to have the name transferred, but this is far riskier than Game Pass delete transferring. To delete a gift card account, you would need to go to Mojang support and request for the account to be deleted. This can take upward of 30 days for the process to fully complete. For this reason, Game Pass delete transferring is preferable whenever possible. 

So, how exactly do you "delete transfer" a name from a Game Pass account? Well, despite the deceptive name, you don't actually delete the account as you would with a gift card account. Knowledge of this method usually costs you $200 because sniping/swapping monopolies do not wish for you to have this method. It only costs ~$10 to perform per transfer, but snipers/swappers will price it very high for profit. Since this method is nearing the end of its lifespan, I'll share it with you (the reader) and anyone else who uses this guide. Myself and someone else discovered the method on our own, so I was fortunate I didn't need to pay anyone to know how this method works.

To delete transfer a name using a Game Pass account, you'll first have to acquire an "unmigrated account". These are Mojang accounts that have not yet been migrated to Microsoft. If you migrate a Mojang account to a Game Pass account that has an expired subscription, the name will be freed up, allowing you to transfer the name to another account. It is highly recommended to consult a "swapper" who can safely transfer your name using this method. Beware, most swappers will charge a heavy fee for this service. They're very reliable though, so it can sometimes be worth paying.

Game Pass delete transferring will no longer be possible past September 19, 2023. That's because Mojang is [no longer offering Mojang accounts the option to migrate](https://www.minecraft.net/en-us/article/account-migration-last-call) past that date. Should you want to transfer a Game Pass name, now would be the best time to do so.

> DISCLAIMER: THIS ARTICLE DOES NOT PROMOTE ACCOUNT BUYING, SELLING, OR DISTRIBUTING. PROCEED WITH CAUTION WHEN PURCHASING MINECRAFT ACCOUNTS. IT IS AGAINST MOJANG/MICROSOFT'S EULA/TOS TO BUY, SELL, OR DISTRIBUTE ACCOUNTS.
