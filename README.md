# KeyViewer
#### A Simple KeyViewer by Orb_H

## How to write config.txt (한국어)
1. 첫 번째 줄에는 창의 크기(정확히는 틀 제외)의 가로와 세로를 스페이스바로 구분하여 작성( ex) 가로 400px, 세로 300px: 400 300 )
2. 두 번째 줄에는 배경색의 RGB를 스페이스바로 구분하여 작성 ( ex) 남색: 0 0 128 )
3. 세 번째 줄에는 글자색의 RGB를 스페이스바로 구분하여 작성 ( ex) 흰색: 255 255 255 )
4. 네 번째 줄에는 키를 눌렀을 때의 배경색의 RGB를 스페이스바로 구분하여 작성 ( ex) 하늘색: 0 191 255 )
5. 그 뒤로는 매 줄마다 키의 특정값, 들어갈 텍스트, 위치, 크기를 스페이스바로 구분하여 작성 ( ex) A키를 (40, 50)의 크기로 (20, 30)에 배치, 표시는 'A'로: 65 A 20 30 40 50 )
6. 5 반복

## Example config.txt (한국어)
```300 130 // 창 크기
64 64 64 // 배경색(진한 회색)
255 255 255 // 글씨색(흰색)
128 191 255 // 눌렀을 때 색깔(연한 하늘색)
160 Shift 10 10 100 50 // VirtKey 텍스트 posx posy sizex sizey, 아래로 쭉
162 Ctrl 10 70 75 50
37 ← 120 70 50 50
38 ↑ 180 10 50 50
39 → 240 70 50 50
40 ↓ 180 70 50 50
```

### Interesting things about config.txt (한국어)
- 같은 키를 여러 군데에 배치할 수 있다.
- 키를 겹쳐서 표시할 수 있다.
- 주석을 달 수 있다. 단, 해당하는 줄의 모든 원소를 적은 뒤 개행을 하지 않고 그 뒤로 붙여 적는다.

<hr/>

## How to write config.txt (English)
1. On the first line, write width and height of container, not window. ( e.g. width 400px, height 300px: 400 300 )
2. On the second line, write RGB of background color ( e.g. Indigo: 0 0 128 )
3. On the third line, write RGB of foreground color ( e.g. White: 255 255 255 )
4. On the fourth line, write RGB of highlighted background color ( e.g. Skyblue: 0 191 255 )
5. On the other lines, write Virtual Key value, text, location, and size ( e.g. Create an A key on (20, 30), with size of (40, 50), and with text of 'A': 65 A 20 30 40 50 )
6. Repeat 5

## Example config.txt (English)
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

### Interesting things about config.txt (English)
- You can locate same key on multiple positions.
- You can draw keys making intersection.
- You can write comments. But you have to append it after the complete line, without line feed.
