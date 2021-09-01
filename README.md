# career 9/1~

<details>
  <summary>0901</summary>

### HTML
  #### 1강
  
  server <-->  client   
    을 -----------     갑   
   전송   -----------     요청   
  
  1. client가 주소를 입력하면 WB -> 운영체제 -> HW 를 통해 통신카드(LAN)에 전송.
  2. 전송받은 요청값을 주소에 맞는 컴퓨터를 찾고 접속. (역순)
  3. WS 는 주속/????.확장자 파일을 찾음.
  4. (역순) 요청보낸 정보를 client로 보냄.
  5. client가 받은 정보를 웹으로 전송 후 보여짐.
  
  #### 2강
  HyperText Markup Language
  
  #### 3강
  Tag란??   
  <태그명 속성명1 = "속성값1" 속성명2 = "속성값2">컨텐츠명</태그명>
  
  #### 4강
  
    <html>
      <head>
        <문서를 정의하는 데이터가 위치함>
      </head>
      <body>
        <문서에 표시되는 컨텐츠가 위치함>
      </body>
    </html>   
    메타데이터 : 데이터를 설명하는 데이터(추상적개념)
        
  #### 5강
  에디터 설치, fiddle 사용
        
  #### 6강
  DTD(doctype) : 문서의 형식을 브라우저에 알려주기 위한 코드 = 문서가 어떤 스펙에 의거해서 작성된 html코드인가를 지정    
                 웹입장에서 문서들을 어떻게 해석해야 하는지 알려주기위해 문서의 초입에 지정
                 웹 규칙에 따라 초입하는 코드가 다름.
        
  #### 7강
  부모 자식 관계
    
  #### 8강    
  링크 : 문서에서 다른 문서로 이동할 수 있는 수단   
        title속성 : 부가적인 정보를 적음   
        iframe : 프레임안에 해당 주소를 띄어줌
        
  #### 9~11강
  문단 : <p> </p>   
  줄바꿈 : <br/>    
  띄어쓰기 : &nbsp;    
        
  #### 12강     
  이미지 넣기    
  <img src="url" alt="대체텍스트" width,height="크기" longdesc="이미지 관련링크,자세한 설명가능" />
 
  #### 13강 
  목록 : (ul > il, ol > li)   
        unordered list, ordered list
        
  #### 14강      
  iframe : 웹 페이지 안 다른 웹페이지(페이스북 좋아요 같은 버튼만 불러와서 누르는 방법가능)     
        scrolling="auto/yes/no"    
        
        
  #### 15강       
  이스케이프 : 태크를 문자열로 보여줌   
  &amp; → & (ampersand, U+0026), &nbsp;   
  &lt; → < (less-than sign, U+003C)   
  &gt; → > (greater-than sign, U+003E)   
  &quot; → " (quotation mark, U+0022)   
  &apos; → ' (apostrophe, U+0027)     
        
  #### 16강      
  표 만들기 : <table></table>   
  표 첫줄 제목 : <th>   
  표 내용 : <td>   
  
  <td colspan, rowspan = "2">내용</td>: 열,행을 병합
        
  #### 17강
  HEAD 태그 : <head> 태그는 문서를 설명하는 태그들이 위치하는 태그다. <body> 태그가 웹페이지가 담아내려는 정보 그 자체라면 head 태그는 body 태그의 정보를 설명하는 메타 정보라고 할 수 있다.
  
  #### 18강      
  META 태그 : 문서에 대한 정보를 기술하는 태그   
        <meta name="description/keywords" content="" />   
        description : 명시적으로 설명해줌 - 검색엔진에서 데이터를 검색할때 description내용을 중요하게 다루는 데이터 (content="html을 처음부터 다시 배우는 수업")   
        keywords : 태그와 같음, 중요키워드를 넣음 - 검색엔진에서 중요하게 다루는 데이터(content="html, code, meta, ...")   
           
        <meta http-equiv="Content-Type" content="text/html;charset=utf-8" />    
        <meta http-equiv="refresh" content="2;url=http://naver.com" /> - 2초후에 네이버url로 이동함.
        
  #### 19강
  title : 문서의 제목을 정의하는 마크업. 제목을 제목 표시줄에 출력해서 문서를 찾는데 도움을 준다. 검색엔진에서 중요한 정보로 취급된다.
        
  #### 20강
  서버와 클라이언트 : 갑을관계 요청과 응답 관계,웹브라우저 웹서버를 각 하드웨어를 통해 전송
  
  #### 21강
  form 태그 : 사용자의 데이터를 서버에 전송하는 방법이다. 일반적으로 아래와 같은 작업을 하기 위해서는 폼을 이용.   
        <form action="서버로 전송한 데이터를 수신할 url" method="데이터를 전송하는 방법">   
        action : 데이터를 어디에 보내는지 지정
        method : get - action에 입력한 url에 파라미터의 형태로 전송/ post - header의 body에 포함해서 전송.   
        get과 post의 차이점 
          
    
          
        php 써보기
  
  #### 22강        
  
          
          
          
          
          
          
</details>
