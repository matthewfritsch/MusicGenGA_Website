Frequently Asked Questions
==================================

**About Mid (midi) Files**
-----------------------------

What Is a .mid File?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.mid or midi, is the abbreviation for Musical Instrument Digital Interface. It's a file that is used by different mixing and music authoring programs, as well as any midi hardware devices (an example of this being a midi keyboard). Midi files hold musical data, like notes (or combinations of notes to make chords), how long a note is held, when a note is played, and how loud a note can be.

Why Not Use Another File Format For Music?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Midi files are a really convenient way of programming music by using a built in Python library. On top of this, it's commonly seen by devices that make video game music. It is also common to see it being used by video game music producing devices and we wanted to replicate that effect.

**Song Specific Questions**
-----------------------------

How Does The Program Work?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Using genetic algorithms and pseudo random chunk creation and then bridging the chunks together to make a song that is influenced by the fitness function. The user also has some control in the beginning to change the theme of the music.

Why Does The Music Sound So Bad?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Try running the program again and changing the starting values or just running the program longer to get a better sounding song in the end. Keep in mind, it's a computer generating the music and might take a couple of tries to get a song you want.

Why Do All Of The Music Files Play Piano Instead Of Other Instruments?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The default instrument for midi files is piano, so to test other instruments, import the midi file into FL studio (or a similar software)

**Software Specific Questions**
-----------------------------

Why Not Use a Different Program For Making Music?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ours is targeted for creating video game music, or to get a starting point for general music. Our code was written in a way to attempt to get the best sounding songs for these scenarios and other programs may have been going for a more general approach. On top of this, ours is free!

Can I Use X Software For Editing The Midi Files?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Some other programs that can edit midi files might be: GarageBand, Aria Maestosa, B-Step Sequencer, Band-in-a-Box, or any other program that accepts midi files and allows for editing. The reason we chose FL studio is because it's a fairly common software used and can be used for what we need it for for free.