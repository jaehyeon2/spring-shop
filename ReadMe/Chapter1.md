#Initial Setting

##Development environment
1. OS : Window 10
2. IDE : Intellij
3. JDK : JDK 11
4. DB : MySQL
5. Build Tool : Maven

## Annotation

###@RestController
- Restful Web API를 좀 더 쉽게 만들기 위한 Annotaion
- @Controller + @ResponseBody
- @Controller : 해당 클래스를 요청을 처리하는 컨트롤러로 사용
- @ResponseBody : 자바 객체를 HTTP 응답 본문의 객체로 변환해 클라이언트에게 전송

###@GetMapping
- 클라이언트의 요청을 처리할 URL을 매핑
- ex)@GetMApping(" /ex "), @GetMapping(value = " /ex ")

###Lombok 라이브러리
- Getter/Setter와 같이 반복정니 자바코드를 컴파일할 때 자동으로 생성해주는 라이브러리

####@Getter/@Setter
- 코드를 컴파일할 때 속성들에 대한 Getter/Setter 메소드 생성
####@ToString
- toString() 메소드 생성
####@ToString(exclude={"변수명"})
- 원하지 않는 속성을 제외한 toString() 메소드 생성
####@NonNull
- 해당 변수가 null 체크, NullPointerException 예외 발생
####@EqualsAndHashCode
- equals()와 hashCode() 메소드 생성
####@Builder
- 빌터 패턴을 이용한 객체 생성
####@NoArgsConstructor
- 파라미터가 없는 기본 생성자 생성

