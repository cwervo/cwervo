# Against Ink, Toward Universal Bits

## Ink
There's [_Magic Ink_](http://worrydream.com/MagicInk/) & then there are it's responses & extensions:
- [`4lpine`](https://johno.com/)'s [_notes on magic ink_](https://johno.com/notes/magic-ink)
- this "alternative approach" [HN post](https://news.ycombinator.com/item?id=4318154)
- this "alternative approach" [HN post](https://news.ycombinator.com/item?id=4318154)
- [Steve Krouse](https://stevekrouse.com/)'s [commentary on _Magic Ink_](https://futureofcoding.org/notes/bret-victor/magic-ink.html)
- [This fascinating thing](http://www.usabilityinstitute.com/beforeandafter/mi_books.htm) that features the quote:
> If you fully design the graphics, interaction design is not necessary!? April 24, 2007



These are all worth reading. I also think the metaphor of ink is basically the wrong abstraction.

## Bits

Let's now follow two different insstitutions Urbit & [The Center for Radical Atoms](https://web.media.mit.edu/~ishii/RadicalAtoms_ACM_Interactios.pdf)

Both of these are what I'll refer to as "packet first" groups. Urbit is fundamentally interesting in an append-only global computer with a microcomputing langauge that is shardable across n-devices. It's concerned, philosophically, with "pushing packets through a new internet".

The Center for Radical Atoms started as the Tangible Media Group's [_Tangible Bits_](https://tangible.media.mit.edu/project/radical-atoms/). It is my estimation that the move to `Radical Atoms` is really more about pushing a concept than moving _away_ from bits. The atoms are still networked.

## Universal Bits?

So what's a universal bit? It's a bit that can make it all the way from an [implantable CGM](https://global.eversensediabetes.com/) to your phone (_into your [PAN](https://en.wikipedia.org/wiki/Personal_area_network)_) to a computer in the room (RPI, laptop, NAS server, w/e). Let's stop here a moment & look around. If you're a single bit, making its way "up", then if you stopped here you'd be available to the WAN or WLAN network (e.g. `localhost:1234/index.html` -> returns `1`). So that's cool. But what if you wanted to keep going?

Let's keep going up the _powers of 10_.
- Let's say you want to share the bit with your friend who isn't on the WLAN. You'll want to get it into either your personal storage network (PSN) (synced Apple `Documents` folder, Google Drive, Dropbox, personal NAS connected to the internet, w/e). Fundamentally you want the bit to be _in the internet_. So you push it either to your PSN or to a traditional web server. Now the bit lives at e.g. `example.com` -> `1`.
- Let's say you want to push the bit up to the ISS. It turns out the [ISS has a 600 bitrate uplink](https://www.sciencealert.com/the-iss-now-has-better-internet-than-most-of-us-after-its-latest-upgrade) so you could trivially make it there. Tangent: [_Near Space Communications Reimagined_](https://esc.gsfc.nasa.gov/news/Near-Space_Communications_Reimagined) announced [`ESC`](https://esc.gsfc.nasa.gov/) which actually does way more than just ISS but manages [laser internet](https://twitter.com/NASALaserComm) & the [NASA NSN](https://twitter.com/NearSpaceNet).
- Okay, one more hop. Let's say you want to make it to the next celestial body, the moon. [There's people working on that](https://www.space.com/aquarian-space-startup-high-speed-internet-moon-mars#:~:text=Night%20Sky%20Tonight-,Startup%20Aquarian%20Space%20aims%20to%20deliver%20high%2Dspeed%20internet,the%20moon%20(and%20maybe%20Mars)&text=The%20startup%20has%20raised%20%24650%2C000,a%20lunar%20satellite%20by%202024.)
- Okay, okay, okay, really. Now we're at the end of our journey. You can, finally, get the bit [all the way to Mars](https://en.wikipedia.org/wiki/Interplanetary_Internet)

![](../assets/images/en.wikipedia.org:wiki:Interplanetary_Internet.png)

The universal bit is only possible when you decouple data from its representation.
