# [1.4.0](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/compare/v1.3.1...v1.4.0) (2026-02-09)


### Features

* **auth:** add OAuth refresh token support ([30a828e](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/30a828e28b4b151d5a88b5908d9681e3601899d8))
* **config:** add config directory support ([f60655f](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/f60655fb9d04d4cd6f8c6de030fb78db675c7fec))
* **sensors:** add illumination, pm, pressure, tvoc ([00de633](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/00de633c003602a3393868a4662fba1c88d98f3f))



## [1.3.1](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/compare/v1.3.0...v1.3.1) (2021-12-05)


### Bug Fixes

* disable log device state updates ([555d614](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/555d614f9fe378835b100566c9454a22e2285eca))
* state неправильно сохранялся для устройств с несколькими range ([6e222e4](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/6e222e4cfe020ca3a0ae6930565b367c4e47d2f4)), closes [#1](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/issues/1)



# [1.3.0](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/compare/v1.2.0...v1.3.0) (2020-07-17)


### Bug Fixes

* правильное прослушивание изменения состояний разных устройств ([a741c37](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/a741c37a5ed812c48559c1ec68c0b758235dab88))
* сохранение state при обновлении списка устройств ([8f9ddca](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/8f9ddcaadba9661d73f6b12e3725d08359e532d5))


### Features

* поддержка properties (встроенные датчики) ([cabe741](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/cabe741635e1f2edf748c3f120882351dd14068b))



# [1.2.0](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/compare/v1.1.1...v1.2.0) (2020-06-28)


### Features

* поддержка разных умений устройств, поддержка одновременного изменения нескольких умений ([6818b23](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/6818b234436588e6b53a1155bb0285935ff42c58))



## [1.1.1](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/compare/v1.1.0...v1.1.1) (2020-06-28)


### Bug Fixes

* добавленные без перезапуска устройства теперь сразу работают ([8707247](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/8707247fddc83db52d3ef89601db31a93044b550))



# [1.1.0](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/compare/v1.0.0...v1.1.0) (2020-05-11)


### Bug Fixes

*  декларативный конфиг ([6572704](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/6572704b255317fcc8e471b8a79353d4058e18d4))
* исправлена ошибка с ненайденным устройством ([ca82dcd](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/ca82dcdb0722a501f436cec5178f9b001d352ddf))
* статус не обновлялся через mqtt stat topic ([8438d50](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/8438d50c00563ecbd8e52d7735964c51a6029556))
* статус DEVICE_NOT_FOUND, если устройство пропало ([b6635a4](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/b6635a4ae2ebd57cac9a08c0cf8c6b74d2806826))
* уникальные id устройств по именам и расположению, исправление ошибок, связанных с переключением состояния ([6cec60a](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/6cec60ad0421b5389faaaadf11bf971cfcc1c830))
* add data to docker volumes ([8094e5a](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/8094e5aa5e96fe8a5a70ebc6b206762b7a2f9363))
* request_id from X-Request-Id ([e2a91dd](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/e2a91dd35672a3b8e488c2c9155627ac46e0e2b4))


### Features

* /provider/v1.0/user/unlink ([82a2409](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/82a24090a65fc218bf5dab4b383f052596d2673e))
* добавление новых устройств без перезапуска ([6f71c01](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/6f71c01608467b88ec3d7689269a94c1cefcca68))
* route /provider/v1.0 ([245b794](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/245b7942aa20b8e198b37445c0fc5b353a618ec4))



# [1.0.0](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/compare/c5b2154991cccc71eab8454fb9b3c525bf8ceac1...v1.0.0) (2019-05-26)


### Features

* управление mqtt устройствами, переписан весь код ([c5b2154](https://github.com/popstas/yandex-dialogs-smarthome-mqtt/commit/c5b2154991cccc71eab8454fb9b3c525bf8ceac1))



