## 边缘计算场景下 QUIC 协议的应用探究

> QUIC（Quick UDP Internet Connection）是谷歌制定的一种基于UDP的低时延的互联网传输层协议。与TCP协议相比，UDP更为轻量，但是错误校验也要少得多。这意味着UDP往往效率更高，但是可靠性比不上TCP。QUIC融合了包括TCP，TLS，HTTP/2等协议的特性，但基于UDP传输。QUIC能减少连接延迟，避免HTTP/2的线头阻塞，还可以快速更新部署，适合移动互联网、物联网和边缘计算领域。要求课题承担者在边缘计算领域探寻合适的应用范式，并给出应用程序的示范实现。

---

### 链接

* [我的GitHub相关仓库](https://github.com/fukaicheng/quic_research)
* [中国知网](https://www.cnki.net/)
* [ResearchGate](https://www.researchgate.net)
* [YoMo Framework](https://yomo.run)

---

### 设计思路

- [ ] QUIC 协议的研究
- [ ] QUIC 协议作为传输层协议时与 TCP/UDP 的异同
- [ ] 网络编程
- [ ] 在边缘计算方面的应用
- [ ] 利用开源框架搭建 IoT Severless 应用

---

### 时间安排

| Time series             | To do          |
| ----------------------- | -------------- |
| 2021.12.01 - 2021.12.28 | 完成[开题报告](#开题报告)   |
| 2022.01.01 - 2022.03.01 | 完成毕设的目标 |
| 2022.03.03 - 2022.03.30 | 完成毕业论文   |

---

### 技术路线

1. Python 语言基础+网络编程
2. Go 语言基础+网络编程
3. Docker 使用
4. YoMo example

---

### 开题报告

##### 文献综述

