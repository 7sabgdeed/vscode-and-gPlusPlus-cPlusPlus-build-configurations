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


***

```shell
# debug <OUTPUT_FILE_NAME> <SOURCE_CODE_FILE> for debug build
# ex:
debug calculator calculator.cpp
./calculator


# release <OUTPUT_FILE_NAME> <SOURCE_CODE_FILE> for release build
# ex:
release calculator calculator.cpp
./calculator

```
