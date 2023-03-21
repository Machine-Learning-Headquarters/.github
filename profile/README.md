### Machine Learning Headquarters
#An exploration in democratizing machine learning technology and the infrastructures that support it.

#Goals and Ideals:  
  -Creating scaleable, affordable hardware for those interested in learning and contributing to machine learning.  
  -Open Source education and designs.  
  
  What is the first hurdle that needs to be overcome? What's the smallest goal we can meet while making some sort of difference?  
  All of the goals below can be done independently in ways that will have an impact (I think), the easiest is by creating a compendium of
  resources for individuals to follow the same path. The next would be to make an open source design for a specific goal (this would be
  the super expandable super clusters). From previous conversation, it sounds like the current bottleneck is affordable high speed network
  technology, so we can start by understanding that and then tackling other avenues.


Minimum Viable Product:  
  A high speed, low cost network interface.
  
Stretch goals:  
  Open source blade for expanding commonly available systems like the RPi.  
  Open Source wrack motherboard for connecting those blades to an ethernet link (the blade is probably useless without this)  
  Open source CPUs that can slot into the blade. This requires new designs all the way down.



Current Configuration:  
  A plurality of [CPUs](<https://github.com/Machine-Learning-Headquarters/CPUDesign> "Current CPU designs") are mounted to a ["blade"](<https://github.com/Machine-Learning-Headquarters/BladeArchitectures> "Current designs for CPU mount board") that allows an interface into a wrack mounted motherboard, more than likely through a PCIe bus. These motherboards can be stacked and expanded through high speed ethernet interfaces that link to high speed network switches in order to expand a supercomputer cluster further.
