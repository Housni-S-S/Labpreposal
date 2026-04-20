# Proposal

## What will (likely) be the title of your project?

Mood Playlist Generator

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A python program that asks the user how they are feeling and generates a playlist of songs for them that matches their mood. It uses the Spotify API to pull real songs and displays them in the terminal

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The Mood Playist Generator is a python program that lets the users input their current mood, such as happy, sad, hype, chill, etc, and receive a list of songs that fit that feeling. The program will use Spotify library, which is a python wrapper for the Spotify API, to search for songs based on mood related keywords and audio features like energy and tempo. When the user runs the program, they will be prompted to type their mood, and the program will return a numbered list of song recommendations including the song title and artist name. The user will also have the option to save the playlist to a text file on their computer so that they can refer to it later. The whole program will run in the terminal and will not require any website or graphical interface.

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

No

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

I am working alone

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

A working python program that takes a mood as input from the user and returns a list of song recommendations that fit that mood using the Spotift API

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

Everything in the good outcome, plus the ability for the user to save their generated playlist to a text file, and a slighlty more polished user experience in the terminal with clear prompts and formatted output

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

Everything in the better outcome, plus the ability for the user to choose a mood from a menu, filter results by genre, and view multiple playlist options before choosing which one to save

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

The first thing I need to do is create a free Spotify developer account and set up an app to get API credentials, which will allow my program to access Spotify's song data. From there I will need to learn how to use Spotify's library, which is a beginner friendly Python library that makes it easier to work with the Spotify API. I will research how Spotify's audio features work, things like energy, valence, and tempo so I can match songs to mood acurately. Then I will start building the program step by step. First getting the API connection working, then building the mood input and search logic, then adding the option to save results to a file.
