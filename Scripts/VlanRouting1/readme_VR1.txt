#config are for router on a stick
#demo file:illustrations/VroutingRouter_stick.pkt

vlan 13 billing
172.16.0.32/27
172.16.0.33 gateway
switchports:fa0/17-24
router int:fa0/0.2

vlan 20 admin
172.16.0.64/27
172,168.0.65 gateway
Switchports :fa0/9-16
router int  :fa0/0.3

vlan 33 reception
172.16.0.0/27
172.16.0.1 gateway
Switchports:fa0/1-8
Router int :fa0/0.1
