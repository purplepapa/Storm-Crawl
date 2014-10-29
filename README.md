storm-crawler
=============

A collection of resources for building low-latency, large scale web crawlers on [Storm](http://storm.apache.org/) available under Apache License.

Alternatively install Maven and do : `mvn clean package` to generate the full jar then with Storm installed run : 

`storm jar target/storm-crawler-0.3-SNAPSHOT-jar-with-dependencies.jar com.digitalpebble.storm.crawler.CrawlTopology -conf crawler-conf.yaml -local`

Mailing list : http://groups.google.com/group/digitalpebble
