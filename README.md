# PlusBot
A points-tracking bot for Reddit

This bot tracks points awarded for helpful contributions in your subreddit. It was originally developed for /r/AutoModerator.

To set it up:

* Invite /u/PlusBot as moderator with at least Posts, Flair, and optionally Config permissions.
* Message me on reddit (/u/captainmeta4) so that I can accept the invitation.
* Add the enclosed snippet of CSS code found in this repository to your stylesheet, or add your own styling for those user flair classes. (I can do this myself if you give PlusBot config permission)

Please note that in order to function, PlusBot will be overwriting flairs of classless users and users whose flair classes include the word `score`. Other flairs will not be affected. If your subreddit uses non-classed flairs, they should be given a class before deploying PlusBot.
