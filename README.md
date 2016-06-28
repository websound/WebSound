# WebSound

## Purpose
The purpose of this repository is to publish & maintain WebSound project definitions, goals, legal information, and discuss upcoming events.

## Project Description
####The Web Platform is the Universal Instrument.

WebSound is an iterative solution to the ['death of people's music'](https://blog.andyet.com/2014/02/26/Pete-Seeger-lessons-learned-from-a-hard-link-to-the-old-world) problem, driven by long-term community engagement and Web Audio/MIDI tool versioning.
* **Blog tl;dr** – Recording technology and the commercial music industry have homogenized and destroyed indigenous folk music collaboration and expressions throughout Western Civilization. Pete Seeger and a handful of others were a valuable bridge to understanding our now non-existent forms of community music and how they can flourish in a post-commercial culture. Web Platform technologies are opening the potential of building common collaborative interfaces and services which can be used as a bridge away from commercial music culture–back to 'indigenous' music making experiences in a globalized context.

####Tools 
WebSound tooling will take 3 fundamental divisions of development over time as the specifications and APIs it relies on are further built and integrated until they are stable enough to ship cross-platform for public use:

**1. Web MIDI driven remote performance and collaboration.**
* Web Applications that act as transceivers of MIDI information across multiple nodes in a global mesh network using [P2P](https://en.wikipedia.org/wiki/Peer-to-peer) [WebRTC](http://www.webrtc.org/) [DataChannels](http://www.html5rocks.com/en/tutorials/webrtc/datachannels/) which enable users to collaborate and perform remotely. These aim at optimizing traditional collaborative performance methods, and to support new network-oriented contexts of musical expression and compostion. (eg. [Composing Music with Recurrant Neural Networks](http://www.hexahedria.com/2015/08/03/composing-music-with-recurrent-neural-networks/))
* Web Audio/MIDI support modules for common audio generation tools, languages, and [DAW](https://en.wikipedia.org/wiki/Digital_audio_workstation)s. We want to support data streams to and from:
    * [Ableton Live](https://www.ableton.com/en/live/new-in-9/), [Logic Pro](http://www.apple.com/logic-pro/), [Pro Tools](http://www.avid.com/us/products/family/pro-tools), [Reason](https://www.propellerheads.se/reason?gclid=CMuUvtv6zcgCFYVhfgod9sYMQw), [FL Studio](https://www.image-line.com/flstudio/), [SuperCollider](http://supercollider.github.io/), [MaxMSP](https://cycling74.com/products/max/), [PureData](https://puredata.info/https://cycling74.com/products/max/), [CSound](https://csound.github.io/about.html), [Faust](http://faust.grame.fr/about/), [ChucK](http://chuck.cs.princeton.edu/), etc.

**2. Common UI Optimization for Audio/MIDI performance input and manipulation.**
<BR/>Refactored common computer interfaces (keyboard, mouse, trackpad, touchscreen) as inviting, kinesthetic, and useful performance controllers.

**3. DAW for distributed recording projects and live remote performance tracking.**
<BR/>A repository hosting service featuring version control and source management for audio recording projects in a multi-tracking format.
* Long-term (_very long term!_): Concurrent distributed audio recording with 24-bit/192kHz high-resolution streams (only this or greater will bring professional record engineering to the Web Platform).
* Integrated DSP tooling and instrument components: popular synthesis/synthesizers, complex/VST sampling, professional audio engineering "plugins," audio/MIDI effects processing.

####Why MIDI?
MIDI is the universally accepted protocol for musical instrument interfacing and performance data interchange–and has been the common-denominator in digital music since its standardization in 1983. In the present day it's not an uncommon practice to facilitate a conversation between 50 years of musical devices with [MIDI to CV conversion](http://www.soundonsound.com/sos/1995_articles/mar95/midi2cvconverters.html)–and incredible feats of compatibility will continue commonly and in greater frequency as the Web Platform utilizes it in powerful ways. Performance optimization will be constant, but there is no need for another musical instrument protocol.

####WebSound Ethos
Max Mathews spurred on a generation of computer musicians by declaring that the Nyquist-Shannon “sampling theorem shows that there are really no limits to the sounds you can make from many samples. Any sound the human ear can hear you can make with the right number, accuracy, and combination of samples–so that the computer is a universal musical instrument.” With endless discrete musical devices and applications built for individual expression since this was published in the early 1960’s, communal collaboration (of the “folk” nature) has been left adrift–even in the web platform. This problem is not native to the web, but parallels our massively commoditized, product-driven music culture which leaves little room for all-ages/all-skill-level interaction when being clobbered by a powerful commercial entity saying that the ‘most-valuable’ musical action is to “put on a big show and get famous.”

Still: we’re at the negative vertex of a parabolic cultural track–and the web is going to take us back to the authenticity of the indigenous musical collaborations of the pre-recording world. I can see a world coming where folk music and musical works are not identified by distributed physical regions, but distributed data regions and indigenous peer to peer networks. From world class performers to small-town grade school students–from recording engineers, to homeless people with access to the internet at a local public library: collaboration and creative exposition will be made available to everyone with no hinderances from class or personal ability.

We will take what Mathews said a step further and say that the Browser is the universal musical instrument, being the most powerful cross-compatible runtime in history–and through the Web Audio and MIDI APIs: we are on the verge of a new renaissance in musical interaction and collaboration which can redo what the commercial recording industry has undone.
