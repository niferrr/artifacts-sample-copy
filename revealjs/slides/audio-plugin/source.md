## Adding audio to a slide

**How to**  
* Enable the audio plugin for your presentation by setting the `enableAudio` option to true in your presentation.json.
* At the top of the slide before any markdown, add `<!-- .element: data-audio-src="<path-to-your-audio-file>" -->` followed by a blank line.
* By convention, put the audio files in `slides/resources/audio` and then under a directory structure matching your slides.  Name your audio file the same as the slide name.  See below for an example.
* You can use external tools for audio, or the built in recording function detailed on the next slide.

```
<!-- .element: data-audio-src="slides/resources/audio/audio-plugin/example.wav" -->

## Adding audio to a slide

You can add audio (like a voice over) to a slide.
```
