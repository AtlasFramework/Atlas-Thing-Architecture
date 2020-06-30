# Atlas-Thing Architecture

Based on the specifications of the IoT-DDL, Atlas thing architecture enables the automatic integration of the devices into the ecosystem and allows the programmer to discover and combine available services to create applications for the smart space. The Atlas thing architecture is a set of lightweight operating layers that initially aim at turning a thing into a smart stand-alone and self-dependable unit, getting smarter, more social, and more interactive with time. Atlas Thing Architecture extends the original Atlas architecture to enable the thing to self-discover itself and announce its presence, services and capabilities to other participants in the smart space. Besides capturing new engagement and programming opportunities, such knowledge exchange increases a thing’s awareness of the surrounding ecosystem and enables discovering and building new social relationships. Along with the provisioning and management capabilities offered by the Atlas Thing Architecture to the space users and developers, the Atlas Thing Architecture supports both thing-to-thing and thing-to-cloud communication paradigms through the support of a set of communication protocols and enabling communication interoperability through protocol translators. The Atlas Thing Architecture also enables, through the IoT-DDL, the thing to dynamically define and generate its own services and formulates appropriate programmable interfaces through which the thing mates can interact and trigger the offered services.

</br>

The architecture takes advantage of lightweight device management standards OMA-LwM2M, object modeling standard IPSO, IoT communication standards REST-HTTP, CoAP, and MQTT. Atlas Thing Architecture, as illustrated below, consists of the following layer:

>- IoT OS services are the basic functionalities provided by the thing’s operating engine for a thing to be part of the IoT (e.g., network module, memory units, I/O ports and interfaces (e.g., I/O, ADC), and its process manager).

>- The Atlas IoT platform represents the logical layer of the architecture to provide new functionalities and services not currently provided by the thing’s OS or engine. Such new services focus on the descriptive and semantic aspects to better enable the thing to discover its own identity, resources, attachments and capabilities, generate services and formulate appropriate interfaces (APIs) as well as enable the thing to engage and interact with thing mates and scenarios through both thing-to-thing and thing-to-cloud communication paradigms for a distributed interactive and social IoT ecosystem. 

>- The Host interface layer shields the Atlas IoT platform and gives it the portability and interoperability it needs. It also maintains the platform’s light weight by maximally relying on services provided by the underlying OS (IoT OS services). 

<p align="center">
  <img src="https://github.com/AtlasFramework/Atlas-Thing-Architecture/blob/master/Resources/AtlasThingArchitecture.jpg" width="700" height="550" title="The Architecture">
</p>

## Read more about it in the following papers:
> - Khaled, Ahmed E., Abdelsalam Helal, Wyatt Lindquist, and Choonhwa Lee. ["IoT-DDL–device description language for the “T” in IoT."]  IEEE Access 6 (2018): 24048-24063.[Link: https://ieeexplore.ieee.org/abstract/document/8334820]
> - Khaled, Ahmed E., and Sumi Helal. "Interoperable communication framework for bridging RESTful and topic-based communication in IoT." Future Generation Computer Systems 92 (2019): 628-643. [Link: https://eprints.lancs.ac.uk/id/eprint/89459/1/1_s2.0_S0167739X17317387_main.pdf]


## Tweet-Specificaitons 
[Check the "Tweet-Specifications" to view the components of the different messages Atlas thing can excahnge and communicate.](https://atlasframework.github.io/Atlas-Thing-Architecture/Tools/TweetSpecs.html)


## Capture and visualize Atlas thing tweets-Specificaitons 
[Use this tool to capture and visualize the different tweets announced and exchanged between Atlas things in your smart space.](https://atlasframework.github.io/Atlas-Thing-Architecture/Viewer/SpaceViewer.html)


## Check the other parts of the Framework:
> - [IoT-DDL.](https://github.com/AtlasFramework/IoT-DDL)
> - Inter-Thing Relationship Framework
> - Runtime Interactive Development Environment
