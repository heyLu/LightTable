# cat /dev/random | LT

## ideas

* opening arbitrary urls/file types
    - images, websites, urls, directories, zip files
        * e.g. different protocols, representations or both
* BOT explorer. it's a graph and making it explorable (possible
    even editable. would make developing LT easier, especially
    for beginners and understanding the interactions between
    different components)
* clickable/jumpable stacktraces. seems to be anticipated as
    lines in stacktraces are already highlighted on `:hover`.
* applications in LT. it's kind of a very advanced web-browser,
    with access to the system (via node) and inspectable, so why
    not at least prototype with/in it?
* a plugin based on `core.typed` that makes validating and exploring
    clojure(-script) programs easier
    - e.g. it should be able to figure out what kinds of objects
        functions expect which is often a bit difficult to do by
        hand.
* a shell interaction plugin, which should make experiments with
    long scripts more enjoyable. but it should probably also integrate
    with the history and completion of the shell.
