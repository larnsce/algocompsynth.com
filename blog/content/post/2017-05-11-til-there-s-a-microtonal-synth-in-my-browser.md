---
title: "TIL There's a Microtonal Synth in My Browser!"
author: "M. Edward (Ed) Borasky"
date: '2017-05-11'
slug: ''
categories: []
tags: ["Harry Parch", "microtonal music", "web audio", "Open Source Bridge", "digital sound synthesis", "just intonation"]
banner: ''
description: ''
images: []
---
[See this talk at Open Source Bridge 2017!](http://opensourcebridge.org/sessions/1976)

Did you know there's a digital sound synthesizer in your browser? There is! It's called the Web Audio API and it's accessible from any JavaScript library or framework. I'll show you how I hacked Web Audio to make microtonal music in the browser.

<!--more-->

I've long been a fan of [microtonal music](https://en.wikipedia.org/wiki/Microtonal_music), especially that of [Harry Partch](https://en.wikipedia.org/wiki/Harry_Partch), who used a [just intonation scale with 43 unequal tones to the octave](https://en.wikipedia.org/wiki/Harry_Partch%27s_43-tone_scale).

There are plenty of JavaScript libraries for accessing Web Audio, but most of them cater only to the conventional Western twelve-tone equal-tempered scale. Microtonal musicians get around this on conventional MIDI-driven digital synths by using semi-ugly hacks involving pitch bend and channel hopping.

But Web Audio is fully programmable - it's JavaScript code! I'll show you how I hack some JavaScript Web Audio libraries to synthesize music using the Partch scale in the browser.
