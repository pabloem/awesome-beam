[<img src="https://beam.apache.org/images/logos/full-color/name-right/beam-logo-full-color-name-right-500.png" align="right">](https://beam.apache.org/)

# Awesome Beam [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated directory of awesome things related to Apache Beam. Inspired by [Awesome Flink](https://github.com/wuchong/awesome-flink) and [Awesome Hadoop](https://github.com/youngwookim/awesome-hadoop).

- [Packages](#packages)
  - [Beam Wrappers](#beam-wrappers)
  - [Transforms](#transforms)
  - [Notebooks](#notebooks)
  - [Machine Learning](#machine-learning)
  - [Tests](#Tests)
- [Resources](#resources)
  - [Official Resources](#official-resources)
  - [Community](#community)
  - [Books](#books)
  - [Courses](#courses)
  - [Papers](#papers)
  - [Blogs and Blog Posts](#blogs-and-blog-posts)
  - [Talks](#talks)

# Packages

## Beam Wrappers

- [Apache Beam in Kotlin to reduce boilerplate](https://blog.papercut.com/apache-beam-in-kotlin-to-reduce-the-boilerplate-code/). Using Kotlin's special features to make Beam Java SDK less verbose!
- [Scio - Scala wrapper for Apache Beam](https://github.com/spotify/scio) Wrap Beam functionality in a simple Scala API.
- [thruber - Clojure wrapper for Apache Beam](https://github.com/atdixon/thurber) Bring Clojure's powerful, expressive toolkit (destructuring, immutability, REPL, async tools, etc etc) to Apache Beam.

## Transforms

- (Pending)

## Notebooks

- [Apache Zeppelin](http://zeppelin.apache.org/) - Web-based notebook that enables interactive data analytics with plugable backends, plotting, etc.

## Machine Learning

- [Tensorflow Transform](https://www.tensorflow.org/tfx/transform/) is a library for preprocessing data with TensorFlow. It uses Beam, and thus it brings the portability aspect of Beam (i.e. run in any supported runner).

## Tests

- (Pending)

# Resources

Various resources, such as books, websites and articles.

- [Error Handling Elements in Apache Beam Pipelines](https://medium.com/@vallerylancey/error-handling-elements-in-apache-beam-pipelines-fffdea91af2a). A blog post detailing how to handle when individual elements have errors in their processing downstream.

## Official Resources

- [Beam Documentation](https://beam.apache.org/documentation/)
 - [Java SDK](https://beam.apache.org/documentation/sdks/java/)
 - [Python SDK](https://beam.apache.org/documentation/sdks/python/)
 - [Go SDK](https://beam.apache.org/documentation/sdks/go/)
- [Beam Wiki](https://cwiki.apache.org/confluence/display/BEAM)
- Beam Quickstarts [Java](https://beam.apache.org/get-started/quickstart-java/), [Python](https://beam.apache.org/get-started/quickstart-py/), [Go](https://beam.apache.org/get-started/quickstart-go/).

## Community

- [Apache Beam Slack Channel](https://the-asf.slack.com/messages/beam) and [Invite to Join](http://s.apache.org/slack-invite)
- [Twitter](https://twitter.com/ApacheBeam)

## Books

- [Streaming Systems: The What, Where, When and How of Large Scale Data Processing](http://streamingbook.net/).

## Courses

- [Apache Beam Katas](https://github.com/apache/beam/tree/master/learning/katas) are interactive Beam coding exercises.
- [Apache Beam | A Hands-On course to build Big data Pipelines](https://www.udemy.com/course/apache-beam-a-hands-on-course-to-build-big-data-pipelines/).

## Papers

- [The Dataflow Model: A Practical Approach to Balancing Correctness, Latency, and Cost in Massive-Scale, Unbounded, Out-of-Order Data Processing](http://people.csail.mit.edu/matei/courses/2015/6.S897/readings/google-dataflow.pdf) - Paper introducing the Dataflow model, which was the predecesor to Beam. (2015)

## Blogs and Blog Posts

- [Official Beam Blog](http://beam.apache.org/blog/)
- [Python Development Environments for Beam on GCP](https://medium.com/google-cloud/python-development-environments-for-apache-beam-on-google-cloud-platform-b6f276b344df) - How to set up a development environment for Python Dataflow jobs.
- [Java Development Environments for Beam on GCP](https://medium.com/google-cloud/setting-up-a-java-development-environment-for-apache-beam-on-google-cloud-platform-ec0c6c9fbb39) - How to set up a development environment for Java Dataflow / Beam jobs.
- [Coding Apache Beam in your Web Browser and Running it in Cloud Dataflow](https://medium.com/google-cloud/coding-apache-beam-in-your-web-browser-and-running-it-in-cloud-dataflow-c41c275d42c8) - How to create and run a Beam Pipeline on Dataflow using Code Editor.
- [Realtime Data Processing with Apache Beam at Dailymotion](https://medium.com/dailymotion/realtime-data-processing-with-apache-beam-and-google-dataflow-at-dailymotion-7d1b994dc816)

## Talks

- So you want to write a Beam SDK? Talk by Robert Bradshaw about the pieces of an SDK and the runner API [[slides](https://docs.google.com/presentation/d/1Cso0XP9dmj77OD9Bd53C1M3W1sPJF0ZnA20gzb2BPhE/edit#slide=id.p)]
- Robust, performant and modular APIs for  data ingestion with Apache Beam - Eugene Kirpichov, Ismael Mejia [[slides](https://docs.google.com/presentation/d/1Ei4T39zS2rNDPjUG-vlEqaqjwG9kMbq_b3S7EsRGj04/edit#slide=id.g41f7bcddd4_0_6)] - Important talk about IO, and what we think is the future of IO for Big Data systems.
- SplittableDoFn - A Transform Developer's perspective. Alex Van Boxel. [[slides](https://docs.google.com/presentation/d/1dSc6oKh5pZItQPB_QiUyEoLT2TebMnj-pmdGipkVFPk/edit#slide=id.g3f64cc4601_2_46)].
- Large Scale Landuse Classification of Satellite Imagery - Suneel Marthi [[slides](https://smarthi.github.io/BBuzz18-Satellite-image-classification-for-landuse/)] [[code](https://github.com/smarthi/satellite-images)] - Excellent talk using Beam's Python SDK to run machine learning over a dataset of images.
- Beam me up, Samza! - The Beam runner for Samza - Xinyu Liu [[slides](https://www.slideshare.net/XinyuLiu11/beam-me-up-samza)].
- Python Streaming Pipelines with Beam on Flink - Aljoscha Krettek, Thomas Weise [[slides](https://docs.google.com/presentation/d/1RUq9dFgu21DhuxVkLu1AewJTHAxMhO1EeBeWFXMAKKg/edit#slide=id.g119cd57211_0_16)]. - A talk about how Beam enables Python pipelines to run on top of Flink.
- Spark Runner (R)evolution - David Moravek, Ismaël Mejía [[slides](https://docs.google.com/presentation/d/1d2irEnzXqpUKSeBCF4QSeCvDYfVUcUpTW4DY0xvOREQ/edit?usp=sharing)] - A talk about Spark runner implementation, performance improvements and roadmap.
