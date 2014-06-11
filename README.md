# Pcduino #
============================================================

```private static int SeqNo(RtuInfo rtu, int no)
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

1. 阿斯顿飞
2. 阿斯发

- 地方

----------
2014-06-11 13:29:44 
