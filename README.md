# IODA (Input Output Device Assignment)

## Motivation 

Being a Gamer I've experienced the same issue over the past 40 years. Insufficient controller support. Racing games that don't allow wheels for steering, flight sims that don't support throttle and pedals etc.

And I've seen hundreds of workarounds for these problems and many programs doing a great job getting around this limitations. Some of the best of these programs imho are FreePIE with it's flexible input output concept and VoiceAttacks with the integration of voice recognition with keyboard, mouse and joystick remapping. If you happen to use Windows take a look at those great tools. But non of them did all of what I expected them to do or did it in a way I expected them to do it and, since I migrated to GNU Linux a few weeks ago, I cannot use them anymore. 

Being a programmer I decided to change the situation and at the same time give something back to the GNU Linux community in return for all the great programs they provided for free.

## Goals

IODA aims to be an universal input to output event mapper. By intercepting any user input from any device and translating and remapping it to any available output device(s) it can serve many purposes
even beyond game controlling. 

## What it can't do
IODA will not add functionality to programs, so you won't be able to add for example head tracking to a game that does not support control of your view independant of your moving direction.

## A few use cases

    1. by remapping and translating keyboard input to keyboard output, it can provide shortcuts for text or keyboard macros.
    2. by remapping joystick input to XInput it can make any Joystick XBox-Controller compatible in any game.
    3. by remapping stick, throttle and pedals to a single virtual joystick, it allows to use all of them in games suppporting only one joystick.
    4. by remapping input from a voice recognition input plugin, to keyboard, mouse and joystick it offers voice control for games and programs and even robots or help in house automation. (Sounds a bit like Alexa? It is in a way! But it would possibly react to a much smaller set of preset voice commands.)

And there are practically millions of other use cases.

## Technical highlights

    * extensible via input output plugins (and maybe a script language plugin to make it user selectable)
    * flexible by script or GUI driven remapping and translation. 
    * using Rust programmming language. (If I get the hang of it.)

## Pricing
Free for all under the (yet to be determined) licence.

## Open source
Source code will be available via github.
