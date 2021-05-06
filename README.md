
# Dockerのjavaサンプルコード

実行コマンド

```bash
docker build -t myjava:openjdk .
docker run -t --rm -v ${PWD}:/mnt myjava:openjdk javac Main.java
docker run -t --rm -v ${PWD}:/mnt myjava:openjdk java Main
```
