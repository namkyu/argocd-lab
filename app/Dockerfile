# nginx:alpine 위에 정적 페이지 한 장만 올리는 최소 이미지.
# 빌드 도구 없이 index.html만 바꿔서 바로 재빌드할 수 있도록 구성.
FROM nginx:alpine

# 로컬에서 작성한 index.html을 nginx 기본 문서 경로로 복사
COPY index.html /usr/share/nginx/html/index.html
