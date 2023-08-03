# kfd_offsets
Offsets for KFD

If you have any issues try messaging me on discord, my username is just as it is on github, lrdsnow

Thanks to [@P5-2005](https://github.com/P5-2005) for a quite a bit of the offsets

## How to use? (arm64e)
- Run `git clone -b kern-version https://github.com/felix-pb/kfd.git` (or `git clone -b hidedock_hidehomebar https://github.com/lrdsnow/kfd.git` for a simplified kfd)
- Get the `dynamic_info.h` from this repo for your device and its version
- replace `kfd/libkfd/info/dynamic_info.h` with the file you just downloaded
- in `kfd/libkfd/info/static_info.h` change t1sz_boot to 17ull if iPhone 14 or 25ull if not iPhone 14
- Build!

## How to use? (arm64)
Warning: kfd doesnt work well on arm64 atm and your offsets have to be gotten manually
- Run `git clone -b arm64 https://github.com/lrdsnow/kfd.git`
- Get the `dynamic_info.h` from this repo for your device and its version or make one manually
- replace `kfd/libkfd/info/dynamic_info.h` with the file you just downloaded/made
- Build!

M1 Offsets are borked
