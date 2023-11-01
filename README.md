# **Moonshot Functional Specifications**

## Table of content:
- [Overview](#overview)
    - [Product description](#product-description)
    - [Product functional capabilities](#product-functional-capabilities)
    - [User Roles](#user-roles)
    - [Use Cases for all operations](#use-cases-for-all-operations)
    - [General constraints](#general-constraints)
    - [Assumptions](#assumptions)
    - [Other software](#other-software)
- [Specific Function Description](#specific-function-descriptions)
    - [Kernel launch](#kernel-launch)
    - [Main GUI for game choice and option menu](#main-gui-for-game-choice-and-options-menu)
    - [Update function](#update-function)
- [External Interfaces](#external-interfaces)
    - [User Interfaces](#user-interfaces)
    - [Hardware Interfaces](#hardware-interfaces)
    - [System Interfaces](#system-interfaces)
    - [Performance](#performance)
    - [Design Constraints](#design-constraints)
- [Attributes](#attributes)
    - [Reliability, Availability, Maintainability](#reliability-availability-maintainability)
    - [Configurability and Compatibility](#configurability-and-compatibility)
    - [Installability](#installability)
    - [Usability](#usability)
- [Additional Requirements](#additional-requirements)
    - [Administration](#administration)
    - [User documentation](#user-documentation)
    - [Project management](#project-management)

<div class="page"/>

# Overview

## Product Description

The purpose of this Functional Specification is to outline the development of a kernel with a dual focus: to transform old computers into eco-friendly retro arcade machines and to serve as a proof of concept for sustainable technology adaptation. The kernel is designed to breathe new life into outdated hardware while demonstrating the feasibility of repurposing technology in an ecologically responsible manner. Key features and capabilities of the system include a user-friendly graphical interface for game selection, the ability to play retro games in single-player or two-player modes, and access to system options for configuration.

## Product Functional Capabilities

The kernel is expected to perform the following functional capabilities:

- **Main GUI:** Provides a user interface for selecting and launching retro games.
- **Game Selection:** Allows users to choose from a list of available retro games.
- **Options Menu:** Offers a menu for configuring system settings and preferences.
- **Support for Joystick and Buttons:** Enables users to control the system using arcade controls.
- **Two-Player Mode:** Supports gaming for two players on compatible games.
- **Retro Aesthetic:** Maintains a retro gaming aesthetic in both design and gameplay.

## User Roles

The intended users of the kernel include eco-conscious individuals, retro gaming enthusiasts, and technology enthusiasts intrigued by sustainable concepts. User roles encompass:

- **Eco-Conscious Users:** Individuals interested in reducing electronic waste and minimizing their environmental footprint.
- **Players:** End-users who interact with the kernel to play retro games.
- **Enthusiasts:** Retro gaming enthusiasts who may also want to customize and optimize the system.

## Use Cases for All Operations

Users will typically engage with the kernel in the following ways:

- **Selecting Games:** Users will navigate the Main GUI to select and play retro games, contributing to the ecological reuse of old hardware.
- **Configuring System Settings:** Users can access the Options Menu to configure display, sound, and other system settings, ensuring a personalized gaming experience.
- **Multiplayer Gaming:** In two-player mode, users can enjoy multiplayer retro games while supporting the proof of concept.
- **Occasional Tasks:** Occasional tasks might include creating backups of game data or importing game ROMs, further demonstrating the versatility of repurposed technology.

<div class="page"/>

## General Constraints

The following general constraints apply to the kernel:

- **Memory Constraints:** The kernel is optimized to work within the memory constraints of vintage hardware, promoting eco-conscious practices and extending the life of existing equipment.
- **Hardware and Kernel Standards:** The kernel adheres to hardware and system standards compatible with Intel processors and x86 architecture, catering to the sustainable adaptation of aging technology.
- **Communication Standards (Future Consideration):** Potential future enhancements, like online updates, will adhere to common communication standards, aligning with the evolving landscape of eco-friendly technology.
- **Maintenance Requirements:** The kernel will require minimal maintenance, primarily for system updates and improvements, ensuring long-term sustainability.
- **Training:** No specialized training is required for optimum use, as the system aims for a user-friendly interface that fosters ecological responsibility.

## Assumptions

Assumptions made during specification include the availability of vintage hardware, the growing relevance of eco-conscious technology practices, and the continued interest in eco-friendly.

## Other Software

The kernel primarily operates independently, focusing on creating a retro gaming environment with an ecological twist. It doesn't have interaction with standard office software like spreadsheets, word processing, or presentation tools. Users are expected to interact with the kernel for gaming purposes, supporting eco-conscious technology choices, and may not require integration with other software for typical use.


<div class="page"/>

# Specific Function Descriptions

## Kernel Launch:

### Description:

The "Kernel Launch" function represents the core process by which the kernel is initiated and the retro gaming environment becomes accessible to users. It plays a pivotal role in initializing the system and preparing it for gaming interactions.

### Inputs:

- **Power Button :** The system include a power button that users can press to start the boot process.
- **Boot Device Selection:** Users may choose the device or medium from which the kernel is booted, such as a USB drive, CD-ROM, or internal storage.

### Processing:

- **Initialization:** The function initializes the core components of the kernel, setting up system parameters, memory, and essential processes for the gaming environment.
- **Boot Sequence:** The function manages the boot sequence, loading the kernel code and any required drivers or libraries.
- **User Interface :** The function initiates the GUI, providing users with a visual interface for game selection.

### Outputs:

- **GUI Display:** If a GUI is included, the function results in the display of the user interface, enabling users to navigate the gaming environment.
- **Game Selection:** In systems with a GUI, users can select and launch retro games from the available options.
- **Gaming Environment:** The function transitions the system into the retro gaming environment, allowing users to play their chosen games using arcade controls and joystick input.

The "Kernel Launch" function is fundamental to the user experience, serving as the starting point for accessing the kernel and the retro gaming environment. It initializes the system, manages the boot process, and may present a user-friendly interface, if applicable, to guide users in selecting and playing retro games.

<div class="page"/>

## Main GUI for Game Choice and Options Menu:

### Description:

The "Main GUI for Game Choice and Options Menu" function is a pivotal component of the kernel, serving as the graphical user interface for users to interact with the system. Its primary role is to offer users a simple and intuitive way to select and play retro games and access essential system options. This function acts as the gateway to the gaming experience and user preferences, enhancing the overall usability of the system.

### Inputs:

- **Joystick Input:** Users provide input via a connected joystick device, allowing them to navigate the menu and make selections.
- **Buttons:** uttons are used for confirming selections and triggering actions within the menu.
- **Keyboard (if available):** For system-level input, a keyboard may also be utilized, allowing administrator to access options that aren't available through the arcade controls.

### Processing:

- **Game Selection:** The function displays a list of available retro games on the screen. Users can scroll through the list using the joystick and select a game by pressing the appropriate arcade terminal button.
- **Options Menu:** In addition to game selection, the function provides access to an options menu where users can configure system settings. This includes options related to display, sound, and other preferences.
- **User Interface Logic:** The function incorporates logic to ensure that user interactions with the GUI are processed accurately. It monitors joystick movements and button presses, updating the display and responding to user inputs.
- **User Feedback:** The GUI offers visual and audio feedback to indicate user selections and system responses.

### Outputs:

- **Game Launch:** When a user selects a game from the menu, the function initiates the chosen game, transitioning from the GUI to the game itself.
- **Options Configuration:** If a user accesses the options menu, the function enables users to configure system settings and preferences, such as screen resolution, sound volume, or control customization.
- **User Interface Display:** The function generates the visual elements on the screen, including game listings and menu options, providing a user-friendly interface.
- **Audio Feedback:** The function may trigger audio feedback, such as button click sounds or menu navigation sounds, to enhance the user experience.

This function serves as the gateway to the retro gaming experience, offering a seamless way for users to choose and enjoy games, customize their gaming environment, and access system settings—all while utilizing a joystick and arcade terminal buttons for navigation and selection. It plays a central role in making the kernel user-friendly and accessible.

<div class="page"/>

## Update Function:

### Description:

The "Update Function" is a critical component of the kernel, responsible for ensuring that the kernel remains up to date and capable of receiving enhancements, bug fixes, and new features. This function allows users to maintain the performance and compatibility of their retro gaming system over time.

### Inputs:

- **USB Key Insertion:** Users initiate the update process by inserting a USB key containing the update package.

### Processing:

- **Update Verification:** The function verifies the authenticity and integrity of the update package to prevent unauthorized or corrupted updates.
- **Update Installation:** Once the update is verified, the function installs the new components or updates to the kernel, ensuring that the system remains current and functional.
- **Version Control:** The function tracks the installed kernel version and may update a version log or database to maintain a history of updates.
- **User Notifications:** In systems with a graphical user interface (GUI), the function may provide notifications to users about available updates and their status.

### Outputs:

- **Update Success Confirmation:** Users receive confirmation that the update process was successful, and the kernel is now up to date.
- **Updated Features and Fixes:** Depending on the updates, users may benefit from new features, performance enhancements, or bug fixes in the retro gaming environment.
- **Version History :** In systems with version tracking, the function maintains a record of updates and their respective versions.

The "Update Function" is a vital aspect of the kernel, ensuring that users can maintain the system's performance and receive the latest improvements. It facilitates the process of keeping the retro gaming environment current and functional, enhancing the user experience over time.

<div class="page"/>

# External Interfaces

## User Interfaces

The user interfaces in this kernel are designed to provide an intuitive and straightforward interaction experience for users. Key components and considerations include:

- **Main GUI:** The primary user interface is the main graphical user interface (GUI), which serves as the gateway to the retro gaming environment. It includes a screen that displays the available retro games for selection, and another screen for system options. The GUI incorporates a retro-style design, using low-resolution graphics to emulate the aesthetics of classic arcade machines.

- **Navigation Flow:** The navigation flow of the GUI is designed to be user-friendly, with clear menus and options for game selection and system configuration. Users can navigate through the available games and access the options menu using a connected joystick device and arcade terminal buttons.

- **Input Validation:** Input validation is implemented to ensure that user inputs are accurate and within the allowed range. The system will validate joystick and button inputs to prevent accidental changes or errors.

- **Display Format:** The GUI supports a low-resolution display format to maintain the retro gaming aesthetic, with screen resolutions suitable for older hardware.

- **Protection from Accidental Changes:** The user interfaces are designed to minimize the risk of accidental changes. For instance, system configuration changes may require confirmation to prevent unintended modifications.

## Hardware Interfaces

The system requires minimal hardware interfaces. Key hardware interfaces include:

- **Joystick and Buttons:** Users interact with the system primarily through arcade controls, including a joystick for navigation and buttons for game selection and menu interaction.

## System Interfaces

The kernel operates as a standalone system, but it may require certain system interfaces:

- **File Import and Export:** The system may support importing and exporting game-related data or settings, typically through USB or other storage media.

## Performance

- **Response Times:** The kernel aims to provide fast response times for users interacting with the GUI and selecting games. Response times for navigation and game launch are optimized to provide a seamless gaming experience.

- **Data Volume:** Given the retro gaming nature, data volume requirements are expected to be relatively low. The kernel's data storage is designed to accommodate retro game ROMs and system configurations without excessive storage demands.

- **Maximum Data File Size:** The system is optimized to work with retro game ROMs and configurations, which are typically small in file size compared to modern games.

- **Maximum Number of Concurrent Users:** The system is designed for single or dual-player gaming experiences, making concurrency considerations less relevant.

## Design Constraints

- **Memory Constraints:** The kernel is optimized to work within the memory constraints of older hardware, ensuring it does not demand excessive RAM or hard disk space.

- **Hardware and Kernel Standards:** The kernel adheres to hardware and kernel standards compatible with Intel processors, x86 architecture, and specific operating systems suitable for vintage hardware.

- **Performance on Older Hardware:** The kernel is designed to provide optimal performance on older hardware, taking into consideration the limited processing power and resources of vintage computers.

These design constraints and considerations guide the development choices to ensure the kernel's effectiveness and compatibility with vintage hardware and the gaming experience.


<div class="page"/>

# Attributes

## Reliability, Availability, Maintainability

Reliability, availability, and maintainability are essential for ensuring a stable and sustainable system:

- **Continuous Operation:** The system is designed to operate continuously, with minimal downtime. It should be reliable enough to run for extended periods, ensuring an uninterrupted gaming experience.

- **Code Structuring:** The kernel code will be structured for ease of future modification and updates. This includes well-documented code and clear coding standards to facilitate maintainability. Version control and code repositories will be used to manage kernel changes and updates.

## Configurability and Compatibility

Configurability and compatibility are vital to ensure the kernel adaptability to various computing environments:

- **Individual Customization:** The kernel will provide options for individual customization, allowing users to configure display, audio settings, and game preferences according to their specific needs and preferences.

- **Operating Environments:** Compatibility with various computing environments, especially vintage hardware, is a priority. The kernel will be optimized for Intel architecture and x86 processors, ensuring broad compatibility with the target hardware.

## Installability

Installability considerations are important for user convenience and a smooth installation process:

- **Data Transfer:** Users may have the option to transfer data from prior releases, ensuring a seamless transition to newer versions. The system will detect and handle data from previous installations efficiently.

- **Prior Release Elements:** The presence of kernel elements from prior releases will be considered. The kernel will aim to maintain compatibility with data and configurations from earlier versions to prevent data loss and facilitate upgrades.

<div class="page"/>


## Usability

Usability aspects are crucial to ensure a user-friendly experience:

- **Error Handling:** The system will feature informative and user-friendly error messages that guide users toward solutions when issues arise. The messages will provide clear instructions for problem resolution.

- **Input Range Checking:** Input range checking will be performed as soon as entries are made. This ensures that users receive immediate feedback when entering values outside of the acceptable range, preventing invalid inputs.

- **User Preferences:** The order of choices and screens in the kernel will correspond to user preferences, promoting a user-centric design. The system will aim to be intuitive and responsive to user interactions.
<div class="page"/>

# Additional Requirements

## Administration

- **Periodic Updating:** The kernel may require periodic updating to incorporate bug fixes, security enhancements, and improvements in performance. An update mechanism should be implemented to facilitate easy and secure kernel updates.

- **Data Management:** While the project does not involve database usage, data management tasks may include managing system configurations, kernel updates. Tools for data management should be provided.

## User Documentation

- **Hard Copy Documentation:** User documentation in hard copy format is not a primary requirement for the kernel project. However, it may be beneficial to provide minimal printed documentation for users who prefer hard copies.

- **Online Documentation:** Comprehensive online documentation is essential. This documentation should be accessible through a user-friendly website or platform. It should cover installation instructions, configuration guidance, troubleshooting, and FAQs. Online documentation will be the primary source of user support.

## Project Management

- **Version Control:** The project should utilize version control systems to manage the development of the kernel codebase. This ensures proper tracking of changes and facilitates collaboration if multiple developers are involved.

- **Testing and Quality Assurance:** A rigorous testing and quality assurance process is essential to identify and resolve issues specific to the kernel. This should include both unit testing and integration testing to ensure the kernel functions reliably.

- **Legal and Regulatory Compliance:** Ensure that the project adheres to any legal and regulatory requirements related to software development and usage, including licensing and copyright considerations.

- **Documentation:** In addition to technical documentation, project documentation should include project plans, development schedules, and resource allocation details.

<div class="page"/>

# Glossary
| Term                | Description                                                      |
|---------------------|------------------------------------------------------------------|
| ALGOSUP             | Innovative software development school. |
| arcade machines     | Retro gaming devices designed for providing classic gaming experiences. |
| audio feedback      | Auditory cues or responses provided by the software to indicate user actions or system events. |
| backups             | Duplicate copies of data or system configurations for safeguarding against data loss or system failures. |
| boot                | The process of starting or initializing a computer or system, often involving loading the operating system. |
| CD-ROM              | A type of optical disc used for storing digital data, often used for software distribution. |
| eco-conscious       | A term describing an environmentally aware and responsible approach to product design or usage. |
| environmental footprint | The impact of a product or system on the environment, considering factors like energy use and waste generation. |
| FAQ                 | Frequently Asked Questions, a document providing answers to common user queries. |
| games ROMs          | Read-Only Memory files used for storing game data and software in retro gaming systems. |
| GUI                 | Graphical User Interface, a visual way for users to interact with a software system. |
| Intel processors    | Central processing units (CPUs) manufactured by Intel Corporation, widely used in computers. |
| internal storage    | The built-in memory or storage capacity within a device or computer. |
| joystick            | An input device typically used for controlling the movement of characters or objects in games. |
| kernel              | The core component of an operating system responsible for managing hardware resources. |
| proof of concept    | A prototype or demonstration illustrating the feasibility and basic functionality of a concept or idea. |
| retro games         | Classic video games from earlier eras, often appreciated for their nostalgic value. |
| storage media       | Physical devices or media used for data storage, including hard drives, SSDs, CDs, and more. |
| USB drive           | A portable storage device that connects via a Universal Serial Bus (USB) port. |
| user-friendly       | Software or systems designed to be intuitive and easy for users to interact with. |
| version control systems | Software tools for tracking and managing changes to code or documents, ensuring collaboration and tracking of revisions. |
| x86 architecture    | A common computer architecture used in Intel and compatible processors. |

