# COM6012 Scalable Machine Learning - University of Sheffield

## Spring 2024

**by [Shuo Zhou](https://shuo-zhou.github.io/) and [Robert Loftin](https://www.robert-loftin.net/), with [Tahsin Khan](https://www.sheffield.ac.uk/dcs/people/academic/tahsinur-khan) and [Xianyuan Liu](https://xianyuanliu.github.io/)**

In [this module](http://www.dcs.shef.ac.uk/intranet/teaching/public/modules/msc/com6012.html), we will learn how to do machine learning at large scale using [Apache Spark](https://spark.apache.org/).
We will use the [High Performance Computing (HPC) cluster systems](https://docs.hpc.shef.ac.uk/en/latest/hpc/index.html) of our university. If you are NOT on the University's network, you **must** use [VPN (Virtual Private Network)](https://www.sheffield.ac.uk/it-services/vpn) to connect to the HPC.

This edition uses [**PySpark 3.5.0**](https://spark.apache.org/docs/3.5.0/api/python/index.html), the [latest stable release of Spark](https://spark.apache.org/releases/spark-release-3-5-0.html) (Oct 25, 2022), and has 10 sessions below. You can refer to the [overview slides](https://github.com/COM6012/ScalableML/blob/master/Slides/Overview-COM6012-2023.pdf) for more information, e.g. timetable and assessment information.

* Session 1: Introduction to Spark and HPC (Shuo Zhou)
* Session 2: RDD, DataFrame, ML pipeline, & parallelization (Shuo Zhou)
* Session 3: Scalable logistic regression (Shuo Zhou)
* Session 4: Scalable generalized linear models (Robert Loftin)
* Session 5: Scalable decision trees and ensemble models (Tahsin Khan)
* Session 6: Scalable neural networks (Tahsin Khan)
* Session 7: Scalable matrix factorisation for collaborative filtering in recommender systems (Robert Loftin)
* Session 8: Scalable k-means clustering and Spark configuration (Robert Loftin)
* Session 9: Scalable PCA for dimensionality reduction and Spark data types (Robert Loftin)
* Session 10: Apache Spark in the Cloud (Xianyuan Liu)

You can also download the [Spring 2023 version](https://github.com/haipinglu/ScalableML) for preview or reference.

If you do not have one yet, we recommend you to sign up for a [GitHub account](https://github.com/join) to learn using this popular open source software development platform.

## An Introduction to Transparent Machine Learning

Shuo Zhou developed a course on [An Introduction to Transparent Machine Learning](https://pykale.github.io/transparentML/) with [Prof. Haiping Lu](https://haipinglu.github.io/), part of the [Alan Turing Institute’s online learning courses in responsible AI](https://www.turing.ac.uk/funding-call-online-learning-courses-responsible-ai). If interested, you can refer to this introductory course with emphasis on transparency in machine learning to assist you in your learning of scalable machine learning.

## Acknowledgement

The materials are built with references to the following sources:

* The official [Apache Spark documentations](https://spark.apache.org/). *Note: the **latest information** is here.*
* The [PySpark tutorial](https://runawayhorse001.github.io/LearningApacheSpark/) by [Wenqiang Feng](https://www.linkedin.com/in/wenqiang-feng-ph-d-51a93742/) with [PDF - Learning Apache Spark with Python](https://runawayhorse001.github.io/LearningApacheSpark/pyspark.pdf). Also see [GitHub Project Page](https://github.com/runawayhorse001/LearningApacheSpark). *Note: last update in Dec 2022.*
* The [**Introduction to Apache Spark** course by A. D. Joseph, University of California, Berkeley](https://www.mooc-list.com/course/introduction-apache-spark-edx). *Note: archived.*
* The book [Learning Spark: Lightning-Fast Data Analytics](https://www.oreilly.com/library/view/learning-spark-2nd/9781492050032/), 2nd Edition, O'Reilly by Jules S. Damji, Brooke Wenig, Tathagata Das & Denny Lee, with a [github repository](https://github.com/databricks/LearningSparkV2).
* The book [**Spark: The Definitive Guide**](https://books.google.co.uk/books/about/Spark.html?id=urjpAQAACAAJ&redir_esc=y) by Bill Chambers and Matei Zaharia. There is also a Repository for [code](https://github.com/databricks/Spark-The-Definitive-Guide) from the book.

Many thanks to

* [Haiping Lu](https://haipinglu.github.io/) and [Mauricio A Álvarez](https://maalvarezl.github.io/), who has developed this module from 2016 to 2022(3). Their contributions are still reflected in the materials.
* Mike Croucher, Neil Lawrence, Will Furnass, Twin Karmakharm, and Vamsi Sai Turlapati for their inputs and inspirations since 2016.
* Our teaching assistants and students who have contributed in many ways since 2017.
