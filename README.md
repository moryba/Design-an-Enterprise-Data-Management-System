# Design an Enterprise Data Management System (Data Architect Nanodegree Program)

## Business Overview
SneakerPark is an online shoe reseller that allows people to buy and sell used and new shoes. Buyers can bid for shoes or buy them outright, and sellers can set a price or sell to the highest bidder.

Each buyer and seller must have an active account in order to sell, bid, or purchase sneakers using SneakerPark’s website.

SneakerPark authenticates the shoes before shipping them to the buyer, so before listing an item, the seller must ship it to SneakerPark’s warehouse. Upon receipt, SneakerPark assigns an item number to each pair of sneakers and notifies the seller that they are now free to list their item. If the item is not listed within 45 days, SneakerPark returns the sneakers to the seller and sends an invoice to the seller for the shipping cost.

If the item is found to be inauthentic or in an unacceptable condition, it is also returned back to the seller in a similar fashion.

When the item sells, the seller's account is credited with the purchase price minus the SneakerPark service fee and shipping fees to deliver the item to the buyer.

## Goal of the Project

The goal is to create the foundational data management tools and artifacts that will allow SneakerPark to better manage their data now and in the future. More specifically, this entails documenting SneakerPark's data systems, setting up a data catalog, designing better data quality and master data management processes, and formalizing data governance roles.

## Process

- Create an Enterprise Conceptual Model that provide a holistic view of data in these three systems

- Design the draft version of the Enterprise Data Catalog by documenting the metadata in an Excel spreadsheet.

- Profile the data to identify 3 data quality issues. Create a document that lists each data quality issue, its description, and a suggested remediation strategy for each.

- Design a data quality dashboard that will report on the issues you’ve identified above plus at least 1 more issue that you foresee might occur in the future.

- Sketch out a proposed MDM implementation architecture, and write a detailed explanation of why you  chose this specific approach.

- Define a set of matching rules that will be used by SneakerPark's MDM Hub to match item and customer entities between the company's different systems.

- Write a paragraph discussing what data governance roles and responsibilities will be necessary to oversee this new Data Management initiative.

## Enterprise Data Model
![alt text](EDM.png)

## Registry Master Data Management - Diagram 
![alt text](MDM.png)

## Registry Master Data Management - Table

## Data Quality Monitoring Dashboard
![alt text](Dashboard.png)
![alt text](Dashboard_2.png)
