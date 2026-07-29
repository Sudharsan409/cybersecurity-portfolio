
---

## 🏷️ Tool

![Gobuster](https://img.shields.io/badge/Gobuster-Directory%20Enumeration-blue?style=for-the-badge\&logo=gnu)

---

# 🔎 Gobuster — Directory Enumeration

### 🎯 Objective

Discover hidden directories and files hosted by the web server.

<details>
<summary>💻 Command</summary>

```bash
gobuster dir -u http://<TARGET_IP>:8080 \
-w /usr/share/wordlists/wordlists/wordlist.txt
```

</details>

### 🔧 Options Explained

| Option | Description                                   |
| ------ | --------------------------------------------- |
| `dir`  | Runs Gobuster in directory enumeration mode   |
| `-u`   | Defines the target URL                        |
| `-w`   | Specifies the wordlist used for brute forcing |

### 🧠 Why This Command?

Directory enumeration was performed to identify hidden endpoints and exposed files.

### ✅ Result

Discovered:

```
Directories
```

---

