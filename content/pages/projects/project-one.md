---
type: ProjectLayout
title: Customer Relationship Management System
colors: colors-a
date: '2025-08-15'
client: Viettel CX
description: >-
  A full-stack Java Spring Boot CRM application with MySQL, Spring Security, and Thymeleaf, enabling role-based access, client management, and contract workflows for improved cross-team coordination.
featuredImage:
  type: ImageBlock
  url: /images/projects/CRM.png
  altText: CRM system dashboard showing client management interface
media:
  type: ImageBlock
  url: /images/projects/CRM.png
  altText: Customer Relationship Management system with role-based access control
---

## Project Overview

This Customer Relationship Management (CRM) platform was built as a comprehensive solution for Viettel CX to enable admins, managers, and employees to manage clients, contracts, and workflows in one centralized system. The project significantly improved cross-team coordination and reduced manual errors.

## Key Features

- **Role-Based Access Control**: Secure authentication system distinguishing between admins, managers, and employees
- **Contract Management Module**: Distinguished between "in-progress" and "done-deal" contracts while maintaining shared attributes
- **Client Management**: Centralized client database with comprehensive tracking capabilities
- **Workflow Management**: Streamlined processes for team collaboration
- **Responsive Interface**: Optimized front-end with Thymeleaf HTML, Tailwind CSS, and JavaScript

## Technologies Used

- **Backend**: Java Spring Boot, Spring Security
- **Frontend**: Thymeleaf HTML, Tailwind CSS, JavaScript
- **Database**: MySQL
- **Testing**: Automated testing with CI/CD pipelines
- **Deployment**: Docker containers

## Challenges & Solutions

The biggest challenge was designing a contract management system that could handle different contract states while maintaining data integrity. I solved this by creating a flexible state machine that allows smooth transitions between contract phases while preserving shared attributes.

> "The key to building great CRM systems is understanding that every workflow decision impacts team productivity and data accuracy."

## Results

- **30% reduction** in manual errors through automated contract state management
- **20% decrease** in task completion time for managers through optimized UI
- **Improved cross-team coordination** with centralized client and contract management
- **Enhanced data integrity** with proper state management and validation

## Repository

**GitHub**: [duchieu260503/crm](https://github.com/duchieu260503/crm)
- Complete Spring Boot application with Maven configuration
- Docker containerization for easy deployment
- MIT License - open source and freely available
- 6 commits showing active development
- Multi-language codebase: HTML (59.3%), JavaScript (23.5%), Java (15.6%), CSS (1.5%)

## Lessons Learned

This project taught me the importance of understanding business workflows when building enterprise applications. The integration of role-based access control and state management gave me valuable experience in building scalable, secure applications that serve multiple user types effectively.
