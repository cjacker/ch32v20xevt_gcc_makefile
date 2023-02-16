# ch32v20xevt with gcc and makefile support

This is pre-converted ch32v20x firmware library with gcc and makefile support from WCH official CH32V20xEVT.ZIP. 

It is converted by '[ch32v_evt_makefile_gcc_project_template](https://github.com/cjacker/ch32v_evt_makefile_gcc_project_template)'

This firmware library support below parts from WCH:

- ch32v203f6p6
- ch32v203g6u6
- ch32v203k6t6
- ch32v203c6t6
- ch32v203f8p6
- ch32v203f8u6
- ch32v203g8r6
- ch32v203k8t6
- ch32v203c8t6
- ch32v203c8u6
- ch32v203rbt6
- ch32v208gbu6
- ch32v208cbu6
- ch32v208rbt6
- ch32v208wbu6

The default part is set to 'ch32v203g6u6'(FlappyBoard), you can change it with `./setpart.sh <part>`. the corresponding 'Link.ld' will update automatically from the template.

The default 'User' codes is 'GPIO_Toggle' from the EVT example, all examples shipped in original EVT package provided in 'Examples' dir.

To build the project, type `make`.

