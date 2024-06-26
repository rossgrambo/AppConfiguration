# featuremanagement

[Source code][source_code] | [Samples][samples]

## 1.0.0b1 - May 24, 2024

### Enhancement

Initial release of the feature management support for Python. Note that, version 1.2.0 or later of `azure-appconfiguration-provider` is required for loading feature flags from Azure App Configuration.

* Loading of feature flags from a dictionary.
* Support for basic feature flags with boolean states.
* Support for feature filters including built-in filters `TimeWindowFilter` and `TargetingFilter`.

[samples]: https://github.com/microsoft/FeatureManagement-Python/tree/main/samples
[source_code]: https://github.com/microsoft/FeatureManagement-Python
