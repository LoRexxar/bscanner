# bscanner
一直没有顺手的扫描器，那就自己写一个吧


# 下面是参数说明

## 必选参数：

- -u 扫描目录
- --test 测试，现在默认扫描http://www.wooyun.org(我随便打的，别打我)

## 可选参数：

- -t,--thread   线程数，默认为30，可选(1~50)
- -e,--ext  是否使用文件类型拓展，默认为关闭，现在的拓展为['.bak','.orig','.inc','.swp','~']
- -f,--filename  字典拓展，默认为./dic/php.txt
- -s,--sleeptime 每次请求的睡眠时间，由于是多线程的，所以这里大一点儿也没关系. 默认1（0-10）
- -l    记录log的等级，默认为2（1-5）
        分别为 1：CRITICAL
               2：ERROR
               3：WARN
               4：INFO
               5：DEBUG

