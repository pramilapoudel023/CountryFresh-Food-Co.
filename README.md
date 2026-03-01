# CountryFresh Rewards – Loyalty Program Implementation 

![Business Analysis](https://img.shields.io/badge/Role-Business%20Analysis-green) ![SDLC](https://img.shields.io/badge/SDLC-Waterfall-blue) ![Retail](https://img.shields.io/badge/Domain-Retail-orange)

## Table of Contents
* [Project Overview](#project-overview)
* [Problem Statement](#problem-statement)
* [Goals and Objectives](#goals-and-objectives)
* [Data Sources and Methodology](#data-sources-and-methodology)
* [File and Folder Structure](#file-and-folder-structure)
* [Key Findings/Results](#key-findingsresults)
* [Tools and Technologies](#tools-and-technologies)
* [Usage and Access](#usage-and-access)
* [Contributors and Contact Information](#contributors-and-contact-information)
* [License](#license)

## Project Overview
This project involves the comprehensive business process analysis and requirements engineering for CountryFresh Food Co., a premium grocery retailer. The initiative, titled "CountryFresh Rewards," aims to modernize the customer experience by replacing fragmented, manual promotional methods with a centralized, data-driven loyalty ecosystem. The project covers everything from initial discovery and process modeling (BPMN) to the definition of 20+ functional requirements and a robust testing framework.

## Problem Statement
CountryFresh Food Co. currently faces a "data blind spot" at the point of sale. 
* **Anonymous Transactions:** The brand cannot identify individual customers or track purchase history.
* **Inefficient Marketing:** Reliance on weekly paper flyers results in generic promotions that fail to resonate with younger demographics.
* **Siloed Data:** Current rewards (like the legacy Salad Bar Card) are not integrated, leading to a fragmented customer experience and missed cross-selling opportunities.

## Goals and Objectives
The project is designed to deliver measurable business value through several strategic objectives:
* **Retention:** Achieve a **10% improvement** in 90-day customer retention.
* **Engagement:** Increase repeat customer visits by **15%** within the first six months.
* **Acquisition:** Grow the student and young professional customer segment by **20%**.
* **Operational Excellence:** Ensure loyalty identification adds no more than **2 seconds** to total checkout time (NFR-01).
* **Compliance:** Ensure 100% adherence to data privacy regulations regarding PII masking (NFR-04).

## Data Sources and Methodology
* **Data Sources:** Analysis was performed using internal business artifacts, including existing Salad Bar Card usage rates, transaction volume estimates, and stakeholder interviews to define a **$135,000 budget** (including 15% contingency).
* **Methodology:** * **Process Mapping (BPMN 2.0):** Developed AS-IS and TO-BE process models to visualize the transition from manual cashier intervention to automated system-driven workflows.
    * **Gap Analysis:** Identified technical gaps in customer identification and real-time discount application.
    * **Requirements Engineering:** Translated business objectives into a structured **Functional & Non-Functional Requirements** document.
    * **Traceability:** Created a **Requirements Traceability Matrix (RTM)** to ensure every Business Objective (BO) is mapped to a testable User Acceptance (UAT) scenario.

## File and Folder Structure
* `README.md`: Project summary and documentation guide.
* `documentation/`:
    * `Project_Charter.pdf`: Project authorization, high-level scope, and budget.
    * `Business_Process_Analysis.pdf`: Deep dive into AS-IS vs. TO-BE comparisons.
    * `Functional_NonFunctional_Requirements.pdf`: Detailed system behavior and constraints.
    * `Business_Rules_Catalog.pdf`: Logic for point accrual, student discounts, and precedence.
* `testing_and_results/`:
    * `Requirements_Traceability_Matrix.pdf`: End-to-end mapping of goals to UAT.
    * `KPI_Framework_Success_Metrics.pdf`: Framework for measuring ROI post-launch.
    * `UAT_Scenarios.pdf`: Test scripts for validating system functionality.
* `visuals/`:
    * `AS-IS_Process_BPMN.pdf`: Diagram of the current manual process.
    * `TO-BE_Process_BPMN.pdf`: Diagram of the optimized loyalty process.

## Key Findings/Results
* **The "To-Be" Transformation:** The new process replaces the siloed "Salad Bar Card" with a unified Rewards ID, allowing for transaction-level CRM data capture.
* **Personalization Strategy:** Data indicates that a **10% Student Tuesday Discount** (BR-03) is the primary lever for capturing the high-lifetime-value young professional segment.
* **Risk Mitigation:** Identified data privacy as a "High" priority; successfully mandated **PII masking** (UAT-14) on cashier-facing screens to ensure security and compliance.

## Tools and Technologies
* **Business Modeling:** LucidChart / BPMN 2.0
* **Documentation:** Microsoft Word / Adobe Acrobat
* **Analysis & Tracking:** Microsoft Excel (for the RTM and KPI Framework)

## Usage and Access
This repository is organized to follow the logical flow of a Business Analysis engagement:
1. **Initiation:** Start with the `Project_Charter.pdf` for the business case.
2. **Analysis:** Review `Business_Process_Analysis.pdf` to see how checkout flows were optimized.
3. **Execution:** Refer to the `Requirements` and `Business Rules` for technical implementation logic.
4. **Validation:** Review the `RTM.pdf` to see how requirements are traced to `UAT_Scenarios.pdf`.

## Contributors and Contact Information
* **Pramila Poudel** – Business Analyst
* https://www.linkedin.com/in/pramilapoudelbusinessanalyst/
* pramilapoudel023@gmail.com

## License
This project is licensed under the [MIT License](LICENSE.txt).
