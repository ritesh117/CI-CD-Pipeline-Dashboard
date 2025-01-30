1. HTMLStructure Subgraph:

This subgraph represents the structure and rendering of the HTML elements on the page.
It includes the following steps:
RenderNavigation: Renders the navigation bar with the logo, title, and buttons.
RenderOverviewCards: Renders the overview cards, including the success rate, average build time, deployments, and active pipelines.
RenderPipelineStatus: Renders the pipeline status section, including the individual pipeline stage cards and the test results chart.
RenderRecentBuilds: Renders the recent builds section, including the progress bar and the builds table.
RenderCharts: Initializes the line charts for the overview cards and the pie chart for the test results.


2. JavaScriptFunctionality Subgraph:

This subgraph represents the JavaScript functionality and interactivity on the page.
It includes the following steps:
InitializeBuilds: Defines the sample build data with additional information.
FormatBuildRow: Formats the HTML string for a single build row, including the status, branch, commit, and time.
RenderBuilds: Renders the build list by clearing the existing content and inserting the new build rows.
SimulateNewBuilds: Simulates the addition of new builds every 10 seconds, updating the build list accordingly.
UpdatePipelineStatuses: Periodically updates the duration text for the pipeline stage cards.
UpdateTestResultsChart: Updates the test results pie chart based on the changes in the build data.
The flow diagram illustrates the overall structure and interactions between the HTML rendering and the JavaScript functionality. The HTMLStructure subgraph represents the static structure of the page, while the JavaScriptFunctionality subgraph handles the dynamic aspects, such as initializing the build data, rendering the builds, simulating new builds, and updating the pipeline statuses and test results chart.

The integration between the two subgraphs is shown through the connections, indicating how the HTML structure provides the foundation for the JavaScript functionality to enhance the user experience and visualize the CI/CD pipeline data.
