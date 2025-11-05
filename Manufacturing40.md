### Complete Study Guide: Automation Stack, Digital Factory, MES, OEE, OPC UA, and Industry 4.0

#### The Five Layers of the Automation Stack

| Layer | Description | Key Functions |
|-------|-------------|---------------|
| Cloud | Top layer involving big data analytics and algorithms | Data sharing with partners, cloud-based analytics |
| ERP   | Enterprise Resource Planning | Managed by IT and accounting, focuses on resource planning at the enterprise level |
| MES   | Manufacturing Execution System | Manages business units, typically handled by systems integrators |
| SCADA | Supervisory Control and Data Acquisition | Plant-wide control, data collection, real-time analysis, and supervisory functions |
| PLC/HMI | Programmable Logic Controller/Human Machine Interface | Direct control and automation of equipment on the factory floor |

#### Key Points of the Automation Stack

- **PLC/HMI Layer**: Focuses on automation and direct control, often managed by OEMs.
- **SCADA Layer**: Responsible for data collection, real-time analysis, and supervisory functions within a plant.
- **MES Layer**: Manages business units and is usually handled by systems integrators.
- **ERP Layer**: Managed by IT and accounting, focuses on enterprise resource planning.
- **Cloud Layer**: Involves cloud-based analytics and data sharing with partners.

#### Roles and Responsibilities

- **OEMs**: Typically operate at the PLC/HMI layer, writing PLC code and developing HMIs.
- **Systems Integrators**: Work on both the SCADA and MES layers.
- **IT Departments**: Manage the ERP layer.
- **Cloud and IIoT**: These are emerging fields with significant growth potential. Cloud-based analytics and integrations are becoming increasingly important.

#### Growth Areas

- **Cloud**: Cloud-based analytics and integrations.
- **IIoT (Industrial Internet of Things)**: Focuses on seamless integration of the automation stack.

#### The Digital Factory

1. **Introduction**:
   - The Digital Factory aims to eliminate paper from manufacturing processes.
   - It involves the digitization of manufacturing as part of the 4th Industrial Revolution.

2. **Key Elements**:
   - **No Paper**: Elimination of paper-based processes.
   - **Connected Stack**: All layers of the automation stack are interconnected.
   - **Real-Time Metrics**: Decision-making based on real-time data.
   - **Big Data Analytics**: Using historical data and advanced analytics to improve operations.

3. **Benefits**:
   - Decreases errors by relying on data from the source of truth.
   - Enhances scheduling accuracy by connecting ERP systems with real-time data from equipment.
   - Enables real-time decision-making based on current data (e.g., weather, shipping, sales).
   - Utilizes predictive maintenance and machine learning to anticipate issues and optimize operations.

4. **Misconceptions**:
   - It is not just about andon boards (visual management tools).
   - It does not mean eliminating people from the process. Instead, it aims to create higher-paying jobs by automating routine tasks and focusing on data analysis and efficiency improvements.

#### Manufacturing Execution Systems (MES)

1. **Introduction**:
   - MES converts sales from ERP systems into actual manufacturing processes.
   - It is often considered the most critical software in manufacturing businesses.

2. **Core Functionalities**:
   - **Work Orders**: Translating planned manufacturing tasks into executable work orders.
   - **Scheduling**: Scheduling work orders for execution.
   - **OEE (Overall Equipment Effectiveness)**: Tracking the efficiency of manufacturing assets.
   - **Downtime Tracking**: Monitoring and managing downtime to improve production efficiency.

3. **Flexibility and Customization**:
   - MES systems are highly customizable and can include a variety of additional functionalities such as recipe management, quality inspection plans, statistical process control, and more.
   - The core functionalities can be expanded based on the unique requirements of each business.

4. **Challenges with MES**:
   - The term "MES" can be misleading because it represents a wide range of capabilities rather than a single, standardized product.
   - Different businesses may require different sets of functionalities from their MES systems.

5. **Integration with Other Systems**:
   - MES systems often integrate with ERP systems for scheduling and work order management.
   - They play a central role in the automation stack, connecting ERP systems with SCADA and PLC/HMI layers.

6. **Implementation**:
   - Boot camps and training programs teach how to build and extend MES capabilities, including ERP integration and advanced analytics.

#### Overall Equipment Effectiveness (OEE)

1. **Introduction**:
   - OEE is a critical metric for manufacturing operations.
   - It is not optional and should be calculated to understand the efficiency of manufacturing processes.

2. **Components of OEE**:
   - **Availability**: The percentage of time the machine was available to run during the scheduled time.
   - **Performance**: The number of parts produced relative to the expected production rate when the machine was running.
   - **Quality**: The percentage of good parts produced out of the total parts produced.

3. **Importance of OEE**:
   - Essential for making informed decisions about maintenance, quality control, and production scheduling.
   - Helps in identifying areas for improvement and optimizing operations.
   - Crucial for achieving the "Holy Grail" of manufacturing, which involves using machine learning and AI for optimal decision-making.

4. **TEEP vs. OEE**:
   - TEEP (Total Effective Equipment Performance) is based on a 24-hour, 7-day schedule and does not account for quality or availability.
   - OEE takes into account the actual schedule, including planned and unplanned downtime, changeovers, and shift changes.

5. **Calculating OEE**:
   - **Availability**: Track all downtime and categorize it as planned or unplanned.
   - **Quality**: Calculate the percentage of good parts produced.
   - **Performance**: Calculate the actual production rate relative to the standard rate.

6. **Benefits of Calculating OEE**:
   - Helps in identifying unrealistic standard rates.
   - Assists in determining the effectiveness of maintenance plans and quality inspection plans.
   - Provides insights into the performance of operators, shifts, raw material vendors, and machines.
   - Essential for achieving the closed-loop integration of the entire business.

#### OPC UA (Open Platform Communications Unified Architecture)

1. **Introduction**:
   - OPC UA is a communication protocol used in industrial automation and the Industrial Internet of Things (IIoT).
   - It stands for OLE (Object Linking and Embedding) for Process Control.

2. **History and Purpose of OPC**:
   - OPC was developed as an extension of Microsoft's OLE technology for industrial automation.
   - The goal was to create an interoperability standard for industrial hardware and software.

3. **Common Use Cases**:
   - OPC is used to enable communication between different PLCs (Programmable Logic Controllers) and software applications in a manufacturing environment.
   - Tools like Kepware's KEPServerEX are used to connect to various PLCs and expose their data through OPC UA.

4. **OPC Foundation**:
   - The OPC Foundation is responsible for managing and developing the OPC standards.
   - It includes members from major industrial companies like Beckhoff, Microsoft, and Rockwell Automation.

5. **Why OPC UA is Not the Future of IIoT**:
   - **Technical Debt**: OPC UA carries remnants of older standards (OPC Classic), making it difficult for engineers to work with.
   - **Corporate Interests**: The OPC Foundation's focus is often influenced by the interests of its corporate members, leading to interoperability issues.
   - **Bureaucracy**: The OPC Foundation is seen as bureaucratic, with members sometimes more focused on their roles within the organization than on providing effective tools.

6. **Comparison with MQTT**:
   - OPC UA is not considered an ideal IIoT protocol by some engineers and architects, who prefer MQTT for its simplicity and scalability.
   - MQTT is often used in modern IIoT architectures for its ability to handle large-scale deployments and its cloud-native capabilities.

#### Industry 4.0 and IIoT

1. **Manufacturing Workflow**:
   - Every manufacturer follows a common workflow: sell, plan, execute, store, ship, invoice, and follow up.
   - As businesses grow, each step becomes more complex and requires specialized software.

2. **Software in Manufacturing**:
   - **CRM (Customer Relationship Management)**: Manages client interactions and sales.
   - **ERP (Enterprise Resource Planning)**: Manages resources, planning, and costing. Many start with QuickBooks and upgrade as they grow.
   - **MES (Manufacturing Execution System)**: Manages the execution of manufacturing processes. Often the last piece of software to be implemented.
   - **SCADA (Supervisory Control and Data Acquisition)**: Provides visibility and control over manufacturing processes.
   - **WMS (Warehouse Management System)**: Manages inventory and warehousing, often starting within the ERP system.
   - **Shipping Software**: Manages the shipping process, sometimes integrated with WMS or ERP.
   - **Invoicing Software**: Handles invoicing, often starting with QuickBooks and upgrading to more robust systems.

3. **Digital Transformation**:
   - Digital transformation in manufacturing often focuses on upgrading ERP systems, but the real value lies in integrating operational technology (OT) with business systems.
   - Many manufacturers waste money on ERP systems that don't provide real-time information or efficiency gains.

4. **Industry 4.0 and IIoT**:
   - Industry 4.0 principles are crucial for integrating ERP systems with operational technology.
   - Use a unified namespace to connect all systems, instead of relying on middleware or explicit connections.
   - Use outbound reporting technology to ensure secure and efficient communication.

5. **Unified Namespace**:
   - A unified namespace allows all software systems to publish and consume data from a single source.
   - This approach simplifies upgrades and maintenance, as systems only need to be configured to publish to or consume from the namespace.

6. **Overall Equipment Effectiveness (OEE)**:
   - OEE is critical for understanding manufacturing efficiency.
   - OEE is calculated as the product of availability, quality, and performance.
   - Improving OEE can significantly increase production capacity without additional investment.

7. **Challenges and Misconceptions**:
   - Many manufacturers struggle with the transition from Industry 3.0 to Industry 4.0 due to internal resistance and lack of understanding.
   - The future of manufacturing lies in leveraging data and infrastructure for efficiency gains and predictive maintenance.
