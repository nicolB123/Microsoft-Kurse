Inhalte des Kurses: PL-300T00-A: Design and manage analytics solutions using Power BI.<br>



Topic 1: Prepare the Data (The Power Query Phase)  

This topic focuses on getting data into Power BI and shaping it until it’s usable.<br>

Data Sourcing: Connecting to SQL Databases, Web, CSV, and the Microsoft Dataverse.

Storage Modes: Configuring Import and DirectQuery, Dual Mode (and knowing when to use which).

Data Profiling: Using the View tab to check Column Quality (errors/empty), Column Distribution, and Column Profile.

Advanced Transformations: Unpivoting columns, Transpose, Merging vs. Appending queries, splitting by delimiter, Custom Columns, Column From Examples, Choose Top N and Bottom N.

Query Management: Using Parameters to change data sources dynamically and view M-code in the Advanced Editor.

Data Quality: Handling "Null" values, replacing errors and values, Fill up and down, removing duplicates, switching data types, Add, Rename, Reorder, or Delete columns.




Topic 2: Model the Data (The Architecture Phase)  

Building the "logic" of the report using data modeling principles.

Star Schema Design: Creating Fact Tables (quantitative data) and Dimension Tables (descriptive data).

Relationship Management: Configuring Cardinality (1:1, 1:Many, Many:Many) and Cross-filter direction (Single vs. Both).

Hierarchies: Creating drill-down paths (e.g., Year > Quarter > Month > Day).

Metadata Configuration: Hiding technical columns, setting "Sort by Column," and defining Data Categories (e.g., Image URL, Address).

Special Dimensions: Building a Common Date Table (CALENDARAUTO()) and handling Role-playing dimensions (e.g., Ship Date vs. Order Date).


Topic 3: Create Model Calculations (The DAX Phase)  

Creating custom logic with DAX and important functions.

Context Control: Understanding the difference between Row Context (Calculated Columns) and Filter Context (Measures).

The CALCULATE Function: Using CALCULATE() to set expressions and filters.

Time Intelligence: Implementing functions like TOTALYTD, SAMEPERIODLASTYEAR, and PARALLELPERERIOD.

Advanced Logic: Using Variables (VAR) to optimize performance and readability.

Iterator Functions: Using SUMX, AVERAGEX etc. to operate on several columns in a table.

Quick Measures: Using the wizard to generate common calculations like running totals.


Topic 4: Visualize and Analyze (The UX Phase)  

Building the report with specific tools for report interactivity.

Report Visuals: Stacked/clustered Bar/Column chart (100% or with Line), Line chart, Card (multi row), Matrix, Table, Slicer

Formatting & Logic: Using Conditional Formatting (colors based on values), creating What-if Parameters for scenario testing, Visual Calculations.

Storytelling: Configuring Bookmarks combined with the Selection Pane to create "toggling" visuals or custom reset buttons.

User Interaction and Filters: Filtering with Report Filter and Slicer, Setting up Sync Slicers (one slicer controlling multiple pages) and Drillthrough (right-clicking to see details on a different page).

Enhanced UX: Using Tooltips, Visual Headers and configuring Visual Interactions (Edit Interactions).

AI Analytics: Using Key Influencers, the Decomposition Tree, Smart Narrative (automated summaries), Q&A Visual and Analyze functionality.

Trend Analysis: Applying Forecasting lines, Anomaly Detection, and Grouping/Binning for histograms.


Topic 5: Manage and Secure (The Governance Phase)  

This covers how the report "lives" in the cloud (Power BI Service).

Workspace Management: Assigning Roles (Admin, Member, Contributor, Viewer) and creating Power BI Apps for distribution.

Security: Implementing Row-Level Security (RLS) static or dynamic (USERPRINCIPALNAME()) for data filtering based on the logged-in user, Single-Sign-on with DirectQuery.

Automation: Understanding Scheduled Refresh, Incremental Refresh and On-premises Data Gateways.

Governance: Applying Sensitivity Labels (Top Secret, Public) and Endorsing content (Promoted vs. Certified).

Distribution: Creating Dashboards (not just reports), setting Data Alerts and create mobile layouts
