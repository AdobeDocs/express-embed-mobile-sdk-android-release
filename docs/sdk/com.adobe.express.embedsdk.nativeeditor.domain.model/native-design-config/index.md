//[sdk](../../../index.md)/[com.adobe.express.embedsdk.nativeeditor.domain.model](../index.md)/[NativeDesignConfig](index.md)

# NativeDesignConfig

class [NativeDesignConfig](index.md)&lt;[D](index.md) : [NativeDocConfig](../native-doc-config/index.md), [A](index.md) : [NativeAppConfig](../native-app-config/index.md)&gt;(val docConfig: [D](index.md), val appConfig: [A](index.md), val exportConfig: [NativeExportConfig](../native-export-config/index.md)? = null)

Consolidated configuration for native workflows, bundling document, app, and export settings into a single object (mirrors the com.adobe.express.embedsdk.DesignConfig pattern used by web workflows).

Generic type parameters preserve the concrete subtypes so callers can access subtype-specific properties (e.g. com.adobe.express.embedsdk.EditImageNativeAppConfig.shouldClose) without casting.

#### Parameters

androidJvm

| | |
|---|---|
| D | Concrete document configuration type. |
| A | Concrete application configuration type. |

## Constructors

| | |
|---|---|
| [NativeDesignConfig](native-design-config.md) | <br>constructor(docConfig: [D](index.md), appConfig: [A](index.md), exportConfig: [NativeExportConfig](../native-export-config/index.md)? = null) |

## Properties

| Name | Summary |
|---|---|
| [appConfig](app-config.md) | <br>val [appConfig](app-config.md): [A](index.md)<br>Callbacks, dismiss handler, and behaviour settings. |
| [docConfig](doc-config.md) | <br>val [docConfig](doc-config.md): [D](index.md)<br>Input document/asset for the workflow. |
| [exportConfig](export-config.md) | <br>val [exportConfig](export-config.md): [NativeExportConfig](../native-export-config/index.md)? = null<br>Export options rendered in the top bar. Pass null to use the default Save button. |
