### On understanding

I am sure some people would classify me as anti-AI and perhaps I am, I use LLM's at work, I've shipped production features without writing a line of code by hand, I've vibe coded hobby projects that I intend to throw away and I don't think any of that is inherently bad.

What I do think is problematic is the foggy haze between me and the systems I am working on, now sure you can call this _high level understanding_ or _focus on the system as a whole_ or whatever other term you want that obfuscates from the fact that you don't know what is going on under the hood.

I'm sure we've all seen the image comparing vibe coding to traditional software engineering with the two rockets side-by-side if not I've included it below.

![./assets/images/vibe-foundations.png](vibe foundations)

I've thought about this image a lot, probably more than I should have and I think both sides are fundamentally wrong.

I think a much better version would be the vide coded side being slightly blurred so we don't really know what's there, is it good? Is it bad? Is it something in between? We're not sure because no one has spent the time building up the mental model that comes with having to solve the problem by hand. 

But I'd also update the software engineered side to include duplicate cables, a sticky note that says `TODO...`, perhaps the the odd crack or exposed wire here or there because let's be honest no production grade system is flawless but as a general rule we know where those flaws are and though we may never get time we'd like to fix them. But most importantly we have visibility and understading of the underlying system and when it breaks or needs extending we know why.

### On progress

But if the LLM's can work on complex systems why should we bother to understand them? That's a totally fair point but understanding isn't just about being able to work on a system it's about being able to make informed decisions pertaining to that system. How can we know a good abstraction from an over-engineered one when we don't understand the underlying trade-offs?
If we don't understand our systems we don't know where the friction is, we don't know what parts of the system might be heading towards collapse until they collapse at 4a.m. in production. And when this inevitably does happen we (or an agent) have to produce the fastest solution to get the system back online as opposed to the best solution which we could have been thinking about had we known in advance.

Now that might not seem important but I think it is in the scenario where we understand the system the users experience no downtime, no one is woken up at 4a.m. and the system is in a better place long term.

In a time when software has never felt more unstable and the [five nines]() feel like a pipedream I think we should think of outages as a direct failure on our part, and I feel confident saying this because we weren't failing this fast or this frequently before the advent of LLM's meaning that better is not only possible but achievable.

### On complexity

Complexity compounds.

Machines can only add to or maintain system entropy but never decrease it. - Find quote.

### On friction

Friction equals focus, and focus equals product. - Find quote.


### On ego

There is a lot of [weird takes](https://x.com/ryanflorence/status/2102849480760721664) out there at the moment that seem to imply that engineers are upset because the barrier to software engineering is now less. This fundamentally flies in the face of the industry as a whole, name an industry more welcoming or more generous with their time. I can't think of any other industry on earth that has an opensource community in the way software engineering does. Software engineering was never _difficult_ to get into but it was _challenging_ and took a certain personality type to keep going when things became difficult.

Maybe there are engineers out there who genuinely do feel upset that there is no longer a moat but every conversation I've had has always boiled down to [craft lovers losing their craft](https://writings.hongminhee.org/2026/03/craft-alienation-llm/) and has nothing to do with software creation becoming more accessible. In fact most people I've talked to are excited about software being more accessible and are hopefull that it will get more people excited about the industry as a whole.

So no I don't buy this narrative for a second it demonstrates a severe lack of empathy or understanding of what some people are going through and doesn't add any real value to the discourse surround the monumental changes our industry is experiencing.

### Conclusion

In short I think we are focusing on the wrong things when we talk about what agents and LLM's are doing to software engineering, the discourse is almost entirely centered around effeciency - and why shouldn't it be most of us write software for money so the more effecient we can be the more money we can make, or at least that's the theory.

I think a more useful thing to focus on is understanding or to use a trendy term [comprehension debt](https://madecurious.com/articles/what-is-comprehension-debt/) and what the long term implications of LLM usage in systems really are.

TODO - talk about the trade offs even if an LLM writes software better than a human in 100% of cases the human now doesn't understand the underlying system and as a result can't meaningfully improve it. If the value in LLM's is their encyclopedic knowledge as well as never resting then use them to review / break / critique the code the human as written. Worst case scenario the LLM is right which the human will be able to accurately guage because they have built up an understanding during the implementation and they make the improvements now the software is in the best state it could have been AND the human understands it fully - the only loss here is time in the sense that the LLM could have done it faster than the human and that you'd get the same result (which is iffy at best).

Invalidate, challenge, review.

Has your agent ever asked you to make archietectural call that you don't really understand? You ask for further clarification but there is still this foggy haze between you and the problem, your finding it difficult to really latch on to the problem so you can make an informed decision. Your tired and digging any deeper would most likely require booting up your editor and getting into the code but you don't feel like that so you decide to go with the `(Recommended)` option.

If your anything like me the above experience probably sits poorly with you and might even make you feel ashamed of yourself, but hey it's what everyone else is doing right? You might even consul yourself and say your [not holding back the ocean](https://ethanniser.substack.com/p/not-holding-back-the-ocean) and if that is enough to sate your worries that's great, but for me at least this industry never used to make me feel this way, frustrated, confused, angry even but never ever ashamed.
