# Linux

---

## Se brugerens grupper

```bash
groups
```

---

## Tilføj en bruger

```bash
sudo adduser <brugernavn>
```

---

## Tilføj bruger til grupper

```bash
sudo usermod -aG <gruppe>,<gruppe>,<gruppe> <brugernavn>
```

---

## Se IP-adresse

```bash
ip address, ip a eller hostname -I
```

---

## Kopiér publickey til server

```bash
type $env:USERPROFILE\.ssh\id_ed25519.pub | ssh <user>@<ip> "mkdir -p ~/.ssh && cat >> ~/.ssh/authorized_keys"
```

---

## Gå tilbage i en mappe

```bash
cd ..
```

---

## Gå ind i en mappe

```bash
cd <directory>
```

---

## Vis filer og mapper

```bash
ls -a eller ls --all
```

---

## Se nuværende placering

```bash
pwd
```

---

## Opret en mappe

```bash
mkdir <mappenavn>
```

---

## Slet en fil

```bash
rm <filnavn>
```

---

## Slet en mappe og indhold

```bash
rm -r <mappenavn>
```

---

## Kopiér filer

```bash
cp <fil> <destination>
```

---

## Flyt eller omdøb filer

```bash
mv <fil> <destination>
```

---

## Opret en tom fil

```bash
touch <filnavn>
```

---

## Vis indhold af fil

```bash
cat <filnavn>
```

---

## Redigér en fil

```bash
nano <filnavn>
```

---

## Ryd terminalen

```bash
clear
```

---

## Vis tidligere kommandoer

```bash
history
```

---

## Vis nuværende bruger

```bash
whoami
```

---

## Overvåg systemprocesser

```bash
top
```

---

## Udvidet procesovervågning

```bash
htop
```

---

## Se diskplads

```bash
df -h
```

---

## Se RAM-forbrug

```bash
free -h
```

---

## Test netværksforbindelse

```bash
ping google.com
```

---

## Kør kommando som administrator

```bash
sudo <kommando>
```

---

## Genstart systemet

```bash
sudo reboot
```

---

## Sluk systemet

```bash
sudo shutdown now
```
