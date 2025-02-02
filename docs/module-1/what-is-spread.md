---
title: What is SPREAD?
description: A course module explaining what SPREAD is and how it can help you manage and visualize product data.
comments: true
hide:
     - toc
---

<style>
.twemoji {
     visibility:hidden;
}

.grid-heading {
     color: var(--primary);
     font-weight: bold;
     font-size: 1.8em;
     display: block
}

.grid-blurb {
     color: var(--darkgrey)
     font-size: 0.8em;
}

.md-button--primary {
     margin-top: 1.5em;
}

.giscus a.btn {
     background-color: blue !important;
}
</style>

The SPREAD product is a platform that provides a suite of tools for data analysis, visualization, and collaboration. The platform allows you to work with product data more efficiently and effectively.

!!! info "More about SPREAD"

     SPREAD was founded to make product data accessible and easy to use. The company was established in 2019 in Berlin and now has over 100 employees. For more on the company, see [About us](https://www.spread.ai/about). For more on the solutions offered by SPREAD, see the [Overview]({{ config.site_url }}) page of the documentation.

The key features of SPREAD include:

* **Data import and integration:** You can import data from various sources, including spreadsheets, databases, and cloud storage services.
* **Data visualization:** SPREAD provides visualization tools, including charts, tables, and maps.
* **Collaboration:** You can share data and visualizations with others in real-time, making it easier to work together on projects.
* **Data analysis:** SPREAD provides a range of analysis tools, including filtering, sorting, and grouping, to help you get insights from your data.

<figure markdown="span" class="noborder">
	![The SPREAD Studio, where you can create applications that visialize data](src/spread-studio-collaboration.png){ .skip-lightbox }
	<figcaption>The SPREAD Studio</figcaption>
</figure>

In this course, we will learn how to ingest data, display data using SPREAD Studio, and also write data to the Engineering Intelligence Graph (EI Graph). The types of data that can be imported into SPREAD include:

| Data type | Description | Data format |
| --- | --- | --- |
| 2D wiring harness | Technical documentation of wiring harness data: connections between electric components from terminal to terminal including module part numbers, connectors, terminals, wires, and auxiliary information. Contains co-ordinates of the flattened wiring harness 2D drawing | kbl, vec |
| 3D model | The 3D CAD model of a product, assembly, or part. | jt, step, x3d, and more |
| 3D wiring harness | Technical documentation of wiring harness data: connections between electric components from terminal to terminal including module part numbers, connectors, terminals, wires, and auxiliary information. May also contain 3D co-ordinates for connectors and [B-splines](https://en.wikipedia.org/wiki/B-spline) and control points for 3D positioning of single wires. | kbl, vec |
| Bill of Materials (BoM) | A list with part numbers, quantities, descriptions, configuration codes (code rules) for a product and its parts or assemblies. Usually, there are different BoMs per department with different detail levels and structures. For example: one for engineering, one for manufacturing, retail, and so on. | xls, xml |
| Bus Communication | The K-Matrix describes which protocol or bus sends which message in which frame and what the single bits and bytes mean. | xml, arxml, xlsx |
| Component ID mapping | Mapping and translation of harness component identifiers. For example, Reference IDs from wiring harness data, Diagnosis IDs from test reports, diagnosis addresses from test reports, Component identifiers from Open Diagnostic Data Exchange (ODX) data, and so on. | xlsx or similar |
| Component specification | Component specifications, including matching signals and error codes to pins. | xlsx, xml, csv or similar |
| Configuration code translation | A translation of configuration codes used in the BoM and order data into natural language. For example: L0L = left-steering. | xlsx or similar |
| Connector housing pictures | 2D pictures of connector housing showing terminal positions within the connector housing, which are mapped via connector housing part numbers. | svg |
| Diagnosis specification | Specification of diagnosis behavior for diagnosis-relevant components - mostly Electronic Control Units (ECUs) - including Diagnostic Trouble Codes (DTCs), error messages, repair messages, or error triggering conditions. | pdx, odx |
| DTC Mapping | Mapping of DTCs to either their start terminal or end component for error cause predictions. | xlsx or similar |
| ECUs | A description of the Electronic Control Units (ECUs). | arxml |
| Functions | Customer or Vehicle functions that describe a behavior of a feature. | xml, csv, xlsx |
| Harness data documentation | Documentation for client-specific logic for wiring harness development and documentation, for example, for distinguishing component types by their Reference ID. | pdf |
| Issue tickets | Raised tickets for issues with electric components, functions and/or software modules. | |
| Regulations | | |
| Requirements | | |
| Signal communication | Description of electric communication between ECUs based on system and bus signals. | arxml |
| Technology data | 3D co-ordinates of electric connectors. | xml |
| Test reports | Test reports and protocols from diagnosis tests based on OBD diagnosis with ECU identifiers and reported DTCs (error codes). | xml, json |
| Vehicle order data | Vehicle order reports with configuration specification of a unique vehicle (VIN) based on configuration codes (code rules) from Bill of Material including additional information such as production number, production date, and so on. | xml, json |
| Wiring harness diagrams | Wiring harness diagrams from legacy systems for harness design and visualization. | png, pdf, tiff, or similar |

## How SPREAD helps product manufacturers

<div class='grid cards' style='max-width: 90vw !important; margin: auto' markdown>

* :white_small_square:

     <span class="grid-heading">Automotive OEMs</span>
     <p class="grid-blurb">Powering the next wave of software-defined vehicles</p>

     ![A 3D model of a vehicle](src/automotive-industry.png){ .skip-lightbox }

     [Explore the use cases](https://www.spread.ai/solutions/automotive#section_category_preview){ .md-button .md-button--primary }

* :white_small_square:

     <span class="grid-heading">Commercial vehicles</span>
     <p class="grid-blurb">Driving the future of intelligent, connected commercial vehicles</p>

     ![A 3D model of a vehicle](src/commercial-vehicles.png){ .skip-lightbox }

     [Explore the use cases](https://www.spread.ai/solutions/commercial-vehicle-oems#section_category_preview){ .md-button .md-button--primary }

* :white_small_square:

     <span class="grid-heading">Defense</span>
     <p class="grid-blurb">Enabling the future of connected, high-precision defense systems</p>

     ![A 3D model of a vehicle](src/defence.png){ .skip-lightbox }

     [Explore the use cases](https://www.spread.ai/solutions/defense#section_category_preview){ .md-button .md-button--primary }

</div>

!!! question "Helpful hints"

    To ask a question, leave a comment in the comments section of the relevant page. Before asking a question, we kindly ask that you search the comments to see if your questions is already answered. Sign up for an account at [github.com](https://github.com). 

     To get the definition of any terminology, such as Engineering Intelligence Graph, hover over the word for a few seconds and a definition box will appear that explains the term.

<blockquote class="next-lesson">In the <a href="what-is-eig.html">next lesson</a> we will learn more about the Engineering Intelligence Graph and how data cycles through the SPREAD ecosystem.</blockquote>
