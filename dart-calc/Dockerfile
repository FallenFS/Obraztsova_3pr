FROM google/dart:latest
WORKDIR /app
COPY calc.dart .
RUN dart compile exe calc.dart -o calc
CMD ["dart", "calc.dart"]
