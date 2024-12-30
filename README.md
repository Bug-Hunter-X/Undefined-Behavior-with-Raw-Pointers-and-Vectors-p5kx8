# Rust Bug: Undefined Behavior with Raw Pointers and Vectors

This repository demonstrates a common error in Rust involving unsafe code and vectors. Modifying a vector through a raw pointer after potentially altering the vector's capacity can lead to undefined behavior and crashes. The bug and its solution are explained in the included files (bug.rs and bugSolution.rs).