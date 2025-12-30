# New User Cheatsheet

Welcome! This quick reference, in lieu of a more complete guide on the sidebar, is here to help you to get started on your Mastodon presence. Let's get started!

## I got my account, now what?

Mastodon and the wider fediverse is geared towards [interactions](should-i.md#reasons-to-use-mastodon), so you're expected to post, not lurk. Therefore:

1. Learn the [basics of posting](#basics-of-posting).
2. [Write an introduction and interact with people](#basics-of-interaction).

Also, the official mobile apps are not that great, so consider using a third-party one. I use Tusky/Pachli.

## Basics of Posting

### Reach

#### What are post visibilities?

You may have seen that there is a visibility option when posting. The official documentation is [here](https://docs.joinmastodon.org/user/posting/#privacy), but the gist is:

| Visibility | Usage |
|:---:|:---:|
| Public | You want the post to reach as many people as possible. |
| Quiet Public (aka. "Unlisted") | You want your followers, and anyone directly arriving at your profile or the post, to see the post. The spread is controlled as the post can only reach more people by boosting or spreading its link. |
| Followers | You only want your followers, plus anyone you mentioned, to see the post. |
| Specific People | You only want anyone you mentioned to see the post. |

There are [additional considerations](https://docs.joinmastodon.org/user/posting/#replies) for replies.

!!! warning

    There is **no** technical obligation for any federating instance to process your posts according to your instructions (and even though the absolute vast majority of instances do, it's impossible to guarantee it for *all* instances), so you should **not** expect any confidentiality with anything you post, even if you delete them!

!!! note

    There is **no** account-wide visibility. You can use [automated post deletion](https://fedi.tips/deleting-posts-automatically-in-mastodon-after-a-certain-time-period/) but the previous warning still applies.

#### Who actually will see my public post?

For each instance you can go through [this flowchart](https://axbom.com/mastodon-tips/#flowchart), but in summary: users on an instance will only see your post if the instance is aware of it, and the awareness generally requires someone being actively aware of you (usually by following or by fetching from a thread). This is why it is very important to interact with others.

#### How can I get more people to see my post?

See [basics of interaction](#basics-of-interaction). In terms of the post itself, consider:

* Adding descriptive hashtags that are likely followed by others.
    * The hashtags should have some - but not too much - post traffic.
    * In general, do **not** invent hashtags.
    * In general, do not use underscore to split words in hashtags. You are, however, encouraged to use PascalCase to help accessibility efforts.
    * Don't overdo it.
    * Tip: if you add them on the last line of the post, Mastodon's web interface will show them as "tags" at the end. This can "hide" hashtags a bit.
* Mentioning relevant post aggregators. See [Guppe groups](https://a.gup.pe/) or [ovo.st](https://ovo.st/) (for Chinese users).
* Using [alt text](#what-is-alt-text).

!!! warning

    You have probably heard that [the  "algorithm" here is the user filters](should-i.md#no-algorithm) and the mute user function.

    Please do not deliberately censor words or use algospeak to bypass that "algorithm." You should not force others that are not interested in your topic to read your posts.

#### Additional considerations

* [Don't use link shorteners](https://fedi.tips/you-dont-need-link-shorteners-on-mastodon/); all links count as 23 characters.
* Do remove unnecessary query strings in links though, whenever practical to do so.

### Features

#### What are content warnings?

See [here](https://docs.joinmastodon.org/user/posting/#cw), but in summary: you can hide your post content under a spoiler so that viewers are prompted to open it manually. You can also set your media as sensitive, and the media will be blurred for others.

[Instance rules](rules.md#nsfw-content), including those of other instances, require you to apply them for NSFW content, or content that may cause psychological distress among general audiences.

You are urged to consider your audience's viewing preferences when determining whether you should apply CW on other posts.

!!! warning
    
    [You are **not** allowed to post NSFW content on mstdn.plus.](rules.md#for-mstdnplus)

#### What is alt text?

Alt texts are generally used for visually-impaired users to help understanding your media. When you compose a post, you're [prompted](https://docs.joinmastodon.org/user/posting/#media) to add an alt text to describe them. This is commonly adopted on Mastodon, and while you are not obligated by rules, writing them often facilitates interactions. See [here](best-practices.md#alternative-text) for more information and ways to help you write one.

## Basics of Interaction

### Tips for Initial Traction

!!! note

    Your bio is searchable if you have opted into the user directory, but hashtags don't particularly improve your profile's exposure. Note that certain platforms (such as bots that read `#nobot` hashtags, as well as [fediverse.info](https://fediverse.info/explore/people)) do make use of hashtags in bio.

If you want to have more people discover your account, consider the following:

* There are toggleable settings in Preferences => Public Profile => Privacy & Reach.
* Outside of Mastodon itself, there are public user directories; see [here](how-to-follow.md#how-to-follow-people-and-content).
* [Follow relevant hashtags](how-to-follow.md#how-to-follow-people-and-content) and [interact with other users](should-i.md#you-want-to-interact-with-others) (keep on reading for best practices for the latter). Others need to know you're there before they will consider to follow you.
* Write an introduction post.

#### I need to write an introduction?

It is the convention for new users to introduce themselves to others. Essentially you write a [public](#what-are-post-visibilities) post with `#introduction` which, well, introduces yourself. You should also [pin](https://docs.joinmastodon.org/user/discoverability/#pinned) the post to your profile. See the hashtag for examples.

You should [include relevant hashtags](#how-can-i-get-more-people-to-see-my-post) to attract others that have similar interests.

### How can I see more content?

See [how to follow](how-to-follow.md).

### What can I do on a post?

You can:

* Boost: this is equivalent to "retweet." You can apply [the same visibility options](#what-are-post-visibilities) to boosts. Note that if you choose to boost follower-only, the author will be notified of your action and the boost count will be incremented, but others viewing the post cannot see that you boosted by clicking the boost count.
* Favourite: the author will be notified of your action and the favourite count, and others viewing the post can see that you favourited by clicking the favourite count.
* Bookmark: this stores the post in your bookmarks. The action is only visible to you.
* Reply.

If you want to give a post more reach, then the appropriate action is to boost. However the decision rests with you.

#### Why can't I see everyone that boosted/favourited?

Unless the post is authored from the instance, an instance can only see boosts/favourites that it sees. For boosts see [here](#who-actually-will-see-my-public-post); for favourites it's only those from users on the instance.

### Anything I need to know before I reply?

* If not all replies are shown...
    * Wait for the instance to fetch the thread (it takes a few seconds and the web interface will show "More replies found"; on other clients you will need to refresh the post manually), or
    * Open the original page.
* Read the room. Be mindful of
    * the context (the author's profile can also be important); and
    * whether what you're about to reply is already there;
* Respect people's boundaries;
* [Don't be a reply guy](best-practices.md#reply-guy);
* [Keep the cool on controversial or distressing topics](best-practices.md#politics).
