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

### iPhone Offsets:
- iPhone 14 Pro Max (iPhone15,3)
  - Works (Shouldnt Need Offset Change if on default kfd), [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone15%2C3)
- iPhone 14 Pro (iPhone15,2)
  - Works, [Offsets for iOS 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone15%2C2)
- iPhone 14 Plus (iPhone14,8)
  - Untested (Should Work), [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone14%2C8)
- iPhone 14 (iPhone14,7)
  - Untested (Should Work), [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone14%2C7)
- iPhone SE (2022) (iPhone14,6)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone14%2C6)
- iPhone 13 Pro Max (iPhone14,3)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone14%2C3)
- iPhone 13 Pro (iPhone14,2)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone14%2C2)
- iPhone 13 (iPhone14,5)
  - Works, [Offsets for iOS 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone14%2C5)
- iPhone 13 mini (iPhone14,4)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone14%2C4)
- iPhone 12 Pro Max (iPhone13,4)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone13%2C4)
- iPhone 12 Pro (iPhone13,3)
  - Untested or Kernel Panic, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone13%2C3)
- iPhone 12 (iPhone13,2)
  - Works on 16.4 & 16.6b1, Rest Untested or Kernel Panic, [Offsets for iOS 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone13%2C2)
- iPhone 12 mini (iPhone13,1)
  - Works on 16.6b1, Rest Untested or Kernel Panic, [Offsets for iOS 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone13%2C1)
- iPhone SE (2020) (iPhone12,8)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone12%2C8)
- iPhone 11 Pro Max (iPhone12,5)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone12%2C5)
- iPhone 11 Pro (iPhone12,3)
  - [Works](https://twitter.com/eveiyneee/status/1683445953951416320?s=61), [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone12%2C3)
- iPhone 11 (iPhone12,1)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone12%2C1)
- iPhone XR (iPhone11,8)
  - Untested, [Offsets for iOS 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone11%2C8)
- iPhone XS Max (iPhone11,6)
  - Untested, [Offsets for iOS 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone11%2C6)
- iPhone XS Max (China) (iPhone11,4)
  - Untested, [Offsets for iOS 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone11%2C4)
- iPhone XS (iPhone11,2)
  - Untested, [Offsets for iOS 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone11%2C2)
- iPhone X GSM (iPhone10,6)
  - Works on [iOS16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone10%2C6/iOS_16.6b1) with [lrdsnow/kfd (arm64 branch)](https://github.com/Lrdsnow/kfd/tree/arm64)

### iPad Offsets:

- iPad Pro 11 4th gen (iPad14,4)
  - Untested, [Offsets for iOS 16.4.1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPad14%2C4)
- iPad Pro 11 3rd gen (iPad13,6)
  - Untested, [Offsets for iOS 16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPad13%2C6)
- iPad Air 5 (iPad13,17)
  - Untested, [Offsets for iOS 16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPad13%2C17)

