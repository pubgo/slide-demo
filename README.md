# [Kafka for Gophers](https://go-talks.appspot.com/github.com/marselester/kafka-for-gophers/kafka.slide)

In order to write reliable Go programs that use Apache Kafka,
one should understand what basic Kafka concepts are.
If you've ever felt uneasy about what happens with your service
when a message is lost or written more than once, you should read
[Kafka: The Definitive Guide](https://www.confluent.io/resources/kafka-the-definitive-guide/).

When it comes to choose a Go library to work with Kafka,
the decision could be tough. I would recommend to check out https://github.com/segmentio/kafka-go.

[This presentation](https://go-talks.appspot.com/github.com/marselester/kafka-for-gophers/kafka.slide)
provides an overview of how to achieve reliable data delivery with Kafka in Go.

Run present to view the slides with notes:

```
$ git clone https://github.com/marselester/kafka-for-gophers.git
$ cd ./kafka-for-gophers/
$ go run golang.org/x/tools/cmd/present -notes
```

https://www.cnblogs.com/gwyy/p/12597953.html#:~:text=Golang%20Present%20%E6%98%AF%20Golang%20%E7%A4%BE%E7%BE%A4%E5%BC%80%E5%8F%91%E5%87%BA%E4%BE%86%E7%9A%84%E4%B8%80%E4%B8%AA%E7%AE%80%E5%8D%95%E5%B7%A5%E5%85%B7%EF%BC%8C%E9%80%9A%E8%BF%87%E7%AE%80%E5%8D%95%E7%9A%84%E8%AF%AD%E6%B3%95%E5%8F%AF%E4%BB%A5%E5%88%B6%E4%BD%9C%20ppt%EF%BC%88%E8%AF%AD%E6%B3%95%E8%BF%91%E4%BC%BC%E4%BA%8E%20Markdown%29%E3%80%82%20%E9%BB%98%E8%AE%A4%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F%E6%98%AF.slide,%EF%BC%8C%E6%98%AF%E9%9A%8F%E7%9D%80%20golang%20%E8%AF%9E%E7%94%9F%E8%80%8C%E5%87%BA%E7%8E%B0%E7%9A%84%E4%B8%80%E7%A7%8D%20present%20%E6%A0%BC%E5%BC%8F%EF%BC%8CGo%20%E6%A0%B8%E5%BF%83%E5%BC%80%E5%8F%91%E6%88%90%E5%91%98%E4%BC%BC%E4%B9%8E%E5%8D%81%E5%88%86%E5%96%9C%E6%AC%A2%E4%BB%A5%E8%BF%99%E7%A7%8D%E6%A0%BC%E5%BC%8F%E5%88%86%E4%BA%AB%20Go%20%E8%AF%AD%E8%A8%80%E3%80%82

https://cs.opensource.google/go/x/tools/+/master:present/testdata/

