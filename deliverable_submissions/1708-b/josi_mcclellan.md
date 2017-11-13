# Josi McClellan 1708-BE



## Mod 2 Deliverables:
* [Written reflection](https://gist.github.com/JosiMcClellan/ef337f2669d2797f851031fa4cb2063e)
* [Feedback II reflection](https://gist.github.com/JosiMcClellan/a342bfcc192d0bed52478700c97bbe01)
Lauren, I wanted to finally talk about our project.

First, I want to apologize directly for the things you said in your feedback.  I was already outlining an in-person apology for some of them when I got your message and saw there were others I hadn't realized I'd done.  You already described them better than I could, so I'll just say I'm sorry.

When I read your feedback, I felt hurt and (very wrongly) angry.  I'm sorry I let my emotions get the better of me for a while.  In retrospect, your words only hurt that much because people are rarely that honest, so to be that honest with me shows that you trusted me with your feelings.  I'm very thankful for that, and I promise not to waste your feedback.

I want to address your use of the word "dominated".  You used the word as a feeling, not as an action, and I can't rightly argue with how you felt.  But I think there must be some difference in how we use that word.  Because if I said that, it would always be about someone I didn't want anywhere near me.  Assuming you meant it how I would, I tried to have as little to do with you as possible because I thought that's , but now I wonder if that didn't make you feel worse.  If it did, I apologize.  Over time, as you continued to be nice to me, I realized that you don't hate me.


Amongst the others, there is



I am curious about your bringing up the fact that "we’re part of a marginalized community at Turing".  This isn't criticism, just a request for clarification.  Even though the statement itself wasn't negative, and even though it came from another member of that community, it still made me feel a little uncomfortable to have my queerness mentioned .  I'm only very recently out, so there's a very high chance that I'm just misunderstanding and taking everything the wrong way, so I figured I'd ask.  One explanation I can conjure is that you were basically asking me to not be weird because we were in the planning group together.

* [Working draft of professional story](https://gist.github.com/JosiMcClellan/b4ed57737849241621ad373683f60be8)
* [Plan for outreach & networking](https://gist.github.com/JosiMcClellan/279b54b20640ab8a4d30c061be055d49)

## Mod 1 Deliverables
[DTR with Emily Wise](https://gist.github.com/wiseemily88/e901d737814ef28375263288ba31282b)
[Strengths and Storytelling Reflection](https://gist.github.com/JosiMcClellan/dabaf11aaad032a239777251bdf61411)


#Meteor
Meteor is a full-stack Javascript framework built on Node known for being quick to develop in.  If you're thinking of
- intro

- pros/cons

| trait |:  pros  :| cons |
|-------|------|------|
| big   | fast to develop| |

- is it right for you?


# Meteor is...
## _...a cool framework_
Specifically, a full-stack Javascript framework known for being quick to develop in.  I recently built an (as yet unfinished) app in Meteor, having chosen it Was it the right choice?  And more importantly, is the right choice for you?  I'll walk through some basic pros and cons of Meteor, and talk about what that might mean for you.

## _...big_
I've described a lot of framework magic.  Like Rails or Django, Meteor is a massive framework that does a ton of work for you.  This makes it very quick to get applications up and running quickly with less boilerplate, configuration, research, etc.  But all that magic comes at the cost of flexibility, ease of debugging, etc.  So there's some big, overarching etc's to consider.

## _...new_
Learning an up-and-coming technology is fun, and if it takes off, you've got a head-start in the new market.  There's also ample opportunity to create or contribute to key open-source libraries.  But support is limited.  The framework and it's libraries are very immature, and while progress has been rapid even this mitigating factor means you have to spend more time keeping up with major version changes.  Tutorials are sparse.  StackOverflow answers are sparse.  Meetups, partners, blogs, they're all sparse.  That said, facing these challenges is a good experience in and of itself.  Also, even if Metoer never becomes hugely marketable, some full-stack Javascript framework almost certainly will, and learning Meteor will teach you the .  And even if you never use Meteor itself in a job or for your own application, it will teach you ideals that you can take with you to another framework.  E.g, if you learn Ruby, you'll write more expressive Java, and if you learn Java, you'll write more efficient Ruby.  People *recently* created Meteor to solve a set of problems, and after learning it, you'll know better how to confront those problems.

## _...fullstack Javascript_
Even the DBMS, Mongo, uses employs a JSON-based query-language and data-format.  This allows the powerful ability to have some code shared between the server and client.  To support this, some code runs differently on between the two environments.  E.g, new Mongo.Collection('name') creates an actual connection to the DB on the server, but on the client creates a empty collection with the same interface that waits to populated by the pub/sub system.

Keeping up with one language is easier than keeping up with two, that simple.

And since the browser understands Javascript, it's really the only option for full-stack.  The only problem is that Javascript kinda stinks.  We all know it.  Node is fast though, and with ES6 and transpile, Javascript isn't all *that* bad anymore.

## _...based on DDP_
...not HTTP.  DDS is a WebSocket-based protocol, so Meteor has live-data built in.  Basically, publications/subscriptions correspond to GET requests, and remote procedure calls to POST et al.  Instead of HTML, JSON is sent back and forth to update just the data needed, and changes can be initiated on the client or the server (in different ways).  And with React or Angular up front, the page can re-render only what's necessary.  Optimistic RPCs, easier with shared code, usually let those updates happen before the server responds.  User-management is a little extra perk; since Meteor keeps an active connection, you can reactively access the current user anytime, anywhere, and incorporating OAuth is painless.  But, it's inherently stateful.

Meteor is inherently stateful.  And care has to be taken to not break your application if the client loses their connection.
 Way easier than using AJAX and all sorts of surrounding support.

Also, the capitalization distinction between Ruby methods and Meteor Methods is so unnecessarily confusing.  Seriously, folks?


**** meteor is *not* *the most scalable framework ever conceived.*

## _...for you?_


## ETC.
I'm a student trying my hand at a blog post, so I apologize for inaccuracies and omissions.  Did I miss some major security flaws? Some minor conveniences?  Let me know below.  Thanks for reading!
