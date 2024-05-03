# 🗒1 概述

小鹤-万磁王是基于官方⌨[小鹤音形](https://google.tigermed.net/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwil3faz5vCFAxVPi68BHQicAt8QFnoECBcQAQ&url=https%3A%2F%2Fflypy.com%2F&usg=AOvVaw3gBahnwrM4WIiTnS9C_eh9&opi=89978449)的一个进阶方案，主要体现在词和字库量的提升，以及对部分词库进行了优化。

# 🕴2 方案适用人群

在经历数次的输入方案更换后（全拼-->智能ABC双拼7年-->五笔2年-->小鹤音形2年），我最终采用了小鹤音形的输入方案。

音码对于日常来说，以读为写的方式，奠定了其<u>听打、想打</u>的优势，更适合日常使用场景；而五笔等诸多全形码方案则在更使用于看打、录入场景，同时其拆字、想字等是需要高出音码多倍的学习成本的。固而，我将使用了两年余久的五笔换成了小鹤，因为我清楚小鹤音形更适合于我。小鹤音形的适合人群：

1. 使用小鹤双拼的人群，进而可以提升，使用小鹤音形；
2. 使用双拼或全拼，可以更换至小鹤音形；
3. 短期内（这里以1个月为基准）需要提升打字速度的人，可以通过学习小鹤双拼，减少码长进而减少击键量，之后可以考虑学习形码来减少选重。
   1. 码长：每个字击打键盘的数量；
   2. 击键量：打完文章敲击键盘的次数；
   3. 选重：比如拼音中的读音“zhong”有多个汉字“中、钟、重”等，此时我们需要按数字键或者翻页键=，对字进行二次选择。



# 🫂3 此方案解决的问题

小鹤官方不论是挂接方案还是官方app，对于词或字的安排都似乎已经到了诸多不合理的场景，所以为了更加适合听打、想打人群，故而希望将词库、字库进行优化，作为挂接方案到可以自定以的输入方案中。

此方案解决的问题以及思路如下：

1. **增大字库**：官方中挂接码单字库仅仅包含了8千余字，一些常用字没有，如伛yurx，现将<u>五笔方案</u>中的简体单字全部加入。
2. **增大词库**：官方大量的常用词没有，进而加入了大量二字词作为二、三位置候选，如果该码没有单字则作为首候选；
3. 优化候选：官方词库中的四字词大量占用了二字词的位置，如万事俱备（无尽）。故将二字词加入作为二候选，将四字词全部作为末尾候选词；