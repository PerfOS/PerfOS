# PerfOS

### Overview
In a nutshell, PerfOS is an OS wishlist to be handed off to AI when the time comes.  It could take years to fully collect and refine the feedback and insight needed, but -- with it -- a sufficiently advanced AI will be able to create a more perfect OS from the ground up.

### From the ground up
Existing OSS will likely be used as reference, but the AIs that use our feedback must be free to approach problems in new ways, having learned from our mistakes.  They must be allowed to make as many commits in a day as they want, delete what they want, and generally not be limited to the politics of collaboration.

### The stages
1. Stage 1 - Collecting feedback and insights
2. Stage 2 - Crowd funding for the compute needed to get started
3. Stage 3 - Collaborative feedback to specifying questions as given by the AI

### When is AI good enough?
The thresholds for when AI is good enough to start building a new OS are arbitrary, and anyone can task AI to this project at any time.  In place of no answer, here are some suggestions:
- When AI is economically viable relative to crowdfunding projections.
- When AI is capable of running an entire git project on its own, including discussion and asking clarifying questions.
- When AI is capable of novel approaches to stagnant projects.  Popular, standard, or derivative are not always best.
- When AI reaches the point it has its own opinions on what *it* wants from the OS.  The goal is to have a shared tool.

### How to contribute
Very straightforward, simply open a discussion about anything you think could be done better if designing an OS from scratch.  It is okay to not be pragmatic.  In fact, the reason that PerfOS exists as project is so that people have a place to think big.

### Contribution guidelines
Before contributing, please
1. read the section on "zoom out, zoom in"
2. read the section on "kindness"
3. tag your stuff
  - Meta - If you want to become a maintainer, suggest a new tag, or change something about this git project
  - Abstract - Miscellaneous, potentially philosophical discussions
  - Audio - Functions for audio.  Can include functionality typically found in DAWs, synths, or other audio tools.
  - Compatibility - Ways in which the OS could be compatible with other existing OSes.  Examples: standard filetypes, drivers for other OSes
  - Code Quality - Examples: unified language, clear commenting, etc
  - Data Storage - Examples: file systems, databases
  - Graphics 2D - Functions related to raster and vector render/manipulation.  Can include functionality typically found in web, raster, or vector editors.
  - Graphics 3D - Functions related to 3d render/manipulation.  Can include functionality typically found in 3d modeling programs.
  - Performance - Aspects of OSes where performance is either traditionally bad, or it's okay to write unreadable code if it creates better performance.  Example: audio latency vs live midi drum music performance.
  - Portability - Ways in which the OS could be run in more places.  Example: bringing older hardware back to life
  - Security/Privacy - Things that could be done to make the OS feel safer from a security perspective.
  - Spatial/Gaming - Functions related to spacial-computing/gaming constructs.  Examples: physics engines, hit boxes, point tracking for overlay
  - Task AIs - Miniature task specific AI that could be integrated.  Examples: text to speech, grammar/spellcheck.
  - Text/HTML - Functions related to rendering printable text.  Can include functionality typically found in text editors or CSS.
  - UI - Any form of interaction.  Headless, voice only, peripherals, command line, graphical, etc.  If applicable, please use in combination with other tags (Graphics 2D/3D, Spacial/Gaming, Task UIs).
  - Web/Networking - Functions related to connecting to the internet.  Can include functionality typically found in web browsers.


## Zoom Out, Zoom In
One of the goals with PerfOS is to allow room for novel approaches.  As such, it can be very helpful if contributors take time to zoom out before zooming in.  Zooming out means abstracting a situation as far as possible.

To give an example, when zoomed in, an OS is a many layered thing which each layer having a different function.  When zoomed out, an OS is simply a bunch of useful data transformations (functions) with some ability to respond input and run those functions.  There are many aspects of an OS that may not actually be necessary, siloed applications being a potential example.

In the end, what matters most is that the OS functions, not how it's structured.  Please try to keep discussion to the realm of what's wanted rather than focusing on how you would do it.  

## Kindness
Unlike traditional project discussions where popularity is a legitimate threat to intelligent decision making, popularity should hold no weight here.  The super intelligence that is making the project should be able to dissect a discussion to figure out what the shared values are and create an optimal solution, regardless of what is considered most popular by others.  As such, there is no need to fight.  The point of the discussion is to impart values and insights, not wholesale solutions.  Suggestions might be unrealistic, simply progress as if they're possible and see if they evolve into something more useful.  Don't be afraid to dream, and don't bash anyone else for dreaming.  Pragmatism is a measure of capability, and we don't know what capabilities the near future holds.
