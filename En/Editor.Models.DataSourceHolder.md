
# DataSourceHolder Class

<em><small>**Assembly:** CodeEffects.Rule.Editor.dll</small></br>
<small>**Namespace**: `CodeEffects.Rule.Editor.Models`</small></em>

## Summary

This class is used to hold named instances of [`GetDataSourceDelegate`](https://codeeffects.com/decision-automation/rule-editor-models-getdatasourcedelegate) types utilized by custom [Dynamic Menu Data Sources](https://codeeffects.com/decision-automation/business-rules-dynamic-menu-data-sources).

## Syntax

```csharp
public class DataSourceHolder
```

## Properties

<div class="members">

- ### Name<br/>
	<small>Type: `System.String`</small>

	Gets or sets the unique names of custom Dynamic Menu Data Sources used by the [`FieldAttribute`](https://codeeffects.com/decision-automation/rule-common-attributes-field), [`ReturnAttribute`](https://codeeffects.com/decision-automation/rule-common-attributes-return), and [`ParameterAttribute`](https://codeeffects.com/decision-automation/rule-common-attributes-parameter).

- ### Delegate<br/>
	<small>Type: [`CodeEffects.Rule.Editor.Models.GetDataSourceDelegate`](https://codeeffects.com/decision-automation/rule-editor-models-getdatasourcedelegate)</small>

	Gets or sets the signature of a method that takes no parameters and returns a collection of [`DataSourceItem`](https://codeeffects.com/decision-automation/rule-editor-client-datasourceitem) used by the custom [Dynamic Menu Data Sources](https://codeeffects.com/decision-automation/business-rules-dynamic-menu-data-sources) feature.

</div>