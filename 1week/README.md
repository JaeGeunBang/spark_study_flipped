###  1 week

<br>

- 주교재: 스파크 완벽 가이드
  - 1 Chapter 진행
- 내 PC에 Spark Setting 진행
  - Spark 2.4
  - Jupyter Notebook
  - Scala 


스파크 RDD 논문 LINK: https://www.usenix.org/conference/nsdi12/technical-sessions/presentation/zaharia

docker로 jupyter 셋팅
```
// 기본 실행
sudo docker run -it --rm -p 8888:8888 jupyter/all-spark-notebook

// docker 데이터 볼륨 공유
sudo docker run -it -v /Users/bangjaegeun/work/git/spark_study_flipped:/home/jovyan/work/spark_study_flipped -p 8888:8888 --name spark_study_fliped jupyter/all-spark-notebook
```

docker 컨테이너 실행
```
sudo docker start spark_study_fliped
```

docker container 확인 및 bash 접속
```
sudo docker ps -a
sudo docker exec -it <continar id> /bin/bash
```



