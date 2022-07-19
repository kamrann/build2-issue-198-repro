Reproduction of [issue #198](https://github.com/build2/build2/issues/198)

In the build configuration, set `config.bin.lib = shared`
The offending line is then the `liba` prerequisite on line 6 of [this buildfile](packages/component-packages/k-data-server/k-data-server/components/data-server/buildfile).
