<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128659440/24.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T326312)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->

# WPF TileNavPane - Display Navigation Buttons and Categories

This example creates a [`TileNavPane`](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavPane), populate it with navigation elements and add custom buttons to the nav bar.

In the XAML markup, four buttons are added to the [`NavButtons`](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavPane.NavButtons) collection. Buttons added to this collection are displayed in the nav bar. The first, which is aligned at the left margin of the nav bar, is the Main Button. The `IsMain` property of this button is set to `true`. Other buttons are aligned to the right using the `HorizontalAlignment` property. The second button contains items, and so a drop-down tile bar is invoked when this button is clicked. Button glyphs are differently aligned (the`GlyphAlignment` property) and the rightmost button does not have a textual content (the `Content` property). All glyphs are specified to be displayed with the glyph theming feature enabled (the `AllowGlyphTheming` property).

One category ([`TileNavCategory`](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavCategory)) is added the [`Categories`](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavPane.Categories) collection. This category contains one child item, which in turn contains two sub-items. The textual and graphical content of tiles is specified with the `TileContent` and `TileGlyph` properties. Textual content of the corresponding buttons in the nav bar is specified with the `Content` property.

## Implementation Details

...

## Files to Review

* [MainWindow.xaml](./CS/WpfApplication303/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication303/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfApplication303/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfApplication303/MainWindow.xaml.vb))

## Documentation

* [NavButtons](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavPane.NavButtons)
* [TileNavPane](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavPane)
* [TileNavCategory](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavCategory)
* [Categories](https://docs.devexpress.com/WPF/DevExpress.Xpf.Navigation.TileNavPane.Categories)

## More Examples

* [WPF TileBar – Bind Items to a ViewModel Collection (MVVM)](https://github.com/DevExpress-Examples/wpf-tilebar-generate-items-from-view-model-collection)
* [WPF Tiles - Create Windows-inspired Tile Layout](https://github.com/DevExpress-Examples/wpf-create-tile-layout-control)

<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=how-to-create-tilenavpane-navigation-buttons-and-categories-in-xaml-t326312&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=how-to-create-tilenavpane-navigation-buttons-and-categories-in-xaml-t326312&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
