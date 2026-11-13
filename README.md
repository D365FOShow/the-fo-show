# The F&O Show: X++ code

Source code for the X++ tutorials on [The F&O Show](https://www.youtube.com/@D365FOShow), a YouTube channel for Dynamics 365 Finance & Operations developers.

## Videos and code

| Video | Code |
|---|---|
| [X++ Containers Explained: Every Method & Gotcha](https://youtu.be/zvzE4mVBG_Q) | [containers/](containers) |
| [X++ Maps Explained: Every Method & Gotcha](https://youtu.be/rlEL7aHoEk0) | [maps/](maps) |
| [X++ Lists Explained: Every Method & Gotcha](https://youtu.be/a76Z_fUjB_s) | [lists/](lists) |

## Using the code

Each `.xml` file is an X++ class in the AxClass format that Visual Studio saves.

1. Copy the file into the `AxClass` folder of a model on your development box, for example `PackagesLocalDirectory\<YourPackage>\<YourModel>\AxClass\`.
2. Refresh Application Explorer in Visual Studio, find the class and add it to your project.
3. Build, set the tutorial class as the startup object, and press F5 to step through it in the debugger, just like in the video.

Each tutorial class has a `main` method that calls the parts in the same order as the video. The long empty comment blocks between parts are only there to keep each part on screen while recording.

All classes start with the prefix `My`. Rename them if they clash with classes you already have.

## License

[MIT](LICENSE)
