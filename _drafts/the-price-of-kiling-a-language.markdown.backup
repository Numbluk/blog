- Topic: Killing Ruby was a mistake. 
	+ The first sentence should spell the doom.
	+ I feel sad whenever I browse new versions of Rails and don't see my company
	+ Billions built off the back that something works and still works
	+ Rails' influence is unmatched to this day
- How it started
	+ Deliveroo started with Rails
	+ It's still the most important service
- How do I know?: I created the most recently and actively developed Ruby service
- Doesn't Deliveroo have standards? Who is steering this ship?
- It starts as an opinion, not an idea. Usually from fresh blood injected into the veins. Like an antibiotic it cares not what it kills, as everything in a category (dynamic, etc) is the enemy.
- Can the ball be stopped once it stops rolling?
- What's the price? The irony is that we have relied on Ruby and Rails for 10 years now and will continue to do so for many more. 
- Lessons learned: 
	+ A widespread dedication through a constitution is necessary. Otherwise the next king will take away your preferences and disputed laws.
	+ Management should be involved.
	+ Edicts don't work, especially when culture is established. 
	+ Multiple languages across the board do not work.
	+ Make hiring advocates a priority
	
The Sad Price Of Killing A Language

Whenever I see the landing page of Ruby on Rails and scroll past the banner listing the logos of companies who use Rails as a badge of honour, I am sadly reminded that a certain teal kangaroo does not feel the same way. Of all the companies, shouldn't Deliveroo be there? After all, Deliveroo is a billion dollar company and its laurels for at one point being the fastest growing startup in Europe's history can be attributed to the fact that it was built on Rails. Although similar technologies have grown to compete, such as Django and Phoenix, Ruby on Rails is still the 800-lb gorilla in the room and largely thanks to its prolific founder, David Henemeier-Hansson. In fact, the missing Kangaroo reminds me of a speech by David Henemeier-Hansson where he spells out this doom:  

> Twitter etc....

Over time, Deliveroo has made moving away from Ruby and Rails a priority. Tech moves fast enough and I've been at Deliveroo long enough that it's like watching history unravel in action: language popularity rising and waning, how a company adjusts, and what players are involved. 

Deliveroo was started in 2013 by the company's current CEO Will Shu and its former CTO Greg Orlowski. Will quit his daytime job at an investment bank to focus on growing the business which included delivering pizzas to many of his former colleagues. Little did he know, but Greg's first lines created the foundation for Deliveroo's technical architecture and Greg's decision to stick with a monolithic application was a surprisingly important one. To this day, not only is the Rails monolith Deliveroo's most important service, but it is the most actively developed and largest service. Here's a rundown of the sheer size: x commits, y contributors, z PRs. 

I am proud of the fact that I created the last high tier service, in terms of impact on customers, in Ruby. It was the perfect combination of business logic and the beauty of Ruby come together to solve a complicated problem; it also happened to be the largest scale explicit use of a graph I have ever used and without this at its heart, would have sadly failed.  Did it use ...? What is the quality of this service now? Sadly, a child has to grow up and I can no longer continue to receive impact for the foundational accelerating of a group or team from something built in days past. I can only look on and clap and remember about the defining moment of clarity sitting in my London flat where I sketched what would become its core architecture. If you noticed, I didn't mention anything about the service being too slow. I want to avoid getting too technical, but it's worth highlighting here that the cost to keep the service alive didn't matter. One of our other blessed languages, Go, was too rigid and would have required a monumental feat to complete the service in a similar amount of time. It also would have been ugly beyond my wildest dreams and defeated the project's primary goals of clarity and development speed. **Scala** on the other hand would have led to functional complexity which I still don't think is worth it. ??? Mention the perfect marriage of metaprogramming and ruby.

Doesn't Deliveroo have standards? "Who is steering this ship?", you might ask. We do. We have a blessed set of languages, but beyond those languages it is largely up to individual teams to decide. A core feature of the company is that it leaves teams unto themselves to execute as they please. 

So how does this start? Ruby's death started as an opinion, *not* an idea. New engineers join the company with a set of takes(?) that certain aspects of the language are bad: it's a dynamic language and therefore understanding the code base will take forever, it supports metaprogramming so new changes will be buggy, it has global interpreter lock so scaling will be inefficient, it is slow so I'll have to create CPU-bound tasks in a different language. What's interesting about each of these points is that they are opinions spun as facts. With all of these opinions in their arsenal at the ready, they are put through the worldwide software engineering hazing ritual of making changes in legacy services which at Deliveroo inevitably involved Ruby. 

Let's make one point clear: making changes in any legacy service can be difficult, not just one written in Ruby; entire books are written on it. Business logic is hard enough to understand in a domain you are unfamiliar with, but it can be even harder when that logic is both temporal and influenced by many people. So the engineer attempts a change, doesn't understand everything completely, the legacy service is slower to build, it can be harder to test end-to-end, but none of this matters to the man ready to take fire at the slightest shortcoming. To him, this is all little too late, it should have never been written in Ruby and he wants everyone to know. The irony is that the engineer's pain may be caused by changes made by someone like himself: new to the business and inexperienced with Ruby. When you spread this across many teams, the scratches and scrapes over time start to tarnish the language on a grand scale. The influence of these engineers is bottoms-up and as old engineers leave, the knowledge of what once was is lost. 
Before you know it, most new services are written in a trendier language with no discernible proof that the language actually mattered in the first place, only opinions and preferences.

So what's the price? 

Deliveroo's most important service has been a Ruby service for the past 10 years, and it will continue to be for many more. You don't have to be a seer to understand that a dedication to purging Ruby leads to only a handful of engineers looking after your most important service. 

END

Speed of development and quality of output decline. The curve is an interesting one, but my experience has led me to see it as a steady curve as old engineers leave and move teams and inexperienced engineers make changes. There is a tipping point once a critical mass of changes by inexperienced engineers far outweighs the old guard and it's from this point on that the curve exponentially swerves. 

The most expensive cost is that we lose all culture and experience around the language we once had. From a hiring perspective, this is beyond costly. For many years we employed excellent Ruby engineers, but as we didn't care to take hold of their expertise and formally disseminate it then it's all for naught. Instead, the culture of the new language takes hold and the cycle repeats until a few leaders steps in to stop the mistake from repeating.

You will probably alienate some of your best engineers once the new ecosystem takes root. I will die on the hill that many engineers choose where they work based on *what* they work with. If an engineer loves Italian food, why would they want to cook French food everyday? "The right tool for the right job" only goes so far when you can solve the problem in ten different ways with five different languages. Preferences matter and attracting passionate engineers improves retention. Edicts don't work, especially when culture is established ???

Is what happened good or bad? It depends on who you ask. ???

Before we get started on preventing this issue, I want to discuss a topic that is almost always neglected: developer cost. As expensive as AWS and 3rd party bills are, it is nothing compare to the cost of a consortium of engineers deciding between the merits of programming languages. When it comes to time, it's not just the cost of the debate, of which there will be many in a transition from one language to another, but the cost of training, the cost of bugs, the cost obfuscated code, the cost of no experts, the cost of avoiding ownership, the cost of migrations, the cost of new tooling; while all of these can be solved independently of a language change, many of them are almost entirely avoidable or greatly reduced should a language change be avoided.

I've been at Deliveroo for almost six years now, and I truly believe this was avoidable and so I'd like to address how this could be avoided and hopefully save at least one startup or company from paying the same price.

First and foremost, make hiring engineers who are language experts a priority. These are the people who will shout the loudest about new language features, ecosystem improvements, and tooling changes which generate excitement. If no one is talking about the benefits of the language, then it becomes an easy target for new engineers to criticize without advocates there to defend it. Hiring language advocates flies in the face of many tech interviews which aim to be language-agnostic, however, language advocates tend to improve the developer experience of many engineers across the company so the effort to create specific interviewing pipelines for this will easily pay for itself.

Secondly, do not allow for any ambiguity of choice when two languages could solve the same problem. Ambiguity will only result in flame wars and a long, long evaluation of the pros and cons of each language for a specific situation across every team. I guarantee this will save you many, many costly meetings in the long run. In practice, this involves making a statement and declaring a default language. It also means not allowing multiple approved languages where there is no **actual proof** that one language will be "better" than the other. 

Thirdly, involve management. Like it or not managers are highly embedded and drive areas of culture where some engineers don't want to: it's their job. Having the power of management behind you makes it easier to not get sucked into flame wars or new engineers constantly questioning the choice of language. A widespread dedication through a constitution between engineers and management is necessary. Otherwise the next king will take away your preferences and disputed laws.

Lastly, be bold about your decisions. "We love Ruby" is a statement people can rally behind. "We support multiple languages" is uninspiring and loaded with baggage. Put the language at the forefront of your engineering culture.

The fact of the matter is that this is a messy problem. You can't point to a single moment in history or blame a single person because there are many moments in history and many people who think diversion away from Ruby was a good one. What about the engineers who left and didn't care to leave their Ruby experience behind? Are they equally responsible? If I'm being honest, then I'm a hypocrite: I was a primary driver for introducing Java into the company and I'm sure many engineers would love to put me to the stake for that. After working somewhere for so long, you can't help but have an affinity for your co-workers: you want the best for them which often means agreeing or disagreeing with things you have a ton of historical knowledge on; the way things were, the way things could have been, the avoiding of one of the most costliest decisions. They say that technical debt can kill a company, then again they also say that's it's really bad business decisions that kill a company. The eternal back-and-forth is always there and always costly.

Maybe none of this mattered in the end. Maybe I just need to grow up and realize that teams move on, the industry changes, and trying to stick with a language for any longer than five years is career suicide. Maybe I'm a little sad for how things could have been: the tooling, the unified culture, the band of engineers! When I boil it down scroll back over the Rails landing page, I truly believe it's simply a lack of the engineering leaders not realizing the cost of decision. An immeasurable one than any infrastructure bill the company ever paid. 

This is a memoriam:

dhh if you're reading this, someone is out there who wishes things could have turned out differently.

`__END__`
END

