#  CityJan
> **Empowering Citizens, Transforming Cities.**

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Node](https://img.shields.io/badge/node-%3E%3D%2014.0.0-brightgreen)

**CityJan** is a next-generation civic engagement platform designed to bridge the gap between citizens and municipal authorities. By leveraging modern web technologies, CityJan provides a seamless interface for reporting, tracking, and resolving civic issues—fostering a cleaner, safer, and more responsive urban environment.


##  Key Features

### � Citizen Portal
*   **Instant Reporting**: Submit issues like potholes, garbage dumps, or street light failures in under 30 seconds.
*   **Geo-Tagging**: Automatically capture precise locations for accurate issue resolution.
*   **Visual Evidence**: Upload photos directly from the device to validate reports.
*   **Real-time Tracking**: Monitor the lifecycle of a complaint from "Submitted" to "Resolved".

### �️ Administrative Dashboard
*   **Centralized Command Center**: A unified view for municipal officers to oversee all city zones.
*   **Visual Verification**: Review submitted images and descriptions before deploying teams.
*   **Status Management**: Update report statuses in real-time to keep citizens informed.


##  Architecture & Tech Stack

CityJan is built on a robust **MERN-like** architecture, prioritizing performance and scalability.

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3, Vanilla JS | Lightweight, fast-loading user interface. |
| **Backend** | Node.js, Express.js | High-performance RESTful API. |
| **Database** | MongoDB Atlas | Cloud-native, scalable document storage. |
| **Storage** | Multer (Local) | Efficient handling of media uploads. |


##  Quick Start Guide

Follow these instructions to set up the CityJan development environment on your local machine.

### Prerequisites
*   [Node.js](https://nodejs.org/) (v14 or higher)
*   [npm](https://www.npmjs.com/) (usually comes with Node.js)
*   A modern web browser (Chrome, Firefox, Edge)

### Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/jayantsingh213/cityjan.git
    cd cityjan
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    

3.  **Launch the Application**
    ```bash
    npm start
    ```
    > **Note:** The server will start at `http://localhost:3000`. The database connection is pre-configured for this demo.

---

##  Demo Credentials

To facilitate testing and evaluation, the system comes pre-loaded with the following accounts. **You can also generate them via `http://localhost:3000/api/setup-users`**.

| Role | Identifier (Phone/ID) | Password | Access Level |
| :--- | :--- | :--- | :--- |
| **Citizen** | `9876543210` | `1234` | Can report and track issues. |
| **Official** | `admin` | `admin123` | Full access to Admin Dashboard. |

---

## 🔮 Roadmap

*   [ ] **Mobile App**: Native iOS and Android applications for on-the-go reporting.
*   [ ] **AI Integration**: Automated categorization of issues using Image Recognition.
*   [ ] **SMS Notifications**: Real-time updates via SMS for non-smartphone users.
*   [ ] **GIS Integration**: Heatmaps for identifying problem hotspots in the city.

---

##  Contributing

We welcome contributions from the open-source community!

1.  **Fork** the project.
2.  Create your **Feature Branch** (`git checkout -b feature/AmazingFeature`).
3.  **Commit** your changes (`git commit -m 'Add some AmazingFeature'`).
4.  **Push** to the branch (`git push origin feature/AmazingFeature`).
5.  Open a **Pull Request**.

---

##  License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Made with ❤️ for a better tomorrow.
</p>
