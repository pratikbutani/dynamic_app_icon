# Dynamic App Icon

[![GitHub stars](https://img.shields.io/github/stars/lesnitsky/dynamic_app_icon.svg?style=social&hash=20230321)](https://github.com/lesnitsky/dynamic_app_icon)
[![Twitter Follow](https://img.shields.io/twitter/follow/lesnitsky_dev.svg?label=Follow%20me&style=social)](https://twitter.com/lesnitsky_dev)

Set any widget as an app icon! (macOS only)

## Installation

```sh
flutter pub add dynamic_app_icons
```

## Example

```dart
class Example extends StatelessWidget {
  const Example({super.key});

  @override
  Widget build(BuildContext context) {
    return const MaterialApp(
      home: AppIcon(
        icon: FlutterLogo(),
        child: Scaffold(
          body: Center(
            child: Text('Flutter logo is now your app icon!'),
          ),
        ),
      )
    );
  }
}
```

## Demo

https://user-images.githubusercontent.com/6261302/227051495-a683add8-8f5a-4bb3-a672-86f865122548.mov

---

Check out [example](https://github.com/lesnitsky/dynamic_app_icon/tree/main/example) for more details

## License

MIT

[![GitHub stars](https://img.shields.io/github/stars/lesnitsky/dynamic_app_icon.svg?style=social&hash=20230321)](https://github.com/lesnitsky/dynamic_app_icon)
[![Twitter Follow](https://img.shields.io/twitter/follow/lesnitsky_dev.svg?label=Follow%20me&style=social)](https://twitter.com/lesnitsky_dev)
