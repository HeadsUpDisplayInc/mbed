Bootloader size optimization modifications:
- custom_targets.json -> Removed device features
- features/filesystem/mbed_lib.json -> Removed filesystem library
- features/mbedtls/inc/mbedtls/config-no-entropy.h -> Slimmed down to just RSA/SHA
- platform/mbed_lib.json -> Removed flush at exit
- rtos/mbed_lib.json -> Removed RTOS

.mbedignore -> Ignored a bunch of things in build
