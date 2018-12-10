# image_components
Reusable components to do with image manipulation

ScaleImage.xaml
- in_OriginalImage <Image> - The original Image object.
- in_Scale <Int32> - The desired, postive scale factor.
- out_ScaledImage <Image> - The scaled Image object.

HighResScreenshot.xaml
- in_UiElement <UiElement> - The UiElement to be captured. If none is specified, the robot takes a screenshot of the entire desktop.
- in_Resolution <Int32> - The desired screenshot resolution. If none is specified, the default system resolution is used.
- in_Scale <Int32> - The desired, positive scale factor. If specified, ScaleImage.xaml is a dependency.
- in_SavePath <String> - The filepath to save the screenshot.
