<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/MainWindow.xaml.vb))
<!-- default file list end -->
# OBSOLETE: How to display custom information in the legend
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e2409)**
<!-- run online end -->


<p><strong>UPDATED:</strong> Starting with version 16.1, we implemented a built-in functionality to add custom legend items to the chart. Refer to the <a href="https://documentation.devexpress.com/WPF/116013/Controls-and-Libraries/Charts-Suite/Chart-Control/Examples/Chart-Elements/How-to-Add-a-Custom-Legend-Items-to-a-Legend">How to: Add a Custom Legend Items to a Legend</a> article for more details.<br><br><br>This example demonstrates how to calculate a total of values displayed by each legend item, and show this total in the legend. This can be done by utilizing a <strong>ControlTemplate</strong> with a Grid, containing a <strong>LegendItemsControl</strong> (for displaying legend items) and a <strong>TextBlock</strong> (showing the result). The summary is calculated in the chart control's <strong>BoundDataChanged</strong> event handler, and assigned to the <strong>DataContext</strong> property of the legend, to provide this value for the TextBlock's text. In the ControlTemplate, the <strong>Border</strong>'s appearance properties (<strong>Background</strong>, <strong>BorderThickness</strong>, <strong>BorderBrush</strong> and <strong>Padding</strong>) and the LegendItemsControl's properties (<strong>ItemTemplate</strong> and <strong>ItemsSource</strong>) are bound to similar properties of the legend. You can customize the legend's layout and appearance as required, using this sample as a starting point.</p>
<p>See also

* <a href="https://www.devexpress.com/Support/Center/p/E2842">How to display check boxes for legend items to control the visibility of series</a>;
* <a href="https://www.devexpress.com/Support/Center/p/E1914">How to customize chart titles</a>.</p>

<br/>


