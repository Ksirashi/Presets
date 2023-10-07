**Boss 1**

Staffs and tiles
```
~Lv2~{"Name":"The Lunar Subterrain Boss 1","Group":"","ZoneLockH":[1164],"ElementsL":[{"Name":"Staff 1 - cast","type":3,"refY":28.0,"offY":-28.0,"radius":4.0,"color":2348810495,"refActorNPCNameID":12501,"refActorRequireCast":true,"refActorCastId":[34783,34789,35254],"refActorComparisonType":6,"includeRotation":true},{"Name":"Staff 2 - cast","type":3,"refY":28.0,"offY":-28.0,"radius":4.0,"color":2348810495,"refActorNPCNameID":12501,"refActorRequireCast":true,"refActorCastId":[34783,34789,35254],"refActorComparisonType":6,"includeRotation":true,"AdditionalRotation":1.5707964},{"Name":"Plates","type":3,"refY":4.0,"offY":-4.0,"radius":4.0,"refActorNPCNameID":12500,"refActorRequireCast":true,"refActorCastId":[34787],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true}]}
```
Trigger for staffs
```
~Lv2~{"Name":"The Lunar Subterrain Boss 1 staff stuff","Group":"","ZoneLockH":[1164],"ElementsL":[{"Name":"Staff 1 - not cast","type":3,"refY":28.0,"offY":-28.0,"radius":4.0,"color":671154152,"refActorNPCNameID":12501,"refActorRequireCast":true,"refActorCastReverse":true,"refActorCastId":[34783,34789,35254],"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true},{"Name":"Staff 2 - not cast","type":3,"refY":28.0,"offY":-28.0,"radius":4.0,"color":671154152,"refActorNPCNameID":12501,"refActorRequireCast":true,"refActorCastReverse":true,"refActorCastId":[34783,34789,35254],"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true,"AdditionalRotation":1.5707964}],"UseTriggers":true,"Triggers":[{"Type":3,"Duration":10.0,"Match":"(12501>35254)"},{"Type":3,"Duration":11.0,"Match":"(12501>34789)"}]}
```

**Boss 2**

Only pillars for now. I'll be doing dashes some time later, but it's a tedious process as it requires manually drawing each pattern, so may take some time.
```
~Lv2~{"Name":"The Lunar Subterrane Boss 2 Pillars","Group":"EW Dungeons","ZoneLockH":[1164],"ElementsL":[{"Name":"Pillars","type":3,"refY":39.5,"radius":5.0,"color":671154152,"refActorComparisonType":7,"includeRotation":true,"refActorVFXPath":"vfx/common/eff/z5d2_stlp2_c0x.avfx","refActorVFXMin":5000,"refActorVFXMax":999000}],"Freezing":true,"FreezeFor":16.0,"IntervalBetweenFreezes":16.0}
```

**Boss 3**

All mechanics except that spiral thingy, not sure how to detect patterns yet, may look into it later.
```
~Lv2~{"Name":"The Lunar Subterrane Boss 3","Group":"EW Dungeons","ZoneLockH":[1164],"ElementsL":[{"Name":"Orbs 1st cast","type":1,"radius":11.0,"color":1677721855,"refActorNPCNameID":12585,"refActorRequireCast":true,"refActorCastId":[35006],"refActorComparisonType":6,"Filled":true},{"Name":"Twilight Phase","type":3,"refY":20.0,"offY":-20.0,"radius":10.0,"refActorNPCNameID":12584,"refActorRequireCast":true,"refActorCastId":[34997,34998,34999,35000,36055,36056],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true},{"Name":"Twilight Phase part 2","type":1,"radius":25.0,"color":1677721855,"refActorNPCNameID":12584,"refActorRequireCast":true,"refActorCastId":[35001,35002],"refActorComparisonType":6,"onlyUnTargetable":true,"Filled":true},{"Name":"Cleave Death's Journey","type":4,"radius":20.0,"coneAngleMin":-15,"coneAngleMax":15,"refActorNPCNameID":12584,"refActorRequireCast":true,"refActorCastId":[34996],"refActorComparisonType":6,"includeRotation":true,"Filled":true},{"Name":"Cleave Hard Slash","type":4,"radius":40.0,"coneAngleMin":-45,"coneAngleMax":45,"refActorNPCNameID":12584,"refActorRequireCast":true,"refActorCastId":[35009,35864],"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{}]}
```
Trigger for Orbs
```
~Lv2~{"Name":"The Lunar Subterrane Boss 3 trigger for Orbs","Group":"EW Dungeons","ZoneLockH":[1164],"DCond":5,"ElementsL":[{"Name":"Orbs 1","type":1,"offX":12.8,"radius":9.0,"color":1677721855,"refActorNPCNameID":12585,"refActorComparisonType":6,"includeRotation":true,"Filled":true},{"Name":"Orbs 2","type":1,"offX":-12.8,"radius":9.0,"color":1677721855,"refActorNPCNameID":12585,"refActorComparisonType":6,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Match":"(12585>35006)","MatchDelay":10.0}]}
```
