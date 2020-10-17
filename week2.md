# Week 2: Hacktoberfest:

Hacktoberfest is a monthlong, annual event that DigitalOcean, an American cloud infastructure provider, has held since 2014. Hosted by Github and organized by DigitalOcean, it has a simple premise: anyone who makes four valid pull requests within the month of October will receive a Hacktoberfest shirt. The event has garnered a lot of attention over the years, amassing 483,127 pull requests from participants in 2019.

It is described on [the event page](https://hacktoberfest.digitalocean.com/) as a "celebration open to everyone in our global community" where people can "make positive contributions to an ever-growing community". The idea is that participants, initially motivated to create pull requests for the t-shirts, will contribute to open-source as a whole and have a long-lasting impact on people and technology.

Recently however, many people have taken a harsher, cynical stance on the company and the festival. In the first day of Hacktoberfest 2020, developer and repository maintainer [Andy Allan](https://twitter.com/gravitystorm) took to his blog to call it ["a corporate-sponsored distributed denial of service attack against the open source maintainer community"](https://blog.domenic.me/hacktoberfest/). Within hours of the event's start, he had received 11 pull requests on a single repository by eager t-shirt lovers, sending notifications to the 485 watchers and wasting the maintainers' time. Without a way to opt out of the event or limiting the interaction in his repository for more than 24-hours ([which has now been fixed](https://twitter.com/github/status/1311772722234560517)), he pleaded with Github and DigitalOcean to genuinely support open-source by preventing/alleviating this problem.

He wasn't the only person with this problem, either. As of October 16, 2020, 444 tweets were made with the hashtag "#shitoberfest", all criticizing the handling of the event and the spam pull requests that repository maintainers were receiving.

In response to the outrage, DigitalOcean released a [series of updates from October 1st to 3rd](https://hacktoberfest.digitalocean.com/hacktoberfest-update) with the goal of reducing spam. Their improvements included:
- making the event opt-in only for projects
- requiring related pull requests to be approved by maintainers
- implementing a banning system for users with many flagged pull requests
- urging participants to read and abide by the rules

It seems that these additions were appreciated by many repository maintainers. After a spree of tweets and retweets criticizing the handling of the event in the beginning, blog author Andy Allan hasn't took to Twitter about the topic against. The initial flood of tweets with the hashtag have also since simmered down and their [update announcement had a generally positive reception](https://twitter.com/hacktoberfest/status/1312221208667185153).

However, problematic pull requests haven't been eradicated completely. Maintainers are still dealing with requests that unnecessarily add words/characters ([1](https://twitter.com/emmalearnscode/status/1314946091943682051), [2](https://twitter.com/shpankus/status/1313637510560481280), [3](https://twitter.com/psuranas/status/1312425016487682054), [4](https://twitter.com/_abim_/status/1313478447252078593)) or by arbitrarily change code syntax, such as converting between single-line and mult-line comments without practical reasoning ([1](https://twitter.com/ShivamJoker/status/1314783210836955142)). Repository maintainers' frustrations are understandable: they signed up for this event to promote open-source development, not to spend hours denying spam pull-requests. However, it's hard to criticize DigitalOcean's response to the scenario. Their prompt reply to the outrage and their decision to make the festival opt-in for repositories seems to have been met positively across the board. Recent tweets by maintainers criticizing the event also seem more sarcastic, lacking the irritated tone of those in the beginning of October.

The decision to allow repositories to opt-in was in line with the requests of developers like Andy Allan, and it seems to have helped greatly, as maintainers who don't want to be bothered will not be. The requirement for pull requests to be approved by maintainers is also helpful, encouraging users to make genuine contributions. These changes encapsulate the best of both worlds: the event still promotes open-source development but it also openly discourages and mitigates spammy pull requests.

I am not a maintainer of a repository, nor am I participant of Hacktoberfest, so my experience in this matter is limited. Based on the response by maintainers, however, their updates seem to have stopped the initial flood of spam into a trickle. It will be interesting to see the statistics of pull requests after the event is over, and observe how impactful the updates actually were.

Resources:
- https://blog.domenic.me/hacktoberfest/
- https://twitter.com/gravitystorm/likes
- https://hacktoberfest.digitalocean.com/hacktoberfest-update
