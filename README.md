# OP(OpenWrt Packages)
Packages for OpenWrt

sed -i '3i src-git op https://github.com/onkk/op' feeds.conf.default  
./scripts/feeds clean  
./scripts/feeds update -a  
./scripts/feeds install -a  


test1
test2