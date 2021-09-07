# career 9/1~

<details>
  <summary>0901 HTML강의</summary>

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
                                <summary>0902 CSS강의</summary> 

  <img width="1256" alt="스크린샷 2021-09-02 오후 3 17 01" src="https://user-images.githubusercontent.com/81910342/131792387-24d1ffa9-27b0-4d98-a280-c587d8fc0b12.png">                              

 <img width="1406" alt="스크린샷 2021-09-02 오후 4 21 46" src="https://user-images.githubusercontent.com/81910342/131800517-123223c0-1fbf-4343-9f10-eddebb9bf07e.png">

<img width="1389" alt="스크린샷 2021-09-02 오후 4 32 56" src="https://user-images.githubusercontent.com/81910342/131801851-17b1e88d-dda9-4c64-84b4-ca8c9ac202dc.png">


<img width="1448" alt="스크린샷 2021-09-02 오후 6 44 26" src="https://user-images.githubusercontent.com/81910342/131822018-e0a0ba83-2ce3-48bd-811b-64728e153e79.png">



</details>

<details>
                                <summary>0903 CSS강의</summary> 


<img width="434" alt="스크린샷 2021-09-03 오전 11 46 25" src="https://user-images.githubusercontent.com/81910342/131942981-1adc16d6-ce24-4bba-bd37-dc1be2661823.png">
<img width="1453" alt="스크린샷 2021-09-03 오전 11 55 11" src="https://user-images.githubusercontent.com/81910342/131943690-0cde67fc-ab6c-4090-b2f9-7057e1e3a15f.png">



</details>

<details>
                                <summary>0904 CSS</summary> 

  flex로 동적페이지 오류, html이미지 확실하게 알기, 

</details>

<details>
                                <summary>0905 CSS</summary> 

  flex로 동적페이지 만들기   
  grid로 동적페이지 만들기

</details>


<details>
                                <summary>0906 HTTP 강의</summary> 

    
   [인터넷 네트워크]
   ## 인터넷 통신

   #### 클라이언트와 서버를 연결해주는 인터넷망(단순 X, 수많은 노드를 거침..)을 어떻게 거쳐서 전송이 되는가???   
>  클라이언트와 서버간의 요청,응답하며 조건이 맞는 인터넷망을 거쳐 데이터를 주고 받음.   
     
  * IP 프로토콜
>  <details>
>  
>  [역할]   
>  주소부여   
>  지정한 IP주소에 데이터 전달   
>  패킷이라는 통신 단위로 데이터 전달   
>  패킷이란 ?   
>  출발지 IP, 목적지IP, 기타.. 를 전송데이터에 씌움   
>  데이터의 IP주소를 지정해줌   
>     
>  [한계]   
>  비연결성 - 도착지IP대상이 없거나 서비스 불가 상태에도 전송이 됨.(일방적)   
>  비신뢰성 - 인터넷망에서 패킷이 사라지거나 순서대로 안올 수 있음.   
>  프로그램구분 - 같은 IP에서 여러서버를 통신하는 경우.   
>     
>  [인터넷 프로토콜 스택의 4계층]   
>  애플리케이션 계층 - HTTP,FTP.  
>  전송 계층 - TCP,UDP.  
>  인터넷 계층 - IP.  
>  네트워크 인터페이스 계층   
>  <img width="794" alt="스크린샷 2021-09-06 오후 7 27 42" src="https://user-images.githubusercontent.com/81910342/132203430-1ed65b7a-65a6-4abf-82cc-3e9a71fd488e.png">
>   
>  
>  </details>
  
  * TCP, UDP
>  <details>
>  
>  <img width="860" alt="스크린샷 2021-09-06 오후 7 28 51" src="https://user-images.githubusercontent.com/81910342/132203553-c8e6dab5-5470-49c4-b417-a49329991cd2.png">   
>  
>  [TCP란?]   
>  전송 제어 프로토콜(Transmission Control Protocol)   
>  TCP는 근거리 통신망이나 인트라넷, 인터넷에 연결된 컴퓨터에서 실행되는 프로그램 간에 일련의 옥텟을 안정적으로, 순서대로, 에러없이 교환할 수 있게 한다. 
>  IP패킷의 TCP세그먼트(출발지PORT, 목적지PORT, 전송제어, 순서, 검증 정보, ...)를 포함해줌으로써 IP의 한계를 해결해줌.   
>  신뢰할 수 있는 프로토콜, 현재 대부분 TCP를 사용   
>  [특징]   
>     
>  
>  |feature|Description|
>  |:--:|:--:|
>  |연결지향 - TCP 3 way handshake(가상 연결)|<img width="889" alt="스크린샷 2021-09-06 오후 7 51 30" src="https://user-images.githubusercontent.com/81910342/132206384-2295616a-48f5-4772-89d1-d6bd066f6acc.png">|
>  |데이터 전달 보증|   <img width="856" alt="스크린샷 2021-09-06 오후 7 52 05" src="https://user-images.githubusercontent.com/81910342/132206450-b3388241-77e3-40d2-bfd5-5166db31132f.png">|
>  |순서 보장|<img width="870" alt="스크린샷 2021-09-06 오후 7 52 23" src="https://user-images.githubusercontent.com/81910342/132206487-36054f7a-6323-4ee6-beb4-a83d6d374b18.png">|
>
>     
>  [UDP란?]   
>  TCP의 안정성을 필요로 하지 않는 애플리케이션의 경우 일반적으로 TCP 대신 비접속형 사용자 데이터그램 프로토콜(User Datagram Protocol)을 사용한다. 이것은 전달 확인 및 순차 보장 기능이 없는 대신 오버헤드가 작고 지연시간이 짧다는 장점이 있다.   
>  IP주소 + PORT주소 + 체크섬 정도만 추가(기능이 거의 없음)   
>  IP와 거의 같음.   
>  
   |.|feature|Description|
>  |:--:|:--:|:--:|
>
>  </details>
  
  * PORT
>  <details>
>  
>  [PORT란?]   
>  한 컴퓨터에서 여러프로그램 사용시 어느프로그램이 내가 어떤서버를 사용할지 연결해주는 번호   
>  포트번호는 어떤프로그램에 접속할지 알려주는 번호   
>  IP는 아파트,PORT는 몇동몇호   
>  FTP - 20, 21.  
>  TELNET - 23.  
>  HTTP - 80.  
>  HTTPS - 443.  
>  
>  </details>
  
  * DNS
>  <details>
>  
>  [DNS란?]   
>  도메인 네임 시스템(Domain Name System)
>  IP의 전화번호부   
>  도메인 명을 IP주소로 변환
>  <img width="856" alt="스크린샷 2021-09-06 오후 8 10 53" src="https://user-images.githubusercontent.com/81910342/132208556-5619ad84-2525-496e-9bfe-920684320a4d.png">
>  
>  </details>

---
   
   ## URI와 웹 브라우저 요청 흐름   
   #### URI.  
   URI는 로케이터(Locator), 이름(Name) 또는 둘 다 추가로 분류될 수 있다.   
   <img width="878" alt="스크린샷 2021-09-06 오후 8 18 04" src="https://user-images.githubusercontent.com/81910342/132209424-ba841a43-e862-4a54-939f-47c27eaad2e1.png">   
      
   * URL - Locator : 리소스가 있는 위치를 지정    
   * URN - Name : 리소스에 이름을 부여.   
   * 위치는 변할 수 있지만, 이름은 변하지 않는다.   
   * URN 이름만으로 실제 리소스를 찾을 수 있는 방법이 보편화 되지 않음.(과거에 추진하다 잘 안됨)   
      
   [문법]   
   프로토콜/호스트명/포트번호/패스/쿼리파라미터   
   ex)https://www.google.com:443/search?q=hello&hl=ko.  
      
   프로토콜 : 어떤 방식으로 자원에 접근할 것인가 하는 약속 규칙(http, https, ftp 등등..)   
   패스 : 리소스경로(path), 계층적 구조   
   쿼리 : key=value 형태, ?로 시작, &로 추가기능, query parameter/query string 등으로 불림, 웹서버에 제공하는 파라미터, 문자형태
   -fragment : html내부 북마크 등에 사용, 서버에 전송하는 정보 아님   
      
   #### 웹 브라우저 요청 흐름.   
   |feature|Description|
   |:--:|:--:|
   |요청메세지|<img width="779" alt="스크린샷 2021-09-06 오후 8 45 12" src="https://user-images.githubusercontent.com/81910342/132212567-aeb6e471-2095-4d0e-87db-c87bd9e1535b.png">|
   |응답메세지|<img width="595" alt="스크린샷 2021-09-06 오후 8 45 45" src="https://user-images.githubusercontent.com/81910342/132212632-2de6a551-a245-4cdc-a44f-b8f829cef0ac.png">|
   
   ---
   
   ## HTTP
   * 클라이언트 서버구조   
   ** Request Response 구조   
   ** 클라이언트는 서버에 요청을 보내고, 응답을 대기   
   ** 서버가 요청에 대한 결과를 만들어서 응답   
   
      
   ---
      
   ## 무상태 프로토콜(Stateless)
   
   서버가 클라이언트의 상태를 보존하지 않음   
   장점 : 서버 확장성 높음(스케일 아웃)
   단점 : 클라이언트가 추가 데이터 전송   
   
   ### Stateful, Stateless 차이
   유상태, 무상태   
         
   * Stateful : 서버와의 상태 보존 / 중간에 다른 서버로 바뀌면 안된다.(바뀔시 서버에 정보가 안남아 있음)   
   * Stateless : 서버와의 상태 보존 안됨 -> / 서버가 바뀌어도 됨. 무한한 서버 증설 가능.   
      
   [실무의 한계]   
   모든것을 무상태로 설계 할 수 있는 경우도 있고 없는 경우도 있다.   
   무상태 : 로그인이 필요 없는 단순한 서비스 소개 화면 등등...   
   상태유지 : 로그인 등등 ...   
   로그인한 사용자의 경우 로그인 했다는 상태를 서버에 유지   
   일반적을 브라우저 쿠키와 서버 세션등을 사용해서 상태 유지   
   상태 유지는 최소한만 사용   
      
   ## 서버로 넘어가기전 내용들은 http메세지에 담고 있나???!!!
   
       
   내일은 비연결성부터 다시 공부&정리


</details>
