SeleniticMOD
============

A Delightful though dark theme for unity monodevelop C#

This is my WIP syntax highlight scheme for Unity Monodevelop, only tested on 4.0.1.

The scheme is based on Tim G. Thomas Visual studio scheme https://studiostyl.es/schemes/selenitic

Reason for this scheme?
I just couldn't stand looking at Monokai anymore... it has been a favorite of mine for years and i still use it for Sublime text 3
but it is hideous in Monodevelop. So in my search of finding a more appealing scheme, i stumbled over this beautiful and smooth scheme for Visual Studio. First problem was VS imports Json, like Xamarin but Unity Monodevelop uses XML, which meant i had to convert everything by hand! By the time i was done, a couple of hours later, i tried importing it.. Validation error!?
Unity Monodevelop scheme editor has got to be the most broken thing i have ever used. if you happen to export one of the default schemes, and change them or just add them again, you CAN'T. I therefore had to make new definitions of the colors, remove all hex values and remove things like width="bold, italic" to width="bold" because the validator is SHIT.

I'm grateful to guavaman, who discovered a way to make it work:
http://forum.unity3d.com/threads/monodevelop-themes-where-to-find.98407/#post-643164


Here is a taste of what it looks like: 
In semantic highlight, which i recommend to use!
![alt tag](http://cloudho.st/i/xFu4McfE.png)
