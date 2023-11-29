# DuoIcons Flutter Library

## Overview:
DuoIcons is a dynamic Flutter library designed to revolutionize icon integration in Flutter applications. This library doesn't just offer a vast collection of icons; it brings a new dimension with its unique two-tone/color feature, allowing developers to infuse even more personality and creativity into their app designs. Whether you're building a mobile app, a web application, or a desktop solution, DuoIcons provides an extensive set of icons with the added flexibility of two-tone coloring.

![img.png](assets%2Fimg%2Fimg.png)

## Key Features:

- Extensive Icon Set: DuoIcons includes an expansive set of icons covering diverse categories such as general UI, social media, communication, navigation, and more. This ensures developers have access to a rich selection of icons for various use cases.

- Two-Tone/Color Option: Elevate your app's visual appeal by leveraging DuoIcons' distinctive two-tone/color feature. Each icon can be customized with two different colors, allowing for creative and eye-catching designs that seamlessly integrate with your application's color scheme.

- Customization Options: Tailor the appearance of icons to match your app's visual identity. DuoIcons provides customization options such as color, size, and style variations, empowering you to create a cohesive and visually stunning user interface.

- Easy Integration: Integration of DuoIcons into your Flutter project is straightforward. Simply import the library, choose the desired icon, and customize it as needed. The library is designed to be developer-friendly, ensuring a smooth integration process.

- Responsive Design: DuoIcons icons are designed with responsiveness in mind. Whether your app is running on a small mobile screen or a large desktop display, these icons maintain their visual appeal and clarity, ensuring a consistent user experience across different devices.

- Regular Updates: Stay up-to-date with the latest design trends and emerging icons. DuoIcons is committed to providing regular updates, introducing new icons and improvements to enhance the library's capabilities.

## Getting Started:

### Install the Library:

```yaml
dependencies:
  flutter_duoicons: ^0.0.1
```

### Import and Use:

```dart
import 'package:duo_icons/duo_icons.dart';

// ...

Icon(
  DuoIcons.home, // Replace with the desired icon
  color: Colors.blue, // Customize the primary color
  size: 32.0, // Customize the size
),
```

```dart
Icon(
  DuoIcons.settings, // Replace with another icon
  color: DuoIcons.twoToneColors(Colors.green, Colors.yellow), // Use two-tone coloring
  size: 32.0, // Customize the size
)
```
## Explore Documentation: 
Refer to the comprehensive documentation for detailed information on available icons, customization options, and best practices.

## Contribute:
DuoIcons is an open-source project, and contributions from the Flutter community are highly encouraged. 
If you have ideas for new icons, improvements, or bug fixes, feel free to contribute to the project on GitHub.

Elevate your Flutter app's visual appeal with DuoIcons – where icons meet simplicity, versatility, 
and the power of two-tone coloring!

## Credits

The icons used in this Flutter package were originally created by [Fernando R.](https://github.com/fernandcf) 
The original icons were designed for HTML and JavaScript libraries.

- Original Icons Repository: [duo-icons](https://github.com/fernandcf/duo-icons)
- Original Creator: [Fernando R.](https://github.com/fernandcf)
