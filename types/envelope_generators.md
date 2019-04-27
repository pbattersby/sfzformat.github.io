---
---
# Envelope Generators

Envelope Generator opcodes are part of the [Modulation](/categories/modulation)
category of opcodes:

#### SFZ 1 EGs

The 3 EG destinations in the SFZ 1 standard are: ampeg (amplitude),
fileg (filter) and pitcheg (pitch).

The EG destinations are represented by (eg type) in the below list - so
`ampeg_attack` would be the amplitude envelope attack, `pitcheg_sustain` would be
the pitch envelope sustain level etc.

These are 6-points Delay-Attack-Hold-Decay-Sustain-Release.

[(eg type)_start](/opcodes/sfz_1/(eg_type)_start)

[(eg type)_delay](/opcodes/sfz_1/(eg_type)_delay)

[(eg type)_attack](/opcodes/sfz_1/(eg_type)_attack)

[(eg type)_hold](/opcodes/sfz_1/(eg_type)_hold)

[(eg type)_decay](/opcodes/sfz_1/(eg_type)_decay)

[(eg type)_sustain](/opcodes/sfz_1/(eg_type)_sustain)

[(eg type)_release](/opcodes/sfz_1/(eg_type)_release)

[(eg type)_depth](/opcodes/sfz_1/(eg_type)_depth)
<br/><br/>

[(eg type)_start_oncc](/opcodes/sfz_1/(eg_type)_start_oncc)

[(eg type)_delay_oncc](/opcodes/sfz_1/(eg_type)_delay_oncc)

[(eg type)_attack_oncc](/opcodes/sfz_1/(eg_type)_attack_oncc)

[(eg type)_hold_oncc](/opcodes/sfz_1/(eg_type)_hold_oncc)

[(eg type)_decay_oncc](/opcodes/sfz_1/(eg_type)_decay_oncc)

[(eg type)_sustain_oncc](/opcodes/sfz_1/(eg_type)_sustain_oncc)

[(eg type)_release_oncc](/opcodes/sfz_1/(eg_type)_release_oncc)
<br/><br/>

[(eg type)_vel2delay](/opcodes/sfz_1/(eg_type)_vel2delay)

[(eg type)_vel2attack](/opcodes/sfz_1/(eg_type)_vel2attack)

[(eg type)_vel2hold](/opcodes/sfz_1/(eg_type)_vel2hold)

[(eg type)_vel2decay](/opcodes/sfz_1/(eg_type)_vel2decay)

[(eg type)_vel2sustain](/opcodes/sfz_1/(eg_type)_vel2sustain)

[(eg type)_vel2release](/opcodes/sfz_1/(eg_type)_vel2release)

[(eg type)_vel2depth](/opcodes/sfz_1/(eg_type)_vel2depth)

#### Flex EGs (SFZ 2)

Flexible EG can have as many points as needed. level and time for each point is
set accordingly.

[egN_points](/opcodes/sfz_2/(egN_points)

[egN_time](/opcodes/sfz_2/(egN_time)

[egN_level](/opcodes/sfz_2/(egN_level)

[egN_shape](/opcodes/sfz_2/(egN_shape)

[egN_curve](/opcodes/sfz_2/(egN_curve)

[egN_sustain](/opcodes/sfz_2/(egN_sustain)

[egN_loop](/opcodes/sfz_2/(egN_loop)

[egN_time_oncc](/opcodes/sfz_2/(egN_time_oncc)

[egN_level_oncc](/opcodes/sfz_2/(egN_level_oncc)

#### Flex EGs destinations

These destinations are added as a suffix to 'egN_' - for example,
eg01_pitch=2400 would have envelope 01 modulate pitch,
with an envelope depth of 2400 cents.

freq_lfo

depth_lfo

depthadd_lfo

pitch

pitch_oncc

depth

depth_oncc

cutoff

cutoff_oncc

resonance

resonance_oncc

cutoff2

cutoff2_oncc

resonance2

resonance2_oncc

eqNfreq

eqNfreq_oncc

eqNbw

eqNbw_oncc

eqNgain

eqNgain_oncc

volume

volume_oncc

amplitude

amplitude_oncc

pan

pan_oncc

width

width_oncc 