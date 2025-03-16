# Ragnarock Pipeline System

Ragnarock is a streamlined and cost-effective VFX pipeline management system designed for small studios and independent teams. It provides a standard yet flexible workflow solution, ensuring efficiency without requiring a large infrastructure or budget.

This project is currently in its initial development phase and serves as a personal initiative. Based on feedback from its first release and survey, the final version may be refined and improved.

## Features

### Core Managers
- **🛡️ Valkyrie (Shot & Task Manager)** - Manages shots, sequences, and tasks. Artists can create shots automatically, and supervisors can assign tasks.
- **🔮 Odin (Project & Asset Manager)** - Handles project structure, assets, and production settings.
- **⚔️ Legion (Employee Manager)** - Tracks artist availability, assignments, and roles.
- **🥷 Ronin (Task Manager)** - Tracks task progress separately for production and management teams.
- **🐺 Fenrir (Render Manager)** - Integrates with Deadline; a custom render manager will be developed later.
- **📖 Mimir (Database Manager)** - GUI tool for managing the database without backend access.

### Supporting Tools
- **🌩️ Ragnarock (Pipeline UI)** - Core system providing a centralized dashboard for all managers.
- **👁️ Heimdall (Review & Versioning Tool)** - Integrated with **Nuke Studio** for version tracking, annotations, and review.
- **📢 Munin (Notification & Messaging System)** - Notifies artists and supervisors about task updates, deadlines, and messages.

### Optional Additions
- **🌍 Huginn (Cloud Sync, Optional)** - Lightweight cloud integration via **Nextcloud, Resilio Sync, Wasabi, or Backblaze B2**.
- **🧠 Skuld (AI-powered Task Predictor, Optional)** - Uses historical data to predict task durations, suggest assignments, and detect bottlenecks.
- **💬 Muninn (Custom Messenger, Optional)** - LAN-based or remote-capable messaging tool with a modern UI, file transfer, encryption, and group chat.

## Tech Stack
- **Frontend:** PySide2 (for the desktop UI)
- **Backend:** Python with MySQL (MariaDB)
- **Database:** MySQL (XAMPP Server)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ragnarock.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the database (MySQL/MariaDB):
   ```bash
   mysql -u root -p < database_schema.sql
   ```
4. Run the application:
   ```bash
   python main.py
   ```

## Contribution
Feel free to contribute by submitting issues, feature requests, or pull requests. Make sure to follow the contribution guidelines.

## License
This project is licensed under a **Custom License**. Commercial use by companies is prohibited without explicit permission from the author. Individuals and small teams can use and modify the project for non-commercial purposes. For business inquiries, please contact the author.

For full license details, see the **LICENSE** file in the repository.
