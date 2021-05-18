# Changes for MinaProtocol

The `ppx_deriving_yojson` protocol was forked from `ocaml-ppx/ppx_deriving_yojson` at
commit b2f0b8631381d01fcee41abd8c017762171b4774.

In order to build with OCaml 4.11.2 and the Jane Street libraries at versions v0.13.x,
one change was made atop tag v3.5.3:

  - In `src/ppx_deriving_yojson_runtime.mli`, declare polymorphic `=`.

This same change appeared in tag v3.6.0.
