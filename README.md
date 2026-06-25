# Project Management System HorizonTechX

A Django based Project Management System designed to help users manage projects, tasks, and workflows through a structured dashboard.

## Overview

This application provides a centralized workspace where users can log in, create and manage projects, track tasks, and monitor progress. It is designed to improve productivity, organization, and collaboration.

## Key Features

- Secure login and user authentication
- Workspace dashboard for project overview
- Task tracking system
- Project and workspace management
- Task status management including completed, pending, and in progress
- Priority based task handling such as high, medium, and low
- Team collaboration support
- Task summary overview in dashboard
- Clean and simple navigation system

## Tech Stack

- Backend: Django Python
- Frontend: HTML CSS Bootstrap
- Database: SQLite
- Version control: Git and GitHub

## Dashboard Modules

- Login and authentication
- Workspace management
- Project tasks
- Task overview panel
- Priority and status tracking
- User profile system

## Installation

```bash
git clone https://github.com/adhilaks/horizontechx_project_management_system.git
cd horizontechx_project_management_system
python -m venv env
env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

