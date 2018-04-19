# SAS Viya with SWAT on jupyter notebook

SAS Viya서버에 Jupyter Notebook 을 설치 하고 실행 하는 방법에 대한 가이드 입니다.

Python 을 통해 Viya 플랫폼을 사용하기 위해서는 SWAT 라이브러리가 필요합니다. 

---

* pip 설치

```
# yum install python-pip
```

* jupyter notebook 설치

```
# pip install jupyter
```

* numactl 패지 설치

```
# yum install numactl
```

> numactl 은 SAS Viay의 CAS\(Cloud Analytic Server\) 서버와 바이너리 통신을 위해 필요한 라이브러리 입니다.

* SWAT 패키지 다운로드 및 설치
* * 다운로드 사이트 : https://github.com/sassoftware/python-swat/releases
  * 다운로드 후 서버에 적당한 위치에 업로드후 설치합니다.

```
# yum install python-swat-1.3.0-linux64.tar.gz
```

* 인증서 환경변수 설정

```
# export 
```

* jupyter notebook 실행하기
* 간단한 소스를 통해 확인하기



