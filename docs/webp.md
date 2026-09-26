| Format | Command                                                                          | Size |
| :----- | :------------------------------------------------------------------------------- | ---: |
| WebP   | `ffmpeg -i test.mp4 -vf scale=830:-2,fps=20 -loop 0 -c:v libwebp_anim test.webp` |  6MB |

![WebP format](../src/test.webp)
