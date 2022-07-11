# Common compile flags

## What is not in this table:

- Non c++ language flags
- Deprecated flags
- Compiler specific values for flags
- On synonym flags, standard version or more meaningful version is preferred

| Flag Description    | gcc            | clang          | clang-cl              | msvc           |
| ------------------- | -------------- | -------------- | --------------------- | -------------- |
| C++ standard        | -std=\<value\> | -std=\<value\> | /std:<value>\<value\> | /std:\<value\> |
| Enable all warnings | -Wall          |                | /Wall                 | /Wall          |
