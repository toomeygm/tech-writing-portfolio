## An explanation of the parameters in xxxFX Expander

**Input/Gain Reduction**  
The display shows the waveform of the output signal (gray) and the amount of gain or attenuation of the signal (yellow). You can set the value range for the waveform display and level adjustment independently by right-clicking in the display and selecting a value range. The selected values are displayed in gray and yellow above and below the graph.

**Peak/RMS**  
There are two modes of input level detection, Peak or RMS. Peak uses the peak level while RMS uses an average over a short period of time. Peak is therefore faster, while RMS is more accurate.

**Attack/Release**  
These time values specify how quickly the effect kicks in (Attack) and how long it takes to become inactive again (Release).

**Soft**  
The characteristic curve of a dynamic effect has a typical bend, the "knee" at the threshold. Use the Soft Knee parameter to round this curve to make the effect sound more natural.

**Threshold**  
Sets the response threshold below which the control will kick in. Note that, strictly speaking, this is only the case if Soft is set to 0. If the Soft value is above 0, rounding results in a transition range, which means that level reduction already starts a little above the threshold.

**Ratio**  
Controls the expansion ratio. You can see from the characteristic curve that the output signal goes to 0 even when input signals > 0, so the expander acts as a noise gate for very low levels.

xxxFX Expander works as a "downward expander", meaning that dynamic processing starts below the threshold and then works downwards. For example, with a set ratio of 2, this means that when the input level is reduced by 3 dB, the output level drops by 6 dB. The larger the ratio value, the faster the signal drops.

**Out Gain**  
After the signal is processed by the variable amplifier according to the volume of the input signal, there is a reduction in volume. You can use the Out Gain fader to compensate for this. Out gain is also known as makeup gain.

**Mix**
Adjusts the balance between unprocessed (dry) and processed (wet) audio signal.
Please note that expander processing results are highly dependent upon input level. After loading a preset, you will still need to adjust the threshold to the current audio material to achieve the results you want.

