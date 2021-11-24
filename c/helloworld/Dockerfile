FROM gcc:4.9
COPY . /helloworld
WORKDIR /helloworld
RUN echo "Instalacao iniciada"
RUN make all
RUN echo "Instalacao concluida"
CMD ["./helloworld"]

