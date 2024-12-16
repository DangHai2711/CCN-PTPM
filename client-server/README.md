# ATM App - Backend & Frontend

Đây là dự án ATM App bao gồm **Backend** và **Frontend** chạy trên Docker. Dự án sử dụng MongoDB làm cơ sở dữ liệu.

## Link Docker

- [Frontend] (https://hub.docker.com/r/danghai2117000/da1-frontend)
- [Backend] (https://hub.docker.com/r/danghai2117000/da1-backend)

## Các bước để chạy ứng dụng

### 1. Tải dự án về

### 2. Chạy ứng dụng bằng Docker Compose

```bash
    docker-compose up
```

Build và run các container cho frontend, backend và MongoDB.

- Frontend sẽ được chạy trên cổng 3000 (http://localhost:3000).
- Backend sẽ được chạy trên cổng 5000 (http://localhost:5000).
- MongoDB sẽ được chạy trên cổng 27017.

### 3. Dừng ứng dụng

```bash
    docker-compose down
```
