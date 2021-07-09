Structured Streaming using the Python DataFrames API
Apache Spark includes a high-level stream processing API, Structured Streaming. In this notebook we take a quick look at how to use the DataFrame API to build Structured Streaming applications. 
We want to compute real-time metrics like running counts and windowed counts on a stream of timestamped actions (e.g. Open, Close, etc) with Watermarking.
