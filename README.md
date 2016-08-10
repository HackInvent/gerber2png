# play-gerber

Forked from https://github.com/dgonner/gerber2png
### work in progress
Upgrade to comply with the specification: https://www.ucamco.com/files/downloads/file/81/the_gerber_file_format_specification.pdf Updated to be integrated with Play!Framework with the following functions:
- Extract the outline dimensions from a gerber file
- Convert a gerber file to png

### route interfaces
GET /gerber/2png    -> returns the png image of the gerber file
GET /gerber/size    -> returns the size of the gerber file with in mm, format: {width:"xxxxx.xx"; height:"yyyyy.yy"}
                    -> option: size?brute=true, returns the following format in mmm: xxxxx.xx;yyyyy.yy

