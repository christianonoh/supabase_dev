<a name="readme-top"></a>

<div align="center">
  <img src="https://via.placeholder.com/80x80/4A90E2/FFFFFF?text=CM" alt="logo" width="80" height="auto" style="border-radius: 50%; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);"/>
  <h1 style="font-family: 'Arial', sans-serif; color: #333; font-weight: bold; margin-top: 10px;">CONTRIBUTIONS MANAGER</h1>
</div>

<!-- TABLE OF CONTENTS -->
<details>
<summary> 📗 Table of Contents</summary>

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [🚀 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [📋 Program Features](#program-features)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)
</details>

<!-- PROJECT DESCRIPTION -->

# 📑 CONTRIBUTIONS MANAGER <a name="about-project"></a>

Contributions Manager is a console-based application written in C that helps manage group financial contributions, member information, and payment tracking. The system is designed for organizations, clubs, or groups that collect regular contributions from members and need to track payments, manage member data, and organize fair distribution systems through tracking lists.

This application provides a comprehensive solution for managing contribution cycles (seasons), tracking who has paid, organizing member information, and creating fair rotation systems for receiving collected funds.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

- **[C Programming Language](https://www.iso.org/standard/74528.html):** Core programming language providing performance and system-level control.
- **Standard C Libraries:** Utilizing stdio.h, stdlib.h, string.h, and time.h for file operations, memory management, string handling, and random number generation.
- **CSV File Format:** Simple and portable data storage format for member information and tracking lists.
- **Cross-Platform Compatibility:** Designed to work on any system with a C compiler.

### Key Features <a name="key-features"></a>

- **Member Management**: Complete CRUD operations for member information including personal details and banking information.
- **Payment Tracking**: Monitor payment status with ability to mark payments and view paid/unpaid lists.
- **Tracking Lists**: Generate fair rotation systems using either random or weighted distribution methods.
- **Season Management**: Reset and start new contribution cycles with fresh payment status.
- **Data Persistence**: All information stored in CSV files for easy data portability and backup.
- **Interactive Console Interface**: User-friendly menu-driven interface for all operations.
- **Flexible Payment Amounts**: Support for different contribution amounts with special member privileges.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 🚀 Getting Started <a name="getting-started"></a>

### Prerequisites <a name="prerequisites"></a>

To run this application, you need:
- A C compiler (GCC, Clang, or MSVC)
- Standard C runtime libraries
- Terminal/Command prompt access

### Installation <a name="installation"></a>

1. **Clone or download the source code**
   ```bash
   # If using git
   git clone [repository-url]
   
   # Or download the .c file directly
   ```

2. **Compile the program**
   ```bash
   # Using GCC
   gcc -o contributions_manager contributions_manager.c
   
   # Using Clang
   clang -o contributions_manager contributions_manager.c
   ```

3. **Run the application**
   ```bash
   ./contributions_manager
   ```

### Usage <a name="usage"></a>

1. **Start the program** - Run the compiled executable
2. **Main Menu Navigation** - Use number keys to navigate through options
3. **Member Management** - Add, edit, delete, or view member information
4. **Payment Tracking** - Mark payments and view payment status
5. **Generate Tracking Lists** - Create fair rotation systems for fund distribution
6. **Season Management** - Reset for new contribution cycles

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- PROGRAM FEATURES -->

## 📋 Program Features <a name="program-features"></a>

### Member Management
- **Add Members**: Store complete member information including name, phone, account details, and contribution amounts
- **Edit Information**: Modify any member detail with validation
- **Delete Members**: Remove members with confirmation
- **View Details**: Display specific member information or view all members

### Payment System
- **Payment Tracking**: Mark members as paid/unpaid for current season
- **Payment Lists**: View separate lists of paid and unpaid members
- **Payment Reset**: Clear all payment statuses for new seasons
- **Flexible Amounts**: Support for different contribution levels

### Tracking Lists
- **Random Generation**: Fair random distribution of receiving turns
- **Weighted System**: Priority based on contribution amounts
- **Queue Management**: First-in-first-out system for fund distribution
- **Special Member Support**: Double entries for higher-tier contributors

### Data Management
- **CSV Storage**: Human-readable data format for easy backup
- **File Operations**: Robust file handling with error checking
- **Data Integrity**: Validation and error handling throughout
- **Season Cycles**: Complete reset capabilities for new periods

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Chinenye**

- GitHub: [@chinenye](https://github.com/chinenye)

👤 **Christian**

- GitHub: [@christian](https://github.com/christian)

👤 **Ebube**

- GitHub: [@ebube](https://github.com/ebube)

👤 **Eze**

- GitHub: [@eze](https://github.com/eze)

👤 **Favour**

- GitHub: [@favour](https://github.com/favour)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions are welcome! This project can be enhanced in many ways. If you encounter any issues or have suggestions for improvement, please feel free to contribute:

**How to contribute:**
- Fork the repository
- Create a new branch for your feature or bug fix
- Make your changes and ensure the code compiles without warnings
- Test your changes thoroughly with different scenarios
- Submit a pull request with a clear description of your changes

**Areas for improvement:**
- Enhanced input validation
- GUI implementation
- Database integration
- Network capabilities for multi-user access
- Additional reporting features
- Backup and restore functionality

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you find this project helpful for managing your group's contributions, please give it a star ⭐️. Your support encourages continued development and improvement!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- Special thanks to **Mr James**, our cohort leader, for his guidance and mentorship throughout the development process
- Gratitude to **Educare**, the organizer of the bootcamp, for providing the platform and opportunity to learn and build this project
- Thanks to the C programming community for excellent documentation and resources
- Appreciation for all contributors who help improve this project
- Special thanks to organizations using this system and providing feedback

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
