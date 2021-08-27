<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128570019/17.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T553953)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/ScaleBreaks/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/ScaleBreaks/MainWindow.xaml))
<!-- default file list end -->
# How to: Manually Insert Scale Breaks into an Axis


This example demonstrates how to manually create scale breaks for a y-axis and customize their appearance.


<h3>Description</h3>

<p>Add a <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.ScaleBreak.class">ScaleBreak</a><strong>&nbsp;</strong>object to the&nbsp;&nbsp;<a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.Axis2D.ScaleBreaks.property">Axis2D.ScaleBreaks</a>&nbsp;collection to insert a scale break into an axis. Then, define the <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.ScaleBreak.Edge1.property">ScaleBreak.Edge1</a>&nbsp;and <a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.ScaleBreak.Edge2.property">ScaleBreak.Edge2</a>&nbsp;property values to set&nbsp;a data range that should be replaced by a scale break. Note that the&nbsp;<strong>Edge1&nbsp;</strong>and&nbsp;<strong>Edge2&nbsp;</strong>should be specified in measurement units of an appropriate axis.</p>
<p>Use the following properties to modify scale breaks' appearance:</p>
<p>-&nbsp;<a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.ScaleBreakOptions.SizeInPixels.property">ScaleBreakOptions.SizeInPixels</a></p>
<p>-&nbsp;<a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.ScaleBreakOptions.LineStyle.property">ScaleBreakOptions.LineStyle</a></p>
<p>-&nbsp;<a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.ScaleBreakOptions.Style.property">ScaleBreakOptions.Style</a></p>
<p>-&nbsp;<a href="https://documentation.devexpress.com/WPF/DevExpress.Xpf.Charts.ScaleBreakOptions.Brush.property">ScaleBreakOptions.Brush</a></p>

<br/>


