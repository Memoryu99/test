# Signal Atlas · 移动网络信号仪表盘

面向手机移动测点场景的浏览器网络质量仪表盘。页面每 500ms 更新，提供实时 RTT、抖动、丢包、轻量上下行测速、网络类型、IP/ASN/出口网络、IP 近似位置、GPS 轨迹，以及 RSRP、SINR、RSRQ、RSSI、PCI、Band、ARFCN、QCI/5QI 等蜂窝字段的详细阈值说明与手动录入。

> 普通网页无法直接读取手机基带的 RSRP、SINR、RSRQ、PCI、QCI/5QI、SSID 或 BSSID。仪表盘会明确显示这些字段的数据状态，绝不生成虚假测量值。

站点由 GitHub Actions 自动部署到 GitHub Pages。

