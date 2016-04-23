# waterbug
An app for helping you win on your WaterRower

#project status
Waterbug is coming along, but there's still a lot to do. We would love for you to help. Email me at jeremy.foster@microsoft.com if you have any questions.
The bulk of the work is likely to be in the UI - that is the [waterbug-client project](http://github.com/codefoster/waterbug-client). It's written in Angular 2.0.
The server component ([waterbug-server](http://github.com/codefoster/waterbug-server)) is currently very simple and only acts as a socket server passing all messages to all other clients. It's essentially a passthru.
The device component is not well tested yet. Rowing strokes can be simulated in the UI, so there's no need to have actual rowers to work on the project.
