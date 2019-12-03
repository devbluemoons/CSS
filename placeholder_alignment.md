## placeholder 정렬값 설정  
  
placeholder 기본값은 오른쪽 정렬이다  
  
왼쪽 정렬이 필요할 경우 적용대상이 되는 css 파일에서 아래와 같이 적용한다

``` css
/* webkit solution */
::-webkit-input-placeholder {
  text-align: left;
}
/* mozilla solution */
input:-moz-placeholder {
  text-align: left;
}
```
   
