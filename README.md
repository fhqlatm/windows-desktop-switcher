# 윈도우10 가상 데스크톱 전환
윈도우10 가상 데스크톱 간의 전환을 용이하게 만들어주는 AutoHotKey 스크립트(.ahk)입니다.

## Installation
1. AutoHokKey ([link](https://www.autohotkey.com/)) 설치

2. desktop_switcher.ahk 스크립트 실행

3. (Optional) <Win> + R -> shell:startup 입력하여 시작프로그램 등록

## Usage
        <Win> + <Num> : <Num> 번호에 해당하는 가상 데스크톱으로 전환
        <Win> + Q     : 이전 데스크톱으로 전환 (= <Ctrl> + <Win> + <←>)
        <Win> + W     : 다음 데스크톱으로 전환 (= <Ctrl> + <Win> + <→>)

이전 및 다음 데스크톱으로의 전환은 처음 데스크톱과 마지막 데스크톱이 맞닿은 것처럼 동작합니다. (Loop)

### Reference
https://github.com/sdias/win-10-virtual-desktop-enhancer

https://github.com/searene/windows-desktop-switcher

더 많은 기능을 원하시거나 원본 스크립트를 참조하시려면 위 링크를 확인해주세요.
