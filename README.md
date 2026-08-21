# CCNA - Cisco Certified Network Associate
# Lab 01: VLAN, VTP, EtherChannel, DHCP, EIGRP, Routing, STP, HSRP

## 🎯 Mục tiêu
Hãy thực hiện triển khai hệ thống mạng của doanh nghiệp trên hình theo yêu cầu sau: 
1. Cấu hình cổng access, trunk, port-channel phù hợp trên các Switch. 
2. Cấu hình SW1 làm VTP Server,  các Switch khác làm VTP Client và cấu hình thêm các VLAN thích hợp 
3. Cấu hình PVST+ trên các Switch sao cho: 
Trên VLAN 2, SW1 làm root switch, SW2 làm Secondary Trên VLAN 3, SW2 làm root switch, SW1 làm Secondary 
4. Cấu hình các cổng SVI trên các Switch và các cổng Ethernet trên Router với địa chỉ IP như quy hoạch.
5. Cấu hình định tuyến EIGRP đảm bảo mọi địa chỉ trên sơ đồ có thể đi đến nhau được 
6. Thực hiện dự phòng gateway cho các PC thuộc VLAN 2 và VLAN 3 theo yêu cầu 
Trên VLAN2, SW1 và SW2 tham gia group 2 với IP ảo 192.168.2.254
SW1 làm Active Trên VLAN3, SW1 và SW2 tham gia group 3 với IP ảo 192.168.3.254, SW2 làm Active 
7. Cấu hình để R1 làm DHCP Server, cấp địa chỉ động cho các PC thuộc VLAN 2 và 3.

## 📝 Hướng dẫn cấu hình
Xem file `Configuration command lab 1.txt`
## Topology
![Network Topology](Topology_lab_1.png)

## 📁 Files
- `Lab 1.pkt` - File Packet Tracer
- `Configuration command lab 1.txt` - Các lệnh cấu hình
- `Topology_lab_1.png` - Sơ đồ mạng
- `Show running-config lab 1.7z` - File cấu hình backup


# Lab 02: Port Security, SPAN
## 🎯 Mục tiêu
- Cấu hình các vấn đề đã đề cập 
- Thiết lập địa chỉ IP
- Kiểm tra kết nối với ping và hoạt động

## 📝 Hướng dẫn cấu hình
Xem file `Configuration command lab 2.txt`
## Topology
![Network Topology](Topology_lab_2.png) 

## 📁 Files
- `Lab 2.pkt` - File Packet Tracer
- `Configuration command lab 2.txt` - Các lệnh cấu hình
- `Topology_lab_2.png` - Sơ đồ mạng
- `Show running-config lab 2.7z` - File cấu hình backup
