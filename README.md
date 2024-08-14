# Taskflow Management System

## Overview
This Laravel-based system allows users to manage projects, tasks, and subtasks. Users can also generate detailed reports of tasks and subtasks under specific projects, optimized for performance on large datasets.

## Features
- User authentication and authorization.
- Project creation, update, deletion, and view.
- Task and subtask management.
- Optimized report generation.

## Eloquent Relationships
- **User** `1..N` **Projects**
- **Project** `1..N` **Tasks**
- **Task** `1..N` **Subtasks**

## Setup Instructions

### Prerequisites
- **PHP**: >= 8.0
- **Composer**: Latest version
- **Database**: MySQL or any other supported database
- **Node.js & NPM**: For managing front-end dependencies

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/project-management-system.git
   cd project-management-system
