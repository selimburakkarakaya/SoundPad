# SoundPad

This JavaScript application performs the function of playing sound effects when keys are pressed from the keyboard. For example, pressing a key on the keyboard causes a specific sound to be played.

How does it work:

1. Keyboard Listener: Listens for the browser window keydown event and triggers the playSound function when any key is pressed.

2. Sound Playback Function: playSound(e) function selects and plays a sound file corresponding to the pressed key. It also adds a visual effect to the pressed key.

3. Transition Removal Function: removeTransition(e) function listens for transition events to remove the visual effect of keys.

4. Key Selection and Visual Effect: Each key is marked with the data-key attribute, and the corresponding sound file and key DOM element are selected with this attribute. A visual effect is added to the pressed key.

##

Features:

- Sound Play: When a key is pressed on the keyboard, an audio file corresponding to the relevant key is played. A different sound file can be assigned to each key.

- Visual Feedback: When a key is pressed, a visual effect is added to the corresponding key. This helps the user feel that they are receiving a response to the keypress.

- Key Selection: Each key is marked with the data-key attribute, and the corresponding audio file and key DOM element are selected with this attribute.

- User-Friendly Interface: Using a simple and understandable interface, it allows users to play sounds by pressing keys.

This simple yet fun app allows users to experience sound effects by interacting on the keyboard. This interactive experience helps users focus their attention and improve their typing skills. By hearing sound effects with every key press, players develop quick reflexes while also increasing their keyboard coordination. This provides both an entertaining experience and helps users improve their skills.
