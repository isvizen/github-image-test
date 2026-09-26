| Format | Command                                                                       | Size |
| :----- | :---------------------------------------------------------------------------- | ---: |
| AVIF   | `ffmpeg -i test.mp4 -vf scale=830:-2,fps=20 -loop 0 -c:v libsvtav1 test.avif` |  2MB |

![AVIF format](../src/test.avif)
