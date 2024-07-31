# FYI
BasicOS isn't like regular operating systems. For one, it isn't made by proffesionals, but a 17 year old moron who needs to prove himself he can code. That means it is limited. The OS is monotasking and is exclusively GUI (although maybe I will implement it someday). A standard library with functions like `printf` or `malloc`, or `strcmp` aren't available here. Instead they are replaced with functions like `graphics_text`, `heap_allocate` and `string_compare`. Why? Because it's my OS, don't like it- make your own.

Another thing: you will notice some functions have a common prefix (`graphics_` or `heap_`). That is because I come from an OOP background and am huffing copium by pretending these prefixes are actually static classes.

Oh and the binaries are run in Ring 0 because I'm too lazy to set up proper paging so please don't write malicious programs :\)
