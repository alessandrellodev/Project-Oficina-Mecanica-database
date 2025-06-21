# Project-Oficina-Mecanica-database
Automotive Workshop Management System
Overview

This project is a database system designed to manage service orders in an automotive workshop. It tracks customers, vehicles, service orders, mechanics, teams, services, and parts, providing a comprehensive solution for workshop operations management.
Features

    Customer and Vehicle Management: Track customer information and their vehicles.

    Service Order Processing: Create and manage service orders with multiple services and parts.

    Team Assignment: Assign teams of mechanics to service orders.

    Inventory Tracking: Manage parts inventory and track usage in service orders.

    Pricing System: Calculate service order values based on reference prices for services and parts.

Database Schema

The system consists of the following main tables:

    Cliente (Customer): Stores customer information.

    Veiculo (Vehicle): Contains vehicle details linked to customers.

    OrdemServico (ServiceOrder): Main table for service orders.

    Servico (Service): Reference table for available services.

    Peca (Part): Reference table for parts with inventory tracking.

    Mecanico (Mechanic): Stores mechanic information.

    Equipe (Team): Groups mechanics into teams.
