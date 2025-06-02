# TODO
- assemble core bits into wg0.conf on portal
- requirements.txt has to differ from usb to rpicam
- erosion user needs:
    - user:
        name: erosion
        groups: video <-------------
        append: yes
        state: present
- install nginx on core to allow direct connection from laptop/phone to car
- deploy-core
- firewall on its own role
- coturn
- iperf3
- community.general.wg_keypair
