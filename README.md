# SystemGuard 💂

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://systemguard.readthedocs.io/en/latest/?badge=latest">
          <img src="https://readthedocs.org/projects/systemguard/badge/?version=latest" alt="Documentation Status"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/blob/main/LICENSE">
          <img src="https://img.shields.io/github/license/SystemGuard-official/SystemGuard" alt="GitHub license"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/releases">
          <img src="https://img.shields.io/github/v/release/SystemGuard-official/SystemGuard" alt="GitHub release"/>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/issues">
          <img src="https://img.shields.io/github/issues/SystemGuard-official/SystemGuard" alt="GitHub issues"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/pulls">
          <img src="https://img.shields.io/github/issues-pr/SystemGuard-official/SystemGuard" alt="GitHub pull requests"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/commits/dev">
          <img src="https://img.shields.io/github/commit-activity/m/SystemGuard-official/SystemGuard" alt="GitHub commit activity"/>
        </a>
      </td>
    </tr>
    <tr>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/network/members">
          <img src="https://img.shields.io/github/forks/SystemGuard-official/SystemGuard" alt="GitHub forks"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/stargazers">
          <img src="https://img.shields.io/github/stars/SystemGuard-official/SystemGuard" alt="GitHub stars"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/SystemGuard-official/SystemGuard/watchers">
          <img src="https://img.shields.io/github/watchers/SystemGuard-official/SystemGuard" alt="GitHub watchers"/>
        </a>
      </td>
    </tr>
  </table>
</div>

SystemGuard is a Flask app designed to monitor server stats such as CPU, Memory, Disk, and Network. It also provides real-time monitoring capabilities which can be useful for system administrators, developers, and DevOps engineers to keep track of their server's performance and troubleshoot issues. The app uses the `psutil` library to retrieve system stats and the `speedtest-cli` library to perform a network speed test.


## Features 🚀

- Lightweight, open-source, and free to use with a straightforward installation process, out-of-the-box monitoring solution.
- Capable of monitoring core server metrics like CPU, memory, disk usage, and network traffic.
- Analyze fluctuations in server performance with historical data displayed as charts.
- Centralized control panel to monitor, manage, and analyze server fleets.
- Role-Based Access Control (RBAC) for managing user permissions.
- Includes built-in security features such as authentication for login, logout, and signup.
- Analyze network speed using the built-in speed test feature.
- Analyze suspicious processes and terminate them with a single click.
- Analyze network statistics using the built-in monitoring tools.
- Analyze the subnet for security vulnerabilities with the built-in security analysis feature.
- Option to download historical data in CSV format for detailed analysis (upcoming feature).
- Role-based dashboards tailored for Developer, Admin, IT Manager, and Manager roles (upcoming feature).
- Update security updates with a single click or automatically update to the latest version to simplify maintenance.

## Get started 🛠️

- Check the [documentation](https://systemguard.readthedocs.io/en/latest/installation.html) for installation instructions.

## Architecture 🏗️

![SystemGuard-Architecture](docs/assets/images/architecture.jpg)

## Tech Stack 🛠️

- **Frontend**: JavaScript, Bootstrap, Chart.js, Grafana
- **Backend**: Python, Flask, SQLAlchemy, SQLite, Prometheus, InfluxDB
- **Monitoring**: psutil, speedtest-cli, nmap, netstat

## Release Notes 📝

- Check the [Release Notes](src/docs/Release.md) file for the latest updates.
- Check the [Release Instructions](src/docs/release_instructions.md) file for the release process.

## Supported Systems 🖥️

- Most Linux distributions are supported, including Ubuntu, CentOS, and Debian.

## How does installation work? 🤔

The installation process is straightforward and can be completed in a few steps. The user needs to run a bash script that installs the required dependencies, sets up the database, creates a conda environment, and adds the Flask server to a cron job. The user can then access the SystemGuard web interface by visiting the server's IP address or domain name. 

For more details, check out the official website: [SystemGuard](https://systemguard.readthedocs.io/en/latest/)

## Product Screenshots 📸

Check the product [screenshots](src/docs/README.md) for a visual representation of the app.

## Why not use a Docker image? 🐳

A Docker image has not been created for this project because it requires access to host-level system metrics and resources.

## Contributing 🤝

Contributions are always welcome! Please read the [contribution guidelines](/CONTRIBUTING.md) first.

## License 📝

This project is licensed under the GPL-3.0 License - see the [LICENSE](/LICENSE) file for details.

### Note
Aegis is the repository used to maintain and develop the SystemGuard tool.
