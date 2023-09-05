FROM eclipse-temurin:17 as builder
WORKDIR /app

FROM builder AS dev-envs
RUN <<EOF
apt-get update
apt-get install -y --no-install-recommends git
EOF
