- 정의
    - 윈도우 운영체제에서 비동기 입출력(Asynchronous I/O)작업을 효율적으로 처리하기 위한 메커니즘
    - 윈도우에서 제공하는 고성능 I/O 모델 중 하나로 이벤트 기반 비동기 프로그래밍을 지원하여 멀티스레딩 작엉ㅂ을 간소화하고 효율적인 시스템 리소스를 관리할 수 있게 한다
- 작업
    - 네트워크 통신
        - IOCP는 네트워크 소켓 통신에서 비동기 입출력 작업을 관리하고 처리하는데 사용된다
        - 여러 클라이언트와 서버 간의 효율적인 통신이 가능하다
    - 파일 입출력
        - 파일 읽기 및 쓰기 작업에서도 IOCP를 사용하여 비동기적으로 파일을 처리할 수 있다
        - 파일 시스템 작업이 블로킹되지 않고 다른 작업을 수행할 수 있다
    - 서버 어플리케이션
        - 서버 어플리케이션에서는 여러 클라이언트 요청을 비동기적으로 처리해야할 때 유용하다
        - 서버는 여러 클라이언트와 동시에 효율적으로 상호작용할 수 있다