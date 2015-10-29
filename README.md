rime-zhengma: Zhengma Support for RIME IME
==========================================

author: Rayson Zhu <vfreex@gmail.com>
based on _不知路人_'s work <http://tieba.baidu.com/p/2307993879>

Usage
-----
1. Copy files located in zhengma-hant, for Traditional Chinese, and/or zhengma-hans, for Simplified Chinese, to your RIME schema directory. For Linux operating systems, RIME schema directory is usually at _~/.config/ibus/rime_.
2. Edit configuration file _default.yaml_.
Add

        - schema: zmhant

or/and

        - schema: zmhans

to entry 'schema_list' to enable Traditional Chinese or/and Simplified Chinese input respectively.

