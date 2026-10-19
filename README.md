# CannBot wheels

Prebuilt Python wheels for CPython 3.11 and 3.12 on Linux AArch64.

## Packages

| File | SHA256 |
| --- | --- |
| `cannbotdsl-0.4.dev28-cp311-cp311-manylinux_2_34_aarch64.whl` | `5a343eadbb1fd57c1caad7cbb4a702b83a3a077ca7d4f010733258a95e4ea427` |
| `cannbot_arena_net_ops-0.1.0-cp311-cp311-linux_aarch64.whl` | `cb2ace3690dc71c4e93143e6d420530595780bc3dd7e3b62ef206407c7a9bde6` |
| `cannbotdsl-0.6.0+g91e7c8f-cp312-cp312-manylinux_2_28_aarch64.whl` | `65b0957dd5462ac97e9318c688d95e9e4e71815832ef3b8c73caf0211998c51f` |
| `cannbot_arena_net_ops-0.1.0-cp312-cp312-linux_aarch64.whl` | `af2d2a83a759ef07700588c187c833cb58583c9941efb4b3d7c221f1a5950633` |
| `cannbot_arena_net_ops-0.1.0-cp311-cp311-linux_aarch64_1.whl` | `a7dd63fe629ca4db90d6cc5e374a6772ef64757ac090d219a97a386aaea7c016` |
| `cannbotdsl-0.6.0+g91e7c8f-cp311-cp311-manylinux_2_28_aarch64_1.whl` | `d77d5e7fe953f50c8b2a3c8c9b69600fb483c18aece80a788ca44343eb2c7cb7` |

## Installation

```bash
python3.11 -m pip install ./cannbotdsl-0.4.dev28-cp311-cp311-manylinux_2_34_aarch64.whl
python3.11 -m pip install ./cannbot_arena_net_ops-0.1.0-cp311-cp311-linux_aarch64.whl

python3.12 -m pip install ./cannbotdsl-0.6.0+g91e7c8f-cp312-cp312-manylinux_2_28_aarch64.whl
python3.12 -m pip install ./cannbot_arena_net_ops-0.1.0-cp312-cp312-linux_aarch64.whl
```

These wheels target CPython 3.11 (`cp311`) or CPython 3.12 (`cp312`) and AArch64 Linux. They are not compatible with x86_64 or other CPython ABI versions.
