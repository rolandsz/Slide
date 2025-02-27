## Current project status

This fork contains build fixes, and it also extends the technical documentation with the location of the client ID.

This project will be on indefinite hiatus for the foreseeable future, and may not be maintained.
Updates are not guaranteed.
See [here](https://github.com/Haptic-Apps/Slide/issues/3449) for details.

You may continue to use Slide if you so wish.
However, with this said, it would be recommended to consider migrating to another (more stable) Reddit client.

Some other open-source (and internally ad-free) Reddit clients include:
- [Infinity For Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit)
- [RedReader](https://github.com/QuantumBadger/RedReader)
- [Dawn](https://github.com/Tunous/Dawn)

# Slide

<img src="app/src/main/res/drawable/ic_launcher.png"
    align="left" width="180" hspace="10" vspace="10">

Slide is an open-source, ad-free Reddit browser for Android.
It is based around the [Java Reddit API Wrapper](https://github.com/mattbdean/JRAW).

Slide is available on the Google Play Store and F-Droid.

<a href="https://play.google.com/store/apps/details?id=me.ccrama.redditslide">
    <img alt="Get it on Google Play"
        height="80"
        src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" />
</a>
<a href="https://f-droid.org/app/me.ccrama.redditslide">
    <img alt="Get it on F-Droid"
        height="80"
        src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" />
</a>

There is an active community for Slide on the
[/r/slideforreddit](https://www.reddit.com/r/slideforreddit) subreddit,
which anybody is welcome to join.

There is also a [Discord](https://discord.gg/hVWAY8A).

## Sponsors

Thank you to our awesome Github Sponsors, who help keep the Slide project going.

|  | GitHub profile |
| --------- | ------------- |
| **KevinNThomas** | https://github.com/KevinNThomas |
| **andrewkdinh** | https://github.com/andrewkdinh |

If you're interested in sponsoring our work, check out the sponsor slots for Slide contributors on the right-hand **Sponsorship** menu.

## Contributing

### Issues

In any project it's likely that a few bugs will slip through the cracks, so it
helps greatly if people document any bugs they find to ensure that they get
fixed promptly.

You can view a list of known issues and feature requests using [the issue tracker](https://github.com/Haptic-Apps/Slide/issues).
If you don't see your issue (or you aren't sure), feel free to [submit it!](https://github.com/Haptic-Apps/Slide/issues/new).

Where appropriate, a screenshot works wonders to help us see exactly what the issue is.
You can upload screenshots directly using the GitHub issue tracker or
by attaching a link (to Imgur, for example), whichever is easier for you.

### Translations

If you are able to contribute a translation into a language missing from Slide,
or spot any room for improvement in an existing translation, we greatly
appreciate anything you can assist with!

[The project uses Crowdin](https://crowdin.com/project/slide-for-reddit),
a platform that allows anybody to contribute to translating the app with as many words at a time as they want.
Crowdin provides a nice interface for translating, and no knowledge of the code is needed.

### Code

If you are a developer and wish to contribute to the app, please fork the project
and submit a pull request.

If you have any questions, feel free to
[ask in the `#android-dev` Discord channel](https://discord.gg/HeShMsX) or
[drop me a message](https://www.reddit.com/message/compose/?to=ccrama) on Reddit.

If this is your first time contributing to the project and want to tackle an
easy issue, take a look at the issues labelled [`Good First Issue`](https://github.com/Haptic-Apps/Slide/issues?q=is%3Aopen+is%3Aissue+label%3A%22Good+First+Issue%22).
These issues have been marked as such because we believe they are easier to fix than other issues.

If you would like to experiment with the application for educational purposes, you can change the default client ID in the following files:
1. [Authentication.java#L34](https://github.com/rolandsz/Slide/blob/master/app/src/main/java/me/ccrama/redditslide/Authentication.java#L34)
2. [Login.java#L49](https://github.com/rolandsz/Slide/blob/master/app/src/main/java/me/ccrama/redditslide/Activities/Login.java#L49)
3. [Reauthenticate.java#L39](https://github.com/rolandsz/Slide/blob/master/app/src/main/java/me/ccrama/redditslide/Activities/Reauthenticate.java#L39)

## Changelog

The file [CHANGELOG.md](CHANGELOG.md) provides an overview of the changes for a
release; for a more detailed look at changes to the app, [view individual commits](https://github.com/Haptic-Apps/Slide/commits/master).

## Licensing

Slide is licensed under the [GNU v3 Public License](LICENSE.txt).
