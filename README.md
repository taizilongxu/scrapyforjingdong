
    scrapy crawl test -s JOBDIR=data -o items.csv

这个命令运行爬虫,输出文件items.csv,可以返回上次中断继续运行.

    watch -n 1 -d 'wc -l items.csv;du -h items.csv'

观察文件变化
