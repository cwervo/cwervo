Blown away that [this](https://cdn.freesound.org/previews/648/648433_11943129-lq.mp3) can become [this](https://strudel.tidalcycles.org/?SzjB4M8TfF8j)

Someday I'll investigate this more seriously but for now here's ChatGPT-4's explanation of the code:

<code>
<pre>
// licensed with CC BY-NC-SA 4.0 https://creativecommons.org/licenses/by-nc-sa/4.0/
// by Felix Roos
samples({ p: 'https://cdn.freesound.org/previews/648/648433_11943129-lq.mp3' })

s("p")
  .loopAt(32)
  .chop(128)
  .jux(rev)
  .shape(.4)
  .decay(.1)
  .sustain(.6)
</pre>
<code>

<p>Here's a breakdown of the code:</p>
  <ul>
    <li><code>samples({ p: 'https://cdn.freesound.org/previews/648/648433_11943129-lq.mp3' })</code>: This line loads an audio sample from the specified URL and assigns it to the variable <code>p</code>.</li>
    <li><code>s("p")</code>: This line selects the sample <code>p</code> as the sound source.</li>
    <li><code>.loopAt(32)</code>: This line sets the loop length of the sample to 32 cycles.</li>
    <li><code>.chop(128)</code>: This line slices the sample into 128 equal pieces, which can be rearranged and played back individually.</li>
    <li><code>.jux(rev)</code>: This line applies the <code>rev</code> (reverse) function to every second repetition of the sample, creating a juxtaposition effect.</li>
    <li><code>.shape(.4)</code>: This line applies a wave shaping distortion effect to the sound, with an intensity of 0.4 (on a scale from 0 to 1).</li>
    <li><code>.decay(.1)</code>: This line sets the decay time of the sound envelope to 0.1 (10% of the cycle duration).</li>
    <li><code>.sustain(.6)</code>: This line sets the sustain level of the sound envelope to 0.6 (60% of the maximum amplitude).</li>
  </ul>
  <p>By chaining these effects and manipulations together, the code creates a unique, transformed version of the original sound sample.</p>