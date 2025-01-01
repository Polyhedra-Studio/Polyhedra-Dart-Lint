## 1.1.0 (2025-01-01)
- [PKG] Updated lints to 5.1.1.
- [PKG] Updated flutter_lints to 5.0.0.
- [META] Updated base SDK to 3.6.
- [ADD] Added `unintended_html_in_doc_comment` from lints 5.1.0.
- [MOD] Turned off secure_pubspec_urls. This is generally a good idea, but we use a local pub repositories for some internal packages.
- [MOD] Turned always_use_package_imports to false. While typically a good idea, relative pathing is better for modules or tightly coupled files. What would be ideal is this rule would be false for children or parents of a file, but enforced for larger degrees of difference. Unfortunately, this rule is all or nothing.

## 1.0.3
- [MOD] Turned off a few new rules that turned out to be more overzealous than needed

## 1.0.2
- [META] Updating `pubspec.yaml` to have more accurate metadata

## 1.0.1
- [FIX] Fixed multiple imports

## 1.0.0

- Initial version.
