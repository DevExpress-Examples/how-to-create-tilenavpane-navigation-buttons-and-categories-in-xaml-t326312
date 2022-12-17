<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128659440/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T326312)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/WpfApplication303/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication303/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfApplication303/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfApplication303/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Create TileNavPane Navigation Buttons and Categories in XAML


<p>This example shows how to create a <a href="https://documentation.devexpress.com/WPF/clsDevExpressXpfNavigationTileNavPanetopic.aspx">TileNavPane</a>, populate it with navigation elements and add custom buttons to the nav bar.</p>
<p>In the XAML markup, four buttons are added to the <a href="https://documentation.devexpress.com/WPF/DevExpressXpfNavigationTileNavPane_NavButtonstopic.aspx">NavButtons</a> collection. Buttons added to this collection are displayed in the nav bar. The first, which is aligned at the left margin of the nav bar, is the Main Button. The <strong>IsMain</strong> property of this button is set to <strong>true</strong>. Other buttons are aligned to the right using the <strong>HorizontalAlignment</strong> property. The second button contains items, and so a drop-down tile bar is invoked when this button is clicked. Button glyphs are differently aligned (the<strong>GlyphAlignment</strong> property) and the rightmost button does not have a textual content (the <strong>Content</strong> property). All glyphs are specified to be displayed with the glyph theming feature enabled (the <strong>AllowGlyphTheming</strong> property).</p>
<p>One category (<a href="https://documentation.devexpress.com/WPF/clsDevExpressXpfNavigationTileNavCategorytopic.aspx">TileNavCategory</a>) is added the <a href="https://documentation.devexpress.com/WPF/DevExpressXpfNavigationTileNavPane_Categoriestopic.aspx">Categories</a> collection. This category contains one child item, which in turn contains two sub-items. The textual and graphical content of tiles is specified with the <strong>TileContent</strong> and <strong>TileGlyph</strong> properties. Textual content of the corresponding buttons in the nav bar is specified with the <strong>Content</strong> property.</p>

<br/>


