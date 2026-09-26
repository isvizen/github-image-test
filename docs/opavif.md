| Format | Command                                                                                           | Size |
| :----- | :------------------------------------------------------------------------------------------------ | ---: |
| OPAVIF | `ffmpeg -i test.mp4 -vf scale=830:-2,fps=30 -loop 0 -c:v libsvtav1 -preset 6 -crf 23 testop.avif` |  5MB |

![OPAVIF format](../src/testop.avif)
