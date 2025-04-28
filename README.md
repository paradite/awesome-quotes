# awesome-quotes

Awesome quotes from podcasts and elsewhere

## Dario Amodei on vision and productivity

> https://lexfridman.com/dario-amodei-transcript

(01:33:01) I don’t want to talk about anyone else’s vision. If you have a vision for how to do it, you should go off and you should do that vision. It is incredibly unproductive to try and argue with someone else’s vision. You might think they’re not doing it the right way. You might think they’re dishonest. Who knows? Maybe you’re right, maybe you’re not. But what you should do is you should take some people you trust and you should go off together and you should make your vision happen. And if your vision is compelling, if you can make it appeal to people, some combination of ethically in the market, if you can make a company that’s a place people want to join, that engages in practices that people think are reasonable while managing to maintain its position in the ecosystem at the same time, if you do that, people will copy it.

(01:33:52) And the fact that you are doing it, especially the fact that you’re doing it better than they are, causes them to change their behavior in a much more compelling way than if they’re your boss and you’re arguing with them. I don’t know how to be any more specific about it than that, but I think it’s generally very unproductive to try and get someone else’s vision to look like your vision. It’s much more productive to go off and do a clean experiment and say, “This is our vision, this is how we’re going to do things. Your choice is you can ignore us, you can reject what we’re doing or you can start to become more like us.” And imitation is the sincerest form of flattery. And that plays out in the behavior of customers, that plays out in the behavior of the public, that plays out in the behavior of where people choose to work. And again, at the end, it’s not about one company winning or another company winning.

## Dario Amodei on talent density

> https://lexfridman.com/dario-amodei-transcript

(01:38:37) This is one of these statements that’s more true every month. Every month I see this statement as more true than I did the month before. So if I were to do a thought experiment, let’s say you have a team of 100 people that are super smart, motivated and aligned with the mission and that’s your company. Or you can have a team of a thousand people where 200 people are super smart, super aligned with the mission and then 800 people are, let’s just say you pick 800 random big tech employees, which would you rather have? The talent mass is greater in the group of a thousand people. You have even a larger number of incredibly talented, incredibly aligned, incredibly smart people. But the issue is just that if every time someone super talented looks around, they see someone else super talented and super dedicated, that sets the tone for everything. That sets the tone for everyone is super inspired to work at the same place. Everyone trusts everyone else.

(01:39:42) If you have a thousand or 10,000 people and things have really regressed, you are not able to do selection and you’re choosing random people, what happens is then you need to put a lot of processes and a lot of guardrails in place just because people don’t fully trust each other or you have to adjudicate political battles. There are so many things that slow down the org’s ability to operate. And so we’re nearly a thousand people and we’ve tried to make it so that as large a fraction of those thousand people as possible are super talented, super skilled, it’s one of the reasons we’ve slowed down hiring a lot in the last few months. We grew from 300 to 800, I believe, I think in the first seven, eight months of the year and now we’ve slowed down. The last three months, we went from 800 to 900, 950, something like that. Don’t quote me on the exact numbers, but I think there’s an inflection point around a thousand and we want to be much more careful how we grow.

## Amanda Askell on language model character and being a world traveler

> https://lexfridman.com/dario-amodei-transcript

(02:53:37) Yeah, so I think there’s ones that are good for conversational purposes. So asking follow-up questions in the appropriate places and asking the appropriate kinds of questions. I think there are broader traits that feel like they might be more impactful. So one example that I guess I’ve touched on, but that also feels important and is the thing that I’ve worked on a lot, is honesty. And I think this gets to the sycophancy point. There’s a balancing act that they have to walk, which is models currently are less capable than humans in a lot of areas. And if they push back against you too much, it can actually be kind of annoying, especially if you’re just correct, because you’re like, “Look, I’m smarter than you on this topic. I know more.”

(02:54:25) And at the same time, you don’t want them to just fully defer to humans and to try to be as accurate as they possibly can be about the world and to be consistent across contexts. I think there are others. When I was thinking about the character, I guess one picture that I had in mind is, especially because these are models that are going to be talking to people from all over the world with lots of different political views, lots of different ages, and so you have to ask yourself, what is it to be a good person in those circumstances? Is there a kind of person who can travel the world, talk to many different people, and almost everyone will come away being like, “Wow, that’s a really good person. That person seems really-“

(02:55:00) … Being like, wow, that’s a really good person. That person seems really genuine. And I guess my thought there was I can imagine such a person and they’re not a person who just adopts the values of the local culture. And in fact, that would be kind of rude. I think if someone came to you and just pretended to have your values, you’d be like, that’s kind of off pin. It’s someone who’s very genuine and insofar as they have opinions and values, they express them. They’re willing to discuss things though, they’re open-minded, they’re respectful. And so I guess I had in mind that the person who, if we were to aspire to be the best person that we could be in the kind of circumstance that a model finds itself in, how would we act? And I think that’s the guide to the sorts of traits that I tend to think about.

## Chris Olah on neurons, gradient descent and dimensions

> https://lexfridman.com/dario-amodei-transcript

(04:44:04) And similarly, when we’re talking about neurons, you can have many more concepts than you have neurons. So that’s at a high level, the superstition hypothesis. Now it has this even wilder implication, which is to go and say that neural networks, it may not just be the case that the representations are like this, but the computation may also be like this. The connections between all of them. And so in some sense, neural networks may be shadows of much larger sparser neural networks. And what we see are these projections. And the strongest version of superstition hypothesis would be to take that really seriously and sort of say there actually is in some sense this upstairs model where the neurons are really sparse and all interpleural, and the weights between them are these really sparse circuits. And that’s what we’re studying. And the thing that we’re observing is the shadow of evidence. We need to find the original object.

Lex Fridman

(04:45:03) And the process of learning is trying to construct a compression of the upstairs model that doesn’t lose too much information in the projection.

Chris Olah

(04:45:11) Yeah, it’s finding how to fit it efficiently or something like this. The gradient descent is doing this and in fact, so this sort of says that gradient descent, it could just represent a dense neural network, but it sort of says that gradient descent is implicitly searching over the space of extremely sparse models that could be projected into this low-dimensional space. And this large body of work of people going and trying to study sparse neural networks where you go and you have… you could design neural networks where the edges are sparse and the activations are sparse.

(04:45:38) And my sense is that work has generally, it feels very principled, it makes so much sense, and yet that work hasn’t really panned out that well, is my impression broadly. And I think that a potential answer for that is that actually the neural network is already sparse in some sense. You were trying to go and do this. Gradient descent was actually behind the scenes going and searching more efficiently than you could through the space of sparse models and going and learning whatever sparse model was most efficient. And then figuring out how to fold it down nicely to go and run conveniently on your GPU, which does as nice dense matrix multiplies. And that you just can’t beat that.

## Li Jiaqi on Haters

> Chengfeng 2025, translated from Chinese

Because sometimes it's pointless to argue with them. You can't win arguments against them, so all I can do is become better. Because when you run faster, those voices can't catch up to you.

## Varun Mohan on Agency

> https://www.lennysnewsletter.com/p/the-untold-story-of-windsurf-varun-mohan

(21:37) I think one of the things that's maybe a little bit undervalued is this kind of agency piece. And I think about this a lot, which is, you have a lot of people that could go through college and go through school and they're basically told exactly what to do on a P-set.
They're given these very, very, I would say, well-defined paths that they need to take. I think maybe in society and just school, we don't prioritize how do you make sure you get people with real agency that want to build something, right?

Their goal is not just to maybe graduate from college and then get a job at a big tech company where they're told exactly what to do or where to put the pixel for this one website. I think that's maybe a skill set that is undervalued just right now, probably in the last maybe 10 years or so.

And I think that's going to be really, really important. For a startup, obviously these are skills that we just look for. We look for people that are really high agency because we just recognize that by default, if we don't innovate and do crazy things, we're going to die. The company is just going to die.

So we just look for this, right? But I would say for most software engineering jobs, that's probably not the case. Just think about big company X and what they're hiring for on the average software engineering interview. It probably doesn't look like that.

## Varun Mohan on Role of Software Engineer / Developer

> https://www.lennysnewsletter.com/p/the-untold-story-of-windsurf-varun-mohan

(13:04) One of the key pieces that we recognized was, with this new paradigm with AI, AI was probably going to write well over 90% of the software, in which case the role of a developer and what they're doing in the IDE is maybe reviewing code. Maybe it's actually a little bit different than what it is in the past.

(17:39) I think when we think about what is an engineer actually doing, it probably falls into three buckets, right? What should I solve for? How should I solve it? And then solving it.
I guess everyone who's working in this space is probably increasingly convinced that solving it, which is just the pure, "I know how I'm going to do it" and just going and doing it. AI is going to handle vast majority, if not all of it.

In fact, it probably actually, with some of the work that we've done in terms of deeply understanding code bases, how should I solve it is also going to get closer and closer to getting done.

If you deeply understand the environment inside an organization, if you deeply understand the code base, how you should solve it, given best practices when the company also gets solved.

So I think what engineering kind of goes to is actually what you wanted engineers to do in the first place, which is, what are the most important business problems that we do need to solve? What are the most important capabilities that we need our application, our product to have?

And actually going and prioritizing those and actually going and making the right technical decisions to go out and doing it. And I think that's where engineering is probably heading towards.

## Varun Mohan on Hiring

> https://www.lennysnewsletter.com/p/the-untold-story-of-windsurf-varun-mohan

(31:01) One of the key pieces that we look for, we have a very high technical bar. So assuming that they actually meet the technical bar, I think we sort of look for people that are really, really passionate about the mission of what we're actually trying to solve and people that are willing to work very hard.

I think one of the things that we don't try to do is convince people, "Hey look, we are a very chill company and it's great to work here." I think, no, this is a very exciting space. It's very competitive.

You should expect us to lose if the people at the company are not kind of... They're not working very hard. And I think one of the biggest dog whistles I hear is, when I ask people how hard are you willing to work, some people actually ultimately say, "Hey, I work very smart."

And I basically ask them a question, "If we have many smart people at our company that also work hard, what's the differentiator going to be? Are you just going to pull them down?" Because I think one of the things that's true about companies is it's like this massive group project.

And I think the thing about a person that is not pulling their weight that's bad. It's not the productivity, right? At some point when the company becomes many hundreds of engineers, I'm not going to be thinking about the one engineer that's not pulling their weight.

It's the team of people they work with that are almost basically saying, "Is this the bar internally at the company? Is this the expectation?"

And I guess, Lenny, if I told you you have a team of five people and the four other people you're working with just don't care, how much are you going to feel like you should care?

## Varun Mohan on Hiring Human Engineers

> https://www.lennysnewsletter.com/p/the-untold-story-of-windsurf-varun-mohan

(1:04:15) I think it really comes down to, do you get incremental value by adding more engineers internally? I'm going to take... First of all, maybe just to set the record straight, if AI is writing over 90% of the code, that doesn't mean engineers are 10X as productive. Engineers spend more time than just writing code.

The review code, test code, debug code, design code, deploy code, right? Navigate code. There's probably a lot of different things that engineers do. There's this one famous law in parallel computing, it's called Amdahl's Law. I don't know if you've heard about it.

But it basically says if you have a graph of tasks and you have this critical path and you take any one task and parallelize it a ton, which is make it almost take zero amount of time, there's still a limit of the amount of how much faster it made the whole process go.

So maybe put simply, let's say you have 100 units of time and only 30 units of time is being spent writing software and I took the 30 and made it three, I only took the 100 and made it 73. It's only a 27% improvement in the grand scheme of things.

So I think look, we are definitely seeing over 30, maybe close to 40% productivity improvements. But I think for the vision that we're solving for, even if I were to say the company in the long tail had 200 engineers, it'd probably be too low still at that point.

So the question is, how much more productivity do you get per person? Actually, maybe just to even say one of those thing for some of these large companies, let's say you took the CIO of a company like JPMorgan Chase, right?

Her budget on software every year is $17 billion and there's over 50,000 engineers inside the company and you told her, "Hey, each of these engineers are now able to produce more technology." That's effectively what you've done, right?

The right calculus that JPMorgan Chase or any of these companies will make is the ROI of building technology has actually gone up. So the opportunity cost of not investing more into technology has gone up, which means that you should just invest even more. And maybe in the short term you have even more engineers, right?

Now, that's not true across the board. There are some companies that are happy with the amount of technology they're building and there's a ceiling on the amount of technology they want to build. But for companies that actually have a very high technology ceiling, this doesn't mean you stop. This actually means you hire more.
