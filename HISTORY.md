v0.4.0 - 2014/05/09
--------------------

* Complete rewrite, using ActiveSupport and separating models and collections
* New methods to handle annotations, details sets

v0.3.0 - 2014/04/16
--------------------

* New and improved methods to handle subscriptions, playlists, playlist items
* `find_or_create_playlist_by` does not yield a block anymore
* `account.subscribe_to!` raises error in case of duplicate subscription, but `account.subscribe_to` does not

v0.2.1 - 2014/04/10
--------------------

* `account.subscribe_to!` does not raise error in case of duplicate subscription
* Accountable objects can be initialized with the OAuth access token if there's no need to get a fresh one with a refresh token

v0.2.0 - 2014/04/09
--------------------

* Replaced `account.perform!` with `account.like!`, `account.subscribe_to!`
* Added `account.add_to!` to add a video to an account’s playlist
* Added `account.find_or_create_playlist_by` to find or create an account’s playlist

v0.1.1 - 2014/04/09
--------------------

* Added support for Ruby 2.0.0

v0.1.0  - 2014/04/08
--------------------

* Support for authenticated resources: Youtube accounts and Google accounts
* Support for public Youtube resources: channels and videos
* Available actions for authenticated Youtube accounts: like a video, subscribe to a channel