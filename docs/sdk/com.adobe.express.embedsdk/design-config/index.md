//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[DesignConfig](index.md)

# DesignConfig

\
open class [DesignConfig](index.md)(val docConfig: [BaseDocConfig](../base-doc-config/index.md)? = null, val appConfig: [BaseAppConfig](../base-app-config/index.md)? = null, val exportConfig: [ExportConfig](../export-config/index.md)? = null, val containerConfig: [ContainerConfig](../container-config/index.md)? = null)

Complete design configuration combining document, application, export, and container settings.

## Constructors

| | |
|---|---|
| [DesignConfig](design-config.md) | <br>constructor(docConfig: [BaseDocConfig](../base-doc-config/index.md)? = null, appConfig: [BaseAppConfig](../base-app-config/index.md)? = null, exportConfig: [ExportConfig](../export-config/index.md)? = null, containerConfig: [ContainerConfig](../container-config/index.md)? = null) |

## Properties

| Name | Summary |
|---|---|
| [appConfig](app-config.md) | <br>open val [appConfig](app-config.md): [BaseAppConfig](../base-app-config/index.md)? = null<br>Application-specific configuration and callbacks |
| [containerConfig](container-config.md) | <br>open val [containerConfig](container-config.md): [ContainerConfig](../container-config/index.md)? = null<br>Webview container display and behavior settings |
| [docConfig](doc-config.md) | <br>open val [docConfig](doc-config.md): [BaseDocConfig](../base-doc-config/index.md)? = null<br>Document configuration specifying input assets or documents |
| [exportConfig](export-config.md) | <br>open val [exportConfig](export-config.md): [ExportConfig](../export-config/index.md)? = null<br>Export options and actions available to users |
