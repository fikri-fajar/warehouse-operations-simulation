# Warehouse Operations Portfolio

## Introduction
This project is a Microsoft Excel based simulation of warehouse operations in a heavy equipment manufacturing environment. It was created to demonstrate my understanding of warehouse workflows, inventory management, and operational processes.

## Project Background
This project was created as part of my self-directed learning in warehouse operations. It simulates key warehouse processes including Receiving, Put Away, Storage, Material Issue, and Stock Opname using Microsoft Excel to develop a practical understanding of warehouse workflows and inventory management.

## Project Objectives
The objectives of this project are:
-	To simulate real world warehouse operations using Microsoft Excel, covering the complete workflow from receiving goods to inventory reporting.
-	To apply inventory management concepts such as stock movement tracking, stock balance maintenance, and data reconciliation.
-	To develop practical Excel skills for organizing, processing, and analyzing warehouse operational data efficiently.
-	To build a solid understanding of warehouse business processes that serves as a strong foundation for working with ERP and WMS systems.
-	To document and showcase a practical warehouse case study using Excel


## Business Process

### Overview
This project simulates the core warehouse operational workflow commonly found in a heavy equipment manufacturing environment. Rather than focusing on building an ERP or Warehouse Management System (WMS), the project aims to develop a practical understanding of the warehouse business processes that are commonly managed through these systems. Microsoft Excel is used as a simulation tool to model the flow of warehouse data across different operational activities, providing a practical representation of real world warehouse operations.

...

### Warehouse Operations Business Process
The following diagram illustrates the end-to-end warehouse operational workflow simulated throughout this project.

  <img src="assets/warehouse-operations-business-process.png" width="750">

### Process Description

| Process | Description |
|----------|-------------|
| Supplier | Approved suppliers provide raw materials or spare parts required for warehouse operations. |
| Purchase Order | A Purchase Order (PO) is created to authorize the purchase of materials from suppliers. |
| Goods Receipt (Receiving) | Incoming materials are received, verified against the Purchase Order, and recorded into inventory. |
| Quality Inspection | Received materials are inspected to ensure they meet quality requirements before being accepted into inventory. |
| Put Away | Approved materials are assigned and transferred to their designated storage locations. |
| Storage | Materials are stored in warehouse locations until they are required for operational use. |
| Inventory Management | Inventory records are maintained to monitor stock levels, locations, and material movements. |
| Material Request | Internal departments submit requests for materials required for operational or production activities. |
| Picking | Requested materials are picked from their storage locations according to the material request. |
| Material Issue | Picked materials are issued and recorded as outbound inventory transactions. |
| Cycle Count | Periodic physical inventory counting is performed to verify inventory accuracy. |
| Inventory Adjustment | Inventory records are updated when discrepancies are identified during the cycle count process. |
| Dashboard & Reporting | Warehouse operational data is summarized into reports and dashboards for inventory monitoring and decision-making. |

---

## Workbook Structure
The workbook is organized into multiple worksheets, each representing a specific function within the warehouse operation. This structure follows the business process illustrated in the previous section, allowing data to flow logically from purchasing and receiving to inventory control and outbound material handling. 

| Worksheet | Description |
|------------|-------------|
| **01_Master_Material** | Stores the master data for all materials, spare parts, consumables, and finished goods, including item codes, descriptions, categories, units of measure, and inventory-related attributes. |
| **02_Master_Supplier** | Contains supplier master data used as a reference for purchasing transactions and supplier management. |
| **03_Master_Location** | Defines warehouse storage locations such as warehouse, zones, racks, and bins to support inventory organization and traceability. |
| **04_Purchase_Order** | Records purchase orders issued to suppliers before materials are received into the warehouse. |
| **05_Goods_Receipt** | Records incoming materials received from suppliers and updates inventory based on approved purchase orders. |
| **06_Put_Away** | Records the movement of received materials from the receiving area to their designated storage locations. |
| **07_Material_Request** | Records material requests from Production, Sales, Service, Dealers, or Branch Warehouses for outbound warehouse operations. |
| **08_Picking_List** | Generates picking instructions based on approved material requests to support accurate and efficient warehouse picking operations. |
| **09_Goods_Issue** | Records outbound material transactions after picking has been completed and updates inventory accordingly. |
| **10_Stock_Card** | Maintains a complete history of inventory movements, including stock-in, stock-out, and running balances for each material. |
| **11_Cycle_Count** | Records periodic physical inventory counts and identifies discrepancies between physical stock and system inventory. |
| **12_Dashboard** | Presents key warehouse performance indicators (KPIs), inventory summaries, stock movement analysis, and operational insights through interactive visualizations. |

Together, these worksheets illustrate how warehouse master data, operational transactions, inventory control, and performance monitoring can be integrated into a structured warehouse management workflow.

-------------
------------- on progress -------------
--------------
## Data Model

## Excel Features

## Dashboard

## Project Highlights

## Future Improvements
