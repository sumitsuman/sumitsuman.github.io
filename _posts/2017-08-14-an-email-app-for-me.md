---
layout: post
date:   2017-08-14
title: An email app for me
subtitle: Designing an email app that fits my personal email use case 
bigimg: 
---


It started with the realization that I don’t receive personal emails on my personal email ID anymore. When was the last time you got one? While you are at it, do you also remember the last time you received a personal snail mail letter from a friend?

Is our personal email app up-to-date with that new reality? Or is it still stuck in the world of trying to weed personal email out of updates, promotions, forum, and social messages :D.

![personal email categorization by Gmail](/img/personal_email.png)

**I decided to do a prototype for a personal email app that I’ll use.** I ignore work-email for this exercise. I have developed a fairly good workflow for it and lots of interesting new products are addressing that space.

Designing for our own self is an interesting exercise. We define our biases. We learn to appreciate that uncovering the needs of a user is not trivial. Even when we know them quite well [;)](https://www.headspace.com/).

## I don’t receive personal emails anymore

I started with an audit of my personal email inbox. I realized that I don’t receive personal emails anymore there. That ship sailed to the messaging port long time ago. But I do get a lot of emails:

* Emails from my bank.
* Email confirmation for the tickets I booked
* Consulting offers
* Messages from recruiters
* Customer service communication with a wide range of companies
* Password resets
* 2FA Pins
* Personal networking messages
* Newsletters
* Updates & notifications from a from a variety of services / products I use
* Engagement emails from the same services / products I use
* Bills
* Marketing emails from services / products I don’t use
* Spam
* Forwards from my dad

I often reply to networking messages, interesting consulting offers, recruitment emails when I’m looking for jobs, customer service communication, direct communication with my bank, etc.

I open the ticket confirmation to ensure I got the right thing, and hope to find them again when I’m traveling. I also look at bills.

I pay attention to notifications from the bank. I open them, read them, take action if needed. I scan the notifications & updates from the products/services I use for something useful/actionable.

I obviously engage with password resets and 2FA codes. I read about 20% of newsletters I get. I ignore all engagement & marketing emails. I mark and delete spam.

I do, sometimes, read the forwards from my dad :).

### To summarize my use case:

* Personal email is the trusted place to receive sensitive information. Things I asked for — tickets, bills, invoices, 2FA codes or non-work professional contact.
* Personal email is a file store for important documents that I may need to reference later.
* Personal email is my sane replacement for push notifications.
* Personal email is low fidelity RSS reader for content that I opted into.
* Everything else is probably unwelcome crap.

## The app for me

The prototype I came up with for me is an app with a tabbed interface. It gets four primary tabs — conversations, documents, newsletters, and notifications. Conversations tab has a sub-tab for conversation requests. Email that is not categorized under any of these categories, is not of interest and gets thrown under “All Emails”.

### Conversations

This tab contains the emails I replied to or received a reply for. I want to engage most actively in this tab, hence the app opens on it.

![Active conversations](/img/1.png)

### Conversation Requests

I have separately categorized emails that would become new conversations only after I reply to them. I often receive emails that meet the criteria for having a conversation but I never get around to replying to them. They are as good as dead until the sender follows up or I’m cleaning my inbox. I don’t want them to crowd my active conversations window, hence I have put them in a separate sub-tab. The unread count, however, does include requests. The neurotic email user in me can’t ignore that for too long.


![Conversation requests](/img/2.png)

### Documents

The tab is self-explanatory. I receive documents that I want to reference later. The attached PDFs are the most important part of the email, hence they get a prominent view. I can click and expand them for a quick view. I can pin them for easy access. Of course, I can access the full email by going inside it.

![Documents](/img/3.png)

### Newsletters

This tab satisfies my newsletter use case. I subscribe to a bunch of them and read a few of them religiously. Easy and dedicated access to them would be nice. I should be able to bookmark or unsubscribe as needed as well.

![Newsletters](/img/5.png)

### Notifications

It would be a bliss to have all email notifications in one place. I should be able to clear them all in one go. Just like we do for push notifications.

![Notifications](/img/6.png)

## Real world feedback

If you made it so far, I invite you to check out the clickable prototype on [Invision](https://projects.invisionapp.com/share/WAD0LX6ZQ#/screens/248427102) and leave your feedback in comments (or message me). 

I’d love to see where other users diverge from my personal view.

I will document the feedback diligently and then pack this up.

While time consuming, this exercise will provide a ready documentation for my biases if I had to develop a real email app for real. In the worst case, I have a good set of ideas to begin with (see what I did there).

*A disclaimer — the prototype is a wireframe that just focuses on primary use cases. It is obviously not a complete interface. I used Adobe Comp so it looks better than hand drawn.*











