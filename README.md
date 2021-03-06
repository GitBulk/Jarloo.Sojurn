Jarloo.Sojurn
=============

![alt tag](/images/screenshot1.png)

About Sojurn
------------

Sojurn keeps track of what TV shows you've watched, and which ones you haven't. It features a backlog so you know what episodes you haven't watched yet, and a timeline that lets you see when your favorite shows will air next. 

You can explore your favorite shows, browsing by season and episode.

- Backlog : The backlog shows what shows you have added but not watched yet.

- Timeline : The timeline lets you view what shows you have added that are upcoming.

Why was it made?
----------------

Sojurn was developed as an experiment to explore Caliburn.micro and Mahapps.metro, and as such provides a great example application to get you familiar with these technologies. With that in mind it is a fully flushed out, and functional application.


About the code
--------------

Sojurn is written in C# using WPF and MVVM. It uses Caliburn.micro and MahApps.metro.


Requires .NET Framework 4.6 for the current main branch. There is a branch for 4.5.1 as well.

For more info:
http://www.jarloo.com/sojurn-the-tv-app/


Data Sources
------------

Currently the data used is from the TVMaze API. Sojurn has been written to easily allow the injection of different data sources, so if you'd prefer another feel free to add it.


Major Changes
------------

Converted to Visual Studio 2015 with C# 6 language features such as null propagation. If you need Visual Studio 2013 there was a branch created before the update.


