# The 20XX Melee Training Hack Pack

![](https://www.mediafire.com/convkey/8bdd/615m44nykd009r4zg.jpg?size_id=4&hash=d89e125dd6e0b507e576c008c4d632c8)

# [Download]()

## Contents
 - [About](#about)
 - [FQA](#fqa)
 - [In Game Commands](#in-game-commands)
 - [Building](#building)

***

## About
This is version 5.0.0 of the community-made redeux of Super Smash Bros: Melee with tons of quality of life features like bugfixes, higher fidelity textures, native widescreen support, a debug menu, and NTSC v1.02.02 with more storage space for `.dol` injections. It also has many more quality of life features for tournament play like stage striking and hiding non-tournament legal stages, tournament default settings, and UCF. It is also suitable for practing solo with things like save states, the ability to make the AI do repeated moves, and the ability to toggle the visibility of collision boxes in game.

There's much more to it than that though.

The project is--and will be--fully compatable with slippi.gg's rollback version of Dolphin. You can download the ISO [here]().

***

## Frequenty Questioned Answers
### Why? And why through git?
I've never really been pleased with the accessibility of getting a copy of 20XX--or rather the lack of accessibility. But one thing I can fix is the ease of getting a copy. In the past, people have been hesitant to release versions of Melee for piracy reasons. It's an open secret what was happening though: people were torrenting potentially-unsafe copies of Melee and then patching them. It is irresponsible to expect people who frankly may not know that much about computers to get a legitimate torrent client, safely obtain a torrent of Melee, and patch it.

But packaging it like this makes it much less likely for a copyright strike to happen, and it's safer for people who *just want to play Melee*.

### Version 5? What's changed?
Well, it's been a little over three years since Achilles1515 released version 4.07++, and there have been few changes in what the community has done, but the changes that have happened since then have been significant.

 - Early in 2020, DRGN [introduced](https://smashboards.com/threads/ntsc-1-02-02-expanded-dol-more-space-for-custom-codes.453112/) a new patch to the NTSC `.dol` which he calls NTSC 1.02.02. It radically changes the amount of space we can allocate for `.dol` injections. All-in-all there's about 60 kilobytes more space, which is an 84% increase!
 - At the beginning of 2019 Cherrim [started working on](https://smashboards.com/threads/remastered-stock-icons-pack.482675/), more accurate, higher quality stock icons. They've continued updating and refining the icons into 2020.
 - At the start of 2019, Dan [made](http://www.20xx.me/ucf.html) a big change to the dashback calculation in the UCF code, and implimented a bugfix that affected Nana.
 - In the middle of 2017, Stache [finished](https://smashboards.com/threads/hd-texture-pack-for-20xx-for-dolphin-current-ver-4-07.448549/) expanding on the HD texture pack that UnclePunch [started](https://smashboards.com/threads/melee-hd-texture-pack-dolphin-v1-01.438813/) back in 2016.

Even though there have only been four advancments in community-created content, I think it's clear they have been major.

### So, why not version 4.08?
My hope here is to take the project into a new direction at the turn of the decade. Achilles certianly made this project possible, but he uh... hasn't been very good at versioning. As far as the public is concerned, the first version of 20XX was version 3, and the last two versions were called 4.07 and 4.07++. Not exactly the most elegant. With this new version, (version 5) I plan to impliment [semantic versioning](https://semver.org/spec/v2.0.0.html) to keep everything straight and orderly.

### SemVer? Seriously? That's just a fad.
Well... maybe. But it's a pretty good fad. And while it may not be a perfect fit since this project doesn't have any dependencies to speak of, there still are features we might add or remove that could justify a bump in one of the last two digits. One thing to bear in mind is that semantic versioning states *"even the tiniest backwards incompatible changes to the public API require a major version bump"* so if even 1 button is remapped to something else, that would be a version change. It's not as useless with a project like this as you may think.

### No PAL support?
The PAL region has really outlived its usefulness. There was a time, when Gamecubes in Europe and Australia were running their games natively at 50Hz on CRT's, but now-a-days the *vast* majority of Melee players have access to a 120Hz+ monitor, and are playing on emulators. On PC, Dolphin and its derivatives are perfectly able to play NTSC Melee at widescreen 480i60 regardless of where on earth you might be. The same is true of a modded Wii or WiiU. They'll be running nintendont, which again, is able to run NTSC flawlessly at 60 FPS.

### Widescreen?! What's wrong with you? What about our history!
Yeah. I get it. CRT good. But look it's the end of 2020. LED monitors are lagless now and refresh at the same-or-higher rates as most CRT's. If your stupid BENQ 144Hz monitor is good enough for the newest Cawaduty game, or VALORANT, or whatever, then I promise it's good enough for Melee. Move on.

***

## In Game Commands
![](https://i.imgur.com/YbOvw80.png)

***

## Building
Build instructions coming soon.
