###### calc()
```css
#contents {
  width: calc(100% - 200px);
  height: calc(100vh - 60px - padding); /* padding 값을 연산식에 포함시키는 것은 부분적으로 적용됨 !! 확인 필요 */
  /* start - padding 속성 설정할 경우 박스 사이즈를 고정하고 내부로 padding 값을 적용하기 위하여 필수 적용 */
  padding: 20px;
  box-sizing: border-box; 
  /* end */
  background: #ebeef0;
}
```
###### checkbox alignment
```css
.checkbox_align {
    position: relative;
    top: number of pixel;
}
```
