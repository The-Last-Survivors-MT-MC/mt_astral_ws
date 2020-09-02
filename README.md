
# Astral

This mod adds regular moon phases, as well as 9 special natural and surnatural Astral events to discover!



## API

* `astral.get_moonth()` return moonth, moonth_name
  This returns the *moonth* (not month!) number, from 1 to 12, and its user-friendly name.
* `astral.get_moon_phase()` return moon_phase, moon_phase_name
  This returns the moon phase (number, from 0: new moon, to 7: waning crescent moon), and its user-friendly name.
* `astral.get_astral_event()` return astral_event, astral_event_name
  If there is a special astral event in progress, it returns that astral event code, otherwise it returns "none".
  The second returned argument is the user-friendly name for that event.
  For 3rd party games, it would allow one to produce some (magical?) effects depending on astral events.

