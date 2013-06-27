entreda-ext repo will have packages/sources for building as well as deployment of Entreda components. 

The top level ‘build’ folder contains 3rd party RPMS/sources required for generating the particular component’s deliverable. For example, build/appliance/ folder will contain files required to generate the Appliance deliverable i.e. ecsg-<version>.rpm. Same holds for the ‘store’ and ‘portal’ components.

The top level ‘deploy’ folder contains 3rd party RPMS/sources required for “deploying” the particular component. For example, deploy/appliance/ folder will contain all packages/files required as pre-requisites prior to the Entreda Appliance deliverable (see above) can be installed. Same holds for ‘store’ component. For the ‘portal’ component, there will be a list of all softwares required to be installed on the system to be setup as the portal, with appropriate versions of each.

The aim of this entire exercise is to ensure that anyone can generate builds for Entreda, and can deploy any component once it is built. The steps for building and deployment have been documented, and will be updated as and when changes (like automation) to the process are done.

NOTE: Another very important point – From next week onwards, we will be moving to CentOS for ALL Entreda components (barring Agents of course). In other words, the Entreda Portal and Entreda Store (what you used to call EBS) platform will change to CentOS 6.3 (x86_64). These used to be OpenSUSE instances. Appliance has already moved to CentOS 6.3 x86_64.

