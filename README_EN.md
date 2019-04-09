# KeyViewer
#### A Simple Customizable KeyViewer by Orb_H

## Warning
If you run some games, key input might be interrupted. In those cases, run KeyViewer.exe as administrator.

## How to write config.txt
1. On the first line, write width and height of container, not window. ( e.g. width 400px, height 300px: 400 300 )
2. On the second line, write RGB of background color ( e.g. Indigo: 0 0 128 )
3. On the third line, write RGB of foreground color ( e.g. White: 255 255 255 )
4. On the fourth line, write RGB of highlighted background color ( e.g. Skyblue: 0 191 255 )
5. On the other lines, write Virtual Key value, text, location, and size ( e.g. Create an A key on (20, 30), with size of (40, 50), and with text of 'A': 65 A 20 30 40 50 )
6. Repeat 5

## Example config.txt
```300 130 // Container size
64 64 64 // Background Color(Dark Gray)
255 255 255 // Foreground Color(White)
128 191 255 // highlighted Background Color(Skyblue)
160 Shift 10 10 100 50 // VirtKey Text posx posy sizex sizey, below are same
162 Ctrl 10 70 75 50
37 ← 120 70 50 50
38 ↑ 180 10 50 50
39 → 240 70 50 50
40 ↓ 180 70 50 50
```

### Interesting things about config.txt
- You can locate same key on multiple positions.
- You can draw keys making intersection.
- You can write comments. But you have to append it after the complete line, without line feed.
