# LittleLemonBackend
This is the backend for the final graded assessment on Meta's Django Framework course on Coursera.


Restaurant Website with Booking System and Menu Pages
This project is a Django-based web application for a restaurant website. It features a menu page that lists all available items, individual pages for each menu item with detailed information, and a booking system to allow customers to make reservations.

Features
Menu Page: Displays all available menu items with basic information.
Individual Menu Item Pages: Provides detailed descriptions for each menu item.
Booking System: Allows users to book tables with a date and time.
User-Friendly Interface: Simple, responsive design optimized for easy navigation.
Prerequisites
Python 3.7+: Ensure Python is installed on your system.
Django 3.0+: This project uses Django, so make sure it's installed in your environment.
Virtual Environment (Recommended): Use a virtual environment to manage dependencies and avoid conflicts.
Setup Instructions
1. Clone the Repository:
   
     - git clone repository-url
   
     - cd project-folder

2. Create and Activate a Virtual Environment

   It’s highly recommended to run this project in a virtual environment. Follow these steps to set one up:
    
   Create a virtual environment

     - python3 -m venv venv
    
   Activate the virtual environment
    
     For Windows:
    
       venv\Scripts\activate
    
     For macOS/Linux:

       source venv/bin/activate

3. Install Dependencies
  After activating the virtual environment, install the required packages:

    - pip install django

# Usage
  Menu Page
    
  Lists all available menu items.
    
      Accessible at http://127.0.0.1:8000/menu.
 
  Individual Menu Item Pages
    
  Clicking on a menu item will open a detailed page with more information.
    
      Accessible at http://127.0.0.1:8000/menu/<item-id>.
  
  Booking System
    
  Users can select a number of guests for a reservation.
    
      Accessible at http://127.0.0.1:8000/booking.
  
  Admin Panel
    
  For managing the menu, booking records, and other site content.
    
      Accessible at http://127.0.0.1:8000/admin (requires a superuser account).








