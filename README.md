# sample_cpphttplib
Sample using cpp_httplib to get data from https://kinduff.github.io/dog-api/

# How to use

## Clone this sample
git clone https://github.com/tractruong/sample_cpphttplib.git

## Clone cpp_httplib
git clone https://github.com/yhirose/cpp-httplib.git

## Compile code
cd sample_cpphttplib/
g++ -I../cpp-httplib/ -o main src/main.cpp -lssl -lcrypto

## Run app
./main

## Sample output
{"facts":["Dogs can be trained to detect cancer and other diseases in humans."],"success":true}


