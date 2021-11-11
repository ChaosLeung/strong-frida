# strong-frida

Make frida strong, bypass frida detection.

## Anti Frida tricks

[Anti Frida tricks](docs/README.md)

## Features

[Patch files](patch/frida-core) base from [@feicong](https://github.com/feicong/strong-frida), update by [@Chaos](https://github.com/ChaosLeung).

```
$ tree patch/frida-core/
patch/frida-core
├── 0001-PATCH-string_frida_rpc.patch
├── 0002-PATCH-io_re_frida_server.patch
├── 0003-PATCH-pipe_linjector.patch
├── 0004-PATCH-io_frida_agent_so.patch
├── 0005-PATCH-symbol_frida_agent_main.patch
├── 0006-PATCH-thread_gum_js_loop.patch
├── 0007-PATCH-thread_gmain.patch
├── 0008-PATCH-protocol_unexpected_command.patch
├── 0009-PATCH-fix_linux_armhf_build.patch
└── 0010-PATCH-default_port.patch
```

## References

https://github.com/hluwa/strongR-frida-android

https://github.com/qtfreet00/AntiFrida

https://github.com/darvincisec/DetectFrida

https://github.com/b-mueller/frida-detection-demo
