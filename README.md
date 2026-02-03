
ZFrame Documentation

Professional documentation for ZFrame Rapid Application Development Platform
RAD Platform Database-First Low-Code Enterprise Ready
Overview
Quick Start
Features
Structure
Overview

ZFrame is a powerful Java-based Rapid Application Development (RAD) platform that enables developers to build enterprise-grade web applications with minimal coding. This documentation provides comprehensive guidance for developers, architects, and technical teams working with ZFrame.

ZFrame follows a database-first approach where forms, reports, and business logic can be generated directly from database schemas, significantly reducing development time while maintaining enterprise-grade security and scalability.
Quick Start
Prerequisites

    Java Development Kit (JDK) 8 or higher
    Microsoft SQL Server 2012 or higher
    NetBeans IDE 8.1 or higher with GlassFish server
    ZFrame IDE (ZIDE) - Portable version

Installation Steps

    Install SQL Server in Mixed Mode (set password for SA user)
    Install JDK 8+ and set JAVA_HOME environment variable
    Install NetBeans 8.1+ with GlassFish server
    Download ZFrame Workspace and IDE from official website

Database Configuration
-- Create required databases CREATE DATABASE ZIDEDB; CREATE DATABASE YourProject_MD; CREATE DATABASE YourProject;
Key Features
Low-Code Development

Build applications with minimal hand-coding using visual designers and code generation.
Database-First Approach

Generate forms, reports, and business logic directly from database tables.
Enterprise Security

Built-in authentication, authorization, and audit logging for enterprise applications.
Workflow Engine

Design and implement complex business workflows with visual workflow designer.
Reporting & Dashboard

Create comprehensive reports and interactive dashboards without coding.
Scalable Architecture

Multi-tenant support and scalable architecture for growing enterprises.
Documentation Structure

The ZFrame documentation is organized into logical sections for easy navigation:
Section 	Description 	Files
01-getting-started 	Introduction, installation, and first project 	4
02-core-concepts 	Architecture, database design, security 	5
03-form-design 	Form creation, controls, data types 	6
04-business-logic 	Modules, reports, workflows, business rules 	4
05-database 	Data modeling, queries, migration 	4