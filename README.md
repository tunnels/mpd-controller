# mpd controler
An alfred workflow for containing a collection of helper scripts for controlling mpd/mpc. Requires mpd and mpc (obviously).

The keyword is "m".

"add random album(s)" and "add random song(s)" both require shuf (part of gnu/coreutils; this can be installed using homebrew with the command, `brew install coreutils`.

### features/commands
**playing**: prints the currently playing song  
**volume**: takes an `int` as input and sets the current volume to that value
**list**: prints all items on the current playlist  
**clear**: clears the current playlist  
**add album/song**: adds the specified song/album at the end of the current playlist  
**random song(s)**: Add `n` random songs to current playlist  
**random albums(s)**: Replace the current playlist with `n` random albums


[Demonstrative Video](https://github.com/tunnels/mpd-controller/blob/master/examples/mpd-controller.mp4?raw=true)
