# Install and enable sogou pinyin on ubuntu

1. Grab latest deb from https://pinyin.sogou.com/linux/?r=pinyin
```
wget http://cdn2.ime.sogou.com/dl/index/15919192613/sogoupinyin_2.3.2.07_amd64-831.deb?st=u-ZO0HFsp18YZX2Hrq_RSg&e=1603814499&fn=sogoupinyin_2.3.2.07_amd64-831.deb

sudo dpkg -i sogoupinyin_2.2.0.0108_amd64.deb

dpkg-reconfigure locales

```
2. Now choose the locale that you want to use, e.g ZN - CN - UTF8 locale.

3. reboot or logoff + login
```
im-config -n fcitx
fcitx-config-gtk3
```

4. add sogoupinyin as input method

5. on input window press control+space to switch input

