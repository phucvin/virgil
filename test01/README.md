cd ..

bin/virgil doc/tutorial/wasm/HelloWorld.v3

bin/virgil compile doc/tutorial/wasm/HelloWorld.v3

./HelloWorld

file HelloWorld

bin/virgil compile -target=wasm doc/tutorial/wasm/ReturnZero.v3

bin/dev/v3c-wasm-wave doc/tutorial/wasm/HelloWorld.v3
