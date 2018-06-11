###### The To Do file shows what needs to be done in a prioritized list with 1. being the next and most important thing to do. ######

# To Do #

1. Design Scope of Product
    * Description of Product
        + Multi-Layered product that helps facilitate access to Digital Entertainment with a sophisticated Cloud Storage                  Service at its core. The Cloud Storage allows a user to fully back-up their digital data (specifically Pictures, 
           Documents, Video, and Audio). The Cloud Storage will allow Operator to store Digital Content to be served to users            for consumption. 
    * Infrastructure
    * Server
    * Client(s)
    * Test Cases (automated testing)
    * Deployment Framework

2. Design Server environment.
    * Create design document to describe design choices
    * Setup 3 CentOS servers (Prod, Dev, Backup)
    * Harden server instances
    * Create user groups for different levels of administration
    * Authentication
    * Catalog Media (data)
    * Store User profile
    * Storage Allocation
    * Data Encryption
    * Payment Processor
    * DVR
    * TV Guide

3. Design Storage hardware and backup process.
    * SAN vs NAS

4. Design Client front end.
    * Technology
    * User Interface
    * Login Authentication
    * Browse Data Catalog
    * View Data
        + Gallery Viewer
        + Video Player
        + Audio Player
        + Doc Viewer
    * Upload Data
    * VPN Client
    * File System Viewer
    * Encode/decode content
    * Data Backup
        + automatically scrubs device filesystem for data backup
    * Screen Analyzer
        + gets device screen info to properly render UI

5. Design Infrastructure
    * Firewall
        + PF
    * VPN
        + OpenVPN
    * Host Environment
        + CentOS
    * Credential Manager
    * Communication
    * Operating System
        + FreeBSD/OpenBSD
    