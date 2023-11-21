---
label: SetUp Flocks
order: 99
icon: "/static/play.png"
---

<style>
    .sample {
        text-align: center;
        color: #1956AF;
        border-radius: 10px;
        background-color: #ff9500;
        border: 1px solid #1956AF;
        padding-top: 20px;
        margin-bottom: 20px;
    }
</style>

# Simple Crow Dock 


:::sample
Go to :  `Content/FlockSystem/Blueprints/BP_CrowDock_Simple`
:::


`Drag To Level` -> Drag and drop the BP system on desired area.

`Open Details Panel,Select NiagaraFX` -> Child FX object simulate on local space to world space of BP_CrowDock_Simple

`Quick Set NiagaraFX` -> Set Spawn Rate,Scale sizes, and select a static mesh


:::sample
Go to :  `Content/FlockSystem/Blueprints/BP_CrowSpline`
:::

`Drag To Level` -> Drag and drop the BP system on desired area.
`Set Spline` -> Drag and drop spline points.

Go to :  `Content/FlockSystem/Niagaras/NS_SplineFlock`


`Add NiagaraFX` -> Add NS_SplineFlock on the current level

`Drag For Spline Initialization` -> Drag NS_SplineFlock object under BP_CrowSpline

`Reset Location` -> Set child NS_SplineFlock location to (0,0,0)

`Quick Set NiagaraFX` -> Set Spawn Rate,Scale sizes, and select a static mesh
