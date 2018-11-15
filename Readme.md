<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Dashboard_ControlAccess/Form1.cs) (VB: [Form1.vb](./VB/Dashboard_ControlAccess/Form1.vb))
<!-- default file list end -->
# How to access API of underlying controls in the WinForms Viewer


<p>The following example demonstrates how to customize controls used to visualize data within dashboard items at runtime using <a href="http://documentation.devexpress.com/#Dashboard/clsDevExpressDashboardWinDashboardViewertopic">DashboardViewer</a>'s API. This approach is described in greater detail in the <a href="https://documentation.devexpress.com/#Dashboard/CustomDocument18019">Access to Underlying Controls</a> help topic.<br />In this example, the following options are changed:<br />- The font of data rows' text is changed in the underlying grid control in the <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardWinDashboardViewer_DashboardItemControlUpdatedtopic">DashboardItemControlUpdated</a> event handler.<br />- The background color of the chart's pane is changed in the <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardWinDashboardViewer_DashboardItemControlUpdatedtopic">DashboardItemControlUpdated</a> event handler.<br />- Values of data cells in the underlying pivot grid control are customized using the <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraPivotGridPivotGridControl_CustomCellValuetopic">CustomCellValue</a> event. Subscription and unsubscription to/from the CustomCellValue event are performed in the <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardWinDashboardViewer_DashboardItemControlCreatedtopic">DashboardItemControlCreated</a> and <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardWinDashboardViewer_DashboardItemBeforeControlDisposedtopic">DashboardItemBeforeControlDisposed</a> event handlers respectively.</p>

<br/>


