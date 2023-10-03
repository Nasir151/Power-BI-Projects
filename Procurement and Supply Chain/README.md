# Procurement and Supply Chain Dashboard

## Business Context

In our dynamic business environment, efficient procurement and supply chain management are pivotal to reducing costs, optimizing resources, and enhancing competitiveness. The Accounts Department of our company meticulously maintains detailed invoice records for every vendor and part procured. These records provide a treasure trove of data that, when analyzed effectively, can unlock valuable insights for the company's strategic procurement decisions.

## Problem Statement

The task at hand is to leverage the vast and diverse dataset encompassing multiple years, plants, business units, materials, suppliers, and more. Our goal is to derive actionable insights that empower the Procurement Department to make data-driven supply chain decisions.

## Dataset Description

The dataset comprises three distinct sets of data:

### Report Data
- Contains information about invoices, including invoice number, month, year, business unit, manufacturing plant, part details, supplier details, quantities, values, and more.

| Column Name              | Type   | Description                                             |
|--------------------------|--------|---------------------------------------------------------|
| Invoice no.              | Text   | Unique identifier for the specific invoice entry.       |
| Month                    | Text   | Month when the invoice was made, defined in numeric form (e.g., 1=Jan, 2=Feb, 3=Mar, and so on). |
| Year                     | Text   | Year when the invoice was made.                        |
| BU                       | Text   | Business Unit of the Manufactured Part.                |
| Plant                    | Text   | Manufacturing Plant of the Business Unit.              |
| Part number              | Text   | Unique Identifier of the specific type of manufactured part. |
| Description              | Text   | Description name of the Part.                         |
| MCR Mat.grp.             | Text   | MCR Material Group the Part Belongs to.               |
| Suppliernumber           | Text   | Supplier who invoiced the part.                        |
| Invoicequantity          | Number | Quantity of the parts invoiced in the invoice.         |
| Invoicevalue             | Number | Total Value of the invoice.                             |
| Invoice exch.Rate        | Number | Currency exchange rate.                                 |
| Invoicecurrency          | Text   | Currency of the invoice.                               |
| Price per price unit(IST rate) | Number | Price of one unit of parts.                            |
| Price unit               | Number | Number of Parts in a Unit.                             |
| AVGPrice PY              | Number | Average Running price (Planning Year).                  |
| AVG Price PY without CE  | Number | Average Running price (Planning Year) without Cost Impact. |
| Type                     | Text   | Type of Invoice.                                       |
| Purchasinggroup          | Text   | Code assigned to a person who is responsible for the specific purchase. |
| Commodity                | Text   | Commodity Define.                                      |

### Material Weights and Source Data
- Provides insights into part weights, casting details, supplier information, and commodity categorization. This dataset enables us to understand the materials used and their sources.

| Column Name                | Type   | Description                                             |
|----------------------------|--------|---------------------------------------------------------|
| Part no                    | Text   | Unique Identifier of the specific type of manufactured part. |
| Part Dic.                  | Text   | Description name of the Part.                         |
| Part Family                | Text   | Family Group the part belongs to.                     |
| Casting P/N                | Text   | Casting Part Number linked to the Final Part.          |
| Casting Source             | Text   | Source where the casting was done.                    |
| Casting Process            | Text   | Process of casting.                                   |
| Plant                      | Text   | Manufacturing Plant of the Business Unit.              |
| SupplierNum                | Text   | Specific Number assigned to each Supplier.             |
| Supplier Name Short        | Text   | Name Of the Supplier.                                 |
| Commodity                  | Text   | Defining Non-Ferrous/Ferrous parts.                   |
| RM Grade                   | Text   | Raw Material Alloy Grade.                             |
| Weight                     | Number | Weight of the parts per Unit.                         |
| Conversion factor (number of parts) | Number | Number of parts in one Unit.                |
| System Weight (Kg)         | Number | Average Weight per part.                              |
| Purchasing group           | Text   | Code assigned to a person who is responsible for the Part and Supplier. |

### Supplier Data
- Focuses on supplier-related information, including their location, business growth strategy, MSME classification, payment terms, and capabilities such as casting and machining.

| Column Name           | Type   | Description                                            |
|-----------------------|--------|--------------------------------------------------------|
| SL no                 | Text   | Serial Number - A unique identifier for each supplier. |
| Commodity             | Text   | Defining Non-Ferrous/Ferrous Suppliers.               |
| Supplier Number       | Text   | Specific Number assigned to each Supplier.            |
| Name                  | Text   | Name Of the Supplier.                                 |
| Buyer Code            | Text   | Code assigned to a person who is responsible for the Part and Supplier. |
| Buyer Name            | Text   | Name Of the Responsible Buyer.                        |
| City Location         | Text   | Location Of the Supplier.                             |
| Strategy Status       | Text   | Business Growth Strategy with the supplier (e.g., 'Go' for Grow & 'NoGo' for Not to Grow). |
| MSME type             | Text   | Micro, Small & Medium Enterprises category of the supplier (Turnover > 100cr). |
| Payment Terms (Days)  | Text   | Payment Release Terms with Supplier.                   |
| Casting               | Text   | Indicates if Supplier has Metal Casting Capability.    |
| Machining             | Text   | Indicates if Supplier has Metal Machining Capability.  |

## Dashboard Objectives

Our mission is to create an insightful and interactive dashboard that addresses several key objectives:

1. **Procurement Trends:** Provide a comprehensive overview of procurement trends over different months and years, segmented by business units and plants.

2. **Supplier Limitations:** Identify any limitations or constraints associated with suppliers, such as their capabilities, payment terms, and growth strategy.

3. **Product-Based Supplier Consolidation:** Determine opportunities for supplier consolidation based on part families, materials, and weights.

4. **Cost Minimization:** Analyze data to minimize cost impacts and optimize procurement strategies.

## Dashboard Features

The dashboard will feature a user-friendly interface with interactive visualizations, including:

- **Time Series Trends:** Line charts depicting procurement trends over time.
- **Supplier Heatmaps:** Heatmaps showcasing supplier capabilities and limitations.
- **Part Family Insights:** Pie charts and bar charts illustrating part family distributions.
- **Cost Optimization:** Tables and visuals highlighting cost minimization opportunities.

## Key Benefits

The Procurement and Supply Chain Dashboard will provide the following benefits:

- Enhanced Procurement Strategy: Data-driven insights for strategic procurement planning.
- Cost Optimization: Identification of cost-saving opportunities.
- Supplier Consolidation: Rationalization of suppliers based on data.
- Efficient Decision-Making: Real-time access to critical procurement information.

## Final Dashboard:

![Capture](https://github.com/Nasir151/Power-BI-Projects/assets/94509995/7bfdad0b-5a7d-441a-9b3c-c529d0474ea6)

![Capture1](https://github.com/Nasir151/Power-BI-Projects/assets/94509995/b82162c8-a5f8-4dfa-8f87-a6c3466e12ce)

By leveraging this dashboard, the Procurement Department will be well-equipped to optimize procurement processes, enhance supplier relationships, and minimize costs while ensuring a seamless supply chain operation.

------------------------------------------------------------------------------------------

