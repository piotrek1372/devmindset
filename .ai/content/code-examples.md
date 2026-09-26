# Code examples

`FACT` The examples README maps each directory to a published article and lists Linux kernel 5.10+, Python 3.10+, gawk, and Bash 5+ as requirements. The current index maps `awk/`, `fork/`, `mmap/`, and `strace/` to English articles.

`PROVISIONAL` Add a repository example when a reader can run it independently to inspect the article's mechanism. Keep short illustrative fragments inline. One directory represents one article concept; multiple cohesive files in that directory are acceptable when needed. Not every article needs an example.

For each example, state article URL(s), dependencies, safe invocation, expected observation, known limitations, platform constraints, and any potentially disruptive behavior. Handle predictable failures, close resources, and make randomness reproducible where comparison matters. Label benchmarks with workload, seed, order, cache state, environment and limits; compare the same inputs. Do not claim production safety solely because the README calls examples “production-oriented.”

`UNKNOWN` Whether PL and EN links must both be listed; which version is canonical; final threshold for a production claim.
