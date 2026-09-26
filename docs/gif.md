| Format | Command                                                                | Size |
| :----- | :--------------------------------------------------------------------- | ---: |
| GIF    | `ffmpeg -i test.mp4 -vf scale=830:-2,fps=20 -loop 0 -c:v gif test.gif` | 14MB |

![GIF format](../src/test.gif)
