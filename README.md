# WASMRustMongoTest
Attempt to use mongodb rust driver in a webassemly project.

Setup, 

Cargo Build
WASM-PACK build

Failed!

This project is just me attempting to get the mongodb rust driver to work with webassembly,
which apparantly it is not designed to do, I think that the dependancies are not able to target wasm32-unknown-unknown. 
So I'm going to have to pursue some other library to connect to mongo db. And try and post this as an example to the 
rust team's JIRA in order to see if I can get a response regarding the intent of this library and maybe how they 
build the wasm compatible stuff that they use in mongodb compass. Might not even have used thier own driver. 
