# FEVM-FN60G-Hackintosh + BCM94352Z

## What I updated from the [original repo](https://github.com/Xmingbai/FEVM-FN60G-Hackintosh).
### NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82
#### (1) Add `-amfipassbeta` to `boot-args` and add Add `AMFIPass.kext`

```text
-v -wegnoigpu agdpmod=pikera gfxrst=1 -amfipassbeta
```
#### (2) Set csr-active-config to `FF0F0000`
For enable OCLP

#### (3) Disable SecureBootModel

#### (4) Kernel
- Disable Intel related kext.
- Add/Enable some kext for BCM support


## OCLP
https://github.com/dortania/OpenCore-Legacy-Patcher/releases
