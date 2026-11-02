# Nexus selected MCUboot metadata curation

Base: `6d3b3d2c38ab20c242e5b9abb04d050086383eb2` (MCUboot 2.4.0).

This topic is a metadata-only selection for the separate Nexus F407 software
reference: P256/SHA256, vendored TinyCrypt and ASN.1, one image, overwrite-only.
The ordinary vendored TinyCrypt and ASN.1 trees remain unchanged. All MCUboot
C/header algorithms, root LICENSE/NOTICE and upstream attributions are unchanged.

The unused submodule declarations and gitlinks below are removed together.
They are not initialized, fetched, packaged as selected dependencies or claimed
as reviewed support. This is not an upstream all-ports distribution and does
not change the selected algorithms. No generic allow-unselected mechanism is
introduced. Future selection of any removed dependency requires a new review,
exact organizational transport/pin and complete source/notice admission.

| Original module | Path | Original URL | Original gitlink |
| --- | --- | --- | --- |
| `submodule "sim/mbedtls"` | `ext/mbedtls` | https://github.com/ARMmbed/mbedtls | `2ca6c285a0dd3f33982dd57299012dacab1ff206` |
| `submodule "boot/cypress/libs/mtb-pdl-cat1"` | `boot/cypress/libs/mtb-pdl-cat1` | https://github.com/cypresssemiconductorco/mtb-pdl-cat1.git | `55b5a5457195ad2a2a02e0a98ca72a9333e26397` |
| `submodule "boot/cypress/libs/pdl/psoc6pdl"` | `boot/cypress/libs/pdl/psoc6pdl` | https://github.com/cypresssemiconductorco/psoc6pdl.git | `0e38b78ef9ae3ce5db0563bdcde80a028c5fc38a` |
| `submodule "boot/cypress/libs/retarget-io"` | `boot/cypress/libs/retarget-io` | https://github.com/cypresssemiconductorco/retarget-io.git | `bd88e66fc6976de49694382a5ce5dc7613f12ace` |
| `submodule "boot/cypress/libs/core-lib"` | `boot/cypress/libs/core-lib` | https://github.com/cypresssemiconductorco/core-lib.git | `a0f53cdda39a373c45cdbf9f853c8018c1172461` |
| `submodule "boot/cypress/libs/psoc6hal"` | `boot/cypress/libs/psoc6hal` | https://github.com/cypresssemiconductorco/psoc6hal.git | `a0d6c08f1178750e29967999860485878fac09f9` |
| `submodule "boot/cypress/libs/cy-mbedtls-acceleration"` | `boot/cypress/libs/cy-mbedtls-acceleration` | https://github.com/cypresssemiconductorco/cy-mbedtls-acceleration.git | `79a9d8e5e0a98531d8b17f94f3f040359e9cdd9d` |

The root Apache-2.0 LICENSE and NOTICE remain mandatory. Preserve TinyCrypt's
Intel BSD-3-Clause and Kenneth MacKay micro-ecc BSD-2-Clause texts and all
source attributions. Vendored ASN.1 retains its own Apache-2.0 attributions.

This selection does not provide a product bootloader release, public trust
roots, trusted counters, physical power-loss evidence, rollback or certification.
The product owns its static layout, keys, watchdog/deadline and recovery policy.
