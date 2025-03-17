---
layout: default
---
Course materials for the
[Auditory Computing](https://www.ucl.ac.uk/module-catalogue/modules/auditory-computing-COMP0161)
module at [UCL Computer Science](https://www.ucl.ac.uk/computer-science/), for delivery in
Term 2 (January-March 2025).

## Tutorial Lab Sessions

**Please bring your laptop and suitable headphones/earphones!**

A provisional schedule is shown below — note that
the topics are only indicative and will almost certainly change
as we go along. Links to any associated content or requirements
for each week will be added as necessary.
Tutorial code will generally be found in the
[tutorials repo](https://github.com/comp0161/tutorials).

* Lab 1: **Basic Acoustics & Auditory Perception** (16 Jan 2025)
    * [`lab01.py`](https://github.com/comp0161/tutorials/blob/main/lab01.py)
      is a script for some basic sound generation and playback using
      the [simpleaudio](https://simpleaudio.readthedocs.io/en/latest/)
      python package. Provided in case anyone is interested,
      but note that **you do not need to run this yourself**.
    * The tutorial makes use of some free audio metering plug-ins. Again, **you
      do not need these** for anything on the module, but they can be useful for
      visualising audio data. Links included for completeness, feel free to ignore.
        * [Wave Observer](https://pressplay-music.com/wave-observer/) (oscilloscope)
        * [Voxengo SPAN](https://www.voxengo.com/product/span/) (spectrum analyser)
        * [TB Spectrogram](https://www.toneboosters.com/tb_spectrogram_v1.html) (spectrogram & spectrum analyser)
* Lab 2: **Signal Detection & Psychophysics** (23 Jan 2025)
    * During the lab you will act as experimental subjects in some basic psychophysics
      experiments that run in your browser. (You will definitely need headphones for these.)
        * [Calibration](experiments/calibration/?home=/index.html)
        * [Pitch sensitivity](experiments/pitch/?home=/index.html)
        * [Detection](experiments/freqlevel/?home=/index.html)
* Lab 3: **Digital Signal Processing** (30 Jan 2025)
    * [DSP tutorial notebook](https://colab.research.google.com/github/comp0161/tutorials/blob/main/lab03.ipynb) (opens in Google Colab)
* Lab 4: **Auditory Scene Analysis** (6 Feb 2025)
    * [`lab04.tidal`](https://github.com/comp0161/tutorials/blob/main/lab04.tidal)
      is a [Tidal Cycles](https://tidalcycles.org) script used to produce some sound examples in the tutorial
    * [CASA tutorial notebook](https://colab.research.google.com/github/comp0161/tutorials/blob/main/lab04.ipynb) (opens in Google Colab)
* Lab 5: **Speech** (13 Feb 2025)
    * If you would like to try viewing your formants and segmenting a speech spectrogram, your best bet is
      probably [Audacity](https://www.audacityteam.org) a free, cross-platform and full-featured audio
      recording and editing application with built-in spectrogram capabilities.
    * You could also use a plug-in such as [TB Spectrogram](https://www.toneboosters.com/tb_spectrogram_v1.html)
      with your preferred audio app.
    * Or do it in code with an audio library such as [librosa](https://librosa.org) or [pyfar](https://pyfar-gallery.readthedocs.io/en/latest/).
    * [Blind Source Separation example](https://scikit-learn.org/stable/auto_examples/decomposition/plot_ica_blind_source_separation.html) from
      [scikit-learn](https://scikit-learn.org) using [Independent Component Analysis](https://scikit-learn.org/stable/modules/decomposition.html#ica)
* Lab 6: **Space & Localisation** (27 Feb 2025)
    * [Auditory Localisation tutorial notebook](https://colab.research.google.com/github/comp0161/tutorials/blob/main/lab06.ipynb) (opens in Google Colab)
* Lab 7: <s>Pitch & Texture (6 Mar 2025)</s>
    * cancelled due to illness
* Lab 8: **Sonification** (13 Mar 2025)
    * [`lab07.sc`](https://github.com/comp0161/tutorials/blob/main/lab07.sc) is a [SuperCollider](https://supercollider.github.io) script for pitch & tuning examples deferred from last week
    * [Sonification tutorial notebook](https://colab.research.google.com/github/comp0161/tutorials/blob/main/lab08.ipynb) (opens in Google Colab)
* Lab 9: **Generating Music with Deep Learning** (20 Mar 2025)
    * [Part 1 — Data](https://colab.research.google.com/github/comp0161/tutorials/blob/main/lab09_part1_data.ipynb) (opens in Google Colab)
    * [Part 2 — Learning](https://colab.research.google.com/github/comp0161/tutorials/blob/main/lab09_part2_learning.ipynb) (opens in Google Colab)
    * [Part 3 — Synthesis & Effects](https://colab.research.google.com/github/comp0161/tutorials/blob/main/lab09_part3_synth_fx.ipynb) (opens in Google Colab)


## Links & Resources

Some of these may be discussed or used in lectures or practicals, others
are purely for interest. At some point they might get organised along
such lines, but in the meantime feel free to browse around.

* [Auditory Modeling Toolbox](https://amtoolbox.org)
* [Al Bregman's Auditory Scene Analysis](https://webpages.mcgill.ca/staff/Group2/abregm1/web/)
* [Dannenberg Introduction to Music Concepts](https://www.cs.cmu.edu/~music/cmp/archives/cmsip/readings/music-theory.htm)
* [CMU Computer Music Project](https://www.cs.cmu.edu/~music/cmp/index.html)
* [The Hearing Garden](https://www.hz-ol.de/en/listening-garden.html)
* [Pure Data (Pd)](https://puredata.info/)
    * [Tutorial: Programming Electronic Music in Pd](http://pd-tutorial.com/english/index.html)
    * [Purr Data](https://www.purrdata.net)
* [SuperCollider](https://supercollider.github.io)
    * [TidalCycles](https://tidalcycles.org)
* [Csound](https://csound.com)
* [Cmajor](https://cmajor.dev)
* [MuseScore](https://musescore.org)
* [LilyPond](https://lilypond.org)
* [FluidSynth](https://www.fluidsynth.org)
* [VCV Rack](https://vcvrack.com/Rack)
* [Music21](https://www.music21.org/music21docs/)
* [Pedalboard](https://github.com/spotify/pedalboard)
* [Strudel](https://strudel.cc)
* [Estuary](https://estuary.mcmaster.ca)
* [Nyquist](https://www.cs.cmu.edu/~rbd/doc/nyquist/)
* [Audacity](https://www.audacityteam.org)