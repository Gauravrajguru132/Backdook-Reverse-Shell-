This project demonstrates a simple reverse shell written in Python for learning purposes.
It is designed to help students and security enthusiasts understand how remote command execution and client–server communication work.

🚀 Features

✅ Client–server architecture using Python sockets

✅ Remote command execution

✅ File transfer support (upload & download)

✅ Cross-platform compatibility (Windows/Linux)

✅ Lightweight and minimal dependencies

📂 Project Structure
reverse-shell/
│── client.py      # Reverse shell client
│── server.py      # Listener / command controller
│── README.md      # Project documentation

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/reverse-shell.git
cd reverse-shell


Install dependencies (if any):

pip install -r requirements.txt

▶️ Usage
Start the server (listener):
python server.py

Run the client (on target machine):
python client.py


Once connected, the server can execute commands remotely on the client machine.

📖 Example

Server side:

[+] Listening on port 4444...
[+] Connection established with 192.168.1.10
>> whoami
client-pc
>> dir
Documents  Downloads  Pictures  client.py


Do not use this tool for unauthorized access.

Use it only in controlled environments where you have explicit permission.
