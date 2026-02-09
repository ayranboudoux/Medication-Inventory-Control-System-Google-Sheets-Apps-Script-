# Medication-Inventory-Control-System-Google-Sheets-Apps-Script-

This project is an automated medication inventory control system developed using Google Sheets integrated with Google Apps Script, focused on organization, traceability, and reduction of manual errors.

# Features

Automated inbound (entry) and outbound (exit) medication records

Dynamic inventory updates (quantity increase or decrease)

Automatic data population using barcode input

Control by batch, expiration date, laboratory, and type

Movement history logging with date and time

Duplicate prevention (processes only unregistered rows)

Automatic detection of the first empty row in the inventory

Diagnostic function (checkSetup) for sheet validation


# System Logic

The onEdit trigger is fired when editing the barcode column in the Entry or Exit sheets

Data is automatically retrieved from the Products sheet

Movements are recorded only if the status field is empty

Inventory updates are handled safely, preserving existing formulas

All actions are logged for audit and tracking purposes


# Technologies Used

Google Sheets

Google Apps Script (JavaScript)

Native SpreadsheetApp services


# Purpose

To provide a simple, efficient, and scalable solution for medication inventory management, adaptable to clinics, pharmacies, warehouses, or other inventory-based environments.
