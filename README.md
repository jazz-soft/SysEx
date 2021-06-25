# Commonly used SysEx messages

## [ 7E ] - Universal Non-Real-Time SysEx Messages
- `F0 7E xx 06 01 F7` - Device ID Request
- `F0 7E xx 06 02 ... F7` - Device ID Response
- `F0 7E xx 09 01 F7` - GM System On (GM)
- `F0 7E xx 09 02 F7` - GM System Off (GM)
- `F0 7E xx 09 03 F7` - GM2 System On (GM2)

## [ 7F ] - Universal Real-Time SysEx Messages
- `F0 7F xx 04 01 xx xx F7` - Master Volume
- `F0 7F xx 04 02 xx xx F7` - Master Balance

## [ 41 ] - Roland

## [ 43 ] - Yamaha
- `F0 43 xx 4C 00 00 7E 00 F7` - XG System On

## [ 00 20 24 ] - MidiSoft
- `F0 00 20 24 00 ... F7` - Karaoke Control

to be continued...