# Bigscreen player wrapper

A single static page for the private Bigscreen iOS app. It iframes a YouTube embed so
the player request carries an HTTP `Referer`, which YouTube has required since July 2025
(without one the player shows "Video player configuration error, error 153").

Usage: `?v=<11-character video id>&autoplay=1`.

Nothing is stored or logged here.
