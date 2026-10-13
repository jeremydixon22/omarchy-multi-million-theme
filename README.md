# Multi-Million

An Omarchy theme from [*The Multi-Million Dollar OS*](https://x.com/ocdjeremy/status/2109445974771064978): the end-title frame and the film's CG sequences as backgrounds, and the film's palette for every app.

```sh
omarchy theme install https://github.com/jeremydixon22/omarchy-multi-million-theme
```

## Palette

The colours come from the cut:

- **Background `#130f18`:** the end-title frame's shadows.
- **Accent `#9ece6a`:** the maze-cube green, also used for window borders.
- **Blue `#3791ff`:** the CRT terminal blue of the opening card.
- **White and cyan:** the CG wireframes.
- **Red:** the readout digits.
- **Gold:** the flare.

**Checked with [lyingterminals.com](https://lyingterminals.com/): A+.** All 15 text colours and the foreground clear 4.6:1 on the background. Every bright colour is brighter than its normal twin, and bright black (comments) is 5.2:1.

The site's one finding, "black: 1.00:1", comes from Omarchy, which sets ANSI black to the background colour for every theme. A theme installed from git can't change that.

## Backgrounds

| | |
|---|---|
| `1-the-multi-million-dollar-os` | the film's final frame (the default). Its intro, the end-title push-in, plays first and ends on this exact frame |
| `2-head-unit` | the same frame without the title |
| `3-head-unit-installed` | the end of the operation: the cube head attached |
| `4-parts-dump` | the parts dump, Mac OS about to drop into the head unit |
| `5-visual-shell-terminal` | the maze cube with its spec readout and circuit traces |
| `6-bipedal-assembly` | the cube head locked onto the wire figure |
| `7-neuro-link` | the wire figure |
| `8-class-prettier` | the powered figure |

All backgrounds are 3840 × 2160. The intro is 2560 × 1440 (5.3 s, silent) and plays on Omarchy versions with background intros. The text and CG are rendered at full size. The photographic plate of the final frame is upscaled from a 1264 × 720 generated clip, so it is softer than the lettering.

## Screensaver art

`screensaver.txt` holds the maze-cube head over the end title, ready for Omarchy's screensaver effects. It is 77 × 20, small enough for the screensaver terminal on a 1152 × 720 logical screen (for example 2304 × 1440 at scale 2). `screensaver.medium.txt` (79 × 27) and `screensaver.large.txt` (118 × 40) suit larger screens. To use one, replace your current art (save a copy first if you've customised it):

```sh
cp ~/.config/omarchy/themes/multi-million/screensaver.txt ~/.config/omarchy/branding/screensaver.txt
```

Preview it from the Omarchy menu under System > Screensaver. To go back to the Omarchy logo, run `omarchy branding screensaver reset`.

## Credits

The imagery comes from the parody [*The Multi-Million Dollar OS*](https://x.com/ocdjeremy/status/2109445974771064978), made with generated video and stills, by [@ocdjeremy](https://x.com/ocdjeremy). The lock-screen title uses Barlow Condensed Black (SIL Open Font License).

## Licence

MIT; see [LICENSE](LICENSE).
