# NASA leadership and Igloo videos

Open [Releases](https://github.com/nathanieldailey-rgb/nasa-leadership-threewall-film/releases) to download the available films. New editions appear when their uploads finish.

- The standard NASA leadership film is for an ordinary screen.
- The three-wall NASA leadership film is one wide video for a three-wall room.
- The six-panel and dome editions use larger files intended for immersive displays.
- PNT 101 is a separate six-panel Igloo film.

Some large movies are divided into files ending in `.part001`, `.part002`, and so on because GitHub limits individual file size. Download all the numbered parts of one movie into the same folder, together with its manifest. They are pieces of one video and will not play separately.

On Windows, open Command Prompt in that folder and run the following command. Replace `movie` with the full common filename before `.part001`:

```bat
copy /b movie.part001+movie.part002 movie
```

If there is a third part, put `+movie.part003` after `movie.part002` in the command. Check the resulting file against the SHA-256 in the manifest before playback. Keep the original parts until the joined movie has been verified.

The NASA leadership editions carry public release approval 26-00254-5. Other videos are added only when their release status is confirmed.
