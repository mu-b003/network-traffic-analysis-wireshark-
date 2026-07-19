# Commands Used

## System Update

```bash
sudo apt update
sudo apt upgrade -y
```

---

## Install Apache

```bash
sudo apt install apache2 -y

sudo systemctl enable apache2

sudo systemctl start apache2

sudo systemctl status apache2
```

---

## Install OpenSSH

```bash
sudo apt install openssh-server -y

sudo systemctl enable ssh

sudo systemctl start ssh

sudo systemctl status ssh
```

---

## Check IP Address

```bash
ip a
```

---

## Open Wireshark

```bash
sudo wireshark
```

---

## Generate ICMP Traffic

```bash
ping 192.168.81.129
```

---

## Generate HTTP Traffic

```bash
curl http://192.168.81.129
```

---

## Generate Multiple HTTP Requests

```bash
for i in {1..5}; do
curl http://192.168.81.129
done
```

---

## Generate DNS Queries

```bash
nslookup github.com

nslookup bitpluss.com
```

---

## Download Web Page

```bash
wget http://192.168.81.129
```

---

## Generate SSH Traffic

```bash
ssh Mubarak@192.168.81.129

pwd

ls

exit
```

---

## Wireshark Filters

```text
icmp

http

dns

tcp

arp

ssh
```
