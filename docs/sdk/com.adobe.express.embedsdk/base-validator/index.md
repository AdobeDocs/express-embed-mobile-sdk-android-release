//[sdk](../../../index.md)/[com.adobe.express.embedsdk](../index.md)/[BaseValidator](index.md)

# BaseValidator

\
abstract class [BaseValidator](index.md)

## Constructors

| | |
|---|---|
| [BaseValidator](base-validator.md) | <br>constructor() |

## Functions

| Name | Summary |
|---|---|
| [validate](validate.md) | <br>abstract fun &lt;[A](validate.md) : [ActionIntent](../action-intent/index.md), [T](validate.md) : [DesignConfig](../design-config/index.md)&gt; [validate](validate.md)(intent: [A](validate.md), input: [T](validate.md)) |
| [validateAuthOption](validate-auth-option.md) | <br>abstract fun [validateAuthOption](validate-auth-option.md)(authOption: [AuthOption](../auth-option/index.md)) |
| [validateConfigParams](validate-config-params.md) | <br>abstract fun &lt;[T](validate-config-params.md) : [ConfigParamsBase](../config-params-base/index.md)&gt; [validateConfigParams](validate-config-params.md)(configParams: [T](validate-config-params.md)) |
| [validateHostInfo](validate-host-info.md) | <br>abstract fun &lt;[T](validate-host-info.md) : [HostInfoSpecifiedBase](../host-info-specified-base/index.md)&gt; [validateHostInfo](validate-host-info.md)(hostInfo: [T](validate-host-info.md)) |
