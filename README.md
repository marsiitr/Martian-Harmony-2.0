# Martian-Harmony-2.0
The idea was to build a robot that can play musical instruments in the same fashion as humans.
It consists of various instruments like Flute, Keyboard, Guitar, etc. All these instruments are being played using different mechanisms.
## Team Members
1. Shivam Maloo
2. Shikhar Bhargava
3. Umesh Kumawat
4. Pradhyuman Mathur
5. Iqbal Khan
6. Moti lal
7. Anant Vashistha
## Mentors
1. Prashant Shekhar Singh
2. Satyajeet Patel
3. Animesh Mishra
4. Peyush Jain
5. Amarthya P.
## Instruments :
  You can follow the readme.md for each instrument for understanding them.
  1. **Flute** : https://github.com/marsiitr/Martian-Harmony-2.0/blob/master/Flute/readme.md
  2. **Piano** : https://github.com/marsiitr/Martian-Harmony-2.0/blob/master/Piano/readme.md
  3. **Guitar**: https://github.com/marsiitr/Martian-Harmony-2.0/blob/master/Guitar/README.md
## Software information Basic

We primarily needed to supply all the notes to the respective instruments and also the time at which they needed to be played.Initially we used Image processing to extract the notes using music sheet. The notes extraction was successful but we were not able to locate the time at which a note was to be played/stopped. So we dropped the idea of using a music sheet .Then we used MIDI files which are basically digital music files and have the information of all the notes of different instruments and the time at which a particular note is to be played. To extract all this information from the MIDI file we used the java codes given in notes,ON/OFF and the time files. We did this for a few songs as only a good MIDI file was available for these much songs and for other songs either the MIDI was not available or a lot of noise was present in the MIDI file.
Through MIDI files proper node times were given to the particular instruments.We have to code the instruments using arduino for those particular nodes.Check individual codes for this purpose.

 
## Inference
This is a really good combination of robotics and music.
There are many people who don't know how to play instruments but appreciate good music,this band could help those people live their dreams.It could also be used for teaching puposes. It could even be used for fun purposes.
