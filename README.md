# career 9/1~
## 1주차
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

## 2주차
<details>
                                <summary>0906~0908 HTTP 강의</summary> 

    
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
>   ||TCP|UDP|
>   |:--:|:--:|:--:|
>   |연결방식|연결형 프로토콜 / 연결 후 통신 / 1:1통신방식|비연결형 프로토콜 / 연결 없이 통신 / 1:1,1:N,N:N통신방식|
>   |특징|<img width="329" alt="스크린샷 2021-09-07 오전 11 12 22" src="https://user-images.githubusercontent.com/81910342/132273703-fa5e09c0-ef67-41d2-be1c-17b43c6f3e38.png">|<img width="325" alt="스크린샷 2021-09-07 오전 11 12 33" src="https://user-images.githubusercontent.com/81910342/132273712-f485fba3-1cb5-4f1a-a04c-5d608ff69705.png">|
>   |관련클래스|.Socket / .ServerSocket|/.DatagramSocket / .DatagramPacket / .MultucastSocket
>
>
>   
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
   scheme:[//[user[:password@]host[:port]][/path][?query][#fragment]   
   <생략>프로토콜/호스트명/포트번호/패스/쿼리파라미터   
   ex)https://www.google.com:443/search?q=hello&hl=ko.  
   
>  <details>
>  <summary>예시</summary>
>  
>  <img width="781" alt="스크린샷 2021-09-07 오후 12 31 30" src="https://user-images.githubusercontent.com/81910342/132280031-edd3fd26-bc9c-4164-89b1-393a462c04cf.png">.  
>  <img width="789" alt="스크린샷 2021-09-07 오후 12 31 44" src="https://user-images.githubusercontent.com/81910342/132280048-b3a04bb1-97e8-4617-8d4f-de69bedd86f5.png">.  
>  <img width="794" alt="스크린샷 2021-09-07 오후 12 31 . 5" src="https://user-images.githubusercontent.com/81910342/132280063-3b5f09b9-c25d-4973-8afe-a30177ce788c.png">.  
>  <img width="810" alt="스크린샷 2021-09-07 오후 12 32 28" src="https://user-images.githubusercontent.com/81910342/132280111-a5681874-443d-4eee-8944-19bd00aad6fb.png">.  
>  <img width="775" alt="스크린샷 2021-09-07 오후 12 32 47" src="https://user-images.githubusercontent.com/81910342/132280145-6c0b3ebd-a675-4418-8040-447535d349de.png">.  
>  <img width="757" alt="스크린샷 2021-09-07 오후 12 33 14" src="https://user-images.githubusercontent.com/81910342/132280179-80933955-437c-48bb-ac87-bb0a05457282.png">.  
>  
>  </details>
      
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
       * Request Response 구조   
       * 클라이언트는 서버에 요청을 보내고, 응답을 대기   
       * 서버가 요청에 대한 결과를 만들어서 응답   
      
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
   
   # 0907
   ## 비연결성
   [문제]   
   TCP/IP 연결유지모델(여러클라이언트에 연결유지, 직접접속하지 않아도 자원소모)   
      
   [특징]    
   HTTP는 기본이 연결을 유지하지 않는 모델.   
   일반적으로 초 단위 이하의 빠른 속도로 응답.   
   실제 서버에서 동시에 처리하는 요청은 수십개 이하로 매우적음.   
   ex) 웹 브라우저에서 계속 연속해서 검색버튼을 누르지 않음.   
   서버자원을 매우 효율적으로 사용 할 수 없음.   
      
   [한계]   
   비연결성 = TCP/IP의 연결을 새로 맺어야함(3way handshake) -> 시간이 늘어남.   
   웹 브라우저를 사이트를 요청하면 HTML뿐만 아니라 자바스크립트, CSS, 추가이미지 등등 수많은 자원이 함께 다운로드.   
      
   [극복]   
   HTTP 지속연결(Persistent Connerctions)로 문제해결 <- HTTP/2 , HTTP/3 버전으로 더 많은 최적화 됨.   
   ex) 수천명이 접속중이어도 설제 동시에 처리하는 요청은 몇십개 밖에 안됨.
   
   ---
   ## HTTP 메세지
   [구조]   
   <img width="578" alt="스크린샷 2021-09-07 오후 12 03 21" src="https://user-images.githubusercontent.com/81910342/132277774-d86b7beb-4401-464b-b3bf-297778491571.png">
      
   [시작라인]   
   - 요청메세지   
   HTTP메서드, 요청대상, HTTP version.  
   GET/POST/PUT/DELETE, 경로, HTTP1.1/2/3   
      
   - 응답메세지   
   HTTP version, 상태코드, 이유문구   
      
   [헤더]   
   HTTP 전송에 필요한 모든 부가정보   
      
   [메세지]   
   실제 전송할 데이터   
   HTML 문서, 이미지, 영상, JSON 등등 byte로 표현 할 수 있는 모든 데이터 전송 가능   
      
   !!!HTTP는 단순, 스펙도 읽어보자!!!   
   메세지도 매우 단순, 단순하지만 확장가능 한 기술(크게 성공하는 기술들의 공통점)   
   
   ---
   
   ## HTTP 메서드 - GET/POST/PUT/DATCH/DELETE/HEAD/OPTION/CONNECT/TRACE
       
   #### [GET]   
   리소스 조회 / URL의 쿼리파라미터,쿼리스프링을 통해 전달   
      
   #### [POST]   
   요청 데이터 처리 / 메세지 바디를 통해 서버로 요청 데이터 전달 / 주로 신규 리소스 등록, 프로세스 처리에 사용   
   !! 단순히 생성, 변경하는 것을 넘어 프로세스를 처리해야 하는 경우   
   ex) 컨트롤 URI.  
   다른 메서드로 처리하기 애매한경우    
   ex) JSON으로 조회 데이터를 넘겨야 하는데, GET메서드를 사용하기 애매한 경우   
   메세지를 담아서 보내는 모든 것을 할 수 있다.

      
   #### [PUT]    
   리소스를 대체 / 리소스 보유시 대체 / 없을시 생성   
   !! 완전히 대체함. 갈아치움   
   
   #### [PATCH]
   리소스 부분 변경   
      
   #### [DELETE]
   리소스 제거
      
   ---
   
   ## HTTP 메서드 속성
   #### 안전 / 멱등 / 캐시가능    
   <img width="1080" alt="스크린샷 2021-09-07 오후 2 02 17" src="https://user-images.githubusercontent.com/81910342/132286985-4a6b9e16-b942-44c7-af4b-1039088cdd1b.png">
      
   #### 안전 : GET, HEAD   
   호출해도 리소스를 변경하지 않는다.   
      
   #### 멱등 : 자동 복구 메커니즘 / 서버가 TIMEOUT 등으로 정상 응답을 못주었을때, 클라이언트가 같은 요청을 다시 해도되는가? 판단 근거 
   호출의 횟수와 상관없이 결과값이 같음.   
   GET - 몇번조회를 해도 결과가 같음   
   PUT - 결과를 대체함 / 멱등은 외부 요인으로 중간에 리소스가 변경되는 것 까지는 고려하지는 않는다.   
   DELETE - 결과를 삭제함. 삭제 된 결과가 같다   
   
   #### 캐시가능 : GET, HEAD, POST, PATCH   
   응답결과 리소스를 캐시해서 사용해도 되는가?   
   GET, HEAD - URL만 key로 잡고 캐쉬, 실무에서 주로 쓰임
   POST, PATCH - 본문내용까지 캐쉬 key로 고려해야 하기 때문에 사용안함 = 구현이 어려움.   
   
   ---
   
   ## HTTP 메서드 활용
   데이터 전달 방식   
   client -> server   
      
   데이터 전달 대표 2가지 방식   
   
   #### 쿼리파라미터 - URI 끝에 key=value 형식   
   GET / 주로 정렬 필터(검색어)   
      
   #### HTTP 메세지 바디를 통한 데이터 전송   
   POST, PUT, PATCH / 회원가입, 상품주문, 리소스등록, 변경 등에 사용   
   
   ### client에서 server로 전송시 4가지 상황
   * 정적데이터 조회 - 이미지, 정적테스트 문서 : 단순 경로(쿼리파라미터X).  
      
   * 동적데이터 조회 - GET사용 / 주로 검색, 게시판 목록에서 정렬 필터(검색어)   
   조회 조건을 줄여주는 필터, 조회 결과를 정렬하는 정렬 조건에 주로 사용   
   GET은 쿼리파라미터 사용해서 데이터를 전달   
      
   * HTML Form 데이터 전송   
   POST 전송 - 저장   
   
>   <details>
>   
>   <img width="836" alt="스크린샷 2021-09-07 오후 3 03 31" src="https://user-images.githubusercontent.com/81910342/132292328-95b96fee-431d-41da-bdce-6c236eba5fc1.png">    
>   바디에 경로   
>      
>   GET 전송 - 저장   
>   <img width="818" alt="스크린샷 2021-09-07 오후 3 06 17" src="https://user-images.githubusercontent.com/81910342/132292603-d7150d7e-787b-4a12-9303-063c144ff2cb.png">    
>   URI에 경로   
>      
>   mulitpart/form-data    
>   <img width="853" alt="스크린샷 2021-09-07 오후 3 11 25" src="https://user-images.githubusercontent.com/81910342/132293128-ba9996db-e124-47ee-9687-09d5ff1e79a2.png">   
>      
>   메세지를 자동으로 만들고 바운더리대로 짤라주고   
>   <img width="556" alt="스크린샷 2021-09-07 오후 3 15 37" src="https://user-images.githubusercontent.com/81910342/132293640-9424b2e3-0641-40fa-bb56-4536bf4f6ef1.png">   
>
>   * HTTP API 데이터 전송   
>   HTML form 형식을 안쓰는 거의 모든 상황, 서버 to 서버, 앱클라이언트나 웹클라이언트(Ajax) 통신
>   <img width="488" alt="스크린샷 2021-09-07 오후 3 27 03" src="https://user-images.githubusercontent.com/81910342/132295016-ec1a4676-6c1e-40bd-9c98-50f559f9e4ff.png">   
>   </details>

   ---

   ## HTTP 메서드 설계
   
      
   |POST|PUT|HTML FORM|
   |:--:|:--:|:--:|
   |<img width="543" alt="스크린샷 2021-09-08 오전 10 31 51" src="https://user-images.githubusercontent.com/81910342/132431410-e084d3df-4426-46e5-9f96-c3dd00df700e.png">|<img width="599" alt="스크린샷 2021-09-08 오전 10 30 53" src="https://user-images.githubusercontent.com/81910342/132431321-68f14305-1278-437a-baf0-c43652861f7c.png">|<img width="708" alt="스크린샷 2021-09-08 오전 11 24 53" src="https://user-images.githubusercontent.com/81910342/132436231-4feab1b5-e35a-4131-8cc7-ded739b88059.png">|
   
   ### 대표 2가지 방법 대부분 POST사용
   1. POST 기반 : 컬렉션   
   ex)회원관리 API제공    
      
   2. PUT 기반 : 스토어   
   ex)정적 컨텐츠 관리, 원격 파일 관리   
       
   * HTML FORM 사용   
   웹 페이지 회원관리, GET/POST만 지원   
      
   <img width="379" alt="스크린샷 2021-09-08 오전 11 36 05" src="https://user-images.githubusercontent.com/81910342/132437316-4f25692c-e244-413a-97e5-da8907e1d4f4.png">
   
   
   정리는 내일 동영상 로딩이안됨...ㄴㅇㅅ   
      
   ---
   
   # 0908   
      
   ## HTTP 상태코드
   클라이언트가 보낸 요청의 처리 상태를 응답에서 알려주는 기능
   
   1xx : 요청이되어 수신처리 -> 거의사용안함.   
   2xx : 요청 정상 처리.   
   3xx : 요청을 완료하면 추가 행동이 필요.   
   4xx : Client 오류, 잘못된 문법등으로 서버가 요철을 수행 할 수 없음.   
   5xx : server 오류, 서버가 정상 ㅛ청을 처리하지 못함.   
      
   <details>
   
   200 : 요청성공   
   201 : 요청성공, 새로운 리소스가 생성됨(created)   
   202 : 요청이 접수되었으나 처리 완료되지 않음. (잘사용안함)   
      
      
      
   3xx : redirection 요청을 완료하기 위해 유저 에이전트의 추가 조치 필요   
   * 영구 리다이렉션 - 특정 리소스 URI가 영구적으로 이동 ex)/members -> /users   
      * 301, 308 : 원래의 URL을 사용 X, 검색엔진 등에서도 변경 인지.   
      
   * 일시 리다이렉션 - 일시적인 변경 ex)주문완료 후 주문 내역이동 PRG -> POST/REDIRECTION/GET.  
      * 302 : Found/리다이렉트시 요청 메서드가 GET으로 변경 될 수 있음 = 본문이 제거 될 수 있음.     
      * 307 : Temporary Redirect/리다이렉트시 요청 메서드가 변경되면 안됨!   
      * 303 : See Other/메서드가 GET으로 변경.    
         PRG   
      <img width="985" alt="스크린샷 2021-09-08 오후 12 03 41" src="https://user-images.githubusercontent.com/81910342/132439733-20ba150f-8479-4359-9fe7-7e6a1f7d01b9.png">   
      
      새로고침해도 GET으로 결과 화면만 조회   
        
   * 특수 리다이렉션 - 결과 대신 캐시 사용   
      * 300 : Multiple Choices/안씀.   
      * 304 : Not Modified/캐시목적으로 사용, 클라이언트에게 리소스가 수정되지 않았음을 알려준다. 따라서 클라이언트는 로컬PC에 저장된 캐시를 재사용한다. (캐시로 리다이렉트 한다.)   
         
            
               
   4xx : 요청에 잘못된 문법등으로 서버가 요청   
   클라이언트가 이미 잘못된 요청, 요청을 수정하지 않는 이상 복구 불가능.   
      
   400 : Bad Request/Client가 잘못 요청 ex) parameter가 잘못되거나, API 스펙이 막지 않을때    
   401 : Unauthorized/인증되지 않음. 인증하는 방법 설명, 본인이 누구인지 확인(로그인), 특정 리소스에 접근할 수 있는 권한, 인증이 있어야 인가가 있음.   
   403 : Forbidden/서버가 요청을 이해했지만 승인을 거부함,어드민 등급이 아닌 사용자가 로그인을 했지만 어드민 등급의 리소스에 접근하는 경우.   
   404 : Not Found/요청 리소스를 찾을 수 없음, 요청 리소스가 서버에 없음, 클라이언트가 권한이 부족한 리소스에 접근 할때 해당 리소스를 숨기고 싶을때.   
       
          
             
   5xx : 서버 오류(왠만해서는 절대 내면 안됨)   
   500 : Internal Server Error/서버 문제로 오류 발생, 애매하면 500 오류, 서버 내부 문제로 오류 발생   
   503 : Service Unavailable/서비스 이용 불가, 서버가일시적인 과부하 또는 예정된 작읍으로 잠시 요청을 처리할 수 없음, Retry-Afer 헤더 필드로 얼마뒤에 복구되는지 보낼 수도 있음.   
   
   </details>
   
  ---
  
  ## HTTP 헤더
  본문의 해석 정보가 모두 들어감.   
     
  ### 표현헤더  
  #### Content-Type : 표현 데이터 형식 / 단순 전송.  
  * 미디어 타입, 문자 인코딩 = html or JSON or image/png or ...   
     
  #### Content-Encoding : 표현 데이터의 압축 방식 / 압축 전송   
  * 바디내용을 압축, 데이터를 읽는 쪽에서 인코딩 헤더의 정보로 압축 해제 ex)gzip, deflate, identity        
     
  #### Content-Language : 표현 데이터의 자연 언어 / 분할 전송   
  *    
     
  #### Content-Length : 표현 데이터의 길이 / 범위 전송    
  * byte단위    
     
  ---
     
  ### 협상 헤더(Content Negotiation)
  클라이언크가 선호하는 표현 요청 = 협상헤더는 요청시에만 사용
     
  #### Accept : 클라이언트가 선호하는 미디어 타입 전달   
  #### Accept-Charset : 클라이언트가 선호하는 문자 인코딩   
  #### Accept-Encoding : 클라이언트가 선호하는 압축 인코딩   
  #### Accept-Language : 클라이언트가 선호하는 자연 언어   
  
  ---
     
  #### 협상과 우선순위 1
  <img width="525" alt="스크린샷 2021-09-08 오후 2 03 20" src="https://user-images.githubusercontent.com/81910342/132449411-50718c21-c114-4041-92ff-96e7d67a3bb5.png">   
     
  * Quality Value(q) 값 사용   
  * 0 ~ 1, 클수록 높은 우선순위    
  * 생략하면 1   
     
  #### 협상과 우선순위 2   
  <img width="441" alt="스크린샷 2021-09-08 오후 2 10 59" src="https://user-images.githubusercontent.com/81910342/132450049-2799614c-5849-4503-ab0a-253f486ea22b.png">   
     
  * 구체적인 것이 우선한다.
  * 더 긴것..   
     
  #### 협상과 우선순위 3
  <img width="624" alt="스크린샷 2021-09-08 오후 2 13 51" src="https://user-images.githubusercontent.com/81910342/132450258-d5dbcb13-bceb-44b5-80bf-cf1f1f601738.png">   
     
  * 구체적인 것을 기준으로 미디어 타입을 맞춘다.   
  
  ---
     
  ## 전송 방식
  단순 전송
  * Content-Length : 한번에 요청하고 한번에 받음   
     
  압축 전송   
  * Content-Encoding :  
     
  분할 전송   
  * Transfer-Encoding : 크기와 메세지를 나눠 보냄 = 크기만큼의 공간을 확보하고 그 공간에 정보를 넣음.   
  * Content-Length는 예상이 안되기 때문에 쓸 수 없음.   
  ex) 큰데이터를 넘길때 분할로 오는대로 보여줌.   
     
  범위 전송   
  * Range, Content-Range : 데이터를 받다가 서버가 끊겼을 시, 원하는 부분부터 데이터를 받을 수 있음.   
  
  ---
      
  ## 일반 정보
  정보성 헤더   
     
  #### From : 유저 에이전트의 이메일 정보   
  #### Referer : 이전 웹 페이지 주소 /Referrer오타 ㅎ   
  * 현재 요청된 페이지의 이전 웹 페이지 주소   
  * 유입경로 분석 가능   
  * 요청에서 사용   
  #### User-Agent : 유저 에이전트 애플리케이션 정보   
  * 클라이언트 애플리케이션 정보(웹 브라우저 정보, 등등...)   
  * 어떤 정류의 브라우저에서 장애가 발생하는지 파악 가능   
  * 통계 정보   
  * 요청에서 사용   
  #### Server : 요청을 처리하는 오리진 서버의 소프트웨어 정보   
  * 진짜 나의 요청이 있는 마지막 server   
  * 응답에서 사용   
  #### Date : 메세지가 생성된 날짜   
     
  ## 특별한 정보   
  #### Host : 요청한 호스트 정보(필수!!!!!)   
  * 하나의 서버에 여러 도메인을 처리해야 할 경우   
  * 요청에서 사용   
     
  #### Location : 페이지 리다이렉션   
  * 웹 브라우저는 3xx 응답의 결과에 Location 헤더가 있으면, Location 위치로 자동 이동(리다이렉트)
  * 응답코드 3xx에서 설명   
  * 201(created) : Location 값은 요청에 의해 생성된 리소스 URI.  
  * 3xx(Redirection) : Location 값은 요청을 자동을 리다이렉션하기 위한 대상 리소스를 가리킴   
     
  #### Allow : 허용 가능한 HTTP 메서드
     
  #### Retry-After : 유저 에이전트가 다음 요청을 하기까지 기다려야 하는 시간   
  * 503 : 서비스가 언제까지 불능인지 알려줄 수 있음.   
  
  ## 인증   
  Aurthorization : 클라이언트 인증 정보를 서버에 전달   
  
  ---
  
  ## 쿠키 Cookie
  * 2개의 헤더가 사용됨   
  ### Set-Cookie : 서버에서 클라이언트로 쿠키 전달(응답)   
  ### Cookie : 클라이언트가 서버에서 받은 쿠키를 저장하고, HTTP 요청시 서버로 전달   
  
  ---
  
   
  
</details>

<details>
  <summary>0909~0910</summary>
  
  https://github.com/JuGeonjeong/TIL-javascript.git
  
  </details>
  
  <details>
  <summary>0912 react</summary>
  
 
  
  </details>
  
  ## 3주차
  <details>
  <summary>0913 Node JS, React JS</summary>
  
  [React JS]   
  https://www.youtube.com/watch?v=BYbgopx44vo   
  https://jeonghwan-kim.github.io/series/2021/04/05/lecture-react-ready.html
  
  </details>
  
  <details>
  <summary>0914 Node JS, React JS</summary>
  
  [React JS]
  
  https://github.com/JuGeonjeong/covid-19
  
  </details>
  
  <details>
  <summary>0915 Next JS START!</summary>
  
  [Next JS]   
  
  https://github.com/JuGeonjeong/Next.js
  
  </details>
  
  <details>
  <summary>0916 Next JS</summary>
  
  [Next JS]   
  
  https://github.com/JuGeonjeong/Next.js#0916
  
  </details>

  <details>
  <summary>0917 Next JS</summary>
  
  [Next JS] 
  
  </details>
  
  <details>
  <summary>0922 Next JS</summary>
  
  [React JS]
  # 0922
  #### 코딩애플 React기초 1강~
  ### 메모
        1. npx create-react-app 프로젝트명
        2. npm start 미리보기
        3. JSX 사용
          * import 사진 = src={}, style = {{  }}
          * { 변수명, 함수, 등... }
          * useState 동적데이터 변경 
          , useMemo, useSelector, useCallback, 등...
  
  </details>
  
  ## 4주차
  
  <details>
  <summary>0927 Next JS</summary>
  
  [React JS]
  # 0927
  #### https://github.com/JuGeonjeong/Next.js/blob/master/README.md#0927
  
  <details>
  $ ipconfig getifaddr en0
설명) 내 로컬 ip주소 확인 방법(맥 명령어)

$ du -sh *
설명) 파일 용량을 확인할수 있는 명령어

$ pwd 
설명) 현제 어디디렉토리에 있는지 경로를 표시합니다.(pwd는 맥에서만 된다.)

$ ls -la 
설명) 현제 디렉토리 안에 있는 파일들 목록들을 보여준다.(-la 생략가능)

$ ll 
설명) 현제 디렉토리 안에 파일들 목록들을 보여준다.

$ cp = 원본복사 
설명) cp web /bin "web"폴더를 /bin에 복사합니다.


$ mv = 원본이동
설명) mv web /bin "web"폴더를 /bin으로 이동합니다.

Ex) $ mv test11 / ~/desktop
설명) 'test11' 폴더를 desktop으로 이동합니다.


$ mkdir = 폴더 생성
설명) mkdir web "web" 폴더(Directory)를 현제 경로에 생성합니다.

Ex) $ mkdir thdbsgh younho so 소윤호 test
설명) 2개이상의 Directory를 연속으로 생성합니다.

$ touch index.html = touch 파일명 
설명) 파일을 만들어 줍니다.

Ex) $ touch index.html

Ex) $ touch css/style.css

Ex) $ touch js/aap.js
﻿
$ rm 
설명) 원복삭제 - rm web or rm -r web "web"폴더를 삭제 합니다.

$ rmdir 
설명) 폴더삭제 - rmdir web "web" 폴더를 현제 경로에서 삭제합니다.

Ex) $ rm text.txt 또는 $ rm –f text.txt

Ex) $ rm * => 현재 작업중이 directory의 모든 파일 지우기

Ex) $ rm –f * => 묻지도 따지지도 않고 다 지우기.

Ex) $ rm –r directory1 => 폴더 및 안의 파일 다 지우기.

Ex) $ rm –rf directory1 => 묻지도 따지지도 않고 다 지우기 (–f 옵션 + –r 옵션)
                          
---
                          
$ sudo = sudo vi /etc/php.ini 
설명) root 권한으로 /etc/ 폴더에 php.ini 파일을 vi로 편집합니다.

$cd => 해당 경로로 이동 합니다. - cd /<경로명>

Ex) $ cd ./ => 현재 폴더를 가르킵니다. 현재 폴더에서 작업을 할 땐 생략 가능합니다.

Ex) $ cd ../ => 현재 폴더에서 한단계 위의 폴더를 가르킵니다.

Ex) $ cd ./soyunho => 디렉토리 이름을 써줘야 해당되는 디렉토리로 들어간다.


$ grep = 파일안 내용찾기
설명) grep head index.php "index.php" 에서 head 가 포함된 낱말을 찾어 냅니다.

$ who 
설명) 현제 접속 또는 로그인중인 모든 사용자를 찾어줍니다.

$ ps 
설명) ps(옵션) - 현제 실행중인 모든 프로세서 표시합니다.

$ kill
설명) kill ichat - ichat 프로세서를 강제 종료 합니다.

$ find
설명) 조건검색어 - find /경로/ -name host.txt /경로/에서 host.txt 파일을 검색합니다.

$ exit 또는 $ logout 
설명) 터미널 안전하게 종류한다.
  </details>
  
  </details>
                                   
## 5주차
                                   
  <details>
  <summary>1005 Nest JS</summary>
  
  [Nest JS]   
  java-spring, NodeJS-NestJS
  https://github.com/JuGeonjeong/hi-nest                                 
  
  
  </details>
                                   
  <details>
  <summary>1006~1008 Nest JS</summary>
  
  [Nest JS]   
  회사 템플릿 코드분석...
  
  
  </details>
  
## 6주차
### 이번주 목표: 프로젝트 api CRUD 하나씩 만들어보기, 직접부딪혀보기!

  <details>
  <summary>1012 Nest JS</summary>
  
  [Nest JS]
  rds, ec2, aquerytool
  
  </details>
                                     
  <details>
  <summary>1013 Nest JS</summary>
  
  [Nest JS]
  
  
  </details>
                                   
  <details>
  <summary>1014 Nest JS</summary>
  
  [Nest JS]
  DB연결하기
  Sequelize vs TypeORM
                                   
  Sequelize - Sequelize는 Node.js 및 io.js를 위한 약속 기반 ORM입니다. PostgreSQL, MySQL, MariaDB, SQLite 및 MSSQL 방언을 지원하며 견고한 트랜잭션 지원, 관계, 읽기 복제 등을 제공.
  TypeORM - 현재 존재하는 다른 모든 JavaScript ORM과 달리 Active Record 및 Data Mapper 패턴을 모두 지원합니다. 즉, 고품질의 느슨하게 결합되고 확장 가능하고 유지 관리 가능한 애플리케이션을 가장 생산적인 방식으로 작성할 수 있음.
                                   
  종일 에러해결하느라 정신없는 하루
  1. mysql.server start 안됨 - 권한 따라가서 mysql, mysql@5.7 삭제를 했지만 mysql@5.7은 불멸의 상태였다. brew list에 있지만 혹시나 하는 맘에 mysql@5.7을 brew install mysql@5.7 후 brew uninstall mysql@5.7을 했더니 삭제됬다!!!
  2. 하지만 똑같이 mysql.server start는 안됬다. 권한 바꿔보고 파일도 만들어보고 설치삭제하면서 지워지지 않은 파일 충돌고려해서 전부 삭제도 해보고 했다. 또 안됬다.
  3. mysql community를 다시 깔아볼까 했다. 문득 예전 강의 듣다가 같은 오류로 고생한게 생각이 났다. 8.0.26버전은 MAC에서 지원이 안되서 8.0.22버전으로 설치했더니 서버가 실행됬던 기억이 있었다. 역시 됬다~!ㅎㅎ
  4. error 1045 (28000)오류: mysql -u root -p 비밀번호를 입력 후 mysql에 접속했다.
  이거 말고 정말 많고 작은 에러들이 많았다. 하루종일 에러를 해결하는데 보냈고 해결되서 매우기뻤지만 좀 찝찝했다. 하지만 미숙했던 터미널 사용에 전보다 많이 익숙해졌다. 오늘도 많이 성장했다~ 꾸준히 하자~
  
  </details>

  <details>
  <summary>1015 Nest JS</summary>
  
  [Nest JS]
  DB연결하기 에러잡기 연결하고 DB구축

  </details>
                                   
## 7주차
### 이번주 목표: 수요일 오전까지 api, 금요일 기록점수관리까지 api, 관리자페이지 완성

  <details>
  <summary>1018 Nest JS</summary>
  
  [Nest JS]
  바울로그라피 테이블생성, 로직짜기 시작

  </details>
                                   
  <details>
  <summary>1019 Nest JS</summary>
  
  [Nest JS]
  설문조사 로직짜기 시작, swagger, JWT                                 
  설문조사 후 토큰생성 완료, 

  </details>            
                                   
  <details>
  <summary>1020~1021 React</summary>
  
  [React]
  관리자 웹 결과점수까지 만들기
  1. git clone 주소
  2. git init
  3. git remote add origin 주소
  4. git remote -v 주소 연결됬는지 확인
  5. npm i
                                   
  ---                                   
  
  1. git add .
  2. git commit -m "커밋메세지"
  3. git push(main) / git push origin master
                          
  ---                           
   
  1. git pull / git pull origin master
                          
  ---                           
  
  1. git branch comflict 해결
                                   
  </details>
                                   
  <details>
  <summary>1022 React, NestJS</summary>
  
  [React]
  api나온부분 완료
  1. .mapdmsd list나 table에서 쓰고 상세페이지는 데이터를 set만해서 객체내용을 하나씩 사용
  2. O,X 표현 {data.isChanged} = 값 안나옴
     API값 Boolean, {data?isChanges?'O':'X'} = true,false에 따라 값 나옴
                                   
  [NestJS]   
  1. format('YYYY.MM.DD') 값 변환
  2. === null? 'X':'O'; = true,false
                          
  [Terminal]   
  1. ls 현위치파일보기 / cd 파일명 : 해당파일로 현위치변경 / rm -r 파일명 : 해당리포지토리 삭제 / mkdir 파일명 : 파일생성
  2. mysql -u root -p : mysql 접속(-p : 비번)
  3. mysql 이랑 mariadb랑 접속상태 중복되면 안됨 : 컴퓨터내 mysql다 찾아내서 삭제 완료 후 mariadb다운시 연결됨
                          
  [AmazonAWS]   
  1. 서버에 올리기 - a3에 bucket이름을 지정 고유한 아이디 보통 도메인주소 ex)bowelography.com - 설정 변경
  2. npm run build - react는 build폴더에 정적인 페이지를 생성해줌 - 해당폴더 open . - s3에 build폴더안의 모든파일을 넣어줌
  3. 실행됨 - 자동업로드파일 bucket이름 입력, accessKeyId, secretAccessKey 입력 - npm run build - upload파일 자동실행하면서 build폴더 안 파일들                                    
  </details>
                          
  ## 8주차
  ### 이번주 목표: 프로젝트마무리, 프로젝트 웹관리자페이지/서버API 이해하고 설명하기, React/NestJS 중 하나만 정해서 공부하기 

  <details>
  <summary>1025 React, NestJS</summary>
                          
   - [ ] 실력을 쌓자   
                          
  [웹 관리자 페이지]api 삭제빼고 완료
  1. 수정
                          
  [git]   
  1. git add . -> git commit -> git pull origin main
                          
  [React]   
  1. dayjs, Datepicker
                          
  </details>
                          
  <details>
  <summary>1026 React, NestJS</summary>
                          
   - [ ] 지금하고 있는 코드 일목요연하게 상대방에게 설명할 수 있을때
                          
  [React]
  1. { __ ? ( true ) : ( false )}
  2. GET은 생략가능 - method, body 없음(당연함)
  3. window.history.back(); -> 뒤로가기지만 리스트함수를 호출하기때문에 새로고침(당연함)
  4. 유저관리 - 통계, 광고배너관리 - 상세/등록, 
  5. <img width="486" alt="스크린샷 2021-10-26 오후 8 18 57" src="https://user-images.githubusercontent.com/81910342/138867620-6eae1dac-4044-4f5f-a9ac-5457f7ddbff9.png">   
  한번더보기
                          
  </details>

  <details>
  <summary>1027 React, NestJS</summary>
  
   - [ ] crud완료, api설계보기
  
  [git]   
  1. git pull origin main --force
  
  [React]
  버튼 함수로 통일시키기
  
  [NestJS]
  1. 코드분석하기
  
  [Webstorm]
  데이터베이스 연결하기    
  database Tool 설치    
  1. ![스크린샷 2021-10-27 오후 3 03 27](https://user-images.githubusercontent.com/81910342/139008736-3aa7d428-f941-4068-b357-c4d5a01af45c.png)
  해당 DBMS선택
  2. ![스크린샷 2021-10-27 오후 3 05 11](https://user-images.githubusercontent.com/81910342/139008889-6667cb40-b0f2-4975-8da5-547865a2b85d.png)   
  프로젝트 .env 파일 설정 한 database_name, database_password 등등 값 입력   
  
  Name : @~~~이름   
  Comment : 주석   
  Host : 도커에 띄운 로컬 MySQL을 사용하므로, localhost로 설정했습니다.   
  User : 계정 이름 ex.(mysql -u root -p) -> root    
  Password : 비밀번호   
  Database : 연결하고자하는 DB   
  URL : 자동완성   
  3. 연결 테스트 후 생성
  
  </details>
  
  <details>
  <summary>1028 React, NestJS</summary>
  
  - [ ] 공지사항, api설계보기, 두번째 프로젝트 시작(새로운 관리자템플릿 분석 - templete 사용)
  
  </details>

  ## 9주차
  ### 이번주 목표: 두번째 프로젝트 ui만들기, api붙이기, 알고리즘문제풀기, JS공부

  <details>
  <summary>1101</summary>

  </details>
  
  <details>
  <summary>1102</summary>

  </details>
  
  <details>
  <summary>1103</summary>

  </details>
  
  <details>
  <summary>1104 React, NestJS</summary>
  
   - [ ] 관리자페이지, api 둘다 시작 정신없다 ㅎㅎ 하나씩 해결해 나가자
  
  </details>


  ## 10주차
  ### 이번주 목표: api붙이기, 알고리즘문제풀기, JS공부, db공부하기

  <details>
  <summary>1107</summary>   
  
  - [ ] 알고리즘문제풀기     
  [알고리즘]     
  알고리즘 문제풀기 시작     
  프로그래머스: 로또 최고순위와 최저순위     
  알고리즘 문제풀이를 시작했고 문제를 처음 봤을때 문제만 이해하는것도 시간이 많이 걸렸다. 로직을 구상 후 코드를 적고 팀원들과 각자의 코드를 설명하는 순서로 스터디가 진행됬다. 하나하나 풀어나가보자!!!

  </details>
  
  <details>
  <summary>1108</summary>
  
  - [ ] 사진파일 등록하는 api와 관리자페이지에 리스트구현
  - [ ] S3 웹서버 올리기
  
  </details>
  
  <details>
  <summary>1109</summary>
  
  - [ ] 사진파일 등록하는 api와 관리자페이지에 리스트구현
  - [ ] S3 웹서버 올리기
  
  </details>
  
  <details>
  <summary>1110</summary>
  
  - [ ] 제발 먼저 에러코드를 잘 읽자   <img width="1853" alt="스크린샷 2021-11-10 오후 8 47 52" src="https://user-images.githubusercontent.com/81910342/141107760-71c492a3-d599-4a4f-a712-2b9c0700d5b6.png">   column을 추가하고 sync 업데이트를 하지 않아서 Unknown column 'secondIll' in 'field list'(테이블목록에 secondIll이라는 컬럼을 모른다) 에러가 뜸

  - [ ] html 주문서만들기 - table-layout:fixed; 그리고 td로 width조정    ![스크린샷 2021-11-10 오후 2 29 51](https://user-images.githubusercontent.com/81910342/141107930-74895d57-0027-4096-903a-e23fc3fbdd9d.png)   
   <img width="936" alt="스크린샷 2021-11-10 오후 3 49 42" src="https://user-images.githubusercontent.com/81910342/141105698-02f6a71c-ec23-477a-8080-43d36c9903d7.png">   

  - [ ] react - ?를 생략하면 데이터undefined로 인식해서 오류 제발 빼먹지말자  ![스크린샷 2021-11-10 오후 8 34 50](https://user-images.githubusercontent.com/81910342/141106072-0b5ad3bc-74c0-4bb2-b34b-e53d52b09927.png).  
  - [ ] nestJS - return new ResponseSuccessDto<any>(데이터 요청 성공시 응답으로 값을 넘겨줘야함 ex)파일등록시 등록Id를 넘겨주고 등록Id와 파일이랑 같이 넘겨줌);
  
  </details>
  
  <details>
  <summary>1111</summary>
  
  - [ ] 통계 로직을 구현해서 프론트에 넘겨줬다.
  - [ ] 
  
  </details>

  <details>
  <summary>1112</summary>
  
  - [ ] nestJS, Sequelize 공식문서 정독하기   
  - [ ] sequelize avg -> 배열로 들어오기때문에 .length로 처리    
  ![스크린샷 2021-11-12 오후 7 33 52](https://user-images.githubusercontent.com/81910342/141453013-778e1cf7-0d5c-4f6e-9480-573f69f19a71.png).   
  - [ ] include:[{model: },], 조인테이블 기억    
  - [ ] Sequelize.literal(`쿼리문`) 기억     
  ![스크린샷 2021-11-12 오후 7 40 49](https://user-images.githubusercontent.com/81910342/141453966-85edf7cc-4f1e-4815-a435-ab7038f4a4c2.png)    
  
  </details>
  
  ## 10주차
  ### 이번주 목표: 새로운 프로젝트 적응하기

  <details>
  <summary>1117</summary>
  
  너무 정신이 없다....새로운프로젝트는 전에 비해 양도 5배 난이도도 5배인것같다...

  </details>
  
  <details>
  <summary>1118</summary>
  
  기본알기 기본공부하기!!!!!!!!

  </details>
  
  ## 11주차
  ### 이번주 목표: 인프런 nest강의, react강의
  
  <details>
  <summary>1122</summary>
  
  - [ ] nest 공부하기(인프런, 공식문서)

  </details>
    
  <details>
  <summary>1123</summary>
  
  - [ ] nest 공부하기(인프런, 공식문서)
  - [ ] api, 관리자페이지 등록, 이미지 등록

  </details>
      
  <details>
  <summary>1124</summary>
  
  - [ ] react 공부하기(인프런, 공식문서)
  - [ ] 관리자페이지

  </details>
      
  <details>
  <summary>1125 React</summary>
  
  - [ ] react 공부하기(인프런, 공식문서), react v6 바뀐것들 
  https://blog.woolta.com/categories/1/posts/211
  - [ ] 관리자페이지
  - [ ] AWS EC2 등록
  산재 랜딩페이지 web, mobile 만듬..... 모바일 -> 모바일페이지 , 웹 -> 웹페이지

  </details>
  
  <details>
  <summary>1126 React</summary>
  
  - [ ] react 페이지 여백없애기 publick <body>에 style="margin: 0;" 넣어서 해결 - 맞는방법인지는 모르겠으나 구글링해도 안나옴...
  - [ ] 관리자페이지

  </details>

  ## 12주차
  ### 이번주 목표: 새로운 프로젝트 적응하기

  <details>
  <summary>1129</summary>
  
  - [ ] api수정
  
  </details>
                                                          
  <details>
  <summary>1202</summary>
  
  - [ ] api수정
  
  </details>
                                                          
  ## 13주차
  ### 이번주 목표: 웹 페이지 만들기..
                                                          
  <details>
  <summary>1206</summary>
  
  - [ ] 
  
  </details>
                                                          
  <details>
  <summary>1207</summary>
  
  - [ ] 
  
  </details>
                                                          
  <details>
  <summary>1209</summary>
  
  - [ ] 공부언제하나....일좀 그만 밀리고싶다......
  
  </details>
                                                          
  ## 14주차
  ### 이번주 목표: 새로운 프로젝트 적응하기, 아침에 알고리즘 한문제씩 
                                                          
  <details>
  <summary>1213</summary>
  
  - [ ] 관리자페이지
  
  </details>
                                                          
  <details>
  <summary>1214</summary>
  
  - [ ] 관리자페이지
  
  </details>

  <details>
  <summary>1215</summary>
  
  - [ ] 관리자페이지
  
  </details>

                                                          
  <details>
  <summary>1216</summary>
  
  - [ ] 관리자페이지: 배열의 인덱스값을 변형해서 상태변경을 했다.
  
  </details>

  <details>
  <summary>1217</summary>
  
  - [ ] 관리자페이지
  
  </details>
                                                          
  ## 15주차
  ### 이번주 목표: 아침에 알고리즘 한문제씩, 
                                                          
  <details>
  <summary>1220</summary>
  
  - [ ] 관리자페이지
  - [ ] 서버 쿼리변경
  
  </details>
                                                          
  <details>
  <summary>1221</summary>
  
  - [ ] 관리자페이지
  - [ ] 웹 css 수정 - 크롬, 익스플로러 호환
  
  </details>
                                                          
