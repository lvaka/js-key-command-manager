# Javascript Key Command Manager
---
This project functions as a way to get familiar with binary search trees.

The JavaScript class should be able to register key commands tied to a callback function.  The class has a method to register new commands.

Usage:  \n
`
    const keyMgr = new KeyCommandManager();  \n
    keyMgr.registerKeyCommand('l r l r b a <enter>', callbackFunction);  \n
`

The app will have an eventListener for keypresses and will listen to a stream of key inputs and will fire the callback when an existing sequence is called.

This exercise demonstrates how a binary tree is used in a practical application.
