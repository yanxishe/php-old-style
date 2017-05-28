#PHP-Old-Style

PHP-Old-Style是一个PHP旧版本函数的兼容层，可以在新的PHP版本中兼容一些被废弃的函数（将旧函数名称用新函数来实现）。比如可以在PHP5.5之后的版本，继续使用mysql_*系列函数。

这样的好处就是可以在尽量不修改或者少修改旧版本代码的情况下，运行在PHP新版本上，并且还采用新版本的新特性。

PHP-Old-Style is a compatibility level of old php versions for running new php versions,for example use mysql_* function in PHP5.5 or later.

交流社区
--
QQ群：204787773


举例说明
--

比如在 PHP5.5 环境中，运行 mysql_connet 会报错， ( 因为mysql系列函数被废弃），截图如下：


采用 php-old-style 之后，就会兼容 mysql_connet等函数，并且使用官方推荐最新的 mysqli来实现转换。这样的好处就是可以在不修改旧版本代码（mysql系列函数）的情况下，运行在PHP新版本上，并且还采用新版本的新特性（mysqli新版本）。






