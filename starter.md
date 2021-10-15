### spring boot 프로젝트 시작하기


https://start.spring.io/ 로 접속하여 조건 설정하고 파일 다운

인텔리제이에서 open -> 다운받은 파일의 build.gradle -> open as project

바로 오류발생
* What went wrong:
Plugin [id: 'org.springframework.boot', version: '2.5.5'] was not found in any of the following sources:

- Gradle Core Plugins (plugin is not in 'org.gradle' namespace)
- Plugin Repositories (could not resolve plugin artifact 'org.springframework.boot:org.springframework.boot.gradle.plugin:2.5.5')
  Searched in the following repositories:
    Gradle Central Plugin Repository

* Try:
Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Exception is:
org.gradle.api.plugins.UnknownPluginException: Plugin [id: 'org.springframework.boot', version: '2.5.5'] was not found in any of the following sources:

- Gradle Core Plugins (plugin is not in 'org.gradle' namespace)
- Plugin Repositories (could not resolve plugin artifact 'org.springframework.boot:org.springframework.boot.gradle.plugin:2.5.5')
  Searched in the following repositories:
    Gradle Central Plugin Repository
