# CodePipeline Pipeline Stages Actions InputArtifacts<a name="aws-properties-codepipeline-pipeline-stages-actions-inputartifacts"></a>

`InputArtifacts` is a property of the [CodePipeline Pipeline Stages Actions](aws-properties-codepipeline-pipeline-stages-actions.md) property that specifies an artifact that the CodePipeline action works on, such as a test or build artifact\.

## Syntax<a name="w13ab1c21c10c81c17c45b5"></a>

### JSON<a name="aws-properties-codepipeline-pipeline-stages-actions-inputartifacts-syntax.json"></a>

```
{
  "[Name](#cfn-codepipeline-pipeline-stages-actions-inputartifacts-name)" : String
}
```

### YAML<a name="aws-properties-codepipeline-pipeline-stages-actions-inputartifacts-syntax.yaml"></a>

```
[Name](#cfn-codepipeline-pipeline-stages-actions-inputartifacts-name): String
```

## Properties<a name="w13ab1c21c10c81c17c45b7"></a>

`Name`  <a name="cfn-codepipeline-pipeline-stages-actions-inputartifacts-name"></a>
The name of the artifact that the CodePipeline action works on, such as `My App`\.The input artifact of an action must match the output artifact from any preceding action\.  
*Required*: Yes  
*Type*: String