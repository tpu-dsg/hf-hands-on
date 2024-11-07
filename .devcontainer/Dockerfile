FROM nvidia/cuda:12.4.1-cudnn-devel-ubuntu22.04

RUN sed -i 's@archive.ubuntu.com@ftp.jaist.ac.jp/pub/Linux@g' /etc/apt/sources.list

# Install uv
COPY --from=ghcr.io/astral-sh/uv:latest /uv /uvx /bin/
