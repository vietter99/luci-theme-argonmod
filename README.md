## Getting started

### Build project

```bash
cd lede/package/lean
rm -rf luci-theme-argon
git clone https://github.com/vietter99/luci-theme-argon.git luci-theme-argon
make menuconfig #choose LUCI->Theme->Luci-theme-argon
make -j1 V=s
```

### Build for OpenWrt official SnapShots and ImmortalWrt

```bash
cd openwrt/package
git clone https://github.com/vietter99/luci-theme-argon.git
make menuconfig #choose LUCI->Theme->Luci-theme-argon
make -j1 V=s
```





