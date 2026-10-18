# more-chords-M-VAVE-FM-1-Custom-Firmware



https://rosen-wav.github.io/more-chords-M-VAVE-FM-1-Custom-Firmware/site/




more chords!

A ChoralRoot remix by rosen for M-VAVE FM1

Built on ChoralRoot by u/Quixotic7 and contributors, with additional engines, creative tools, sequencing features and performance refinements.

Huge thanks to everyone behind ChoralRoot, Felucca, Melodee, ORBIT and Monk for making this project possible.

Engines

PROPHET — A Prophet-5-style engine adapted from Melodee, with native patch editing.

SWARM — Adapted from ORBIT. A detuned oscillator ensemble for wide unison sounds, evolving pads and harmonic textures.

CLUSTER — Adapted from ORBIT. Up to seven oscillators, with phase feedback, drifting pitch and adjustable harmonic character. Optimized for this remix.

CLOUD — An oscillator-based granular engine adapted from ORBIT. It creates grains from synthesized waveforms rather than samples, with two grains per voice. Includes Size, Density, Spread, Detune, Chirp, Stack and Tone controls, plus additional wavetable banks.

DRIFT — An original more chords! engine with five detuned oscillators, independent slow drift and phase modulation. Controls include Spread, Drift, Density, Tone, Rate, Phase, Round and Tilt.

WAVE TERRAIN — An original more chords! engine that generates sound by moving along two-dimensional paths across sonic surfaces. Includes Terrain, Orbit, Motion, Depth, X/Y Shift, Skew and Smooth controls, with smoothed terrain and position changes.

FM6 — A DX7-inspired six-operator FM engine inherited through ChoralRoot and Melodee, using Dexed-derived synthesis.

FM TONE — ChoralRoot’s QUAD engine: an original Digitone-inspired four-operator FM implementation.

VA — ChoralRoot’s virtual-analog engine, with oscillator, filter, envelope and modulation editing.

PHASE — Felucca’s phase-distortion engine, based on the author’s CrispyZebra oscillator. Includes multiple waveform shapes, a second oscillator line, ring modulation and a sub oscillator.

CZ-1 — A Casio CZ-inspired phase-distortion engine inherited through ChoralRoot and Melodee, with native tone editing.

BASS — A dedicated bass engine with two oscillators, a sine sub, drive and a resonant low-pass filter.

MORPH — A more chords! engine that crossfades between two independently running presets from the same supported engine. Use Manual, Random or Up/Down motion, with speed, amount and chord-trigger controls. Leave the position between the endpoints to layer both sounds. Prophet, CZ-1 and BASS are excluded.

Presets and sound collections

350+ factory presets.

64 USER preset slots, shared across the engines.

Save edited sounds as new USER presets or overwrite supported existing preset entries.

Favourites provide quick recall of supported factory presets and saved USER sounds. They reference existing sounds rather than adding extra USER slots.

A separate Bass collection holds eligible sounds for the bass track.

Hold HOME from the home screen to access the Favourites/Bass collection menu.

Prophet, CLOUD and MORPH cannot be used as bass sounds.

Playing and performance

ChoralRoot supplies the underlying chord-playing system, chord qualities, extensions, voicing logic and performance framework. more chords! extends their interaction with MIDI, sequencing and sound selection.

Velocity-sensitive FM1 keys, integrated using Monk as a reference/source, with a softer response curve for easier quiet playing.

External MIDI note velocity is supported.

Two musical parts: one chord track and one bass track. MORPH uses a third internal part for its second patch.

Simple and Advanced chord play styles. Simple uses the Advanced-style interaction but clears added chord extensions when changing chords.

Maj, Min, Dim and Sus chord modifiers, plus 6, 7, major 7 and 9 extensions.

Lock for retaining chord modifiers.

No Chords, Just Keys: play individual notes and chords normally. With Bass enabled, holding three or more notes also plays the lowest held note using the selected bass preset.

No Chords, Just Keys and its automatic bass behaviour also work with external MIDI.

External MIDI can control chord modifiers, extensions and Lock.

An adjustable MIDI Chord Start sets the modifier-key region, preserving the black-key/white-key layout.

Lock state is shared between the FM1 controls and external MIDI.

The keyboard remains playable while browsing engines and settings.

Rosen Mode, inspired by AFX Mode: change preset on each new chord, with Next, Random and Ping Pong options.

Swag Voicing, chord voicings movement using Ping Pong, Random or Tennis modes.

Clock-synced Gate, with 1/4, 1/8, 1/16 and 1/32 divisions.

Clock-synced sidechain in the SEQ menu.

Improved voice replacement prioritizes the new chord when chords overlap, with short transition smoothing to reduce discontinuities.

Step sequencer and loops

The remix expands ChoralRoot’s underlying loop and transport framework with a paged step editor and additional storage.

30 loop/sequence slots, each up to 8 bars long.

Fixed 4/4 time signature.

Three banks of ten slots: 1–10, 11–20 and 21–30.

The last keyboard key switches banks. Its LED is off, blinking or steadily lit to indicate the selected bank.

Eight step buttons per page, mapped to FX, SEL, ENV, LFO, HOME, SAVE, ARP and SEQ.

Hold SEQ to enter the step editor.

Play a note or chord, then press an empty step to insert it.

Chords played in No Chords, Just Keys mode can also be inserted, including their bass note.

Occupied steps are illuminated. Press an occupied step to delete it.

Hold a step to preview it while stopped. Preview is disabled during playback.

Hold a step and turn SELECT to extend its duration. Sustained regions appear in a different colour.

Turn SELECT normally to select a step.

Turn ALGORITHM to change the global grid resolution: 1/16, 1/8, 1/4, 1/2 or 1/1. The default is 1/4.

Changing resolution redistributes existing notes on the grid while retaining their musical timing.

EDIT moves to the previous page; GLOBAL moves to the next.

OCT− and OCT+ continue to transpose the live keyboard.

Hold EDIT, GLOBAL or PLAY to leave the editor without stopping playback.

PLAY starts and stops the sequence. Entering the editor does not automatically start playback.

A moving playhead indicates the current step.

The keyboard and preset encoder remain usable inside the sequencer.

Sequence length follows the loop length selected in the held-PLAY menu.

Step sequences can be saved and recalled in the same slots as recorded loops.

Playback starts aligned to the internal clock or external MIDI clock/transport.

Tempo nudge: hold PLAY and press OCT+ or OCT− to temporarily speed up or slow down playback without changing the stored BPM.

Held-SEQ controls for click, BPM, sidechain and transpose remain available.

Normal REC behaviour outside the generator/editor context retains layer undo.

Saved loops and sequences can be deleted from the held-SAVE menu.

Creative tools

Preset Randomizer

Hold REC while editing a preset to open the randomizer.

Generate variations with visual “Preset generated” feedback.

Press OCT+ to confirm or OCT− to cancel.

Confirmation does not automatically overwrite a saved preset.

Chord Progression Generator

Hold REC from the sequencer context to open the generator.

Choose a root and Major, Minor or Chromatic mode.

Progression styles include Pop, Classic, Journey, Circle, Dream, Surprise, Jazz, Andalusian, Turnaround, Steps and Tritone.

Generated ideas can include Maj, Min, Dim and Sus chords, with 6, 7, major 7 and 9 extensions.

Press PLAY to audition an idea before accepting it.

Generate another idea during playback without stopping the transport.

Press OCT+ to move the progression into the step sequencer for immediate editing.

Generated progressions are not automatically saved to a loop slot.

CLOUD wavetable banks

Added in more chords!:

Classic, Warm, Glass, Hollow and Digital banks.

The ENV page contains:

Bank: waveform-bank selection.

Scan: Off, Up/Down, Forward or Backward.

Rate: automatic scanning speed.

Depth: scanning range around the selected Wave position.

CLOUD’s original amp ADSR remains on the second ENV page.

OSC Wave selects the manual waveform position or the centre of automatic scanning.

Bank and waveform changes enter through the grains’ fades rather than abruptly replacing active oscillators.

The four additional banks occupy 2 KB of XIP storage, without increasing voice-state RAM.

Effects, audio and interface

Four effects sends: Drive, Chorus, Delay and Reverb.

The original Felucca Chorus, Delay and Drive are retained.

Church reverb, adapted from the Melodee-derived reverb components, is the sole reverb algorithm.

The former reverb algorithm selector now controls stereo Width, alongside Size, Damping and send level.

Clean output mode is the default.

USB audio recording at 44.1 kHz, with optional 48 kHz support, inherited through ChoralRoot/Melodee.

Separate stereo Master, Chord and Bass recording pairs over USB.

USB audio options persist across restarts.

Engine-specific parameter screens and an updated MORPH interface.

Enlarged more chords! startup artwork.

Startup muting and fade-in measures to reduce power-on audio transients.

Credits

ChoralRoot — u/Quixotic7 and contributors: the original project, chord-playing foundation, voicing and Swag logic, performance framework, FM1 interface, FM TONE/QUAD and VA engines, and integration of inherited synthesis, editing, storage and audio features.

Felucca — Leo Kuroshita / @kurogedelic, Hügelton Instruments: the underlying FM1 platform, hardware support, DSP framework, PHASE engine, original effects, build tools and firmware infrastructure.

Melodee — Kerem Kilic, Ellic Studio: source and integration work behind FM6, CZ-1, Prophet and USB audio/reverb components used or adapted through ChoralRoot.

Dexed and its contributors: synthesis lineage used by FM6.

Devin Acker: the uPD933 model used in the native CZ renderer.

ORBIT and its contributors: source project for the SWARM, CLUSTER and CLOUD adaptations. Individual engine source notices remain applicable.

Monk and its contributors: reference/source for FM1 keyboard velocity integration.

rosen / more chords!: remix design, additional engines and creative tools, expanded sequencing and storage, MIDI/performance refinements, CLOUD wavetable banks, UI work for new engines, DSP adaptations.

All original copyright notices and applicable licenses remain with their respective authors. Synthesizer names describe inspiration or compatibility and do not imply manufacturer endorsement.
