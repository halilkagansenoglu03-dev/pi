# Piglin Quit (Fabric 1.21.11, client-side)

Only zombified piglins count. If none is loaded for 10 seconds in a row, you
are disconnected from the multiplayer server. A countdown is always shown above
your hotbar. In singleplayer it only shows the timer (test mode) and never kicks.

Change the time: edit SECONDS_WITHOUT_PIGLIN in
src/main/java/com/piglinquit/PiglinQuitClient.java

The build file is .github/workflows/build.yml (hidden folder - if your upload
skips it, create it by hand on GitHub). The finished mod is piglinquit-jar,
containing piglinquit-1.0.0.jar.
