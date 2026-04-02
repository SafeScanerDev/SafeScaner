🛡️ SafeScaner v5.0 — Pure Security Logic
SafeScaner is a lightweight, transparent, and powerful tool designed to detect malicious activity (Miners/RATs/Stealers) on your system. Version 5.0 serves as the foundation for a new generation of scanners focused on maximum openness and efficiency.
💎 Why Version 5.0 is a Breakthrough
In the fifth version, we completely reimagined the search logic, moving from simple filename scanning to deep content analysis.
Deep Keyword Analysis: The system recognizes dangerous code constructions (powershell bypass, bitsadmin, taskkill) used by 90% of modern stealers and miners.
Zero-Infection Architecture: The scanner requires no installation. It is a clean Batch script that leaves no traces in the registry and collects no personal data.
Smart Logging System: Automatically creates detailed reports in the logs folder. You always see exactly what was found and where.
Total Control: Unlike closed-source antiviruses, SafeScaner gives you the choice: delete a suspicious object or keep it if it's your personal tool.
🤝 Why You Can Trust Us
Trust in the security field is paramount. SafeScaner is built on Open Source principles:
Open Source Code: You can read every single line of our script. We do not hide our logic behind complex compiled files. You know exactly what the program does.
Local Operation: The scanner works exclusively on your device. Your files and their names are never sent to cloud servers.
Community Driven: The project is developed with the support of cybersecurity enthusiasts. We value our reputation and the transparency of our development processes.
⚠️ Important Note
SafeScaner utilizes system utilities for analysis. Due to its deep inspection and powerful commands, some antiviruses may falsely flag the script as "suspicious." This is a False Positive caused by the fact that security tools often use the same methods as malware to analyze the system.
🌐 Connectivity & Support
Stay in touch with the developers, follow updates, and suggest your ideas:
💬 Telegram / Menalog: tteroson
💻 GitHub / VNDCODE: [SafeScanDev]
🎮 Discord Community: [https://discord.gg/u6GUXnrs]
SafeScaner v5.0 — We don't just scan files. We protect your digital freedom.

🔍 Типы обнаруживаемых угроз
SafeScaner v5.0 сфокусирован на выявлении наиболее опасных классов вредоносного ПО, использующих скриптовые методы закрепления в системе:
Тип угрозы	Описание	Примеры выявляемого кода
Stealers (Стиллеры)	Кража паролей, куки-файлов и данных банковских карт из браузеров.	Cookies, Login Data, Local State
Crypto Miners (Майнеры)	Скрытое использование ресурсов вашего ПК для добычи криптовалюты.	powershell -Command, taskkill (завершение диспетчера задач)
RAT / Backdoors	Предоставление удаленного контроля над вашим компьютером злоумышленнику.	hidden, bypass, schtasks (автозагрузка)
Network Droppers	Скрипты, которые скрытно скачивают основные вирусы из сети.	bitsadmin, curl, wget, certutil -urlcache
Privilege Escalation	Попытки получить права администратора или создать скрытого пользователя.	net-user, reg add, runas
