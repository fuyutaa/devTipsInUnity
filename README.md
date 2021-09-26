# devTipsInUnity
 some useful tricks

Hiding or Disabling inspector properties :

[Header("Resources")]
public bool ConsumeResources = true;
 
[ConditionalHide("ConsumeResources")]
public bool DestroyOnResourcesDepleted = true;
[ConditionalHide("ConsumeResources")]
public float ResourceAmount = 100.0f;
[ConditionalHide("ConsumeResources")]
public DemoClass AnotherExampleDataClass = new DemoClass();