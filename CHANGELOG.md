# Changelog

## [0.3.0](https://github.com/amritk/dev-go/compare/v0.2.0...v0.3.0) (2026-09-18)


### ⚠ BREAKING CHANGES

* **api:** 6 breaking changes to the SDK surface.
    - Renamed SDK from `TestIt` to `ScalarGalaxy`.
    - Removed operation `planets.pizzas.list` (`GET /planets`).
    - Removed operation `planets.pizzas.create` (`POST /planets`).
    - Removed operation `planets.pizzas.retrieve` (`GET /planets/{planetId}`).
    - Removed operation `planets.pizzas.delete` (`DELETE /planets/{planetId}`).
    - Removed operation `planets.pizzas.uploadImage` (`POST /planets/{planetId}/image`).

### Features

* **api:** update SDK name (+11 more changes) ([7a4e41e](https://github.com/amritk/dev-go/commit/7a4e41efc675b9ac5fd2d8d2d401f2f0d2a6bb52))

## [0.2.0](https://github.com/amritk/dev-go/compare/v0.1.0...v0.2.0) (2026-09-18)


### ⚠ BREAKING CHANGES

* **api:** 7 breaking changes to the SDK surface.
    - Renamed SDK from `ScalarGalaxy` to `TestIt`.
    - Removed operation `planets.list` (`GET /planets`).
    - Removed operation `planets.create` (`POST /planets`).
    - Removed operation `planets.retrieve` (`GET /planets/{planetId}`).
    - Removed operation `planets.update` (`PUT /planets/{planetId}`).
    - Removed operation `planets.delete` (`DELETE /planets/{planetId}`).
    - Removed operation `planets.uploadImage` (`POST /planets/{planetId}/image`).
* **api:** Renamed SDK from `DemoApiScalarGalaxy` to `ScalarGalaxy`.

### Features

* **api:** initial SDK generation ([83a7e99](https://github.com/amritk/dev-go/commit/83a7e993a8a7bbb639657d51806f602db70f8c22))
* **api:** update SDK name (+1 more change) ([a01ac07](https://github.com/amritk/dev-go/commit/a01ac077e0a20a4e08fdffd07d9b784bd0f95161))
* **api:** update SDK name (+12 more changes) ([d17c9d4](https://github.com/amritk/dev-go/commit/d17c9d4ed4ad0e4a644bb01c94d575615a39136f))


### Chores

* **api:** update generated SDK content ([b429f4b](https://github.com/amritk/dev-go/commit/b429f4b634ad31c5d68af0b14a5c7f069ba788fb))
* **api:** update generated SDK content ([48256fe](https://github.com/amritk/dev-go/commit/48256feef08906e950cf9bba05d7c962957e09f9))
