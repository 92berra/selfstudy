# Screenshot(Recording) to GIF
 
#### Install

```
brew install ffmpeg
```

<br/>

#### Transform

```
ffmpeg -i input.mov -vf "fps=10,scale=320:-1:flags=lanczos" output.gif
```

<li>fps=10 : 초 당 프레임 수</li>
<li>scale=320:-1 : 너비를 320픽셀로 조정하며 높이는 비율에 맞게 자동으로 설정</li>

<br/>
<br/>
<br/>
<br/>

<div align='center'>
92berra ©2024
</div>