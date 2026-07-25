
# Smart Delivery Tracking & Notification System

An automated shipment monitoring application that tracks delivery progress from web-based tracking portals and sends real-time notifications when the shipment status changes.

## Problem

Users often need to manually refresh tracking websites because many logistics providers do not provide instant notifications.

## Solution

This project automates tracking using Playwright browser automation and integrates Telegram Bot API for instant delivery alerts.Built an automated delivery monitoring system that periodically checks shipment tracking pages, extracts real-time delivery status using browser automation, and sends instant notifications when the package status changes.


# 📦 Smart Delivery Tracking & Notification System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue">
  <img src="https://img.shields.io/badge/Automation-Playwright-green">
  <img src="https://img.shields.io/badge/Notification-Telegram%20API-orange">
  <img src="https://img.shields.io/badge/Database-SQLite-lightgrey">
</p>


## 🚀 Project Overview

**Smart Delivery Tracking & Notification System** is an automated shipment monitoring application that tracks package delivery status from online tracking portals and sends real-time notifications when the delivery status changes.

Many logistics websites require users to manually refresh tracking pages to check shipment progress. This project solves that problem by automating browser interaction, extracting delivery updates, and notifying users instantly.

---

# 🎯 Problem Statement

## The Challenge

Customers often face these problems:

- ❌ No instant delivery notifications
- ❌ Manual tracking page refresh required
- ❌ Missed delivery updates
- ❌ Multiple tracking websites with different interfaces


## The Solution

This application automatically:

1. Opens the shipment tracking website
2. Extracts the current delivery status
3. Monitors status changes
4. Stores previous tracking information
5. Sends instant notifications when delivery is completed


---

# 🏗️ System Architecture

             User
              |
              |
              ▼

      Tracking URL Input

              |
              |
              ▼

    Python Delivery Monitor

              |
              |
              ▼

    Playwright Automation

              |
              |
              ▼

    Shipment Tracking Website

              |
              |
              ▼

    Status Extraction Engine

              |
              |
              ▼

    Status Change Detection

              |
              |
              ▼

    Telegram Notification

              |
              |
              ▼

          User Phone 📱




---

# ✨ Features

## Current Features

✅ Automated browser-based tracking  
✅ Dynamic website interaction using Playwright  
✅ Delivery status extraction  
✅ Real-time status monitoring  
✅ Telegram push notifications  
✅ Screenshot capture for debugging  
✅ Modular Python architecture  


---

## Future Enhancements

🚀 Multiple shipment tracking support

🚀 Web dashboard for monitoring packages

🚀 User authentication system

🚀 PostgreSQL database integration

🚀 Email and SMS notifications

🚀 AI-based delivery prediction

🚀 Cloud deployment using AWS


---

# 🛠️ Technology Stack


## Programming Language

- Python 3.12


## Automation Framework

- Playwright


## Web Technologies

- HTML
- CSS
- DOM Extraction


## Notification Service

- Telegram Bot API


## Database

- SQLite


## Development Tools

- Visual Studio Code
- Git
- GitHub


---

# 📂 Project Structure

DeliveryNotifier/

│
├── README.md

├── requirements.txt

├── app.py
│ └── Main application

│
├── scraper.py
│ └── Website tracking extraction

│
├── notifier.py
│ └── Notification service

│
├── config.py
│ └── Application configuration

│
├── database/

│
├── logs/

│
├── screenshots/

│
└── tests/





