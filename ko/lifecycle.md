# 라이프 사이클

만약 여러분이 XE3를 사용하거나 XE3의 플러그인을 개발하려는 개발자라면 XE3의 사용법, 플러그인 제작법 그리고 XE3에서 제공하는 여러가지 서비스들을 사용하는 방법만 숙지하는 것만으로도 충분할 수 있습니다. 하지만 여러분이 좀더 고도의 기능을 필요로 하는 플러그인을 만들거나 XE3를 제대로 사용하고 싶다면, XE3가 어떤 방식으로 작동하는지에 대한 전체적인 그림을 알고 있어야 합니다. 전체적인 그림을 알고 있지 않다면 결국 한계에 도달할 것이고, 전체적인 그림을 알기 위해 노력하는 시점이 올 것입니다.


XE3 사이트는 웹서버에 설치돼 있고, 사용자들은 자신의 웹브라우저에서 사이트 주소에 접속해 요청을 보낼 것입니다. XE3는 모든 요청을 `index.php` 파일에서 처리합니다. `index.php`의 역할은 요청이 들어왔을 때, XE3 어플리케이션을 로딩하고 요청을 처리하기 위해 어플리케이션을 실행시킵니다.
