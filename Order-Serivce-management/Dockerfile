# Usar uma imagem base do OpenJDK
FROM eclipse-temurin:21-jdk-alpine

# Definir o diretório de trabalho dentro do container
WORKDIR /app

# Copiar o arquivo JAR gerado pela aplicação para o container
COPY target/Order-Serivce-management-0.0.1-SNAPSHOT.jar app.jar

# Expor a porta usada pela aplicação
EXPOSE 8080

# Comando para executar a aplicação
ENTRYPOINT ["java", "-jar", "app.jar"]