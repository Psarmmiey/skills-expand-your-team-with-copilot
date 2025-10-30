# Mergington High School Activities

A website application that allows teachers to manage student participation in extracurricular activities at Mergington High School.

## Features

### For All Users
- **View Activities**: Browse all available extracurricular activities
- **Search**: Search activities by name, description, or schedule
- **Filter by Category**: Filter activities by type (Sports, Arts, Academic, Community, Technology)
- **Filter by Day**: View activities scheduled for specific days of the week
- **Filter by Time**: View activities scheduled for before school, after school, or weekends
- **Activity Details**: View comprehensive information including:
  - Activity description
  - Schedule with day and time information
  - Current participant list
  - Available spots and capacity

### For Teachers (Login Required)
- **Teacher Authentication**: Secure login/logout functionality
- **Register Students**: Enroll students in activities by providing their email
- **Unregister Students**: Remove students from activities with confirmation
- **Manage Capacity**: View and manage activity enrollment limits

## Technology Stack

- **Backend**: FastAPI (Python web framework)
- **Database**: MongoDB (persistent data storage)
- **Frontend**: HTML, CSS, and vanilla JavaScript

## Guides

- **[Development Guide](../docs/how-to-develop.md)** - For developers: setup and development instructions
- **[Teacher's Guide](../docs/teacher-guide.md)** - For teachers: how to request changes without coding
