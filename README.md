# [Tools](https://delicate-walrus-052.notion.site/Tools-025fd1a6c31d48b78e71389be757f7a3?pvs=4)

## 1. MariaDB - [Notion link](https://delicate-walrus-052.notion.site/MariaDB-Docker-845c0c4f59d54a5cb340255e2bcdbac6?pvs=4)

### 특징
#### MySQL과의 호환성
MariaDB는 MySQL과 소스코드를 같이 하므로 사용방법과 구조가 MySQL과 동일하다. 이름만 다르지 명령어나 사용방법 (5.5까지) 모두 MySQL과 동일하다. 편의를 위해 MariaDB는 동일한 MySQL 버전과 바이너리 드롭인 교체를 지원한다. MariaDB는 MySQL과 소스코드를 같이 하므로 사용방법과 구조가 MySQL과 동일하다. 이름만 다르지 명령어나 사용방법 (5.5까지) 모두 MySQL과 동일하다. 편의를 위해 MariaDB는 동일한 MySQL 버전과 바이너리 드롭인 교체를 지원한다.

* 데이터와 테이블 정의 파일(.frm) 파일이 바이너리 호환이 된다.
* 모든 클라이언트 API, 프로토콜 그리고 구조가 동일하다.
* 모든 파일이름과 바이너리, 경로, 포트, 소켓 그리고 기타 등등이 동일하다.
* 모든 MySQL 커넥터(PHP, Perl, 파이썬, 자바, .NET, MyODBC, Ruby, MySQL C 코넥터 등)가 MariaDB와 동일하게 작동한다.

근본적인 차이점은 MariaDB는 GPL v2 라이선스를 따르는 순수한 오픈소스 프로젝트이기에 오라클로부터 자유롭다. MariaDB의 모든 코드는 GPL, LGPL, LPGL, BSD의 라이선스로 만들어져 있다. 누구나 필요로 하면 커뮤니티를 통해 MariaDB를 내려받아 쓸 수 있다.

#### 성능
MariaDB 커뮤니티는 MySQL과 비교해 애플리케이션 부분 속도가 약 4~5천배 정도 빠르며, MySQL이 가지고 있는 모든 제품의 기능을 완벽히 구현하면서도 성능 면에서는 최고 70%의 향상을 보이고 있다고 주장한다.

#### 

#
## 2. Docker - [Notion link](https://delicate-walrus-052.notion.site/Docker-2d6822927e0c402daabcb3f521def38c?pvs=4)

Docker install(mac) - https://docs.docker.com/desktop/install/mac-install/

Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications. By taking advantage of Docker’s methodologies for shipping, testing, and deploying code, you can significantly reduce the delay between writing code and running it in production.

### The Docker platform
Docker provides the ability to package and run an application in a loosely isolated environment called a container. The isolation and security lets you to run many containers simultaneously on a given host. Containers are lightweight and contain everything needed to run the application, so you don’t need to rely on what’s installed on the host. You can share containers while you work, and be sure that everyone you share with gets the same container that works in the same way.

Docker provides tooling and a platform to manage the lifecycle of your containers:

* Develop your application and its supporting components using containers.
* The container becomes the unit for distributing and testing your application.
* When you’re ready, deploy your application into your production environment, as a container or an orchestrated service. This works the same whether your production environment is a local data center, a cloud provider, or a hybrid of the two.

#
## 3. Jenkins - [Notion link](https://delicate-walrus-052.notion.site/Jenkins-205b880270ec485b88e214f691810716?pvs=4)

Install guide - https://www.jenkins.io/doc/book/installing/

Minimum hardware requirements:
- 256 MB of RAM
- 1 GB of drive space (although 10 GB is a recommended minimum if running Jenkins as a Docker container)

Recommended hardware configuration for a small team:
- 4 GB+ of RAM
- 50 GB+ of drive space

#