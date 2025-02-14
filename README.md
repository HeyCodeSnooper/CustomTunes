Always change json file when adding new music
and if you have none:
-get music in .ogg format and if it is mp3 use audacity to convert it.
-go to your sounds.json in the Minecraft folder
paste this into it

{
SOUND_EVENT: {
        "sounds":[
          {
              "name": Example1,
              "stream": true
          },
          {
              "name": Example2,
              "stream": true
          }
         }
      ]
   }
}
        if you want more than 2 songs:
put a comma at the bottom curly bracket
SOUND_EVENT: {
        "sounds":[
          {
              "name": Example1,
              "stream": true
          },
          {
              "name": Example2,
              "stream": true
          },<-------------------------------------- (this one)
         }
      ]
   }

make a new line under it and add

          {
              "name": Example1,
              "stream": true
          }
and so on

to rename your files:

say i have a file called song.ogg to replace Example1.ogg.

i would use the "name" attribute and name it song, like this:

before:
{
              "name": Example1,
              "stream": true
          }
after:
{
              "name": song,
              "stream": true
          }
or if you dont want the coding work at all, just use it how it is but replace the Example1 and Example2 .ogg files with your music.

if you want me to do it for you, send me your file and name your email 'Song Fix for MC CustomMusic Resource Pack [put your Minecraft version here]'

my email is tscjxd@gmail.com

happy listening
