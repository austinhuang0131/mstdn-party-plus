# Should I use Mastodon?

!!! note

    Please read the [prologue](prologue.md) first for key assumptions that apply to this page.

In summary:

* Mastodon is, at the end of the day, another social media platform. Using Mastodon alone does not free you from the ills of the general design of social media platforms.
* Although Mastodon is an improvement from many other platforms, those improvements have often been [overstated](#some-discussions-on-others-arguments).
* Your Mastodon experience greatly depends on *you*. You have to put in the work and think [outside the box](#you-are-open-minded-and-want-to-learn).

## Reasons to use Mastodon

### You want to interact with others

From [Exodus: moving to Mastodon](https://quantixed.org/2024/08/14/exodus-moving-to-mastodon/) by Stephen Royle:

> The platform is truly focussed around discussions and interactions. It is not about getting people fired up to argue with each other. I think this is the final hurdle with getting people to use Mastodon.

Despite changing landscape after the Twitter exodus, this has been mostly held true. However, do note that Mastodon is not magically healthier (I have certainly seen heated arguments): you have to put in the work.

### You are open-minded and want to learn

The fediverse has many diverse perspectives. Although sharing similar universal values - that is, you are unlikely to meet someone that is holds *polar opposite* beliefs to you (because of general appeal of the fediverse, but also due to [instance biases](#no-algorithm)), often you will find disagreements in some of their positions, mainly because they have different backgrounds, experiences, identities, etc. and:

* some attributes (eg. being racialized or queer) mean that by experience, they have differing opinions from the mainstream, and that you will usually not encounter them on conventional platforms; and
* some attributes imply different expertise or personal stake in topics they're involved in;
* norms on Mastodon and the wider fediverse is significantly different than those of other platforms, for example: [alt text](best-practices.md#alternative-text), [content warnings](https://community.hachyderm.io/docs/hachyderm/content-warnings/), etc.

Always assume there is something they know but you don't. Don't be a [reply guy](best-practices.md#reply-guy). 

Of course, that is not to say that others are always correct. Misinformation or extreme opinions can be developed (again, [often for reasons you might agree with](#no-algorithm)), and it is often difficult to challenge them. However, it is the author's opinion to advise new users to abide by the Golden Rule and consider the recipient's background, even in such scenarios.

### You have strong interests, and want to see contents relevant to them

If you have a specific niche hobby - eg. in arts, games (like tabletop ones), technology (like ham radio), etc. - that you invest a lot in, then using an instance catering to such may be beneficial to you. There are also instances catering to specific scientific communities.

Unfortunately, for the vast majority of people who have no such interests, this does mean that content-wise, the fediverse may not be so different from conventional platforms, unless you intentionally work to discover such interests.

## Reasons to not use Mastodon

### You rely on network effect and/or monetization

Unless you already have a large, loyal audience (eg. popular political commentators originating from Twitter) or, for businesses, you cater to niches (especially nerdy or artistic ones), it may be difficult to get traction, as traditional SEO techniques only apply loosely, and [there is a consensus to interact genuinely](#you-want-to-interact-with-others). Many users and administrators are also wary of monetization efforts.

You can, however, use hashtags to increase your posts' visibility.

### You only follow and not post

Many users are skeptical of others trying to follow them without filling out profile descriptions or writing any non-reply posts. Some insist that you must write an `#introduction` or fill out your bio.

### You want to act

[Mastodon is a bubble.](https://wingolog.org/archives/2024/09/24/fedi-is-for-losers) Sure, it is a more progressive bubble, but it is a bubble (well, more like many small bubbles inside a large bubble), like every other social media. This is especially so due to the prevailing moral convictions of the user bases. Owing to reputational concerns I will not elaborate further, but if you want to go out and change things, then go out and change things. No social media can replace concrete action.

Donating to "mutual aid" campaigns on the fediverse is acting; discourse is not.

## Some discussions on others' arguments

### Non-commercial

Most English-speaking instances are non-commercial and rely on donations. While in practice this has sustained for a long time, keep in mind that:

* Money can run dry, especially if the administrator experiences unexpected personal hardships (however a good instance will very likely donate);
* Even if money did not run dry, administrators can experience burnouts;
* The fediverse has mostly survived due to non-enforcement of privacy & content regulations, as well as the lack of legal bases, be it intentional or impracticality; in other words, should they ever be enforced, many instances may find themselves in legal limbo;
* Instances can still be acquired by commercial interests (eg. the sale of three Japanese-speaking instances to Suji Yan due to regulatory and financial problems). There is also [nothing preventing an instance from selling out your data](#privacy).

Furthermore, commercial actors in the fediverse are not unknown:

* Commercially-operated instances (like Threads, `me.dm` for Medium, etc.) and ActivityPub integrations of conventional platforms (like Flipboard and possibly Tumblr) exist;
* Certain non-profit efforts (eg. Nivenly) to improve aspects of the fediverse may be funded by commercial interests.

...for which there are different opinions among users on the appropriate approach to them.

All in all, the non-commercial nature of the fediverse is fragile and the legacy, while mostly positive, has some imperfections.

### "No algorithm"

There is little algorithmic personalization in the fediverse: the only known use of that is follow suggestions, which displays some follow-of-follow. You can use [text-based filters](https://fedi.tips/filtering-your-timeline-to-hide-posts-on-mastodon/) or mute accounts to apply personalization.

Most feeds are chronological (1), and the trending feed is based on total interaction counts seen on the instance, decayed by time. While the feeds are not strictly personalized (beyond explicit actions by the user), many fail to realize that by [current technical implementations](https://axbom.com/mastodon-tips/#flowchart) result in that **the feeds are biased by the instance's views of, and interactions with, the fediverse, which then reflects the user makeup of the instance.** This could be beneficial in interest-specific instances, but might be detrimental in more general instances. [Ultimately this falls back to the general "echo chamber" nature of all social media platforms.](#you-want-to-act)
{ .annotate }

1. ...which can be gamed using the scheduled post feature, but that's a different matter.

### Moderation

You get to choose your instance, thereby choosing the moderation you're subject to, but:

* Moderation processes of most instances are not transparent, and it is difficult to determine their reputation beforehand, even more so when [instance biases](#no-algorithm) empowers people to vigorously defend their own instances even in the face of serious allegations;
* When moderation controversies do arise, they tend to be *very serious*. See: [Fosstodon](https://mastodon.social/@lo__/114370692797365997), [mastodon.lol](https://www.reddit.com/r/Mastodon/comments/10y6yb0/mastodonlol_instance_shutting_down_in_3_months/), etc.
* Migrating your account is far from painless: you will leave behind your posts (1) and may lose followers due to difference in blocks or even network issues. It also takes a while to be able to refollow everyone, since some instances place limits on the ability for newly-created accounts to interact.
    { .annotate }
    
    1. ...save certain Misskey forks that allows you to carry your posts with you

### Privacy

Most fediverse instances do not attempt to analyze your behaviour (other than what's already done in Mastodon itself) and do not collect your data beyond what you explicitly provide. However, this still requires you to trust your instance operator, since they can still see your personal information (email, IP addresses, etc.).

The other, more invisible concern on privacy is to what extent third parties can collect or use your posts. Despite the technical and legal nature that public content is, well, public, many thinks that they have more control of their content than there really is. There is a strong consensus that *any* collection of public data, even in good faith (eg. to improve discoverability or interoperability), should require strict opt-in consent, notably [on the controversy regarding Bridgy Fed's Bluesky bridge](https://github.com/snarfed/bridgy-fed/issues/835). Developers insist on [protocol](https://mastinator.com/apology/) [design](https://mastodon.social/@akurilov/114343771754860533), while users insist on the potential of misuse, with both sides often overreacting. In fact, Mastodon did not have search for many years due to the [belief](https://mastodon.social/@Gargron/4947733) that full-text search supports harassment and, as you know, it was eventually implemented as an opt-in feature.

Does it really protect privacy or is it just gesturing? Certainly none of the above protects a truly malicious party from using an ActivityPub instance to scrape everything, so there is certainly an overstatement of how much privacy people really have here. But developers should also be aware of the cultural norms.