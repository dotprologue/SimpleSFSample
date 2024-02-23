# SimpleSFSample

 A sample system for ScenarioFlow with practical functions. It contains functions like displaying dialogue lines, replacing character images, moving characters, and so on, but dosn't contain functions for save.

To run example:

+ Open `SimpleSFSample/SimpleSFSampleScene`
+ Make sure that the scenario script `Quiz` is attached to the `ScenarioScript` property in the `ObjectBuilder` object
    + There are the three available scripts in the `SimpleSFSample/Stories` folder, `Quiz(SFText)`, `Quiz(Composite)`, `Quiz_Alt(SFText)` by default. You can attach another one instead
+ Enter the play mode


### CAUTION

+ This sample will cause conflict with [SavableSFSample](https://github.com/dotprologue/SavableSFSample.git). If you have already imported SavableSFSample, you have to delete it before importing this sample or create a new Unity project.
+ All the scripts in SimpleSFSample are published under the MIT license, so you can use them freely as long as you follow the license. However, the use of the images used in the sample, for example, images of Sheena, Rio, and other UIs, is permitted only for private use intended for learning purposes or citation.

![](./Movies/Scene.gif)