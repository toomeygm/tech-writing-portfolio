### Audio plug-in user manual (US-EN)

## How to use xxxFX Expander
Input/Gain Reduction: (1) The display shows the waveform of the output signal (gray) and the amount of gain or attenuation of the signal (yellow). You can set the value range for the waveform display and level adjustment independently by right-clicking in the display and selecting a value range. The selected values are displayed in gray and yellow above and below the graph.
Peak/RMS: (2) There are two modes of input level detection, Peak or RMS. Peak uses the peak level while RMS uses an average over a short period of time. Peak is therefore faster, while RMS is more accurate. 
Attack/Release: (3) These time values specify how quickly the effect kicks in (Attack) and how long it takes to become inactive again (Release).
Soft: (4) The characteristic curve of a dynamic effect has a typical bend, the "knee" at the threshold. With the Soft value you can more or less round this curve to make the effect sound more natural (this is called "soft knee").
Threshold: (5) This sets the response threshold below which the control will kick in. Note that, strictly speaking, this is only the case if Soft is set to 0. If the Soft value is above 0, rounding results in a transition range, which means that level reduction already starts a little above the threshold.
Ratio: (6) You can control the expansion ratio using this parameter.
You can see from the characteristic curve that the output signal goes to 0 even when input signals > 0, so the expander acts as a noise gate for very low levels.
xxxFX Expander works as a "downward expander", meaning that dynamic processing starts below the threshold and then works "downwards". For example, with a set ratio of 2, this means that when the input level is reduced by 3 dB, the output level drops by 6 dB. The larger the ratio value, the faster the signal drops.
Out Gain: (7) After the signal is processed by the variable amplifier according to the volume of the input signal, there is a reduction in volume. The Out Gain fader can be used to compensate for this. Out gain is also known as "makeup gain".
Mix: (8) Adjusts the balance between unprocessed (dry) and processed (wet) audio signal.
Please note that expander processing results are highly dependent upon input level. After loading a preset, you will still need to adjust the threshold to the current audio material to achieve the results you want.

Sidechain controls and filter
A sidechain is a secondary stereo input channel pair that can be used to control the expander using a different signal to the one being processed. For instance, you can link the drums and bass more rhythmically by using the expander on the bass track and controlling it using the kick drum on another track.
Your host software must support sidechaining, i.e. it must be able to route audio from one track (or bus) into the additional inputs (3/4) of the plug-in on another track. Check your host software manual to find out if and how you can do this in your host software.
