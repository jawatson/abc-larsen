# abc-larsen
Grey Larson's Ornamentation for ABC notation

This is a small project to create ABC decorations suitable for 
use wih [abcm2ps](https://github.com/leesavide/abcm2ps) using Grey Larsen's system for ornamentation in Irish Traditional Music.

Details of Grey Larsen's notation may be found in the book 
"The Essential Guide to Irish Flute and Tin Whistle" and 
at [http://greylarsen.com/resources/larsen-font/](http://greylarsen.com/resources/larsen-font/)

The file sample.abc demonstrates usage of the format file
and should be processed with the comamnd;

    abcm2ps -O sample.ps sample.abc

PDF files may be created directly with the command;

    abcm2ps sample.abc -O - | ps2pdf - > sample.pdf 

The tunes folder contains examples of the format file in a musical context.
