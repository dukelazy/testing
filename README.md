Pcduino
============================================================

```c#

private static int SeqNo(RtuInfo rtu, int no)
{
    int i;
    int k = 0;
    bool FindOk;
    FindOk = false;
    for (i = 1; i < 10; i++)
    {
        if (rtu.Elem.Substring(6 + i, 1) == "1")
        {
            k = k + 1;
            if (k == no)
            {
                FindOk = true;
                break;
            }
        }
    }

    if (FindOk)
        return i * 10;
    else
        return 99;
}

```

### Introduction ###

**inputs**

- follow
- make

* welcome

**Solving** *these* 

# problems #

## will ##

----------

2014-06-11 13:29:44 


I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"


I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

[google]: http://google.com/        "Google"
[yahoo]:  http://search.yahoo.com/  "Yahoo Search"
[msn]:    http://search.msn.com/    "MSN Search"

##*参考资料*##

*[1\].  ^Google.[分析屏蔽原因][1].谷歌中国.2013-09-14.*  
*[1\].  ^Google.[分析屏蔽原因].谷歌中国.2013-09-14.*
<!--引用的网址-->
[1]: http://www.google.com/        "Google.[分析屏蔽原因].谷歌中国.2013-09-14."