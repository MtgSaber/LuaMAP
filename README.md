# LuaMAP

LuaMAP stands for Lua Mobile Agent Platform, and it is a hobby project intended to explore
a rather unique approach to distributed computing.
It is based on a project that I worked on as part of my research at Kennesaw State University,
which employed some of the basic concepts in this project.

Simply put, this is a distributed computing library which supports the Mobile Agent paradigm.
Specifically, it provides software modules to implement a platform whose basic unit of computation
is the Lua-programmed Mobile Agent.

The Mobile Agent specification can be mostly decoupled from this platform, allowing for platforms
with different implementations.
This one will be built on JVM, and its microservices will be containerized with Docker.
The Mobile Agent specification only defines the most basic features,
such as agent migration,
and is defined around HTTP and Lua exclusively.
The platform provided by this project will provide many more features, making LuaMAP a robust,
rich platform to build distributed applications with.

The original code used in my research contains many references to the research itself,
so this project will be written from the ground up so that it can be isolated from the research.
Rebuilding this project will also allow for development with different underlying technologies,
such as Akka.
The original was very hastily implemented, and I would like to create a cleaner, open-source version.

This readme will be updated in the coming months (probably May 2022) to add more details and better formatting.
For now this project is on hiatus until my other personal project,
[Saber Modpack Manager](https://github.com/MtgSaber/Saber-Modpack-Manager),
is at a suitable state for my profile, OR, until I have substantially more free time than I currently have.
