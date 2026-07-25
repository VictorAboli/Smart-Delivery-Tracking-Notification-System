
# Smart Delivery Tracking & Notification System

An automated shipment monitoring application that tracks delivery progress from web-based tracking portals and sends real-time notifications when the shipment status changes.

## Problem

Users often need to manually refresh tracking websites because many logistics providers do not provide instant notifications.

## Solution

This project automates tracking using Playwright browser automation and integrates Telegram Bot API for instant delivery alerts.Built an automated delivery monitoring system that periodically checks shipment tracking pages, extracts real-time delivery status using browser automation, and sends instant notifications when the package status changes.

DeliveryNotifier/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── app.py                 # Main application
├── scraper.py             # Website tracking extraction
├── notifier.py            # Notification service
├── config.py              # Configuration settings
│
├── database/
│   └── status.db          # Stores previous statuses
│
├── logs/
│   └── app.log
│
├── screenshots/
│
└── tests/
    └── test_tracker.py


Tech Stack
Programming Language
Python
Automation
Playwright
Web Scraping
BeautifulSoup (if needed)
DOM element extraction
Notification
Telegram Bot API
Data Storage
SQLite
Scheduling
Windows Task Scheduler / Cron
Development Tools
VS Code
Git
GitHub


Architecture Diagram

              User
                |
                |
        Telegram Notification
                |
                |
        Notification Service
                |
                |
        Delivery Monitor
                |
                |
        Playwright Browser
                |
                |
        Tracking Website


How It Works

1. User provides tracking URL

2. System launches automated browser

3. Playwright loads tracking page

4. Application extracts delivery status

5. Status is compared with previous status

6. If status changes:

   Out For Delivery
          |
          ↓
     Delivered

7. Notification sent to user

Multiple Tracking Numbers

Example:

Package 1:
4539287691 → Delivered

Package 2:
7839201921 → In Transit

Store in SQLite:

tracking_id
website
current_status
last_checked
