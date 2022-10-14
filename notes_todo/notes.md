# Notes


## Steps to learn sparrow recsys

[ ] whole picture of this project
    [ ] project structure
    [ ] how to run the project
[ ] re-produce the code step by step (roll back the code based on git log maybe)
    [ ] the order of re-produce
    [ ] understand the code and re-produce


## Project Structure

1. src: main code for online service including 3 components
   1. offline
   2. near line
   3. online
2. RecPySpark: Offline training for 
   1. embedding 
   2. feature engineering
   3. CF algorithm
3. TFRecModel: offline training for DL models including embeddingMLP, deepFM.. 

## TODO

1. [ ] [Book Recommended](https://time.geekbang.org/column/article/292682)
2. [ ] [多路召回的代码在哪儿？](https://time.geekbang.org/column/article/299494)


## Redis

```shell
# Reference url: https://redis.io/docs/getting-started/
# install redis 
brew instal redis
# start redis 
redis-server
# launtch redis cli: 
redis-cli

```

