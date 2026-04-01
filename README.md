# Jenkins 실습

## 프로젝트 구조

``` bash
project/
├── docker-compose.yml
├── backend/
│   ├── Dockerfile
│   ├── main.py
│   └── requirements.txt
└── frontend/
    ├── Dockerfile
    └── index.html
```

### 실행 방법

``` bash
bashdocker-compose up -d    # 전체 실행
docker-compose down     # 전체 종료
docker-compose down -v  # 볼륨까지 삭제
```

### 접속 주소

- 프론트엔드: http://localhost
- 백엔드 API: http://localhost:8000
- API 문서: http://localhost:8000/docs
