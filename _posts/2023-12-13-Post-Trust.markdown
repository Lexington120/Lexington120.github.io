---
layout:     post
title:      Trust
author:     Brad Greer
tags: 		post template
subtitle:  	How can we achieve trust with respect to digital information
category:   thoughts

theme: night
---
<!-- Start Writing Below in Markdown -->

# Trust

## How can we achieve trust with respect to digital information

How can we trust information that is gathered by people that are not ourselves without relying on their integrity

If someone wishes to fudge experimental results right now, it is fairly easy to do so. Simply open your CSV in an editor, change some numbers and now you have a dataset that is not accurate, yet presents identically to your peers.

We can extend this to more complicated information and more complicated editing tools. If you with to change or fabricate video and audio data, there exist many tools that allow you to do that and disguise that fact.

Much of the digital informaiton that exists today is not menually entered into a computer by a human, but created by a transducer from environmental readings.

We now have at our disposal modern cryptographic techniques that can guarantee certain information in certain contexts. How can we use these techniques to guarantee that information created by transducers can be trusted by even the people that were not involved in the experiment?

How to verify the legitimacy of information: transducers that turn environmental info to digital - in this case audio and visual information with cameras
Certified footage and audio
As it's created, information is processed by custom hardware that generates an encrypted signature with a secure private key on hardware, transforming digital data that the transducer has captured
This digital data can later be used with a public key to ensure that it has not been editied at all after being captured

After discussing with my friend Sam:

The system can never be perfect, so is it better to have more certainty in the entire data set, with some false content that is accepted as 100% true or is it better to have a distrobution of skepticism across the set of data based on factors that have been developed a long time?

The system falls apart anyway, even if implemented perfectly. Users know that no system is perfect and that there is a chance that a given piece of content that they are consuming is fake. Even if a crypto module is never broken into successfully and all verified content is actually true, if a user sees something unbelieveable, they will assume that the system has been hacked, rather than be convinced of the video

Just because the system falls apart, doesn't mean that it's not marketable. Is this ethical or does it just create more waste for no useful outcome?
