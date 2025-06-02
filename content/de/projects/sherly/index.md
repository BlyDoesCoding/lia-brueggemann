---
title: 'Sherly'
slug: 'sherly'
summary: 'Sherly is a Multithreaded Duplicate File Finder for your Terminal, written in java. You can Easily find duplicate Images, videos as well as any other type of Data. That can be helpful if you run on small storage or just want to keep regular housekeeping.' # This is what will be displayed as summary for the post (the theme will automatically generate one from the content you write in the post if left empty)
description: # This is what will be displayed as meta data (the theme will automatically grab it from summary if left empty)
date: '2023-04-03T11:16:02+02:00'
expiryDate: '' # You want your post to vanish after a certain date? Write it down here! Must be in the same format of `date`
translationKey: sherly # If you have a translated post for this one, set the same translationKey to have the translation displayed
layout: 'single'
version: '1.1.4' # <--- Add this line
source: "https://github.com/BlyDoesCoding/Sherly"
releases: "https://github.com/BlydDoesCoding/Sherly/releases"
languages:
  - java

platforms: # <--- New parameter
  - Windows
  - Linux
  - macOS
license: "BSD 2-Clause" # <--- Add this line
---

Sherly is a Multithreaded Duplicate File Finder for your Terminal, written in java. You can Easily find duplicate Images, videos as well as any other type of Data. That can be helpful if you run on small storage or just want to keep regular housekeeping.

## Installation

Install via AUR


```
  yay -S sherly-git
```

Compile yourself

```
  git clone https://github.com/BlyDoesCoding/Sherly
  cd Sherly
  mkdir -p Bin
  javac -d Bin src/*.java -Xlint
  cd Bin
  jar cfe sherly.jar Main ConsoleColors.class Main.class ThreadedCompare.class
  #the jar file will be in the Bin Folder
```





## Usage/Examples


Usage: sherly -f inputfolder1 inputfolder2 inputfolder3 [options]

   -h / -help             show this
   -f / -folder           all the folders you want to scan for (see example above!)
   -c / -color            enable colored messages
   -t / -threads          override default Thread number (default is usually number of cores * 2)
   -p / -progress         enable progress indicator
   -d / -delete           delete all dups except one without asking first
   -n / -noinput          skip all user input
   -debug                 debug stuff
