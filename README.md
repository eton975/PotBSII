# PotBSII
Pirates of the Burning Sea II development repository
Main development repository.

Code structures for
1. Website HTML, HTTPS, TLS and CSS (/website)
2. Game launcher (encryption and salting required for usernames and passwords) (/launcher)
3. Game client window (/client)
4. Game server and database (encryption and salting required) (/server)
5. Special x86 assembly, DirectX 11, OpenGL/Vulkan OpenCL, PhysX and DirectX 12 acceleration code, possibly automatically generated by a good compiler. AMD64 and Intel 64 optimisations, because Intel64 has VERY small differences from AMD64 that can cause page faults and memory leaks! (/optimisedbinaries)

Engine: Unity, UE4, CryEngine, Torque3D? Hooks for this from the game logic and to the screen?
