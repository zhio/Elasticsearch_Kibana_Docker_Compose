FROM docker.elastic.co/elasticsearch/elasticsearch:7.3.2
#这里有一个交互过程
RUN sh -c '/bin/echo -e "y" | elasticsearch-plugin install  https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.3.2/elasticsearch-analysis-ik-7.3.2.zip'
RUN sh -c '/bin/echo -e "y" | elasticsearch-plugin install  https://github.com/medcl/elasticsearch-analysis-pinyin/releases/download/v7.3.2/elasticsearch-analysis-pinyin-7.3.2.zip'
