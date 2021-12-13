<p align="center"> 

  
THIS IS ONE ENGINE OF FNF FOR ANDROID!!!".


Support the ORIGINAL project on the itch.io page: https://ninja-muffin24.itch.io/funkin

"IF YOU MAKE A MOD AND DISTRIBUTE A MODIFIED / RECOMIPLED VERSION, YOU MUST OPEN SOURCE YOUR MOD AS WELL"
-LUCKYDOG7

# download

ORIGINAL PORT:https://github.com/luckydog7/Funkin-android/releases




# Build instructions

1. first of all we need to set up haxe and haxeflixel read more here - https://github.com/ninjamuffin99/Funkin

  - Install haxe 4.2.2 instead of 4.1.5
  - if you updated it dont forget execute this command 'haxelib upgrade' and press 'y' everywhere
  - Also get extension-webm using this command: 'haxelib git extension-webm https://github.com/KlavierGayming/extension-webm'
  - the reason we use a different repo again is cuz of a lil error that happens with the audio sync, just adds a "public var renderedFrames" instead of "var renderedFrames", that's all extra that's needed


2. after that, download Android studio, Jdk, Ndk revision 15c from these sites

  - jdk - https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

  - android studio - https://developer.android.com/studio

  - ndk - https://developer.android.com/ndk/downloads/older_releases?hl=fi


3.install jdk, android studio 
  - unzip ndk (ndk does not need to be installed)


4. we need to set up android studio for this go to android studio and find android sdk (in settings -> Appearance & Behavior -> system settings -> android sdk)
![andr](https://user-images.githubusercontent.com/59097731/104179652-44346000-541d-11eb-8ad1-1e4dfae304a8.PNG)
![andr2](https://user-images.githubusercontent.com/59097731/104179943-a9885100-541d-11eb-8f69-7fb5a4bfdd37.PNG)


5.and run command `lime setup android`
  - you need to insert the program paths

  - as in this picture (use jdk, not jre)
![lime](https://user-images.githubusercontent.com/59097731/104179268-9e80f100-541c-11eb-948d-a00d85317b1a.PNG)

  - Now do "lime rebuild extension-webm windows" (in the command line), if you're planning to build for windows. If you're plannin to build for android (which you obviously are), use "lime rebuild extension-webm android". If you get an error, download [this](https://www.mediafire.com/file/8jteungeq2bzc3l/Android.zip/file) and put the folder inside it in C:/HaxeToolkit/haxe/lib/extension-webm/git/ndll


7. open project in command line `cd (path to fnf source)`
  - and run command `lime build android -final`
  - apk will be generated in this path (path to source)\export\release\android\bin\app\build\outputs\apk\debug\Funkin-debug.apk


## Credits / shoutouts
- [BLACKTORD(ehehhehehehehhe)](https://github.com/BlackTMod) - the creator of the engine
- [ninjamuffin99](https://twitter.com/ninja_muffin99) - Programmer
- [PhantomArcade3K](https://twitter.com/phantomarcade3k) and [Evilsk8r](https://twitter.com/evilsk8r) - Art
- [Kawaisprite](https://twitter.com/kawaisprite) - Musician
- [luckydog](https://github.com/luckydog7) - original android port

''This game was made with love to Newgrounds and it's community. Extra love to Tom Fulp.''
  -LUCKYDOG7 (THE BIG SHOT)

  IM DONT MAKE THIS PORT!!!!I JUST MAKE ONE ENGINE/MOD FOR [[[THIS NICE PORT]]]

