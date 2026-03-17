docker build --target ci -t ttungbmt/superset:6.1.0 .

docker compose -f docker-compose-image-tag.yml up -d
docker compose -f docker-compose-image-tag.yml down
