HELLO-CAML
========================

installation
---------------
- opam switch create . ocaml-base-compiler.4.07.1
- eval $(opam config env)
- opam install merlin ocp-indent dune utop
- dune build bin/main.exe
- dune exec bin/main.exe