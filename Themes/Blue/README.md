# Blue theme for Win11 Settings Styler
This theme makes the Settings app blue.

**Author**: [FireBlade](https://github.com/FireBlade211)

## Installation
To import the theme styles:

1. Open the Windows 11 Settings Styler mod in Windhawk
2. Go to the Settings tab and select Textual Mode
3. Copy and paste the content below into the box and click **Save settings**:

<details>
<summary>Content (click to expand)</summary>

```yaml
theme: ''
styleConstants:
  - ''
controlStyles:
  - target: Frame#PermanentNavRootFrame
    styles:
      - Background=#03A5FC
  - target: SystemSettings.View.EntityItem
    styles:
      - Background=#0373FC
      - Foreground=White
  - target: Microsoft.UI.Xaml.Controls.NavigationView#PermanentNavigationView
    styles:
      - Background=#03ADFC
      - Foreground=White
  - target: ContentPresenter
    styles:
      - Foreground=Black
  - target: ContentPresenter#SubtitleContent
    styles:
      - Foreground=White
  - target: StackPanel#BackgroundStackPanel
    styles:
      - Background=Blue
  - target: TextBlock#TitleContent
    styles:
      - Foreground=White
  - target: ContentPresenter#TitleContent
    styles:
      - Foreground=White
  - target: ContentPresenter#IconContentPresenter
    styles:
      - Foreground=White
  - target: Button#ContainerButton
    styles:
      - Background=Blue
  - target: SystemSettings.View.ReactNativeExperienceViewControl
    styles:
      - Background=Blue
  - target: SystemSettings.View.TwoSegmentsHeroUserControl#OneSegmentHeroEntityItemUserControl
    styles:
      - Background=DeepSkyBlue
  - target: SystemSettings.View.SettingsNavigationViewItem > Grid#NVIRootGrid > NavigationViewItemPresenter > Grid#LayoutRoot > Grid#PresenterContentRootGrid > Grid#ContentGrid > ContentPresenter > TextBlock
    styles:
      - Foreground=White
themeResourceVariables:
  - ''
```
</details>