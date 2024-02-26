Ice pillars and Fire spheres for **Boss 1 and 2**
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 1-2","Group":"EW Dungeons 81-89","ZoneLockH":[974],"ElementsL":[{"Name":"Ice pillar","type":3,"refY":40.0,"radius":2.0,"fillIntensity":0.4,"originFillColor":1157628159,"endFillColor":1157628159,"refActorNPCNameID":10397,"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true},{"Name":"Spheres 1","type":3,"refY":40.0,"offY":-40.0,"radius":2.0,"color":2516582655,"fillIntensity":0.3,"originFillColor":1006633215,"endFillColor":1006633215,"refActorNPCNameID":10395,"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true},{"Name":"Spheres 2","type":3,"refY":40.0,"offY":-40.0,"radius":2.0,"color":2516582655,"fillIntensity":0.3,"originFillColor":1006633215,"endFillColor":1006633215,"refActorNPCNameID":10395,"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true,"AdditionalRotation":1.5707964}],"UseTriggers":true,"Triggers":[{"Type":3,"Duration":5.0,"MatchIntl":{"En":"The ice pillar uses Pillar Pierce."}},{"Type":3,"Duration":5.0,"MatchIntl":{"En":"Dequeued message: The pyric sphere uses Pyric Sphere."}}]}
```


Triggers for Hide and Seek for **Boss 1**
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 1 p1","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-143.97313,"refY":36.471935,"refZ":496.0,"offX":-144.0062,"offY":69.2698,"offZ":496.0,"radius":20.0}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":13.0,"Match":"MapEffect: 0, 1, 2","MatchIntl":{"En":"MapEffect: 0, 1, 2"}}]}
```
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 1 p2","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-133.21559,"refY":42.761444,"refZ":496.0,"offX":-159.95444,"offY":58.243256,"offZ":496.0,"radius":20.0}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":13.0,"Match":"MapEffect: 1, 1, 2","MatchIntl":{"En":"MapEffect: 1, 1, 2"}}]}
```
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 1 p3","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-154.68367,"refY":42.45824,"refZ":496.0,"offX":-124.944756,"offY":59.502445,"offZ":496.85007,"radius":20.0}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":13.0,"Match":"MapEffect: 0, 16, 32","MatchIntl":{"En":"MapEffect: 0, 16, 32"}}]}
```
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 1 p4","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-144.01372,"refY":61.506413,"refZ":496.0,"offX":-143.95804,"offY":25.913273,"offZ":496.0,"radius":20.0}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":13.0,"Match":"MapEffect: 1, 16, 32","MatchIntl":{"En":"MapEffect: 1, 16, 32"}}]}
```
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 1 p5","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-154.79306,"refY":55.352554,"refZ":496.0,"offX":-127.487,"offY":39.549908,"offZ":496.0,"radius":20.0}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":13.0,"Match":"MapEffect: 0, 128, 256","MatchIntl":{"En":"MapEffect: 0, 128, 256"}}]}
```
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 1 p6","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-132.97176,"refY":54.778603,"refZ":496.0,"offX":-166.59285,"offY":35.390625,"offZ":496.0,"radius":20.0}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":13.0,"Match":"MapEffect: 1, 128, 256","MatchIntl":{"En":"MapEffect: 1, 128, 256"}}]}
```


Fire breath for **Boss 2**
```
~Lv2~{"Name":"Ktisis Hyperboreia Boss 2 fire breath","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"fire front","type":4,"radius":20.0,"coneAngleMin":-60,"coneAngleMax":60,"originFillColor":1677721855,"endFillColor":1677721855,"refActorComparisonType":7,"includeRotation":true,"onlyVisible":true,"refActorVFXPath":"vfx/common/eff/m0709_fire_stlp_c0d1.avfx","refActorVFXMin":6000,"refActorVFXMax":30000},{"Name":"fire front 2","type":4,"radius":20.0,"coneAngleMin":-60,"coneAngleMax":60,"originFillColor":1677721855,"endFillColor":1677721855,"refActorComparisonType":7,"includeRotation":true,"onlyVisible":true,"refActorVFXPath":"vfx/common/eff/m0709_fire_stlp_c2d1.avfx","refActorVFXMin":6000,"refActorVFXMax":30000},{"Name":"fire right","type":4,"radius":20.0,"coneAngleMin":60,"coneAngleMax":180,"originFillColor":1677721855,"endFillColor":1677721855,"refActorComparisonType":7,"includeRotation":true,"onlyVisible":true,"refActorVFXPath":"vfx/common/eff/m0709_fire_stlp_c1d1.avfx","refActorVFXMin":6000,"refActorVFXMax":30000},{"Name":"fire right 2","type":4,"radius":20.0,"coneAngleMin":60,"coneAngleMax":180,"refActorComparisonType":7,"includeRotation":true,"onlyVisible":true,"refActorVFXPath":"vfx/common/eff/m0709_fire_stlp_c4d1.avfx","refActorVFXMin":6000,"refActorVFXMax":30000},{"Name":"fire left 1","type":4,"radius":20.0,"coneAngleMin":-180,"coneAngleMax":-60,"originFillColor":1677721855,"endFillColor":1677721855,"refActorComparisonType":7,"includeRotation":true,"onlyVisible":true,"refActorVFXPath":"vfx/common/eff/m0709_fire_stlp_c5d1.avfx","refActorVFXMin":6000,"refActorVFXMax":30000},{"Name":"fire left 2","type":4,"radius":20.0,"coneAngleMin":-180,"coneAngleMax":-60,"originFillColor":1677721855,"endFillColor":1677721855,"refActorComparisonType":7,"includeRotation":true,"onlyVisible":true,"refActorVFXPath":"vfx/common/eff/m0709_fire_stlp_c3d1.avfx","refActorVFXMin":3000,"refActorVFXMax":30000}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":10.7,"Match":"(10398>25734)","MatchDelay":0.3},{"Type":2,"Duration":10.7,"Match":"(10398>25736)","MatchDelay":0.3},{"Type":2,"Duration":10.7,"Match":"(10398>25735)","MatchDelay":0.3}]}
```


**Boss 3**
```
~Lv2~{"Name":"Ktisis Hyperboreia Karukeion","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":"Karukeion","type":3,"refY":42.0,"offY":2.0,"radius":5.0,"fillIntensity":0.4,"originFillColor":570425599,"endFillColor":570425599,"refActorNPCNameID":10494,"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true,"FillStep":1.0}],"UseTriggers":true,"Triggers":[{"Duration":40.0}]}
```
```
~Lv2~{"Name":"Ktisis Hyperboreia Quadruple","Group":"EW Dungeons 81-89","ZoneLockH":[974],"DCond":5,"ElementsL":[{"Name":" |","type":2,"refY":-70.0,"refZ":-1.4151809E-13,"offY":-30.0,"offZ":1.4054511E-13,"radius":0.0},{"Name":"—","type":2,"refX":-20.0,"refY":-50.0,"refZ":1.9073489E-06,"offX":20.0,"offY":-50.0,"offZ":-1.335144E-05,"radius":0.0}],"UseTriggers":true,"Triggers":[{"Type":2,"TimeBegin":40.0,"Duration":30.0,"Match":"(10399>25894)","MatchIntl":{"En":"Hermes readies Quadruple."}}]}
```
