Title: Hello
Category: random
Tags: site,about

There's tension between adding some content or working on how the site
looks. I guess I'll add some content first, and worry about looks
later, so here I go:

I let the [previous version of
think.random-stuff.org](https://web.archive.org/web/20201124054151/https://think.random-stuff.org/
"Internet Archive copy of think") go quiet a long
time ago. The most recent post was June, 2015 and the site went
offline in late 2020. We'll see how long this one lasts.

Given the mixed (i.e. random) nature of the things I'll be posting,
it's invariable that there will be parts of the blog that are too
technical for most. I'll keep the technical content mostly separate
from the non-technical, but for this post, there's some stuff you may
want to bleep past.

-------------------------------------------------------------------------------

There was some internal debate (yes, I talk to myself) about how to
host this. After poking around a bit, I settled on Pelican as the site
generator (the old one was Wordpress) so I could dip my technical toe
into the static hosting waters.

Then I did some tests with [Ubuntu](https://ubuntu.com) and the [Caddy web server](https://caddyserver.com) on a
[Digital Ocean](https://www.digitalocean.com) droplet as well as  with [Netlify](https://www.netlify.com) pulling from [GitHub](https://github.com).

I really like Caddy. But I really don't like Ubuntu[^1]. I used to run
[FreeBSD](https://www.freebsd.org) servers on Digital Ocean but they seem to have dropped the
ability to create new FreeBSD droplets. I tried using an old FreeBSD
12.1 snapshot but I found myself futzing around too much trying to
bring it up to 12.4. I looked around for other FreeBSD hosting, [Vultr](https://www.vultr.com)
looked good, but then I thought I should try Ubuntu on Digital
Ocean. I got it up and running quickly and installed Caddy from the
[Debian](https://www.debian.org) apt repo.

In parallel I tried the GitHub repo and Netlify combination which
turned out to be the winner. I can always move to self-hosted pretty
quickly.

I want to have a lot of photos on this site so that meant I had to decide
whether to host them myself or elsewhere. I had a mostly unused
[Flickr](https://www.flickr.com) account so I played with embedding images from there. Flickr
provides embed codes and I think I can live with the overlays it puts
on the photos for a few seconds when they are first displayed.

[^1]: Mainly I bristle at what I see when I run 'ps' on a brand-new
install of Ubuntu. There's so much cruft running! Doing the same on a
FreeBSD system is a breath of fresh air.

-------------------------------------------------------------------------------

I'll leave you with a photo:


<a data-flickr-embed="true"
href="https://www.flickr.com/photos/allandoyle/52182937488/in/datetaken-public/"
title="Chipmunk eating a blueberry"><img
src="https://live.staticflickr.com/65535/52182937488_74cd08f9a1.jpg"
width="354" height="500" alt="Chipmunk eating a blueberry"></a><script
async src="//embedr.flickr.com/assets/client-code.js"
charset="utf-8"></script>
