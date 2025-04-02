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

> Chengfeng 2025

Because sometimes it's pointless to argue with them. You can't win arguments against them, so all I can do is become better. Because when you run faster, those voices can't catch up to you.
