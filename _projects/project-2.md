---
title: "CodeTalk"
excerpt: "VisualStudio plugin to improve code glanceability, navigability and alertability to IDE information."
collection: projects
---
Graphical User Interface (GUI) based Integrated Development Environments (IDEs) provide important information through visual cues. Sighted developers can glance through code, quickly navigate by scroling, pointing and clicking and get realtime information from IDEs through visual cues like syntax coloring, etc. CodeTalk improves code glanceability, navigability and alertability (realtime access to information) through UI enhancements, speech and non-speech cues. CodeTalk also introduces TalkPoints, an audio debugging experience. CodeTalk supports 3 types of TalkPoints:

* Speech TalkPoints:
    These TalkPoints are similar to console log statements but are spoken when the TalkPoint is hit. The user can set a message that should be spoken.
* Tone TalkPoint:
    These TalkPoints can be configured to play a specific tone when they are hit. These can be used to know whether an if block has been executed or not, etc.
* Expression TalkPoints:
    The developer can have specific expressions evaluated in the execution context and have the result spoken. These TalkPoints can be very useful as the developer can experiment with performing different operations on the variables in the execution context without affecting the actual code.

One unique feature to TalkPoints is that the developer can choose to not break when these TalkPoints are hit. The developer can listen to the associated audio cue and continue execution.

*CodeTalk has been awarded second place (developers category) in the Microsoft Hackathon 2017!*