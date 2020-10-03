# Fallout: Miami SE Plugin

This is playground repository for F4SE plugin for Fallout: Miami extensions (unofficial at the moment).

I want this README to serve as a sort of a notebook or diary about my journey on implementing my first F4SE plugin.

## High Level Goals

My primary goal is to learn how to extend F4 engine and peek inside its inner workings. As for the Fallout: Miami tasks:

* suppress inventory notifications for added and removed items
  * check how the player's inventory is being managed
  * check how the notification is being generated (Papyrus vs. native listener)
  * check where the notification queue is being stored (Scaleform vs. native queue)
  * check if it is easier to prevent the notifications from being generated or removed from the queue afterwards

## Learning Goals

Unfortunately I am far from a skilled C++ programmer and/or Windows programmer so I don't expect this to be a smooth ride. I want to learn:

* basics of F4 threading model
* basics of Scaleform stuff
* basics of F4 eventing (how various events are being dispatched)
* how to reverse engineer function calls, stuff in memory and what are the best tools for such task
* how to debug internal function calls
* how to peek inside F4 memory (e.g. where is notification queue)
* how to write compact F4SE plugin

## Debugging Fallout 4

TODO: one of my first tasks was to learn how to debug f4... papyrus debugger, F4SE build, VS2019, ...

## Creating F4SE Plugin

TODO: best way to create plugin - using F4SE repo (based on SSE example) vs. using vcpkg
