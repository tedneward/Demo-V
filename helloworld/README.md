# helloworld

This was created with `v new`, but the implicitly-created `.git` directory for the folder was deleted by hand. (Otherwise Git has some serious issues with bringing it into a larger Git repo, that is to say, this Demo-V repository.)

Technically this could be shorted to just the single line inside of `main()`, without declaring the module or the `main` function, but this is what `v new` scaffolds out.

Run the code with `v run .`

Compile it to a binary with `v .`, which produces `helloworld`.

Keep the C-generated source by doing `v -keepc -o main.c .`. The `-o` is necessary to name the C file generated, which seems to disagree with the `-keepc` flag is supposed to do, according to the docs.

