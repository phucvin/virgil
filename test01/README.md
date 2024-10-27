cd ..

bin/virgil doc/tutorial/wasm/HelloWorld.v3

bin/virgil compile doc/tutorial/wasm/HelloWorld.v3

./HelloWorld

file HelloWorld

bin/virgil compile -target=wasm doc/tutorial/wasm/ReturnZero.v3

bin/dev/v3c-wasm-wave doc/tutorial/wasm/HelloWorld.v3

time bin/v3i doc/tutorial/examples/Methods/Fibonacci.v3 

bin/v3c-x86-64-linux doc/tutorial/examples/Methods/Fibonacci.v3 

time ./Fibonacci

> 0.6s

cd test/

./all.bash