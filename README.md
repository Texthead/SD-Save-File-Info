# SD Save File Info
Information in regards to the Save Files of Sonic Dash, a mobile game developed by HARDlight. Feel free to use as guidance when attempting to modify values manually.

Based on the information present in Save Files from Sonic Dash v4.28.0. Information is likely to be outdated or missing; this list isn't complete nor do I have current motivations to do so. You'll have to take the info as is.


Sonic the Hedgehog, Sonic Dash, and other intellectual properties are owned by SEGA or their respective owner(s). The information present here does not exist for any malicious intentions.
## Format
The placement of a field in a SD Save File isn't indicitive of what it corresponds to in-game, so headers are used on the line above the aforementioned field to identify what it represents, as an example:
Header             | Field 
-------------------|-------
RingsAsBlaze_Total | 377   

...would exist as:
```
RingsAsBlaze_Total
377
```
Note that save files don't require all fields to be present to be functional.
## Info

Header                 | Type    | Description 
-----------------------|---------|-------------
EnemiesTotal           | Integer | Total enemies (badniks, PAC-MAN ghosts, drones) defeated by the player by any means, such as rolling or performing a homing attack
LastSessionNumber      | Integer | Numerical identifier for the most recent Sonic Dash instance on this device. Increments by one every time the application is booted from a close
NumberOfSessions_Total | Integer | Total amount of times the game has been booted up from a close. Should always be equivalent to **LastSessionNumber**

