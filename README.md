# DIGITAL HEIST CTF CHALLENGE
🚀 CTF Challenge: "Digital Heist - The Two Keys"

Welcome to Digital Heist, a high-stakes cybersecurity operation where you must infiltrate AI S.A.U.E.R. Corp's compromised Linux system and retrieve two secret keys:

- 🔑 USER KEY (/home/ctf/user.txt) – Your entry point, proving you’ve breached the system.
- 🔐 ROOT KEY (/root/root.txt) – The ultimate challenge, locked behind strict root access.

📜 Challenge Story
You are a renegade hacker working for an underground cyber group called The Shadow Syndicate. Your mission is to infiltrate AI S.A.U.E.R. Corp, a shady organization rumored to be involved in illegal data trading.

Their testing server has been exposed on the internet, and a misconfiguration in their web application hints at a potential way inside. If you can get a foothold, you might be able to escalate privileges and steal their most valuable secrets!

🛠 Step 1: USER KEY
You discover an exposed web interface running on port 5000. It allows user input but seems vulnerable to command injection or arbitrary file read. Can you extract /home/ctf/user.txt?

🔓 Step 2: ROOT KEY
The root key is inside /root/root.txt, only accessible by root.


🔗 Download Challenge:

```
docker pull iven86/digital-heist-ctf:latest
```
```
docker run -p 5000:5000 -p 22:22 --name digital-heist-ctf iven86/digital-heist-ctf:latest
```

☕️: [Buy me a coffee](https://paypal.me/IvenLeniFernandez)
