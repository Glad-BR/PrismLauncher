The only difference between this and the upstream vcpkg port is removing the `libiconv` dependency, and only requiring `libpng` when the `tool` feature is enabled. It's very annoying we need to bundle this entire tree to do that.

-@getchoo
