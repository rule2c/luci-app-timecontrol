sed -i '$a src-git timecontrol https://github.com/rule2c/luci-app-timecontrol.git' feeds.conf.default

./scripts/feeds update timecontrol
./scripts/feeds install -a -p timecontrol
