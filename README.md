# FreshPlantUML

This is a refreshing color scheme for PlantUML.

(* We are currently specializing in sequence diagrams, so we have not checked it with other diagrams)

---
## Sequence
![Example](/out/example/test.svg)

```pu
@startuml
!include pu.conf // Load config

// Contents

@enduml
```

---
## WBS

```pu
@startwbs wbs
!include wbsTheme.pu

// Contents

@endwbs
```

![Example](/out/example/wbs.svg)

---
## Mindmap

```pu
@startmindmap mindmap
!include wbsTheme.pu

// Contents

@endmindmap
```
![Example](/out/example/mindmap.svg)
