Bootloader size optimization modifications:
- features/mbedtls/inc/mbedtls/config-no-entropy.h -> Slimmed down to just RSA/SHA
- Removed features/unsupported/tests/mbed/env/test_env.cpp and test_env.h --> Why does mbed cli include these by default?
- Added crc32 library
