# Apache Kafka

Apache Kafka to platforma do prztwarzania danych strumieniowych - danych napływających w sposób ciągły. Z platofmą można zapoznać się [tutaj](https://kafka.apache.org/quickstart).

### Zadanie
Zaimplementuj program wyświetlający średni czas spędzany przez użytkowników na danej stronie (średnią z ostatnich 30 sekund).
1. Stwórz program w Pythonie generujący dane mówiące ile czasu użytkownik o danym id spędził na danej stronie internetowej.
2. Powyższy program generowane dane powinien wysyłać na topic kafki.
3. Powyższy program powinien generować dane w sposób strumieniowy.
4. Stwórz program, korzystając z Kafka Streams, wypisujący na ekran średni czas spędzany przez użytkowników na danej stronie (średnią z ostatnich 30 sekund).
5. Dane powinny być wyświetlane w postaci tabeli.
6. Całość powinna działać jako kontenery Dockera (jeden lub kilka kontenerów).