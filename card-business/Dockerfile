FROM ubuntu:22.04
RUN apt-get update && \
    apt-get install -y python3.11 python3.11-dev python3-pip
WORKDIR /app
COPY . .
RUN pip3 install --no-cache-dir -r requirements.txt
EXPOSE 8080
ENV LOGOMARCA="chrome://branding/content/about-logo.png"
ENV FOTO="https://images.unsplash.com/photo-1555421689-43cad7100750?q=80&w=1887&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
ENV NOME="Docker Study"
ENV IDADE=99
ENV EMAIL="EMAIL@GMAIL.COM"
ENV PROFISSAO="Student"
ENV SITE="www.google.com"
CMD ["python3", "app.py"]
