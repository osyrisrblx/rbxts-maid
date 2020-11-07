# rbxts-maid
Quenty's [Maid](https://github.com/Quenty/NevermoreEngine/blob/version2/Modules/Shared/Events/Maid.lua) class with types!

```TS
import Maid from "@rbxts/maid";

const maid = new Maid();
maid.GiveTask(() => print("Clean me!"));
maid.GiveTask(game.Workspace.ChildAdded.Connect(() => print("Child Added!")));
maid.GiveTask(new Maid());
maid.GiveTask({ Destroy() {} });
maid.DoCleaning();
```
