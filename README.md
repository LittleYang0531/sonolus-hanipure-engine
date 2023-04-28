# Sonolus Hanipure Engine

A recreation of Honeyworks Premium Live engine in [Sonolus](https://sonolus.com).

## Links

-   [Sonolus Website](https://sonolus.com)
-   [Sonolus Wiki](https://github.com/NonSpicyBurrito/sonolus-wiki)

## Installation

```
npm install sonolus-hwpl-engine --save
```

## Custom Resources

Engine ID: `1`

### Skin Sprites

| ID  | Sprite                         | Hanipure Asset Path                                   |
| --- | ------------------------------ | ----------------------------------------------------- |
| 1   | Stage                          | `/ingameskin/fieldskin/{name}/bg_line_rhythm`         |
| 2   | Judgment Line                  | `/ingameskin/fieldskin/{name}/game_play_line`         |
| 11  | Left Directional Flick Note    | `/ingameskin/noteskin/{name}/DirectionalFlickSprites` |
| 12  | Right Directional Flick Note   | `/ingameskin/noteskin/{name}/DirectionalFlickSprites` |
| 21  | Left Directional Flick Marker  | `/ingameskin/noteskin/{name}/DirectionalFlickSprites` |
| 22  | Right Directional Flick Marker | `/ingameskin/noteskin/{name}/DirectionalFlickSprites` |

### Effect Clips

| ID  | Clip                     | Hanipure Asset Path                        |
| --- | ------------------------ | ------------------------------------------ |
| 1   | Directional Flick Single | `/sound/tapseskin/{name}/directional_fl`   |
| 2   | Directional Flick Double | `/sound/tapseskin/{name}/directional_fl_2` |
| 3   | Directional Flick Triple | `/sound/tapseskin/{name}/directional_fl_3` |

### Particle Effects

| ID  | Effect                           |
| --- | -------------------------------- |
| 1   | Circular Left Directional Flick  |
| 2   | Circular Right Directional Flick |
| 11  | Linear Left Directional Flick    |
| 12  | Linear Right Directional Flick   |

## Documentation

### `version`

Package version.

### `engineInfo`

Partial engine information compatible with [sonolus-express](https://github.com/NonSpicyBurrito/sonolus-express).

### `engineConfiguration`

Engine Configuration.

-   `engineConfiguration.path`: path to file.
-   `engineConfiguration.buffer`: buffer of file.
-   `engineConfiguration.hash`: hash of file.

### `engineData`

Engine Data.

-   `engineData.path`: path to file.
-   `engineData.buffer`: buffer of file.
-   `engineData.hash`: hash of file.

### `engineThumbnail`

Engine Thumbnail.

-   `engineThumbnail.path`: path to file.
-   `engineThumbnail.buffer`: buffer of file.
-   `engineThumbnail.hash`: hash of file.

### `fromHanipure(chart)`

Converts Hanipure chart to Level Data.

-   `chart`: Hanipure chart.
