DISQUS Comment Service integration for Zotonic
==============================================
Installation
------------

    cd zotonic/priv/modules
    git clone https://github.com/AlainODea/mod_comment_disqus.git

Usage
-----
Under **Modules**, enable **Comments (DISQUS)**
Under **Modules**, disable **Comments** (they don't coexist)
Under **Config**, make a new config setting with *Module* `mod_comment_disqus`,
*Key* `disqus_shortname` and *Value* is your shortname from Disqus.

