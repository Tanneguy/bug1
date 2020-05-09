# Elm App Bug Report

This project was created with create-elm-app and

* editing Main.elm to include 2 png images
* adding to png files in the src folder

### The bug

One of the png file is not imported to buil/static/media.
The workaround was to load it in **Pinta** & save it as a different file.

### The cover-up

The main problem is that the builds ignores the file **silently** and finishes with a successful completion message.


