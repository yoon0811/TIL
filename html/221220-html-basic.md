감싸고 있는 건 조상 요소, 
자식 요소는 후손요소라고도 한다 , 
자식을 감싸는 바로 위는 부모 요소 

class 와 lang 과 같은 것은 전역 속성이라고 하고 
어떤 태그에도 붙일 수 있다. 

div 요소 포커스 불가능 포커스를 받아야하는 경우에는 tabindex = '-1' contenteditable 을 넣어 준다 (-1 을 넣을 경우에는 음수여서 순서를 따라 갈 때 무시됨. 0을 포함한 양수를 넣을 것 ) 

contenteditable


****인라인 요소에 width,height, margin-top/bottom, padding-top/bottom은 적용불가 
display:block 요소로 바꿔야함 
레이아웃 잡을 때 인라인 요소 쓰지 말 것 


position:fixed 를 하면 disply:block으로 적용되는 것 
중복으로 적지 말 것 

word-break: keep-all 단여 단위로 줄바꿈을 한다. 
(한글은 자바스크립트에서 별도처리해야하는게 있음)

