# 使用 OpenJDK 17 作為基礎映像
FROM openjdk:17-jdk-slim

# 設定工作目錄
WORKDIR /app

# 將 Maven build 產出的 jar 複製到容器內
COPY target/EZMall-*.jar app.jar

# 指定容器啟動時執行的命令
CMD ["java", "-jar", "app.jar"]

# 容器對外暴露 8080 端口
EXPOSE 8080
