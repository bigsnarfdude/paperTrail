# paperTrail

Experiments with Apache Storm writing analytics to Redis

Data visualized in D3.js via Flask

# storm install

https://gist.github.com/bigsnarfdude/93561cf1c4181758ede0

# run project

Build jar file for storm:
`mvn package`

Submit jar to storm:
`storm jar target/storm-basic-analytics-0.0.1-SNAPSHOT-jar-with-dependencies.jar com.example.TopNTweetTopology`

# Potential Algos or data structures

  * Average
  * Cardinality 
  * Moments
  * Mean
  * Quantiles
  * Geo Bounds?
  * Max
  * Min
  * Top K
  * Percentiles
  * Percentile Ranks
  * Sum
  * Top hits
  * Counts
  * Increments
  * T-Digest
  * MinHash

# Questions to answer

1. Activity Tracking on Strings and Things (Did user 'x' log into System 'y'?)
2. Event Tracking on Things (Tell me about all the 500 errors in the past week on System 'y'?)
3. Leaderboards
