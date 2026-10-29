FROM debian:bookworm-slim
RUN apt-get update \
    && apt-get install -y --no-install-recommends build-essential gdb clangd \
    && rm -rf /var/lib/apt/lists/*