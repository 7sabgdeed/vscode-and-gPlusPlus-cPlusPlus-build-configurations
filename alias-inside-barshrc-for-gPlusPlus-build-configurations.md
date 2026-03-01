add these lines in ~/.bashrc

- for debug build

```shell
alias debug="g++ -std=c++23 -ggdb -pedantic-errors -Wall -Weffc++ -Wextra -Wconversion -Wsign-conversion -Werror -o"
```

- for release build

```shell
alias release="g++ -std=c++23 -O2 -DNDEBUG -pedantic-errors -Wall -Weffc++ -Wextra -Wconversion -Wsign-conversion -Werror -o"
```

then run 

```shell
source ~/.bashrc
```
