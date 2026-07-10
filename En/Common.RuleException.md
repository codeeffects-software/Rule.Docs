
# RuleException Class

<em><small>**Assembly:** CodeEffects.Rule.Common.dll</small></br>
<small>**Namespace**: `CodeEffects.Rule.Common`</small></em>

## Summary

Provides the base class for all rule-related exception types used by both the [Rules Engine](https://codeeffects.com/decision-automation/business-rule-evaluation) and the [Rule Editor](https://codeeffects.com/decision-automation/business-rule-editor).

## Syntax

```csharp
public class RuleException : System.Exception
```

## Inheritance

- `System.Object`
	- `System.Exception`
		- **CodeEffects.Rule.Common.RuleException**
			- [`CodeEffects.Rule.Editor.InvalidRuleException`](https://codeeffects.com/decision-automation/rule-editor-invalidruleexception)
			- [`CodeEffects.Rule.Editor.MalformedXmlException`](https://codeeffects.com/decision-automation/rule-editor-malformedxmlexception)
			- [`CodeEffects.Rule.Editor.SourceException`](https://codeeffects.com/decision-automation/rule-editor-sourceexception)
			- [`CodeEffects.Rule.Engine.EvaluationException`](https://codeeffects.com/decision-automation/rule-engine-evaluationexception)