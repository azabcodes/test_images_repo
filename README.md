# 🖼️ Test Images Repository

This repository contains a collection of **sample images** for testing, prototyping, or development purposes.

## 📁 Structure

```
/images
  1.jpg
  2.jpg
  ...
  ....jpg
```

* Images are stored in the `images` folder.
* Each image can be accessed via **raw GitHub URLs** for easy use in your projects.

## 🌐 Accessing Images via URL

You can use the images directly in your Flutter, web, or other projects. Example:

```dart
final imageUrl = 'https://raw.githubusercontent.com/azabcodes/test_images_repo/main/images/1.jpg';

  static List<String> imageUrls = List.generate(
    30,
    (index) {
      final coreUrl='https://raw.githubusercontent.com/azabcodes';
      return '$coreUrl/test_images_repo/main/images/${index + 1}.jpg';
    },
  );
```

* To access other images, just change the number at the end (`1.jpg` → `2.jpg`, etc.).

## ⚡ Usage Ideas

* Testing **image grids** or **carousel views**.
* Experimenting with **image shaders** or **filters**.
* Populating demo projects with real content without needing to download assets locally.

## 📌 Notes

* Currently, the repository contains 60 sample images.
* More images can be added later by following the same naming pattern.
