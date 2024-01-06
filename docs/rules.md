# Rules and Enforcement Guidelines

!!! warning

    **When reporting posts, please provide context** (unless it is reasonably obvious)**.**
    
    **When reporting accounts, please attach the concerning posts.** I will go through a reported account's recent posts, but there is no guarantee that I *can* find the concerning posts, especially when the report does not have details. I cannot dig into mentions-only posts if they are not included in the report, so you must attach them if applicable.

    **For users reporting accounts on remote instances:** if you choose one of the reasons from "it violates instance rules" and forward the report, the remote instance **WILL NOT** see the reason you've chosen (they'll only see "other"), so please remember to provide context in the textbox, which is forwarded to the remote instance.


!!! warning

    The enforcement guidelines are ultimately guidelines. Here I list examples, but the interpretation depends on the exact situation and is up to the administration, particularly in cases where a moderation decision may affect the reputation of the instances (ie. ability of other local users to interact with remote instances).

Generally speaking, punishments are adjusted to the severity of the offense as well as past behaviour. Severity is perceived harm to other users or the instance itself: hate speech or illegal content would be considered high severity where account suspension is often warranted, whereas accidental omission of CW would not. Past behaviour is not just "strikes" or reports: sufficient amount of posts of the reported account will be inspected to determine, in particular, how much "bad faith" was the offense committed in.

## NSFW content

### For mstdn.party (and most other generalist instances)

> Posts that contain nudity, sexually explicit, or violent content must be marked with an "NSFW" content warning and media marked as sensitive when posting

See [here](https://fedi.tips/how-to-use-content-warnings-cws-on-mastodon-and-the-fediverse/) for how to mark posts with a CW.

Generally, offending posts will be marked as sensitive when reported, and repeated offenses will result in *all* posts of the entire account being marked as sensitive.

The rule is not enforced for avatars and profile banners *for now*, but this is likely to change in the future.

### For mstdn.plus

> 1. Nudity and sexually explicit content is prohibited for accounts registered on this instance
> 2. Violent media must be marked as sensitive when posting

Remote accounts that post NSFW content, as well as remote instances that mainly host accounts that post NSFW content, will be silenced, however there is no reprecussion in following them.

## No discrimination

> No racism, sexism, homophobia, transphobia, xenophobia, or casteism

This rule is written as it is on mastodon.social as well as many other generalist instances. The exclusion of any specific term is not intentional, and bad faith attempts to challenge the exact terminology **are** considered to be in violation of the rule.

Please do not report posts solely because you *disagree* with them; I only remove posts if *it is clear* from the post itself, as well as any context provided to me (primarily through report details), that the rule is violated.

## No incitement of violence

> No incitement of violence or promotion of violent ideologies

This rule is written as it is on mastodon.social as well as many other generalist instances.

This often overlaps with the rule above, but note that this rule has no quantifier, in particular in the "incitement of violence" part. This means that you cannot advocate for violence against specific figures, no matter how public they are and how rhetorical your post is.

## No harassment

> No harassment, dogpiling or doxxing of other users

This rule is written as it is on mastodon.social as well as many other generalist instances.

[Subtooting](https://www.urbandictionary.com/define.php?term=subtoot) in bad faith (in particular, with the intent to ridicule or insult the person depicted, or to damage a person's reputation) **is** generally considered harassment (there are very few exceptions). If a person's behaviour is suspected to violate a rule, then please *report* them.

Character assassination against those who reply due to disagreement **is** harassment. Debate the argument, not the debaters.

[Sealioning](https://en.wikipedia.org/wiki/Sealioning) **is** harassment.

## No illegal content

> No content illegal in the United States, Germany, or Finland 

You're well aware of what the most common illegal content are; I should not need to explain this.

## No disinformation

> Do not share intentionally false or misleading information

Anything that has been debunked by *proven facts* is fair game. Here the "intentionally" matters; in an armed conflict, for example, the absence of neutral fact-checking means most things are speculations and thus neither one who casts doubt on those speculations, nor one who reiterates them is, by itself, violating *this* rule (though an armed conflict is likely not a neutral example as those to engage in either may violate other rules).

## Bots

I do apply quite a lot of leeway in enforcing this rule.

> Bots must be marked as bots in their profile preferences, and automated posts should be unlisted (exceptions apply).

Any accounts that produce automated posts and do not plan to manually respond to replies are considered "bots" here.

Automated posts should be unlisted, but to not create additional workload or discrepancies with other instances, currently I do not enforce this on accounts that

* provide content of *general* public interest *and* post at an average frequency of at most once per hour with reasonable spacing, or
* are bridges of their own accounts on other platforms (that is not ActivityPub).

This applies to remote accounts as well (to lesser extent). For example, I limit `bots.krohsnest.com` as weather forecasts of specific locations are not in *general* public interest, though users who may still follow each account manually.

## No Twitter bridges

mstdn.party only:

> Twitter-mirroring instances like BirdsiteLIVE will be suspended, if you want to browse Twitter, use Twitter.

To [quote](https://fediverse.neat.pub/2023/07/10/threads/) from Jonah:

> We block Twitter bridges like BirdsiteLIVE because they do not foster any sense of community. As a one-way mirror, replies and favorites aren’t reflected on Twitter’s side of things, which makes for a confusing experience, and essentially leaves us to host a read-only mirror of Twitter for free, which is neither cost-effective nor encourages Twitter users to switch to Mastodon.

Also, federating with Twitter bridges generates a lot of performance overhead, so it is not technically feasible either.

Individual Twitter-mirroring account will not be blocked under this rule.

## Language

> You must select the appropriate language for a post.

See [here](https://fedi.tips/setting-your-language-preferences-on-mastodon-and-filtering-out-posts-in-other-languages/). This is necessary for the proper functioning of the timeline language filter. If a post is in multiple languages, choose one that represents a significant part of the post.

I will only enforce this if reported.

I am not against non-English accounts using either instance, but regional instances is very likely to work out for you better. Note that I can moderate *some* foreign languages (I interact with Chinese, Japanese and French accounts on my main).

## No spam

> Do not spam or abuse network features.

Spam includes excessive posts, favourites/boosts, and reports. "Abuse of network features" include sockpuppeting (posting the same content on multiple ActivityPub accounts), intentional disrespect of user features (using typos to bypass keyword filters), automated block detection, etc.

Business accounts are permitted, provided that they are created by the firm themselves (no SEO) and post at reasonable frequencies.

## Mastodon Server Covenant

As both instances are on the server picker, we follow [the Covenant](https://joinmastodon.org/covenant).