
# Android SDK (android-sdk)

Install Android SDK `cmdline-tools`, `platform-tools`, and, `build-tools`.

## Example Usage

```json
"features": {
    "ghcr.io/ThomasIAm/devcontainer-features-android-sdk/android-sdk:1": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| platform | SDK platform version | string | 34 |
| build_tools | SDK build-tools version | string | 34.0.0 |
| base_packages | packages will override default packages, split by space | string | - |
| extra_packages | extra packages, split by space | string | - |
| java_version | OpenJDK version to install (e.g., 11, 17, 20) | string | 21 |



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/ThomasIAm/devcontainer-features-android-sdk/blob/main/src/android-sdk/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
