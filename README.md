# TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA


<p align="center">
<img src="https://github.com/ivsg-psu/TrafficSimulators/blob/master/Images/CARLA_day.png" alt="Traffic Simulators" width="960" height="486">
</p>
Welcome to the GettingStartedWithCARLA wiki! The goal of this wiki is to get users started with CARLA, an open-source simulator for autonomous driving research. 

***

<!-- TABLE OF CONTENTS -->
# Table of Contents
<details open>
  <summary> Click to see/unsee </summary>
  <ol>
    <li>
        <a href="#CARLA-machine-hardware-settings">CARLA machine hardware settings </a>
        The work in this area includes information of CARLA machine hardware settings.
    </li>
    <li>
        <a href="#How-to-install-CARLA">How to install CARLA?</a>
        The work in this area includes information to guide how to install CARLA. 
    </li>
    <li>
        <a href="#How-to-run-a-simple-simulation-in-CARLA">How to run a simple simulation in CARLA?</a> 
        The work in this area involves information to guide how to run a simple simulation in CARLA.
    </li>
    <li>
        <a href="#Understanding-more-features-in-CARLA">Understanding more features in CARLA.</a>
        The work in this area includes information to guide users to understand more features in CARLA, such as how to control the surrounding traffic, how to run CARLA in synchronized mode etc. 
    </li>
    <li>
        <a href="#Advanced-topics-in-CARLA">Advanced topics in CARLA</a>
        The work in this area involves advanced topics in CARLA, including how to import a customized map into CARLA. 
    </li>
    <li>
        <a href="#Testing-the-limits-of-CARLA">Testing the limits of CARLA.</a>
        The work in the area includes tests to check the limits of CARLA, including the finest time measurements in CARLA, repeatability tests in CARLA etc. 
    </li>
    
  </ol>
</details>

<a href="#table-of-contents">Back to top</a>

***
# Comparisons of different traffic simulations tools 
The work in this area includes comparisons of different traffic simulations tools.
<details closed> 
  <summary> Click to see/unsee </summary>
</details>
<a href="#traffic-simulators">Back to top</a>

# Coordinate systems used for large-area spatial simulations

<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators/wiki/Spatial-Coordinate-System">
      Spatial Coordinate System of Simulator
      </a>
      <br>
      This wiki page presents the coordinate systems for describing a point on the surface of the earth, compare the accuracy of various calculations using these coordinate systems, and provide the rationale for choosing a specified sequence of these coordinate systems (with the associated transformations) in the simulation environment built for the NSF CPS “Forgetful Databases” project. 
    </li>
  </ul>
</details>

<a href="#traffic-simulators">Back to top</a>

# Getting started with different simulators
The work in this area involves getting started with different simulators, such as AIMSUN, SUMO, etc.
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO">
     TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithSUMO
      </a>
      <br>
     This details the work on how to get started with SUMO traffic simulator. 
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation">
     TrafficSimulators_GettingStartedWithDifferrentSimulators_GettingStartedWithCARLA-SUMOCosimulation
      </a>
      <br>
     This repo details the work to get started with CARLA-SUMO cosimulation.
    </li>

  </ul>
</details>
<a href="#traffic-simulators">Back to top</a>

# Interacting with simulator data non-real-time modes
The work in this area includes interacting with simulator data non-real-time modes(e.g. how to load AIMSUN trajectory traces in MATLAB or ROS, example data sources for traces, plot these traces, etc.).
<details closed> 
  <summary> Click to see/unsee </summary>
</details>
<a href="#traffic-simulators">Back to top</a>

# Real-time interaction with simulator tools
The work in this area involves real-time interaction with simulator tools (for example, interacting with AIMSUN via ROS). 
<details closed> 
  <summary> Click to see/unsee </summary>
</details>
<a href="#traffic-simulators">Back to top</a>

# Automatic generation of random road configurations for driving simulators
The work in the area includes automatic generation of random road configurations for driving simulators (the random highway tool, for example).
<details closed> 
  <summary> Click to see/unsee </summary>
</details>
<a href="#traffic-simulators">Back to top</a>

# Import of real-world road information into traffic simulators
The work in this area includes import of real-world road information into traffic simulators (for example, importing OSM into AIMSUN - some of this is in Field Data areas).

<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_ImportRoadInfo_MATLAB_To_RoadXML_To_AIMSUN">
      TrafficSimulators_ImportRoadInfo_MATLAB_To_RoadXML_To_AIMSUN
      </a>
      <br>
      This is a collection of functions that converts MATLAB data into a RoadXML format for use by AIMSUN. This was originally written by Marcus Putz in Summer 2020 as his summer internship project.
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/ivsg_master/wiki/TrafficSimulators_ImportRoadInfo_OSM_To_AIMSUN">
      TrafficSimulators_ImportRoadInfo_OSM_To_AIMSUN
      </a>
      <br>
      Describes manually importing real-world road information from OSM to Aimsun.
    </li>
  </ul>
</details>
<a href="#traffic-simulators">Back to top</a>


# Extraction of information from traffic simulators
The work in this area includes extraction of information from traffic simulators (for example, extract network from AIMSUN).
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_ExportTrafficInfo_ExtractRoadNetworkFromAimsunShapeFile/wiki">
      TrafficSimulators_ExportTrafficInfo_ExtractRoadNetworkFromAimsunShapeFile
      </a>
      <br>
      This details the code to extract road network information from shapefiles exported from AIMSUN.
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators_ExportTrafficInfo_FromAIMSUNIntoDatabaseViaROS">
      TrafficSimulators_ExportTrafficInfo_FromAIMSUNIntoDatabaseViaROS
      </a>
      <br>
      Shows a process to exort traffic information from AIMSUN into a database system using ROS.
    </li>
  </ul>
</details>

<a href="#traffic-simulators">Back to top</a>



# Calibration of model parameters
The work in this area includes calibration of model parameters.

<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/TrafficSimulators/tree/master/CarFollowingModel">
      Implementation of Car Following Model
      </a>
      <br>
      This details the code to work to develop a simple car following model.
    </li>

  </ul>
</details>
<a href="#traffic-simulators">Back to top</a>


# Coordination of traffic simulators with V2x systems
The work in this area includes coordination of simulators with V2x systems.
<details closed> 
<summary> Click to see/unsee </summary>

For introduction to this topic, see:

* [The 2020 Transportation Engineering and Safety Conference Session No. 2E: Automated Driving System (ADS) Grant Proposals](https://www.youtube.com/watch?v=MnelLz4in9Q&feature=youtu.be&ab_channel=LarsonInstitutePSU)

* [The 2020 Transportation Engineering and Safety Conference Session No. 5A: Work Zone Safety](https://www.youtube.com/watch?v=shE3wVdQdu4&feature=youtu.be&ab_channel=LarsonInstitutePSU)

* [The 2020 Transportation Engineering and Safety Conference Session No. 7E: Innovations for Emergency Responders/AV](https://www.youtube.com/watch?v=gfhFmjzZ92g&feature=youtu.be&ab_channel=LarsonInstitutePSU)


The Federal Geographic Data Committee (FGDC) recently released [version 3.0 of the Work Zone Data Exchange (WZDx) Specification](https://github.com/usdot-jpo-ode/jpo-wzdx), which enables infrastructure owners and operators (IOOs) to make harmonized work zone data available for third-party use. The WZDx Specification is intended to make travel on public roads safer and more efficient through ubiquitous access to data on work zone activity.

<img src="https://github.com/ivsg-psu/TrafficSimulators/blob/master/WorkZone_v2x.png" height="400" width="800" >

HIGHLIGHTS

Established under the FGDC Transportation Subcommittee, the [Work Zone Data Working Group (WZDWG)](https://github.com/usdot-jpo-ode/jpo-wzdx/wiki) developed version 3.0 of the WZDx Specification in 2020, based on prioritized issues and new insights from the data producer and data consumer community. This past development cycle demarcated several WZDWG milestones including the launch of two additional WZDx subgroups—the Technical Assistance Subgroup and Worker Presence Subgroup—who worked in tandem with the Specification Update Subgroup to advance WZDx goals. WZDWG and subgroup members spent the past 6 months encouraging conversation on the WZDx GitHub site, identifying and prioritizing changes to the WZDx Specification for version 3.0, and holding meetings with data producers and consumers representing various constituencies across the work zone ecosystem (e.g., IOOs) to review potential changes for inclusion in version 3.0.

WZDx SPECIFICATION VERSION 3.0 CHANGES

In September 2020, the WZDWG approved and merged the proposed changes into version 3.0 of the WZDx Specification, which was released on 9/23/2020. Version 3.0 made several changes to improve usability and consistency, including standardization of lane sequencing and version formatting, additional properties to support detour information and other road events for implementing agencies, and relationship entities to describe correlations between road events and work zone phases (i.e., non-WZDx entities on the road).

FOR MORE INFORMATION
Version 3.0 of the WZDx Specification and a link to release notes detailing all the changes made to the specification in greater depth can be found on the WZDx version 3.0 release page.  For additional information about the WZDx Specification, refer to the working group's GitHub Wiki page and the WZDx website. If you are interested in joining the WZDWG and/or contributing to the specification development conversation, please email avdx@dot.gov. 


</details>
<a href="#traffic-simulators">Back to top</a>

# Miscellaneous 
The work in this area includes information that does not fit other categories (for example, simulating fuel economy of traffic via traffic simulators).
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/EcoTrafficSimulation/wiki">
      EcoTrafficSimulation
      </a>
      <br>
     This is a summer project in 2020 to simulate the fuel economy of entire segments of traffic, via AIMSUN traces, for highway and urban situations.
    </li>

  </ul>
</details>

<a href="#traffic-simulators">Back to top</a>


