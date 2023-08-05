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
- A16 (Requires t1sz_boot 17ull)
  - [Processor Offsets, 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/A16)
  - [Device Offsets, iPhone 14 Pro Max (iPhone15,3), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone15%2C3)
  - [Device Offsets, iPhone 14 Pro (iPhone15,2), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone15%2C2)
- A15 (Everything A15 and below require 25ull t1sz_boot)
  - [Processor Offsets, 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/A15)
  - [Processor Offsets, iPhone 14(+), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/A15_iPhone14)
  - [Device Offsets, iPhone 14+ (iPhone14,8), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone14%2C8)
  - [Device Offsets, iPhone 14 (iPhone14,7), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone14%2C7)
  - [Device Offsets, iPhone SE 2022 (iPhone14,6), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone14%2C6)
  - [Device Offsets, iPhone 13 Pro Max (iPhone14,3), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone14%2C3)
  - [Device Offsets, iPhone 13 Pro (iPhone14,2), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone14%2C2)
  - [Device Offsets, iPhone 13 (iPhone14,5), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone14%2C5)
  - [Device Offsets, iPhone 13 mini (iPhone14,4), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone14%2C4)
- A14
  - [Processor Offsets, 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/A14)
  - [Device Offsets, iPhone 12 Pro Max (iPhone13,4), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone13%2C4)
  - [Device Offsets, iPhone 12 Pro (iPhone13,3), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone13%2C3)
  - [Device Offsets, iPhone 12 (iPhone13,2), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone13%2C2)
  - [Device Offsets, iPhone 12 mini (iPhone13,1), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone13%2C1)
- A13
  - [Processor Offsets, 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/A13)
  - [Device Offsets, iPhone SE 2020 (iPhone12,8), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone12%2C8)
  - [Device Offsets, iPhone 11 Pro Max (iPhone12,5), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone12%2C5)
  - [Device Offsets, iPhone 11 Pro (iPhone12,3), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone12%2C3)
  - [Device Offsets, iPhone 11 (iPhone12,1), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone12%2C1)
- A12
  - [Processor Offsets, 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/A12)
  - [Device Offsets, iPhone XR (iPhone11,8), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone11%2C8)
  - [Device Offsets, iPhone XS Max (iPhone11,6), 16.0-16.5](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone11%2C6)
  - [Device Offsets, iPhone XS Max (China) (iPhone11,4), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone11%2C4)
  - [Device Offsets, iPhone XS (iPhone11,2), 16.0-16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPhone11%2C2)
- A11 (Doesn't work with perf.h [use this repo for reference](https://github.com/Lrdsnow/kfd/tree/arm64))
  - [Device Offsets, iPhone X GSM (iPhone10,6), 16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/iPhone10%2C6/iOS_16.6b1)

### iPad Offsets:
- Warning: None of these have worked sadly, need fix

- iPad Pro 11 4th gen (iPad14,4)
  - [Device Offsets for iOS 16.4.1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPad14%2C4)
- iPad Pro 11 3rd gen (iPad13,6)
  - [Device Offsets for iOS 16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPad13%2C6)
- iPad Air 5 (iPad13,17)
  - [Device Offsets for iOS 16.6b1](https://github.com/Lrdsnow/kfd_offsets/tree/main/DeviceSpecific/iPad13%2C17)
