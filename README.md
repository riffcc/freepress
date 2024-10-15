# freepress
Decentralised WordPress plugin marketplaces for Orbiter. 

Don't fork, rescue.

THIS IS NOT READY YET IN ANY WAY

https://x.com/riffccproject

## What this is NOT
* An attack on WordPress, Automattic or anyone associated with
* A fork of WordPress

## What is FreePress?
FreePress is a decentralised plugin marketplace system for WordPress, built using something called Defederation (which we use Orbiter to achieve). Or, we hope, it will be.

(We still need to build it!)

## What this is so far
This is vapourware until we prove otherwise! We'll start to form this into a real thing in this repo and start asking for comments.

## Why is it called FreePress?
It's intended to reduce the risk of centralised plugin marketplaces like WordPress.org, while still allowing plugin authors to distribute plugins and own their own destiny and work.

## How will it work?
* Users will be able to host an Orbiter Lens, or pay someone else to host one for them.
* Users will be able to use their Lens to upload their own plugins.
* Each Lens may follow other Lenses to build up a single library of plugins.
* Users can search across multiple Lenses to find plugins - in fact, if Lenses mutually follow each other, they will each look like a single Lens, with all plugins from both.
* We'll initially upload all confirmed open source plugins to FreePress, and then once ready, start enabling new uploads.
* We'll also have a process for authors to prove themselves as the original authors of plugins, then have our plugin removed from our Lens and added to a Lens of the authors choosing - which then allows authors to completely control their own plugin distribution and sign new releases.

Lenses are free to host and run, and are just HTML/JS so can be deployed to GitHub Pages. If you want to see an example of a lens, see https://orbiter.riff.cc - it'll show you what a Lens-based distributed streaming service could look like.

The only real cost of a Lens is the domain name, plus the cost of your content itself. Orbiter runs in-browser using OrbitDB, so there's (almost) no server at all and no infrastructure costs.

## But moderation?
Yes! So, the idea is that since each lens has to follow other lenses, simply put, you only follow lenses that "fit your vibe" - in other words, match or close-enough match your own ethics, moderation and copyright policies and so on.

FreePress (and Orbiter in general) is designed to use the existing *trust rails* that you already have, instead of trying to create a new global truth. As such, each site moderates their own content and conduct, and each Lens is responsible for the content it hosts. Lenses with a tendency to fall to spam, toxicity or worse will end up being gently removed from the community by simply being defederated from other Lenses who disagree with their moderation choices.

## So that means viruses aren't allowed?
Orbiter reduces the risk vs an unmoderated marketplace. It's not a perfect solution, but generally speaking people won't want to jeopardise their Lens by hosting malicious content. At the same time, it provides a better balance than WordPress.org does today.

## What's the difference between Orbiter and FreePress?
Orbiter is just a platform for applications (such as Flagship, which is what we call "riff.cc" itself now, our flagship Lens). FreePress is one of the first alternate use cases being built out for Orbiter, largely in response to issues between WordPress.org and plugin authors.

We feel there's a better way to make a plugin marketplace, we're going to try and build it in the open for anyone to use.

## Other plans
We can do private IPFS retrieval links, so there should thus be also a way to do a paid plugin marketplace for WordPress plugins. We're talking to some plugin authors about how best to do this at the moment, and will be patiently and carefully listening to and responding to feedback.

*Everyone has the right to freedom of opinion and expression; this right includes freedom to hold opinions without interference, and to seek, receive, and impart information and ideas through any media regardless of frontiers.*

## Credits
* Thanks to everyone in the WordPress community for the kind words.
* Thanks to the Orbiter team.
