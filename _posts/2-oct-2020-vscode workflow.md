## first steps in tooling up vscode for web dev
there are some requirements i want to achieve, essentially all of it as of now involves ide integration with build tasks
that triggers some process. vscode tutorial for integrating sass demonstrates how to create a build task through using json for
specification/configuration. the extended part of the tutorial then goes on about using gulp. I know a bit about gulp, my first most
immediate concern is whether gulp watching ability has anything like a cache hit-miss feature where it wont execute the full pipeline
unless something changes. come to think of it, this is a bit difficult because it would require gulp to understand sass/css paths of
dependency, especially given that sass supports includes. 

### react workflow research
i haven't done any research into established workflows but i sort of know what i want to achieve in my workflow, which is to separate the designing of the ui from the implementation of interactions/react stuff. in this case the labour in this part of the workflow contributes only in making design decisions but also towards the final css of the component/thing and html. 

1. have some sort of capacity to work on react components as just sass+html and view them through a live-preview feature. (the mocking aspect of the ui)

resources
1. [vscode sass/lean tutoral](https://code.visualstudio.com/docs/languages/css)
