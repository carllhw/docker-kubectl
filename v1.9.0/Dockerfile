FROM alpine:3.7

ENV KUBECTL_VERSION v1.9.0
RUN curl -L -o /usr/local/bin/kubectl "https://storage.googleapis.com/kubernetes-release/release/$KUBECTL_VERSION/bin/linux/amd64/kubectl" \
  && chmod +x /usr/local/bin/kubectl
