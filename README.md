# potato's style
귀차니즘을 위해서 만든 스타일입니다.   
html 태그의 클래스 이름만 지정해서 스타일을 적용해 줍니다.    

# 사용설명서
## 기본 준비핟기
1. 이 리포지토리를 복제하거나 다운받으세요.
2. 적절한 위치에 스타일을 넣어줍니다.
3. html에서 이 스타일을 불러옵니다.
```
    <link rel="stylesheet" href="./style.css">   
    <link rel="stylesheet" href="./box.css">    
    <link rel="stylesheet" href="./border.css">    
    <link rel="stylesheet" href="./button.css">    
    <link rel="stylesheet" href="./font.css">    
    <link rel="stylesheet" href="./border.css">    
```

<link rel="stylesheet" href="./style.css">   
<link rel="stylesheet" href="./box.css">    
<link rel="stylesheet" href="./border.css">    
<link rel="stylesheet" href="./button.css">    
<link rel="stylesheet" href="./font.css">    
<link rel="stylesheet" href="./border.css">   

4. 준비가 완료되었습니다! 아래 설명서를 잘 읽어주시기 바랍니다!   

## box.css
태그의 기본적인 배경색과 내부에 있는 택스트를 배경색의 보색으로 적용합니다. 만약 택스트 색깔이 맘에 들지 않은 경우 태그에서 스타일로 덮어쓰시면 됩니다.
- 사용방법
```
    <div class = "box-색깔이름">내용</div>
```
- 적용 예
```
    <div class = "box-green">이것은 초록색 입니다.</div>
```
<div class = "box-green">이것은 초록색 입니다.</div>

* 참고: 색깔 이름은 <a href = "https://www.w3schools.com/colors/colors_names.asp">여기<a>를 참고했습니다.
