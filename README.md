# 编写tcp包，宿端口是8080, 报头里的标志位是ACK，内容是“I am IDS Homework I”，这个内容在负载的第100字节到第200字节的位置出现
# 检测到符合这个规则的数据包，snort就报TEST ALERT
