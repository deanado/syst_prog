FROM ubuntu
RUN apt-get update && apt-get install -y g++
COPY cled.cpp .
RUN g++ /cled.cpp -o cled
CMD ./cled

