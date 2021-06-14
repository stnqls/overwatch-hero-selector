# 🎮 오버워치 캐릭터 선택하는 페이지

## 완성된 페이지
img<width = "80%" src = "https://user-images.githubusercontent.com/81519415/121843684-b1765500-cd1d-11eb-8a01-aa6fff38e253.png"/>
---
### 캐릭터 선택시 효과
```css
.hero {
  width: 80px;
  height: 84px;
  border: 3px solid #fff;
  border-radius: 10px;
  margin: 4px;
  background-color: #555;
  box-sizing: border-box;
  transform: skewX(-14deg);
  overflow: hidden;
  transition: 
    transform .1s,
    background-color .6s;
}
.hero:hover {
  background-color: #ff9c00;
  transform: scale(1.3) skewX(-14deg);
  z-index: 1;
}
```
