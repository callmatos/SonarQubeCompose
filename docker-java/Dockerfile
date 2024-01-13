FROM java-estrategia

WORKDIR /app

COPY . .
RUN javac OlaMundo.java

RUN java --version

EXPOSE 3000

CMD ["java",OlaMundo]