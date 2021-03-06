Edgar documentation
=================
- [Good Documentation](https://www.sec.gov/info/edgar/pdsdissemspec092812.pdf)
- [Same thing as ^](https://www.sec.gov/info/edgar/pdsdissemspec910.pdf)
- [Documentation summary](http://okfnlabs.org/blog/2014/03/04/sec-edgar-database.html)
- [t](https://stackoverflow.com/questions/13504278/parsing-edgar-filings)

Edgar data
=========
- [Base directory](ftp://ftp.sec.gov/edgar/)
- [Daily](ftp://ftp.sec.gov/edgar/Feed/2016/QTR3/20160729.nc.tar.gz)
- [Also quaterly](ftp://ftp.sec.gov/edgar/full-index/2016/QTR3/company.idx)
- [Monthly](ftp://ftp.sec.gov/edgar/monthly/xbrlrss-2016-07.xml)
- [Daily](ftp://ftp.sec.gov/edgar/daily-index/master.20160729.idx)
- [HTTP API](https://github.com/rahulrrixe/SEC-Edgar/blob/master/SECEdgar/crawler.py#L47)

Other analyses
=============

- [Benford's law applied to Edgar data with python](https://hornportfolio.com/2015/12/26/edgar/)
- [Getting Edgar data with python and raptor XML](www.slideshare.net/afalk42/xbrl-us-altova-webinar)
- [Many analyses based on Calcbench API](http://blog.andrewonfinance.com/)

Spark
=====

- [Spark on docker](https://hub.docker.com/r/sequenceiq/spark/)
- [Quick start guide to Spark API](http://spark.apache.org/docs/latest/quick-start.html)
- [Thorough introduction to Spark API interactively](http://spark.apache.org/docs/latest/programming-guide.html)
- [Cloudera course in Spark API](http://www.cloudera.com/documentation/enterprise/latest/topics/spark.html)
- [Docker image](https://github.com/sequenceiq/docker-spark)
- [Jupyter Spark kernel](https://github.com/apache/incubator-toree/blob/master/README.md)

Scala
======

- [Wikiepedia scala overview](https://en.wikipedia.org/wiki/Scala_%28programming_language%29)
- [Language tutorial](http://docs.scala-lang.org/overviews/collections/overview)


Libraries for edgar
===================

- [Scala Edgar library](https://github.com/mmistroni/EdgarApp)
    * [Download manager](https://github.com/mmistroni/EdgarApp/blob/master/src/main/scala/edgar/actors/DownloadManager.scala)
	* [File manager](https://github.com/mmistroni/EdgarApp/blob/master/src/main/scala/edgar/actors/EdgarFileManager.scala)
	* [Request launcher](https://github.com/mmistroni/EdgarApp/blob/master/src/main/scala/edgar/actors/EdgarRequests.scala)
	* [Spark Downloader](https://github.com/mmistroni/EdgarApp/blob/master/src/main/scala/edgar/spark/EdgarSparkDownloader.scala)
	* [Index file processor](https://github.com/mmistroni/EdgarApp/blob/master/src/main/scala/edgar/core/IndexProcessor.scala)
	* [Edgar sink](https://github.com/mmistroni/EdgarApp/blob/master/src/main/scala/edgar/core/EdgarSink.scala)
- [Python Edgar library 1](https://pypi.python.org/pypi/SECEdgar)
- [Python Edgar library 2](https://pypi.python.org/pypi/python-edgar/1.0)
- [Python Edgar library 3](https://github.com/datasets/edgar)
- [Python Edgar library 4](https://github.com/andrewkittredge/financial_fundamentals)

Cool stuff
=========

- [Wikipedia: Hindly Milner type system](https://en.wikipedia.org/wiki/Hindley%E2%80%93Milner_type_system)
