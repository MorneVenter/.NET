<img align="left" width="116" height="116" src="../pezza-logo.png" />

# &nbsp;**Pezza - Phase 4 - Step 1** [![.NET Core - Phase 4 - Step 1](https://github.com/entelect-incubator/.NET/actions/workflows/dotnet-phase4-step1.yml/badge.svg)](https://github.com/entelect-incubator/.NET/actions/workflows/dotnet-phase4-step1.yml)

<br/><br/>

Standards

## **Install StyleCop**

[Overview](https://github.com/StyleCop/StyleCop)

Add Phase 4/Data/StyleCopRuleSet.ruleset to your Solution

![StyleCopRuleSet](Assets/2021-01-15-10-25-17.png)

Install StyleCop.Analyzers Nuget Package to all Projects

![StyleCop.Analyzers](Assets/2021-01-15-10-26-37.png)

Add the StyleCop Rule Set in every project file.

![](Assets/2021-01-15-10-30-33.png)

```
<CodeAnalysisRuleSet>$(SolutionDir)\StyleCopRuleSet.ruleset</CodeAnalysisRuleSet>
```

Fix build errors

Move to Step 2
[Click Here](https://github.com/entelect-incubator/.NET/tree/master/Phase%204/Step%202) 