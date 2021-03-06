---
layout: layouts/post.njk
title: >
  270 RR #talkpay with Lauren Voswinkel
date: 2016-07-27 07:00:24
episode_number: 270
duration: 50:43
audio_url: https://media.devchat.tv/ruby-rogues/RR270TalkPay.mp3
podcast: ruby-rogues
tags:
  - ruby_rogues
  - podcast
---

## [All Remote Conferences](https://allremoteconfs.com/)

&nbsp;02:01 - Lauren Voswinkel Introduction

- [Twitter](https://twitter.com/laurenvoswinkel)
- [GitHub](https://github.com/Valarissa)
- [New Relic](https://newrelic.com/)
  02:39 - May 1st: [International Workers’ Day](https://en.wikipedia.org/wiki/International_Workers%27_Day)
- [Lauren Voswinkel: #talkpay and the Importance of Collective Action](https://recompilermag.com/talkpay-and-the-importance-of-collective-action/)
- [Taft–Hartley Act](https://en.wikipedia.org/wiki/Labor_Management_Relations_Act_of_1947) (The Labor Management Relations Act of 1947)
  06:11 - [#talkpay](https://twitter.com/hashtag/talkpay?lang=en)
- [Information Asymmetry](https://en.wikipedia.org/wiki/Information_asymmetry)
  10:22 - Fair Trade of Value; Companies and Salaries
- [Kelley Blue Book](https://www.kbb.com/)
  19:37 - Salary Maximization and Negotiations22:40 - Executive Salaries
- [Planet Money: Episode 682: When CEO Pay Exploded](https://www.npr.org/sections/money/2016/02/05/465747726/-682-when-ceo-pay-exploded)
  25:58 - Hashtag Effectiveness
- [Glassdoor](https://www.glassdoor.com/index.htm)
  29:05 - Implications of Salary Reveals32:08 - The Labor Management Relations Act of 1947 (Cont’d)Salary Sharing Between Employees35:41 - Sharing Salary Information Publicly and [Impostor Syndrome](https://en.wikipedia.org/wiki/Impostor_syndrome)
- [Crab Mentality](https://en.wikipedia.org/wiki/Crab_mentality)
  37:38 - Job Elimination42:40 - Is/has #talkpay been successful?&nbsp;More Information
- [Ex-Apple, Google, Intel geeks in line for \$415m over wage-fix pacts](https://www.theregister.co.uk/2015/01/16/silicon_valley_415m_wage_fix_pacts_settlement/)
- [Wage Stagnation in Nine Charts](https://www.epi.org/publication/charting-wage-stagnation/)
- [Highlights of women’s earnings in 2014](https://www.bls.gov/opub/reports/womens-earnings/archive/highlights-of-womens-earnings-in-2014.pdf)
  &nbsp;Picks
- [The Name of the Wind by Patrick Rothfuss](https://www.amazon.com/Name-Wind-Kingkiller-Chronicles-Day/dp/075640407X/ref=pd_bxgy_14_3?ie=UTF8&psc=1&refRID=5D4HAGF13KDVVE2W7EDW) (Sam)
- [The Lies of Locke Lamora](https://en.wikipedia.org/wiki/The_Lies_of_Locke_Lamora) (Coraline)
- [Brandon Sanderson's Alcatraz Versus the Evil Librarians Series](https://brandonsanderson.com/books/alcatraz/alcatraz-versus-the-evil-librarians/) (Chuck)
- [Bose QuietComfort 3 Acoustic Noise Cancelling Headphones](https://www.amazon.com/Bose-QuietComfort-Acoustic-Cancelling-Headphones/dp/B0081XAXXM/ref=sr_1_9?ie=UTF8&qid=1468872096&sr=8-9&keywords=bose+noise+cancelling+headphones) (Chuck)
- [Brené Brown: The power of vulnerability](https://www.ted.com/talks/brene_brown_on_vulnerability?language=en) (Lauren)
- [Brené Brown: Listening to shame](https://www.ted.com/talks/brene_brown_listening_to_shame?language=en) (Lauren)

### Transcript

**CORALINE:&nbsp;** Board games on Thursday.

**SAM:&nbsp;** On Wednesdays, we wear pink.

**_[This episode is sponsored by Hired.com. Every week on Hired they run an auction where over a thousand tech companies in San Francisco, New York, and L.A. bid on Ruby developers providing them with salary and equity upfront. The average Ruby developer gets an average of 5 to 15 introductory offers and an average salary offer of $130,000 a year. Users can either accept an offer and go right into interviewing with a company or deny them without any continuing obligations. It’s totally free for users. And when you’re hired, they give you a $1,000 signing bonus as a thank you for using them. But if you use the Ruby Rogues link, you’ll get a $2,000 instead. Finally, if you’re not looking for a job but know someone who is, you can refer them to Hired and get a $1,337 bonus if they accept the job. Go sign up at Hired.com/RubyRogues.]_**

**_[I’m excited to tell you about a new sponsor to the show, Rollbar. One of the frustrating things about being a developer is dealing with errors. Ugh. Relying on users to report errors, digging through log files to debug issues, or a million alerts flooding your inbox ruining your day. With Rollbar’s full-stack error monitoring, you get the context and insights and control you need to find and fix bugs faster. It’s easy to install. You could start tracking production errors and deployments in eight minutes or less, or automatically create new issues in GitHub, JIRA, Pivotal Tracker, etcetera. They have a special offer for Ruby Rogues listeners. Go to Rollbar.com/RubyRogues to sign up and get the bootstrap plan free for 90 days. That’s 300,000 errors tracked free. Give Rollbar a try today. Go to Rollbar.com/RubyRogues.]_**

**CHUCK:&nbsp;** Hey, everybody and welcome to Episode 270 of the Ruby Rogues Podcast. This week on our panel, we have Sam Livingston-Gray.

**SAM:&nbsp;** Shai Hulud.

**CHUCK:&nbsp;** Coraline Ada Ehmke.

**CORALINE:&nbsp;** So happy to be here today.

**CHUCK:&nbsp;** I'm Charles Max Wood from DevChat.tv. I welcome you to go check out any of the remote conferences that I'm putting on. I'll put the links on that in the show notes. We also have a special guest this week, and that's Lauren Voswinkel.

**LAUREN:&nbsp;** Hi!

**CHUCK:&nbsp;** Do you want to introduce yourself real quick?

**LAUREN:&nbsp;** Sure. My name is Lauren Voswinkel. I am a Senior Web Developer with New Relic. I previously worked with Sam, actually at LivingSocial. I primarily do Ruby developments and I'm kind of on the show because of a thing that I did both last year and this year on May 1st which is the #talkpay. Now, the things that I enjoy doing include fire breathing and fire spinning and whatnot. I play with fire both in literal and figurative sense.

**CHUCK:&nbsp;** Very nice.

**CORALINE:&nbsp;** So, Lauren, I have to ask you this significance of doing this on May 1st, and I suspect, I know the reason.

**LAUREN:&nbsp;** The significance of doing this on May 1st is that it is International Workers' Rights Day and the reason why I specifically chose to do it on that day is because Labor Day in the US is actually a holiday that was created in order to remove American workers from those more left-leaning, progressive, collective action type movements. Yes, it is basically trying to bring American workers back into an international discussion.

**CORALINE:&nbsp;** I was pretty fascinated by a lot of the political and labor history, especially in the 20's and 30's and really amazed by how much of a melting pot of ideas were coming out of that time period. People were experimenting with different philosophies of government, different philosophies of the relationship between labor and capital. It seemed like all that got put on hold during the World Wars. Do you have a feeling about like what we lost in that process?

**LAUREN:&nbsp;** Well, funny fact about that. The article that I wrote for The Recompiler talks in quite a bit of detail about exactly that. The main focus of that particular article was a discussion about how really the breaking down of collective action was a concerted effort, actually, on the part of governments and businesses. Basically, I had a hypothesis before I actually went into doing Talkpay in general, that one of the major pushbacks for collective action in this union rights and workers' rights natural was that the anti-communist movements during the McCarthy Era. That was really borne out in a very clear kind of way, when I looked into what's known as the Taft–Hartley Act, I believe, in 1947.

In the Taft–Hartley Act, there was a restriction of union rights particularly with regard to policies about strikes. Employees were no longer able to do it like on the spot strike. That was considered to be illegal. They need to start giving a 90-day notice in order to go into negotiations before there was any type of business impact.

But the thing that really like solidified the whole understanding that it was a backlash from fear of communism was that in the Taft–Hartley Act, there was a provision that required all labor union organizers to write a signed and notarized affidavit that was then sent into the National Labor Relations Board saying, that they were not affiliated with the communist party, and were not actually going to work to overthrow the US Government.

**CHUCK:&nbsp;** Oh, that's funny.

**LAUREN:&nbsp;** So, right in that wall was basically, "Nope, we think you're all a bunch of dirty commies and we're going to require you to have this on file so that we can use it against you, if there's any type of case." I hope that answer your question, Coraline.

**CORALINE:&nbsp;** I think, you've provide some really valuable context so thank you.

**SAM:&nbsp;** We brought up a couple of interesting things here so far. One is the National Labor Relations Board, which I think, we'll probably come back around to later. But before we do that, you mentioned Talkpay without really talking about what it is. What is Talkpay, Lauren?

**LAUREN:&nbsp;** Talkpay was a hashtag and is a hashtag that I had the idea to bring forward, and bring into the world to get people to disclose salary and information with names attached in order to help balance out the information imbalance. But basically, to work to remove the barriers that people have about this taboo surrounding discussion of pay. The reason why I wanted to help breakdown those taboos about discussions of pay is because in our current labor environments, there's a really lopsided exchange of information between employers and employees.

Employers have access to numerous sources of information, talking about what the “market rate” is. Whereas, employees really don't have much of anything except for just talking about it with friends, family and their peers in the same work environment --

**SAM:&nbsp;** Except there is social taboos. I'm sorry to cut you off, but like there are a few social taboos around like not talking money with your friends and family, right?

**LAUREN:&nbsp;** Exactly. That is exactly the point because no one feels comfortable talking about it, it basically means that people have no idea what their skills are actually worth a lot of the time.

**SAM:&nbsp;** I believe the economic term for this is information asymmetry, right?

**LAUREN:&nbsp;** That would be correct. That information asymmetry is something that is really kept wages suppressed across the board in our country - our country being the United States. That asymmetry is what is kind of the heart of what I was trying to poke at, basically. We just make general assumptions about how employers are going to regard us, and a lot of times, we kind of lose sight of the fact that salary negotiation is an inherently antagonistic relationship. It’s not necessarily hostile, and there's no like ill will there. But at its core, a salary negotiation is a company looking to hire you, and looking to pay you the least amount of money that they think they can get away with where you won't immediately start looking for another job. Because of that, they use all of this information that they have, services that provide market rates. They freely share information with other people during meetings with other CEO's talking about like the latest startup in there saying how much do you pay for your senior developers and whatnot?

They have access to a lot of information that they then use in order to say, "Okay, we're going to try to pay less than that," or get away with paying as little as possible because they're trying to make as much money as possible. It's an understandable thing to do. But fundamentally is basically trying to screw over the worker as much as possible and --

**SAM:&nbsp;** No, it's about extracting as much profit as possible. Shareholder value and all that, right?

**LAUREN:&nbsp;** Yes, well, shareholder value and all that is exactly screwing over every individual employer.

**[Laughter]**

**SAM:&nbsp;** Oh, yes, but --

**CHUCK:&nbsp;** See, I have a different point of view on this and that it's also a market transaction. So, if I'm negotiating a salary with my employer, effectively we're trying to fit. Yes, there is some antagonism there. I'll grant you that. But we're trying to work out what I think is a fair rate for my time versus what they're willing to pay. If I'm content with my salary, and they're content with the work I'm giving them, isn't that a fair trade of value?

**LAUREN:&nbsp;** Normally, it would be a fair trade of value. Except when previous salary are often used in order to dictate the new salaries. So, when someone has not negotiated right off the bat, and they are making, say, \$50,000 like when they're straight out of school, and they voluntarily yield that information every time that they switch jobs, that information is then used against them and keeps their salary at a repressed rate. While, yes, it is a "fair transaction", if that worker knew what their skills were worth, they would probably look at it and go, "What the hell? Why am I being paid like 20, 30, 40 thousand dollars less than my peer who is doing the same work that I am.

**CORALINE:&nbsp;** I should point out too that in a market economy the value of goods is pretty much established and well-known. The value of a given commodity is based on, "Oh, this is slightly higher quality than the run of the mill widget," Or, "This is a widget that was manufactured to lower quality standards so it can be offered at a discount." The price of the widget, the market value of the widget is more broadly known than I think, the market value of a developer.

**SAM:&nbsp;** Oh, yeah, and there's two things in there that I'd like to unpack. One is this idea that- you know, we brought up the information asymmetry before. There is no Kelley Blue Book for developer salaries. I mean, to some extent salaries overall, right? The employers have access to much more information than we do because I might you know, in a given year, I might interview at one or two places. Unless, I find myself out of work, and then I might interview at three or four, right?

But the other part of that is that even if there were a Kelley Blue Book for developer salaries, how do you evaluate an individual developer?

**CHUCK:&nbsp;** Before we go there, I want to just go back to this conversation that we were having because I still have a little bit of an issue saying, if this developer could have negotiated a salary of $70,000, even though, the company hadn't known that they were making $40,000 before and they negotiate 50 or 60, is the company really doing them a disservice? It feels like, because the employee does not have the information to ask for 70, and doesn't know that they shouldn't give their past salary information to the employer, it seems like some of that responsibility does fall back on the employee. That is not just the employer trying to screw them over.

**LAUREN:&nbsp;** I would then, counter with the statement that there are so many social factors that restrict people's abilities to freely talk about information like women and people of color are often chided for being too aggressive, or being too, basically, standing up for themselves. So those factors, those like social punishments, play out in negotiations so that they often feel a need to pull back and to accept what's originally given. That then leads into saying this like income inequality.

While, yes, there is some personal involvement that needs to be looked at. The deck is stacked against people. So, you can't say, "Oh, it's that person's fault," when society's been telling them that they shouldn't do that their entire lives.

**CORALINE:&nbsp;** There's another aspect to what you're saying, Chuck, and I think that's a critical point, Lauren, and I want to come back to that definitely. But if an employer gets away with paying a substandard salary, we all know, all of our experiences say, you're not going to get a raise that has commensurate with the rate of inflation, let alone, the rate of the value that you are adding to an organization. The way a developer gets a raise is by moving jobs. What does the employer really gaining except accumulate in the cost of training and retraining and retraining new workers for that substandard salary? Is that tradeoff really worth it?

**CHUCK:&nbsp;** Well, I would agree with you there. I think, turnover probably cost companies more than anything else in their business as far as loss in productivity or profit or whatever you want to call it, because you have to effectively spend the time and money to bring somebody on board and then to train them, and then to do all of that other stuff. So, yeah, if they figure out that they're worth more and they go somewhere else, then, you have just lost the game as a company.

**SAM:&nbsp;** Which is why there's an incentive for companies to discourage employees from sharing that information with each other and with people outside their companies, right? They discourage information sharing within the company because they don't want one person to get upset that another person may be making more or less than them.

**CHUCK:&nbsp;** Actually, I have a story about this.

**SAM:&nbsp;** Yeah, let's hear it.

**CHUCK:&nbsp;** Back when I was working as a manager for a company. I'm not going to be too specific because I don't want to smear the company that I was working for and the manager that was responsible for it, ultimately, was let go. But when we started building out the support team for this company, we hired two guys to help us out and figure out to do some of the work that we were doing for support. Then, as time went on, we hired more and more people. But I only was involved in hiring the first two or three, and then, they hired somebody to be my manager, and he hired the rest of the team.

When he hired the rest of the team, it turned out that he hired somebody who looked a whole lot like kind of that model employee that you would imagine you get, and he made him an offer for a higher hourly rate than the other two guys that had been there for a while. Eventually, one of them walked across- he left his pay stub out, this other employee - left his pay stub out so these two guys who'd been there for a while, probably contributed more to the team than anyone else, and they found out that he was making more than them so they went to this boss and he actually lied to them about it. They sort of held up the pay stub and said, "This is really what's going on."

Eventually, that manager was let go and those two employees got raises. But it just comes down to basically that this guy looks like the kind of person that this manager wanted to hire and so he hired him and gave him a higher pay. You know, if that information hadn't never come around, then the two other employees would have been happy with their salaries and they would have been paid less and everything would have gone on as normal.

I think, there is a discussion to be had over what's fair versus what we should or shouldn't know about each other. But, yeah, it was interesting. It was really interesting just to see that as soon as the information came out, those two guys weren't happy with what they were getting paid anymore. I think, it plays into this, I'm not sure exactly how. But I think, it's an interesting, at least in my experience, way of seeing things where- Yeah, I mean, if we'd lost those two support technicians, we would have been hurting, and it probably would've cost the company a bunch of money to find and hire people to make up for the work that they would have been doing.

**LAUREN:&nbsp;** Going back to the concept of some companies acting in bad faith, in the tech community, we had some of the largest names in technology: Apple, Intel, Google, and whatnot, like all of the people of the very high ends of those companies collaborating to keep salaries lower. They were saying that those companies weren't going to poach. They're basically colluding to suppress wages. You can't see something like that and then, say companies are acting in workers' interests, in any kind of sense.

**CHUCK:&nbsp;** I agree with you that those companies were not acting in good faith, at the same time, I don't think all companies do that.

**LAUREN:&nbsp;** It's true that all companies do not do that. But when you have some bad actors and those people are getting away with it. Particularly, when they're at the high end of the spectrum, they are keeping the entire market suppressed in that case.

**SAM:&nbsp;** Especially, one of them was Google, which I think pays more than almost any other company on the planet, as far as I know, and they and Apple, and looks like Intel according to this article I found. They all basically conspired to keep wages lower than the actual market in their area - Silicon Valley - would have led them to be. So, yeah that naturally has a suppressing effect everywhere else.

**CORALINE:&nbsp;** So I'm interested in the fact that there's this asymmetry of information that Sam brought up and yet, developers are so in demand that we can pretty much set the terms of our employment. So what is the missing factor here that is keeping us all from maximizing our salaries as part of these negotiations? I think, Lauren talked on some of it in terms of the cultural taboo for women and people of color to ask for what they think is fair. But I think, probably, the same things happening to a white dudes, too?

**SAM:&nbsp;** Yeah, I certainly feel ashamed of talking about my salary with other people. I have to consciously make myself get over that, but, yeah, there's a lot of sort of enculturation around like this will be rude, or embarrassing, or make people feel bad, or it seems like you're bragging, right?

**LAUREN:&nbsp;** There's definitely in this cultural understanding and belief that it's you're either participating in your own shame, or you are shaming other people when you're sharing that type of information. That discomfort and whatnot is kind of the core of what needs to be addressed. It really is a phenomenon that only works to the majority of the population’s detriment. When it comes right down to it, the middle class as a whole has been atrophying for decades at this point, and really they are the driver of the economy, as a whole.

One of the reasons why I saw fit to start encouraging this breaking down of this taboo is the hope that it would filter down to all sectors and people would start having these conversations because trickle-down economics just doesn't work. We've seen that over the past three and a half decades. If you want to enliven an economy on a broad scale, you need to put disposable income in the hands of the masses, so to speak. Like, if people are only able to afford the bare necessities the companies that are going to be making the most profit, are going to be the people selling those necessities. You're looking out like gas companies. You're looking at companies that are discounting on food. You're looking at Wal-Mart. You're looking at Target to a large extent.

All of these companies are taking the vast majority of income and companies that are selling what are considered less necessary goods are suffering for it. I think, we in the tech sector, are probably going to start seeing that fairly soon as the economic crunch becomes more and more prevalent.

**CORALINE:&nbsp;** You know I just realized something. Executive salaries tend to be public.

**LAUREN:&nbsp;** Yeah, there's a reason for that.

**CORALINE:&nbsp;** What is that reason, you think?

**LAUREN:&nbsp;** That reason is basically so that they don't get completely out of hand.

**CORALINE:&nbsp;** You don't think they're completely out of hand?

**[Laughter]**

**LAUREN:&nbsp;** So they are already completely out of hand. I'm saying, so they don't even get more out of hand.

**CHUCK:&nbsp;** So what do you mean by out of hand?

**LAUREN:&nbsp;** Most people have the belief that salaries should be based on the amount of profit and good in a company that is being delivered to the company. Like there should be some degree of performance basis in there. But what ends up happening with the CEO salaries, with corporate executive salaries is they're making 100, 200, 300, 500 times the salary of the median salary paid out by the company. So you're looking at that, and you have to have this question of like, "How in the hell is one person providing three hundred times the return of the median worker at that company?" It's kind of mind boggling to me how corporate executives end up justifying those salaries.

**CHUCK:&nbsp;** So you're saying that the CEO's aren't worth it? There aren't worth being paid that much?

**LAUREN:&nbsp;** Yeah, they are not worth the amount they're being paid. There are CEO's who have driven companies into the ground and made killings off of doing so.

**CHUCK:&nbsp;** That's true, but that's on the boards that run those companies. I see the CEO market as a market just like the programmer markets a market. If you want to get the CEO that you think is going to take your company to the place that you want it to be, then you have to pay them whatever the market is demanding for that position, for that person.

**LAUREN:&nbsp;** But that information is public. So therefore, they know that they can keep bumping that number up. Whereas, for programmers or for any workers, that information isn't public so there's less ability to go, "Oh well, I could just go over to this other company that's willing to pay \$180,000 for my skills," and having that transparency is kind of a double-edged sword.

**CHUCK:&nbsp;** Yeah, I think this is the crux of the argument behind Talkpay, right? Is that, if all of the information about who was making what, where, were publicly available, then people would go to the place where they can get the best market value, so to speak, for their skills.

**LAUREN:&nbsp;** Yes, that's exactly right, and basically as a whole, we should be able to bump our salaries up collectively until the fair market value, and what we bring to the valuation of the company is reached. There's a ratio there that is something that should happen naturally but because of secrecy, because of this asymmetry, it's been artificially suppressed. That's really what Talkpay is trying to address.

**CHUCK:&nbsp;** Okay, so what I want to get into then is hashtag on Twitter going to make this change effective, or are there other things that we can or should do that are going to bring about this, sort of level the playing field and give us less asymmetry in our information?

**LAUREN:&nbsp;** I chose to do a hashtag simply for two reasons. One reason is that it's tied to a person's identity. Something like Glassdoor has existed for years before Talkpay has. But I've talked to a number of people who have looked at information on Glassdoor where sharing salary information is given anonymously, and they find reasons to justify why that, like fictitious person is making so much more.

You look at an amount, a dollar value, and you look at what you're making and it's like if I'm making $135,000 a year as a developer who has been working for ten years, and someone at some company just in the field of software development with a senior software engineer title is making $360,000 a year, I'm going to imagine someone who is absolutely prolific like --

**SAM:&nbsp;** Like a [inaudible] something, right?

**LAUREN:&nbsp;** Yeah, just someone who is far and beyond, pushing the boundaries of what is possible in the field. But when I find out that that person who is making \$360,000 is the guy like five desks down who is doing basically the same things that I'm doing, and I'm muttering about code quality, I'm going to look at that and be like, "Well, shit! Why am I not making that much money?"

That is why I chose to do a hashtag so that these dollar values would have actual people attached to them. Is there something else that can be done? Is there more that can be done about this? Absolutely. There is totally is. But this was something that I was seeing to just get the ball rolling, to have these discussions. Not just about sharing salaries but about the taboo surrounding sharing salaries. To have people say, "Hey, I'm uncomfortable sharing salaries." Well, why are you uncomfortable sharing salaries? Why does that feel like it's something that you shouldn't be doing?

**CORALINE:&nbsp;** I have a great reason for not wanting to participate in hashtag and that is, as a transgender woman, I feel like my employment can be terminated arbitrarily at any point in time. There is no legal protection in my state. For me, I don't have a protected status as a transgender person so I can be fired without cause. It's seems to me like revealing my salary could be that thing that would say, "Oh, we don't like the fact that she did that. We think that that is disingenuous. We think that that was revealing company information that we'd rather keep private. We're just going to let her go." So what were some of the real world implications of the retaliation against people who participated in hashtag? Did you hear any stories?

**LAUREN:&nbsp;** I've actually hadn't heard any stories of someone being retaliated against. One of the reasons was that when I originally- in the article that first kicked off Talkpay, I discuss the National Labor Relations Act of 1936, which basically prohibits companies from actually punishing people for discussing pay. It was kind of shocking to me to find this out because literally, every company that I had worked at, before I kicked off the hashtag, literally every company that I had worked for had a little clause in their employee handbook that basically said that you can't share salary information.

When I read about the National Labor Relations Act, that was explicitly called out as being illegal to do, like a company cannot prohibit the exchange of that information. So that was one of the things kind of emboldened me to first start exploring this. But I will absolutely say that when I first disclose my salary information publicly at Cascadia Ruby 2013, that was what I like to refer to as a pant-shitting moment. That was nerve wracking to an extreme degree exactly because of the fear of retaliation.

We live in a country where pretty much every state is known as an 'at-will' employment state, which basically means that you can be fired for any reason regardless of status.

**CORALINE:&nbsp;** Or no reason.

**LAUREN:&nbsp;** Yes.

**SAM:&nbsp;** At any time with or without notice.

**LAUREN:&nbsp;** Exactly. There is that extra fear that when you are a marginalized individual, that it will come back to you and that's actually one of the reasons why a friend of mine, Stephanie Morillo, she actually started collecting anonymous information from primarily women and people of color to then share for the hashtag, which I actually had mixed feelings about because of the fact that I wanted names attached.

**SAM:&nbsp;** Yeah, I was going to ask you about that.

**LAUREN:&nbsp;** I completely understand why she did it, and why that was really important. But it will also kind of undermined the impact of publicly disclosing with name attached like both in breaking down the taboo and helping others to realize their own potential market value for their skills.

**SAM:&nbsp;** Now, I have a clarifying question for you about that National Labor Act, what it is that you said?

**LAUREN:&nbsp;** National Labor Relations Act.

**SAM:&nbsp;** -- Act, thank you. I've done a little bit of reading about this myself. Not nearly as much as I suspect you have. But some of the things that I've seen have explicitly called out the idea that that act protects disclosures between employees and was meant as a way to maybe help workers self-organize a little bit better. I know that you are legally allowed to share your salary information with somebody that you work with, but as I understand it, some companies try to make a case that sharing your information outside the company is somehow still a trade secret.

**LAUREN:&nbsp;** So, if you have access to an entire pay structure, like if your manager or if you have access to a horribly locked down employee database, and get that salary information, not through the discussion with your coworkers and what not, then that is information that was obtained - I don't want to say it, illegally but like in bad faith and so, isn't covered by the National Labor Relations Act.

However, discussion of your own personal salary outside of company work time is perfectly legal. It is protected by the National Labor Relations Act. They cannot, absolutely cannot dictate who you can talk about with your salary. The implication that would be made if you couldn't discuss salary information outside of the workplace would be you can even tell your own family --

**[Laughter]**

**LAUREN:&nbsp;** -- Which is completely absurd.

**CHUCK:&nbsp;** Just to clarify. I can talk to coworkers or neighbors or the guy down the street or some stranger walking down the road that I'm passing going the other way about my salary, as long as I'm not on work time.

**LAUREN:&nbsp;** Even if you are at work time, you technically should be able to do that. That's what the National Labor Relations Act was specifically calling out. It was saying that that workers could not be punished for, basically, doing collective action on company time.

Now, there's restrictions based on like you can't do an organization for a union on company time and still expect to be paid. But what was being called out was like discussions during lunch hour about pay, where employers were retaliating against. So that was basically called out. It was like, you can't do that. You can't actually control your employee’s behavior when they're not being paid by you.

So it's kind of nebulous because you said before that it was like on company time. They can tell you like, you're not talking about your job, get back to work type of things, and would potentially be able to retaliate against you for that. But if you were at your place of employment and having lunch or whatnot, then that is you being off the clock technically, and they can't tell you like, "Oh, you can't talk about that here because you're at work." So, it's the kind of like legal caveat and nuances that are really kind of Byzantine.

**CORALINE:&nbsp;** I'm curious about the intersection of sharing your salary information publicly and impostor syndrome because I personally do not feel like I deserve the salary that I am receiving, relative to other people who I see as much, much better in the field than I am.

**LAUREN:&nbsp;** My feelings about that particular aspect is this is one of the reasons that we need to have these types of discussions, because what it comes down to is that people should be making what they're worth, and we are right now, suffering from salaries being artificially repressed. So that kind of anxiety and impostor syndrome coming up, really to me feels like an effect of living in this like salary-repressed situation.

It's not that you shouldn't be making that much. It's that everyone else should be making more. That really is another one of the main drivers for why I started Talkpay in the first place. The whole crabs in a bucket thing of like, "Oh, people shouldn't be making \$160,000 for sitting at a keyboard," and whatnot. Well, it's like, well, why not? If I write a program that saves a company like two million dollars in revenue annually, theoretically speaking, I should be making even more money because I just saved up crap ton of money for the company.

So, this belief that we are not contributing as much, I grapple with that a lot because of this mentality that we should devalue the work that we're doing and not put it in terms of raw dollars like the companies that we're working for are actually doing.

**SAM:&nbsp;** I have a follow up from that. One of the things that I've been thinking about and struggling with for years as a developer is this idea that my job is basically to destroy other jobs, you know?

**[Laughter]**

**SAM:&nbsp;** I take things that bunch of clerical people in clerical positions could do and I make them more efficient, and by more efficient I mean, it takes fewer people to do them. That is literally taking somebody's job away from them. Now, I sort of balance that out with myself by thinking about what I take away is boring work, and I make the boring work easier to do so that humans can focus on the more interesting edge cases. But still, like there's been a discussion for quite a while now about the larger effect of automation on manufacturing industry, but we are automating office work, which used to be a pretty good way to make a living.

**LAUREN:&nbsp;** Yeah, I've killed so many jobs personally. It's something that I've thought about --

**CORALINE:&nbsp;** You're like a politician. That's amazing.

**[Laughter]**

**LAUREN:&nbsp;** I know, right? I grapple with that a lot. Fundamentally, what it comes down to is kind of an accelerationist type of perspective. Accelerationism is this belief that like things should be... not should be but like things will get sped up to a point of like un-tenability before they get actually addressed and taken care of. So a part of me feels very accelerationist about this where like we are rapidly coming to a point in our society where we're reaching a tipping point. We need to start assessing things and wondering like do people need to be working in order to live.

That is a huge question that we're going to need to start addressing, because we're also coming to a point where artificial intelligence might make our jobs obsolete. We need to kind of grapple with that. It's something that weighs heavily on my mind. So this discussion and this push for collective action and for working as kind of a united front in disclosing salaries and getting used to having difficult conversations, particularly surrounding pay, is one that has kind of ulterior motives. In that, I really want people to start asking difficult questions about the nature of work and the nature of life in a place where there aren't jobs for every single person.

**CHUCK:&nbsp;** I see it from right now, and this is a generalization. It's not always true but I think it is usually true, that the jobs that we eliminate like office work and things like that are things that ultimately aren't moving society forward, or if they are, and they can be automated, then we can move those workers to other places where they can move society forward in more meaningful ways.

So I don't feel terrible about making something more efficient because what that means is that we can then, redistribute our manpower to things that make a bigger difference. Like I said, I know that's not always the case, but in a lot of cases, it is the case.

**LAUREN:&nbsp;** Yeah, I definitely feel that is the case. But the problem that I haven't see is that the places that will really help propel humanity as a whole forward are completely and horribly underfunded, like if you look at the sciences and whatnot.

One of the things that's been really depressing about Talkpay has been seen in the number of people who have left the hard sciences and the humanities in general as well, like they have left fields they have become experts at. I mean, talking about people with master’s degree in genetics, people with PhD in material sciences, things like this. Leaving those fields because they weren't paying anything.

People with PhD is talking about, "Hey, back in 2014, I was making \$26,000 a year," and they moved to software because there are getting paid 100,000 plus, like --

**SAM:&nbsp;** And they're getting paid that much to work on a service that will bring you, and I kid you not, this is a literal thing in Portland, warm cookies in the evening. Or any of the variety of other things that your mom is no longer doing for you.

**LAUREN:&nbsp;** Or like the hardware devices that allow you to video chat with your pet.

**[Laughter]**

**SAM:&nbsp;** Right. These have long lasting societal and humanitarian value.

**CORALINE:&nbsp;** So, Lauren, I'm curious. I want to bring it back a little bit. Do you consider the Talkpay project successful? What do you think the net impact of your effort was?

**LAUREN:&nbsp;** The Talkpay Project is a work in progress, and I think it always will be. What I mean by that is that I think, it has been successful and it is helping to propel these conversations. The fact that I'm on this show right now, or talking about this, means that it worked to some degree. But we constantly need to be talking about collective action and talking about populations as a whole.

We need to constantly be advocating for ourselves because if we are not lending our own voices to our own benefit, no one is. When I say that it's a work in progress, I'm saying that I will continue doubting about this every year, at least, until it is a regular occurrence that people feel like they don't feel bad about sharing this information. They don't feel bad about advocating for themselves. That's really the end goal of Talkpay.

It is successful and I hope it will continue to be successful. I hope that I won't be like 70 or 80 years old from decades from now being like, "Why are we talking about this still?"

**CHUCK:&nbsp;** All right. That seems like a good place to wrap up. Sam do you have some Picks for us?

**SAM:&nbsp;** Oh, yeah. Let me see. I've been doing a fair bit of reading lately. I have this tendency to read books to the exclusion of everything else, such that if I start a book, I will stay up until three in the morning to finish it so I read in binges. One of my latest binges was a book by Patrick Rothfuss called The Name of the Wind, and it has a sequel whose name I don't remember off the top of my head. This is sort of like classic style fantasy. But it's really well done. I really enjoy the writing. The characters are really rich. I enjoyed the world building. This is a fantasy world that mixes elements of magic and [inaudible], with also the sort of 18th century Newtonian physics. So they actually have a very scientific approach to magic, which I find really interesting.

Anyway, it's a really well done book, and the one thing I will warn you about is that it isn't intended to be a trilogy, and there are currently two and a half books in it. The author is extremely... how shall I say? Deliberate about his writing. So if you want to wait until the third book is out, and you may want to because they're really good and compelling. You might want to put this Pick on a shelf for a while, as it were. But it's well worth your time. That's it for me.

**CHUCK:&nbsp;** Awesome. Coraline, what are your Picks?

**CORALINE:&nbsp;** I also have a fantasy book to recommend. It is called The Lies of Locke Lamora. It's a fantasy novel by Scott Lynch. It's part of a series called The Gentleman Bastard series. It's about a group of elite con artists calling themselves The Gentleman Bastards and they live in a city called Camorr which is based on Venice on an unnamed world that is not our world. There's a lot of interplay between like the past and the present. Locke Lamora and his gang get themselves into various means of getting in trouble with very elaborate schemes for robbing the rich, and sort of taking advantage of the very rigid society which they love. It is a very fun book.

I don't know, I've always had a thing for heist movies and heist movies is like they don't tend to be really good movies. But there's something that's really fun about them, and this book has the feeling of a heist movie. The action is constantly moving forward and there's constant surprise and it's full of twist. It's a lot of fun. It's not a challenging read at all. If you're looking for a series to get involved with, you could do much worse than The Lies of Locke Lamora.

**LAUREN:&nbsp;** I feel almost compelled to recommend the Mistborn trilogy by Brandon Sanderson if you enjoyed that because the first book has an amazing feel of being like this epic heist.

**CHUCK:&nbsp;** Yeah, terrific book too. I was actually going to pick up Brandon Sanderson book. I've been going through and reading pretty much all of his books. Just because I've enjoyed so many of them. One of the book series that I don't hear talked about as much and it's a much more lighthearted and humorous book series is Alcatraz Versus the Evil Librarians. They're funny books. There's a new one coming out called Alcatraz Versus the Evil Librarians and The Dark Talent. It picks up after the latest Alcatraz book, which I don't think he published one in a while. Anyway, I'm really interested to see that one come out and I'm excited about it.

One of the things that I'm going to pick since I'm traveling to Chicago, this evening, actually, is I have Bose noise canceling headphones, and I just love having those in the airport and on the airplane. I can't say enough good things about them. They work really well. It kind of makes it so I can tune everything out and I can either read or listen to a book or you know, while I'm traveling, listen to music while I work on stuff, and it's just terrific. I'm going to pick those. I'll put a link to them in the show notes.

**SAM:&nbsp;** Oh, second thing. I bought a pair of those, a year or two ago, and I've discovered I'm much less tired when I arrive at my destination when I've had the noise canceling for the flight. It's great.

**CHUCK:&nbsp;** Yep. Lauren, what are your Picks?

**LAUREN:&nbsp;** So my Picks right now are two TED Talks by Brené Brown. The two TED Talks are The Power of Vulnerability and Listening to Shame. They are absolutely amazing talks. Really discussing about how shame and vulnerability are kind of cruxes to human connection. I feel like they really kind of gel with the discussion about Talkpay because there is a lot of vulnerability and shame goes into talking about pay. So, I highly recommend listening to those two TED Talks just because they really help kind of put our lives and our interactions with the people into perspective.

**CHUCK:&nbsp;** Awesome. Well, people want to find out more about you, what you're doing, get involved in Talkpay, what do they do?

**LAUREN:&nbsp;** Well, they can use the hashtag or follow me on Twitter. I am @LaurenVoswinkel, a very startling name. I know it comes out of nowhere, but @LaurenVoswinkel on Twitter is where I can be found.

**CHUCK:&nbsp;** All right. Well, thank you for coming. We'll wrap the show up and we'll catch you all next week.

**_[Bandwidth for this segment is provided by CacheFly, the world’s fastest CDN. Deliver your content fast with CacheFly. Visit CacheFly.com to learn more.]_**

**_[Would you like to join a conversation with the Rogues and their guests? Want to support the show? We have a forum that allows you to join the conversation and support the show at the same time. You can sign up at RubyRogues.com/Parley.]_**
