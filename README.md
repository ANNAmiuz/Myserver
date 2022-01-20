# Preparation
```shell
# make a new directory
mkdir build
cd build
cmake ..
```

# Format and Check
```shell
# format the code
make format
# code check
make cpplint
# tidy the code
make clang-tidy
```

# Compile
```shell
make server
# mock clients for test
make multiple_client
make single_client
```