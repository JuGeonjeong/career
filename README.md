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
        get   
         * !URL에 정보가 담겨서 전송된다.!
         * 전송할 수 있는 정보의 길이가 제한되어 있다.
         * 퍼머링크로 사용될 수 있다.   
        post   
         * !header의 body에 담겨서 전송된다.!
         * URL 상에 전달한 정보가 표시되지 않는다.
         * GET에 비해서 보안상 약간의 우위에 있다. (사실상 동일하다) 단순 url에 정보가 안보임.
         * !전송할 수 있는 데이터의 길이 제한이 없다.!
         * 퍼머링크로 사용할 수 없다.
         * 서버 쪽에 어떤 작업을 명령할 때 사용한다.
         * (데이터의 기록, 삭제, 수정 등)   
          퍼머링크 : 어떠한 정보를 식별하는 고유의 주소체계
    
          
        익히기 - https://www.inflearn.com/course/html-%EA%B8%B0%EC%B4%88/lecture/103?tab=curriculum
  
  #### 22강
  텍스트 필드 : 사용자로부터 텍스트 입력 받는다. 한줄 정도의 단문에 적당하고 긴 줄의 텍스트는 <textarea>를 이용한다.   
  <input type="text name="값의 이름" value="값" disabled="disabled" readonly="readonly" />   
  disabled와 readonly의 차이 : 데이터 전송값의 유무
          
  #### 23강
  비밀번호 : input type="password"        
  
  #### 24강          
  hidden data : 화명상에 보이지 않는 컨트롤을 생성. 서버로 전달할 데이터지만 사용자에게는 노출될 필요가 없는 데이터인 경우 사용.           
  데이터를 갖고 페이지를 넘겨야 할 상황에 숨겨서 사용된다.
                              
  #### 25강
  textarea : 여러줄의 텍스트 입력 할 때 사용, 속성 추가 rows="행의 수", cols="열의 수"                            
  
  #### 26강
  radio : 여러개의 항목 중에서 하나만을 선택 할 수 있도록 제한하는 컨트롤, radio의 name값은 동일/value값은 다름   
  checked="checked" - 기본으로 선택   
  select(콤보박스) : 여러개의 항목 중에서 원하는 것을 하나만 선택하는 컨트롤로 흔히 콤보박스라고 부름.   
  check박스 : 여러개의 항목 중에서 원하는 것을 복수로 선택할 수 있게 하는 컨트롤로 체크박스라고 부름.   
  checked="checked" 여러개의 항목 체크가능/name="속성값[]" : []안에 value값을 배열로 전송.
   
  #### 27강
  파일전송 : 업로드할 파일을 선택할 수 있는 컨트롤을 생성.   
  <input type="file" name="서버쪽에서 파일을 식별하기 위한 이름" />   
  <enctype="multipart/form-data">속성이 없으면 파일전송이 안됨.
                                             
  #### 28강                                         
                                             
  #### 29강
  URL : (Uniform Resource Locator)이란 웹페이지, 이미지, 동영상과 같은 정보가 위치하는 유니크한 위치 정보.   
  http:// - scheme : 통신에 사용되는 방식,프로토콜(통신규약).
  ~~.com - hosts : 자원이 위치하고 있는 웹서버의 이름, 도메인이나 IP가 사용된다.                                 
  /~~~/~~~/~~~ - url-path : 루트 디렉토리부터 자원이 위치한 장소까지의 디렉토리와 파일명.                                 
  ?move=view - query : 웹서버에 넘기는 추가적인 질문.                                 
  #root - bookmark : 하이퍼링크를 클릭했을 때 특정 위치로 이동하기 위해서 사용.지정된 스크롤 위치.   
                                
  #### 30강 
  path(경로)   
  상대경로 : 문서를 기준으로 한 다른 리소스들의 위치정보.   
  절대경로 : 문서의 위치를 가르키는 도메인을 포함한 전체 위치정보.   
                                
  https://www.inflearn.com/course/html-%EA%B8%B0%EC%B4%88/lecture/113?tab=curriculum
  
  #### 31강                              
  검색엔진최적화(SEO) : 검색엔진에 잘 노출될 수 있도록 하는 활동.   
  HTML과 검색엔진 최적화의 관계 : 검색은 정보를 찾는 행위이고, 웹에서 정보를 표현하는 언어는 HTML이기 때문에 의미에 맞는 HTML 코딩은 자연스럽게 검색엔진 최적화에 기여한다.
  
                                
  ### 후기
  학원에서 팀프로젝트 하면서 개념을 이해하고 사용했다기 보단 필요한것만 구글링해서 부분적으로 사용했는데 흩날리는 개념들을 정리할 수 있어서 좋았다.                                 
  이스케이프, php와 절대경로,상대경로, 검색엔진최적화 한번 더 봐야함!
  한번 더 봐야겠고 너무 졸려서 일단 자야겠다.
                                
</details>
                                
<details>
                                <summary>0902</summary> 

  <img width="1256" alt="스크린샷 2021-09-02 오후 3 17 01" src="https://user-images.githubusercontent.com/81910342/131792387-24d1ffa9-27b0-4d98-a280-c587d8fc0b12.png">                              
                                
</details>
