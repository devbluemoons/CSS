## position
- static : top, right, bottom, left, z-index 속성이 아무런 영향도 주지 않습니다. 기본값입니다.
- relative : 자기 자신을 기준으로 top, right, bottom, left의 값에 따라 오프셋을 적용합니다.
- absolute : 가장 가까운 위치 지정 조상 요소에 대해 상대적으로 배치합니다.
- fixed : 
	- 뷰포트(viewport)의 초기 컨테이닝 블록을 기준으로 한 위치에 배치됩니다.
	- 단, 요소의 조상 중 하나가 transform, perspective, filter 속성 중 어느 하나라도 none이 아니라면
	- (CSS Transforms Spec 참조) 뷰포트 대신 그 조상을 컨테이닝 블록으로 삼습니다
- sticky : 
	- 테이블 관련 요소를 포함해 가장 가까운 스크롤되는 조상과 컨테이닝 블록(가장 가까운 블록 레벨 조상)을 기준으로
	- top, right, bottom, left의 값에 따라 오프셋을 적용합니다. 오프셋은 다른 요소에는 영향을 주지 않습니다
  
[Ref.] https://developer.mozilla.org/ko/docs/Web/CSS/position
  
###### sticky
```css
thead th {
	z-index: 100;
	background: #ddebf5; 
	font-weight: bold; 
	position: sticky;
	top: 0;
}
```
  
###### set border for sticky thead 
```css
th:before {
	content:'';
	position:absolute;
	left: 0;
	top: 0;
	width:100%;
	border-top:1px solid #7d9aae;
}

th:after {
	content:'';
	position:absolute;
	left: 0;
	bottom: 0;
	width:100%;
	border-bottom:1px solid #C2D2DF;
}
```
