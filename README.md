# LOTR_Film_Trilogy-Subtitles

## About this repository

This repo was created to find the errors that were made when these subtitles were OCR'd. The subtitles were in the Blu-ray PGS format, ripped from Blu-rays.

From what I've observed, the most errors arose when OCRing non-Latin-based languages. In this case, Japanese, Chinese, Greek (a lot of errors), Korean, Russian, and Thai.

## How to use

First, if you don't intend to watch it with the movies, you can just read it here on GitHub or download it and read it with your preferred program.

But if you do, the most permanent solution is using a multiplex tool to join it with the video, audio, and possibly other subtitles already on there.

If you just want a temporary solution, you can search in your media player, in the subtitle chooser menu or similar, for an option where you can *Add* or *chose* a *subtitle file*.

## Combining instruccions

Thanks to genekellyjr/LOTR-Subs for the instructions.

Before you start, these are the instructions for the 1080p Blu-ray. The instructions for the 4K edition and the 1080p remastered (which is a downscaled 4K version) may be different.

### The Fellowship of the Ring Extended Edition

The 1080p version of FOTR released has an incorrect color throughout the whole film. You can watch it perfectly fine, but the colors aren't as they should be.

Per 44rh1n @ https://originaltrilogy.com/topic/44rh1ns-The-Fellowship-of-the-Ring-Extended-Edition-Color-Restoration-Released/id/61952:

> Both the official Blu-ray and Digital-HD releases are affected. Not only does this new master suffer from an ugly green tint throughout the entire course of the film, but it lacks important visual details in the bright highlight and dark shadow areas as well. In addition to these problems, it appears that the original color timing, in many instances, has actually been completely tossed aside; in several areas there are stray power windows (masks used in the color grading process to select certain areas of the frame), and the lack of HSL qualifications (custom selections of specific hue, saturation, and luminance values) that result in a muddier color grade than the original DVD release.

Because of this, it's best to acquire a color-corrected version of this film, the most complete being 44rh1n's "The Fellowship of the Ring" Extended Edition Color Restoration. Which can be acquired by contacting 44rh1n or SnooPac on Original Trilogy and providing evidence that you own the film's Blu-ray. To combine it, the V2 version is recommended, since it's separated like the original Blu-rays.

#### Combine

> * In MKVToolNix "Add as new source files..." the disc 1 movie, the d1 color corrected mkv, and either the d1 translated subs (can add them after combining tho via the combined subs) or directly go for the combined (do not append d2 trans subs to that). Then "Append" (right click thing you want to append to, choose Append) the d2 movie to the d1 movie, the d2 color corrected to the d1 color corrected, and the d2 subs to the d1 subs.
>
> * In MKVToolNix go to the Output tab's Splitting section set the Split Mode to "By parts based on frame/field numbers".
>
> * Put in the box: `-151968,+152138-`
>
> * Click "Start multiplexing"

### The Two Towers Extended Edition

> * In MKVToolNix "Add as new source files..." the disc 1 movie and either the d1 translated subs (can add them after combining tho via the combined subs) or directly go for the combined (do not append d2 trans subs to that). Then "Append" (right click thing you want to append to, choose Append) the d2 movie to the d1 movie and the d2 subs to the d1 subs (if not adding in the combined subs later).
>
> * In MKVToolNix go to the Output tab's Splitting section set the Split Mode to "By parts based on frame/field numbers".
>
> * Put in the box: `-153368,+153450-`
>
> * Click "Start multiplexing"
>
> *Note that I got a warning about indexes being bad or something from MKVToolNix but everything seems fine. I got the warning for doing it in the 1 shot method and appending the seperately split files (split d1 at 153368, split d2 at 24, then append without any splitting), so seems no way to avoid but no problem either.*

### The Return of the King Extended Edition

> * In MKVToolNix "Add as new source files..." the disc 1 movie and either the d1 translated subs (can add them after combining tho via the combined subs) or directly go for the combined (do not append d2 trans subs to that). Then "Append" (right click thing you want to append to, choose Append) the d2 movie to the d1 movie and the d2 subs to the d1 subs (if not adding in the combined subs later).
>
> * In MKVToolNix go to the Output tab's Splitting section set the Split Mode to "By parts based on frame/field numbers".
>
> * Put in the box: `-183583,+183686-`
>
> * Click "Start multiplexing"
>
> *Note that I got a warning about indexes being bad or something from MKVToolNix but everything seems fine. I got the warning for doing it in the 1 shot method and appending the seperately split files (split d1 at 183583, split d2 at 24, then append without any splitting), so seems no way to avoid but no problem either.*

