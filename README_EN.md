Chemical Titration Simulator
A free, browser-based acid–base titration simulator built with Unity (WebGL). It turns abstract neutralization reactions and titration curves into something you can see and interact with, lowering the learning curve for chemistry.
Live Demo
No installation needed — just open it in your browser:
https://asd9801479-commits.github.io/Chemistry-Experiment-Simulation/

The first load takes a few seconds. A brief blank screen while the progress bar runs is normal.

About
This is a free chemistry experiment simulator I built on my own. I made it because chemistry felt too abstract to me, and I wanted something that lowers the learning curve. Since I don't know any programming languages, I created this simple simulator with the help of Claude AI for now. Feedback from users is very welcome!
This project is a graduation project, made to present acid–base titration in a visual, interactive way so learners can build an intuitive feel for how pH changes and where the equivalence point lies.
Features

Real-time titration curve — plots pH against added volume as you titrate, with the equivalence point marked.
Animated burette and beaker — graduations, stopcock, and rising/falling liquid levels, with the solution shifting color as pH changes.
Hold-to-add — press and hold an add button to dispense rapidly, no frantic clicking required.
Guided tutorial — a 5-step walkthrough on your first visit.
Endpoint hints and result summary — a heads-up as you approach the endpoint, and a summary panel when the experiment is complete.

How to Use
ControlDescription+1.0 mL / +0.1 mLAdd base (coarse / fine adjustment)-1.0 mL / -0.1 mLRemove basePress and hold a buttonContinuously add / removeVolume sliderDrag to set the added volume directlyResetClear the experiment and start overpH value / Added volumeLive readout of the current pH and amount of base added
The Chemistry
The beaker holds a hydrochloric acid (HCl) solution, and sodium hydroxide (NaOH) is added dropwise through the burette to neutralize it. Both are a strong acid / strong base, reacting as:
HCl + NaOH → NaCl + H₂O

Both acid and base are set to 0.1 M.
The solution starts acidic with a low pH; as base is added, the pH rises slowly.
Near the equivalence point (where acid and base exactly neutralize), the pH jumps sharply over a very small change in volume — the defining feature of a titration curve.
Past the equivalence point, adding more base turns the solution basic, and the pH approaches that of the base itself.

By adjusting the added volume yourself and watching the curve go "flat → steep → flat," you get an intuitive sense of why hitting the titration endpoint precisely matters so much.
Development

Engine: Unity 2022.3.62f3
Platform: WebGL
Tooling: Independently conceived and designed by the author, with the code written with the help of Claude AI.

Author & License

Author: Wen-Chang Chen
Student ID: B0214634
Institution: Department of Chemistry, Chinese Culture University
Completed: (date)
License: Released under the MIT License — free to use and modify, with attribution retained.
