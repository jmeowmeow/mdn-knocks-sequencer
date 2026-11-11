# webaudio-examples

Note: this repository only contains code derived from MDN's step-sequencer example. The following text excerpts MDN's README.

Code examples that accompany the [MDN Web Audio documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API).

## Serving the examples

To preview the examples, clone the repository and navigate to the example you want to view.
For example, if you have Python installed, you can use the following commands to serve the `audio-analyser` example:

```bash
cd audio-analyser
python3 -m http.server
```

> [!NOTE]
> If you're using the built-in Python HTTP server, be sure to use at least [Python version `3.10.12`](https://www.python.org/downloads/release/python-31012/).

Then navigate to `http://localhost:8000` in your browser.

For more information on serving files locally using different languages or technologies, see [Running a simple local HTTP server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/set_up_a_local_testing_server#running_a_simple_local_http_server).

## Repository contents

### Step sequencer

The [step-sequencer](https://github.com/mdn/webaudio-examples/tree/main/step-sequencer) directory contains a simple step-sequencer that loops and manipulates sounds based on a dial-up modem. For more information see [Advanced techniques: creating sound, sequencing, timing, scheduling](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Advanced_techniques). See the [live demo](http://mdn.github.io/webaudio-examples/step-sequencer/) also.

