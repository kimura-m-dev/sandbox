# sandbox
すなあそび
## 作ったAPIを動かすときにやること
- Docker Desktop for Macを起動する
- Dockerを起動する
  - docker-compose -f ./docker/docker-compose.yml up --build --remove-orphans
- アプリケーション（Spring Boot）の起動
  - GradleよりbootRunを実行する
    - Gradleタブ > sandbox(プロジェクト名) > Tasks > application > bootRun
