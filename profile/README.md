## NATO Education and Training Network Federation Object Model (NETN FOM)


* [Download AMSP-04 Ed C and STANREC 4800 Ed 3](https://nso.nato.int/nso/nsdd/main/standards)

* [Download NETN-FOM v4 FOM modules in HLA4 Format](https://github.com/AMSP-04/NETN-FOM/tree/master/FomFiles_HLA4)

* [Download NETN-FOM v4 FOM in HLA Evolved Format](https://github.com/AMSP-04/NETN-FOM/tree/master/FomFiles_Merged_HLA_Evolved)


Efficient and effective use of Modelling & Simulation (M&S) capabilities requires standards for connecting and integrating M&S components across the training system enterprise.

AMSP-04 NATO Education and Training Network Federation Object Model (NETN-FOM) specifies how to represent and share data in distributed simulation environments where M&S services (federates) are connected and federated using the NATO mandated IEEE 1516 High-Level Architecture (HLA) standard (STANAG 4603).

The NETN-FOM focuses on technical interoperability issues in distributed simulation and provides patterns for scenario initialization, transfer of modelling responsibilities, simulation entity tasking and patterns for managing dynamic change of model resolution.

Maintenance and updates of AMSP-04 is coordinated by the NATO Modelling and Simulation Coordination Office (MSCO), managed by the NATO Modelling and Simulation Group (NMSG) and performed as NATO Science and Technology Organization (STO) technical activities (currently MSG-223) in support of the NMSG Modelling and Simulation Standards Subgroup (MS3). AMSP-04 is maintained on GitHub and all release and development versions are publicly available.

Several versions of the NETN-FOM have been released and the latest version is NETN-FOM v4.

|Version|Description|Developed by|Released|
|---|---|---|---|
|v1.0|Initial release of the NETN-FOM|MSG-068|22 FEB 2014|
|v2.0|[Release of the NETN-FOM included in AMSP-04 Ed A](https://github.com/AMSP-04/NETN-FOM/releases/tag/v2.0)|MSG-134|28 MAR 2018|
|v3.0|[Release of the NETN-FOM included in AMSP-04 Ed B](https://github.com/AMSP-04/NETN-FOM/releases/tag/v3.0)|MSG-163|26 MAR 2021|
|v4.0|[Release of the NETN-FOM included in AMSP-04 Ed C](https://github.com/AMSP-04/NETN-FOM/releases/tag/v4.0)|MSG-191|11 MAR 2025|

The NETN-FOM consists of a set of HLA FOM Modules providing standard interfaces for representing simulated entities, events, and other models of real-world objects, processes and phenomenon. It also provides standard interfaces and patterns for simulation interplay between systems in a federated distributed simulation to allow multi-resolution modelling, transfer of modelling responsibilities, tasking and simulation control.

NETN-FOM v4 consists of 14 FOM Modules with dependencies between them and to other standard FOM modules. The NETN-FOM v4 extends and complements the [SISO-STD-001-2015 Standard for Real-time Platform Reference Federation Object Model (RPR FOM) v2](https://www.sisostandards.org/resource/resmgr/standards_products/siso-std-001.1-2015_rpr_fom.pdf) standard and depends on some of the RPR-FOM modules.

Starting from NETN-FOM v4 all FOM modules are managed in the NETN-FOM repository. 
This repository also contain all releases of NETN-FOM.

The Master Branch of the NETN-FOM repository always contain the latest released version of the NETN-FOM.

The Develop Branch of the NETN-FOM repository always contain the latest stable development version of the NETN-FOM including all FOM modules. In the Edit Branches, you will find work-in-progress.

MSG-223 is currently maintaining the NETN-FOM and working to deliver a draft proposal for a NETN-FOM v4.x or v5 by the end of March 2027.
