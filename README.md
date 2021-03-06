# About

This is a plugin for Plover to display your typing speed as you type, in either
or both of words per minute or strokes per minute:

  * **Words per minute**: Shows the rate at which you stroked words in the last
    10 and 60 seconds.
  * **Strokes per minute**: Shows how efficiently you stroked words in the last
    10 and 60 seconds. Lower values are more efficient, e.g. a value of 1 means
    that on average it took you one stroke to write out a word.

A word is defined in one of three ways:

  * **NCRA**: The [National Court Reporters Association](https://www.ncra.org/)
    defines a "word" as 1.4 syllables. This is the measure used for official
    NCRA testing material.
  * **Traditional**: The traditional metric for "word" in the context of
    keyboarding is defined to be 5 characters per word, including spaces. This
    is compatible with the notion of "word" in many typing speed utilities.
  * **Spaces**: A word is a whitespace-separated sequence of characters. This
    metric of course doesn't take into account the fact that some words are
    longer than others, both in length and syllables.

The meters look like this:

![The WPM meter in action](media/wpm-meter.png)
![The strokes meter in action](media/strokes-meter.png)

# Installation

To install this plugin, you'll need to build Plover from source, then install
this package with an invocation something like this:

```
pip install git+git://github.com/arxanas/plover_wpm_meter
```

Then launch Plover and select the WPM meter from the tools.

# License

This plugin is licensed under the GPLv3.

Icon made by [Freepik](http://www.freepik.com/) from [www.flaticon.com](http://www.flaticon.com/).
