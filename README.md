# 简介   
ESP32 WIFI工作在STA(station)模式。
# 基于esp-idf-v2.1版本
官方idf链接：[https://github.com/espressif/esp-idf/releases/](https://github.com/espressif/esp-idf/releases/)<br />
# 使用说明
1 更改Makefile中esp-idf的路径为你自己的存放路径或者改环境变量
<pre><code>
# your esp-idf path
IDF_PATH = /home/wang/share/esp32/esp-idf-v2.1
</code></pre>
2 更改user_wifi_sta.h文件中WIFI信息为你自己的WIFI
<pre><code>
#define WIFI_SSID           "yourwifi"
#define WIFI_PASS           "wifipassword"
</code></pre>
3 make编译



