Customize In-Game Radio
=======================

Local mp3 files
---------------

- Create a windows shortcut to your mp3 music folder in the folder of this Readme file. Or place your .mp3 directly in this folder. (subfolders are also supported)


Internet Streaming Radio
------------------------

Edit the streamingInternetRadios.xml with a text editor and add your favourite radio stations.

    <streamingInternetRadios>
         <streamingInternetRadio href="http://www.my-favorite-radioXYZ.com/stream.m3u" />
         <.../>
         <.../>
    </streamingInternetRadios>

URLs ending in .mp3 .m3u or .pls are supported for streaming radio stations:

http://www.my-favorite-radioXYZ.com/stream.m3u
http://www.my-favorite-radioXYZ.com/stream.pls
http://stream11.my-favorite-radioXYZ.com/radio.mp3