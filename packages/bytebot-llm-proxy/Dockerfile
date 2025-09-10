FROM ghcr.io/berriai/litellm:main-latest

# Add custom config into the image
COPY ./bytebot-llm-proxy/litellm-config.yaml /app/config.yaml

CMD ["--config", "/app/config.yaml", "--port", "4000"]
