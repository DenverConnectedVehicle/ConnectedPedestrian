# Request for Proposal (RFP): Pedestrian Detection at Mid-Block Pedestrian Crossings
## Advanced Transportation Congestion Management Technology Deployment (ATCMTD)
### Department of Public Works
### City and County of Denver, Colorado
### 

Denver is seeking to purchase the Automated Pedestrian Detection devices to enable the Connected Pedestrian project. The purchase will cover the four pedestrian crossings locations associated with the ATCMTD grant.

This procurement is for either a thermal imaging detection system or a video detection system (henceforth referenced as pedestrian detection system) that will be utilized at existing Pedestrian Hybrid Beacon (PHB) locations in the City and County of Denver (CCD) to determine the presence of pedestrians in the crosswalk.  The purpose of utilizing the pedestrian detection system at PHB locations are as follows:
   1. To extend the alternating flashing red indication (wig-wag) of the PHB if pedestrian activity is still detected in the crosswalk, and
   1. To activate an Advance Warning Sign (AWS), typically a W11-2 displayed on either a blankout color LED sign or a full matrix color LED Dynamic Message Sign (DMS), for both directions of travel at each PHB location.  Each AWS will remain activated as long as a pedestrian is detected in the crosswalk no matter the state of the PHB beacon.  

Below are the questions Denver seeks in addition to technical proposals, as well as the requirements on technologies proposed to Denver.

## Questions for Vendors
In your firm's response to this RFP, please include responses to the following questions.

1. Does your device include any dedicated short-range communications (DSRC) radio technology in addition to its detection functionality?

1. Please provide information about methods of remotely updating Firmware in a secure manner. Does your solution support failsafe firmware updates? Can OS updates be applied independently of application updates?

1. Please list device's supported services and protocols, including as applicable:  Address Resolution Protocol (ARP), Domain Name System (DNS), Dynamic Host Configuration Protocol (DHCP), File Transfer Protocol (FTP), HyperText Transfer Protocol (HTTP), HyperText Transfer Protocol Secure (HTTPS), Internet Control Message Protocol (ICMP), Internet Group Management Protocol (IGMP), Internet Protocol version 4 (IPv4), Network Time Protocol (NTP), RTP Control Protocol (RTCP), Secure Copy Protocol (SCP), Secure Shell (SSH), Transmission Control Protocol (TCP), Universal Plug and Play (UPnP), and User Datagram Protocol (UDP), National Transportation Communications for Intelligent Transportation (NTCIP), Simple Network Management Protocol (SNMP), and Message Queuing Telemetry Transport (MQTT). 

## Requirements for Pedestrian Detection at Mid-Block Pedestrian Crossings

---
#### Contents
* [General](PedDetection.md#General)
* [Detection Requirements](PedDetection.md#Detection-Requirements)
* [System Considerations](PedDetection.md#System-Considerations)
* [Electrical Requirements](PedDetection.md#Electrical-Requirements)
* [Mechanical Requirements](PedDetection.md#Mechanical-Requirements)
* [Maintenance Considerations](PedDetection.md#Maintenance-Considerations)
* [Documentation, Training, and Technical Support](PedDetection.md#Documentation,-Training,-and-Technical-Support)

---

#### General
1. Quality Assurance
   1. The manufacturer of the pedestrian detection system shall possess valid ISO 9001 certification for its Quality Management Systems.
1.	Applicable Codes and Standards
    1. Electromagnetic Compatibility: Germane portions of FCC 47 CFR Part 15, Subpart B; pedestrian detection system manufacturer to describe further in its response.
    1. Environmental Compliance
        1. Ingress Protection (IP) rating of 67 (dust tight and submersible up to three feet depth) or better.
        2. Operating temperature of -35°F to +165°F or better under normal operating loads.
        3. Humidity of 0% to 95%, non-condensing or better.
        4. Operating altitude range up to 5,700 feet.
        5. Shock and vibration in accordance with NEMA TS 2 (2016) requirements or better.
        6. Heater or similar protection to prevent the accumulation of frost, ice, and snow on the sensor side of the pedestrian detection system; pedestrian detection system manufacturer to elaborate on how it addresses this requirement so that detection of pedestrians is not obscured.
    1. Hazardous Substances: Compliance with Reduction of Hazardous Substances (RoHS) Directive 2011/65/EU.
    1. Dedicated Short Range Communications (DSRC):  *If applicable*, the pedestrian detection system manufacturer shall indicate if it complies with the standards listed below and what Roadside Unit (RSU)/Onboard Unit (OBU) manufacturers they are currently compatible with based on actual field testing or implementation.  Manufacturer shall also describe if additional licensing is required to support DSRC and any corresponding costs.
        1. Compliance with FCC Part 90 (for OBU) or Part 95 (for RSU)
        1. IEEE 1609.12-2016 - WAVE Identifier Allocations
        1. IEEE 1609.3-2016 - WAVE Wave Short Message Protocol (WSMP)
        1. IEEE 1609.2-2016 - WAVE Security Services for Applications and Management Messages
        1. SAE J2735-2016
            1. Basic Safety Message (BSM)
            1. Map Data (MAP)
            1. Personal Safety Message (PSM)
            1. Signal Phase and Timing (SPaT)
        1. SAE J2945/1_201603 On-Board System Requirements for V2V Safety Communications
        1. SAE J2945/9 - Vulnerable Road User Safety Message Minimum Performance Requirements
        1. Use of 1609.2 security credentials issued by Security Credential Management System (SCMS) providers
        1. Device must be certified by [OmniAir](https://omniair.org/certified-products/)  or be in the process of receiving certification.
        1. USDOT RSU 4.1 Revision to Dedicated Short-Range Communication Roadside Equipment Specification - [link](https://rosap.ntl.bts.gov/view/dot/3621/dot_3621_DS1.pdf)
    1. Open Standards:
       1. Open Network Video Interface Forum (ONVIF) conformance, as applicable for pedestrian detection systems that utilize video. Pedestrian detection system manufacturer to describe which profile(s) it conforms to.
       1. Open Source Software (OSS) conformance that allows inspection, modification, and enhancement of source code in accordance with the corresponding OSS license. Pedestrian detection system manufacturer shall describe how it conforms to OSS or if it utilizes a proprietary software. If a proprietary software is utilized, please describe the terms of the license and the corresponding cost structure, if any.
       1. Application Programming Interface (API) support; pedestrian detection system manufacturer shall describe the type of API (e.g., web-based, operating system, etc.), its corresponding specifications, and if there is an additional fee for use of the API.
1. Warranty: The pedestrian detection system manufacturer’s warranty shall cover three years for replacement or repair of defective equipment.  The pedestrian detection system manufacturer shall describe if it meets or exceeds this requirement, additional tiers of warranty that are available for purchase (and price), and if there are separate warranties for various components of its pedestrian detection system.

#### Detection Requirements
The pedestrian detection system shall be capable of detecting the presence of pedestrians in the crosswalk.  It must be able to differentiate between vehicles and bicycles traveling perpendicular to the crosswalk and have the capability to determine that vehicles and bicyclists traversing the crosswalk in this direction are not pedestrians.
1. Image/Processor: The pedestrian detection system manufacturer shall describe the processor utilized for thermal sensing and/or video image processing.
   1. The pedestrian detection system manufacturer shall indicate if any external devices (e.g., additional illumination, image intensifiers, etc.) are required to detect and identify images.
   1. For thermal processors, the pedestrian detection system manufacturer shall indicate how the sensor adjusts to ambient temperature changes at the installation location.
   1. For video processors, the pedestrian detection system must not be susceptible to horizontal and vertical blooming due to brightly lit objects, such as car headlights, that may obscure image detail and blind the image processor.
   1. Please describe your system’s anticipated pedestrian detection rate and false alarm rate for this intended application. Please describe your company's method of assessing precision and recall of the system and state overall anticipated accuracy within +-5% of actual results.
1. Minimum Scene Illumination:  If applicable, the pedestrian detection system manufacturer shall describe the minimum illuminance (in foot-candles) required at the PHB locations for the effective use of its pedestrian detection system. 
1. Resolution: The minimum resolution required is 320x240.
1. Variable Frame Rate: Frames per second (fps) shall be user-definable from 1-30 fps. 
1. Human Detection Distances:  The pedestrian detection system manufacturer shall discuss the human detection distances associated with the appropriate products for CCD’s specific application.  A qualified manufacturer’s engineer or technician is invited to perform a field visit to survey the first four PHB locations where the system will be implemented and provide recommendations on the ideal mounting location(s) for its pedestrian detection system, including the number of detectors it recommends for each site.  Only one of the four locations has a raised median with no landscaping.  Proposed mounting locations include traffic signal poles, traffic signal mast arms, and street light poles with traffic signal mast arms. If possible, pre-existing Astro-Brac camera brackets already purchased by CCD shall be the preferred option for mounting.
1. Data Collection: The pedestrian detection system shall be capable of collecting speed, count, and presence.  This can include, but is not limited to, the number of times the presence of a pedestrian(s) was detected and average crossing speeds or time utilized for crossing. This can include live and post-processed data on instantaneous speed and time to cross.

#### System Considerations
1. Firmware/Software:  The pedestrian detection system manufacturer shall indicate what methods are available to securely update field side firmware.  The manufacturer shall also describe if any central software is provided or available for a fee to perform remote management and configuration of deployed detectors.  If a central software is available, please provide the candidate OS needed to support the software and the minimum system configuration requirements (e.g., processor, RAM, primary storage, etc.).  If it is a web-based system, please provide the browsers that are supported.  

1. Video Outputs:  The pedestrian detection system manufacturer shall indicate what items it supports and does not support from the list below.  The manufacturer is invited to also list items it supports that are not listed below that could be beneficial for CCD.
   1. Digital:  H.264/H.265
   1. Streaming:  Maximum Bit Rate (MBR), Variable Bit Rate (VBR), and/or Constant Bit Rate (CBR) from 50 Kbps up to 4 Mbps
   1. Video:  Real-time Transport Protocol (RTP)/Real Time Streaming Protocol (RTSP), unicast/multicast
   1. Display:  For video, the pedestrian detection system manufacturer shall describe the number of colors its system can support for output displays.  For thermal, the manufacturer shall describe how warmer objects will be displayed with cooler objects and the number of colors available in its color palette.
   1. Interface:  Ethernet, RJ-45 (8P8C connector, T568B pinout), minimum 10/100 Mbps
   1. Security:  The pedestrian detection system manufacturer shall describe what items it can and can’t provide based on the list below.  Additional security considerations provided by the manufacturer that are not listed below are welcome to be described further.
      1. IEEE 802.1X Port-based Network Access Control (PNAC) for authentication to connect to CCD’s communications network.
      1. User login for access to the pedestrian detection system with a username and password and the ability to remind users that their password is expiring based on a user-selectable period from 1 to 12 months.
      1. Certificate based authentication for access to camera's Linux system. Certificate based camera authentication.
      1. A minimum of two user access levels (supervisor and maintenance technician) that affects the abilities of each to perform specific actions when logging into the pedestrian detection system.  The permissions shall be user-definable with the supervisor having access to more permissions then the maintenance technician.
      1. The pedestrian detection system manufacturer shall define the well-known, registered, and private ports it uses in accordance with the Internet Assigned Numbers Authority (IANA) to ensure that some of the ports needed for system operations aren’t blocked by CCD cybersecurity requirements.
1. Control Input/Outputs (I/O): The pedestrian detection system manufacturer shall outline the items it can and can’t comply with based on the list below.
   1. The pedestrian detection system manufacturer shall indicate the number, type, and load rating of relay outputs its system supports.
   1. The pedestrian detection system needs to support 24 VDC logic contacts compatible with industry standard detector rack assignments.
   1. Or, the pedestrian detection system needs to support NTCIP outputs as alternative to control IO.
1. Standalone Processor: The pedestrian detection system manufacturer shall indicate if its system includes a standalone processor that will be located in the controller cabinet.  If so, it needs to be compatible for use with a Serial Data Link Communication (SDLC) interface in accordance with NEMA TS 2 Type 2.
1. Recording Capabilities: An existing Network Video Recorder (NVR) will be utilized for storage and to support reviewing of recorded video to assess the performance of the pedestrian detection system.
1. Data Flow and Ownership Collection
   1. The pedestrian detection system manufacturer shall describe how data from the system can be accessed for review both locally at the PHB as well as remotely at CCD’s Tech Shop and Traffic Management Center (TMC).  The manufacturer shall provide a conceptual data flow diagram to delineate the process for data flows to the remote locations previously listed.
   1. It is required that CCD retains ownership of all raw and processed data.  The pedestrian detection system manufacturer shall address in its response how it typically handles ownership of data and any issues with the stated requirement.

#### Electrical Requirements
1. PoE or Midspan Injectors: The pedestrian detection system shall have the capability to use Power over Ethernet (PoE) directly from CCD’s existing PoE Ethernet switch in each controller cabinet.  The existing PoE Ethernet switch’s support Type 1 (IEEE 802.3af) and Type 2 (IEEE 802.3at) power standards.  The pedestrian detection system manufacturer shall indicate if it requires a higher PoE power standard and outline the Extended Operating Temperature (EOT) midspan PoE injectors it recommends for use with this application, including EOT power supplies for the midspan PoE injectors.  EOT shall conform to the Environmental requirements contained in NEMA TS 2 (2016).
1. CATx Cabling: The pedestrian detection system shall recommend the minimum Category of Performance cable to be used with its system and whether the cabling must be Shielded Twisted Pair (STP) or Unshielded Twisted Pair (UTP).
1. Power Requirements: The controller cabinets have 120 VAC and 24 VDC available for use with the pedestrian detection system.  The pedestrian detection system manufacturer shall outline which voltage it plans to use, the maximum load expected, and whether EOT power supplies will be used to convert VAC to VDC.

#### Mechanical Requirements
1. Dimensions: The pedestrian detection system manufacturer shall provide the physical dimensions of the product it is recommending for this application, including any sunshield mounted on the product.  Dimensions shall be without any mounting brackets and associated mounting accessories.
1. Mounting: The pedestrian detection system manufacturer shall provide a datasheet of the mounting hardware it recommends using for mast arm and pole mounting options for its product.
1. Weight: The pedestrian detection system manufacturer shall provide the weight of its product, including the sunshield, if applicable.

#### Maintenance Considerations
The pedestrian detection system manufacturer shall provide information on the Mean Time Between Failures (MTBF) and Mean Time To Repair (MTTR) to gauge the reliability and maintainability of its system, respectively.
1. Identify a local supplier that maintains an adequate inventory of parts to support maintenance and repair of its system, including estimated lead times for procuring these parts.
1. A list of spare parts shall be generated to assist CCD in knowing what to keep on hand for preventive maintenance and emergency repairs.
1. A list of test equipment and tools shall be prepared to assist CCD in knowing what must be made available to technicians for maintaining, testing, troubleshooting, and repairing the system.

#### Documentation, Training, and Technical Support
The pedestrian detection system manufacturer shall provide the following from the list below.
1. Product Documentation
   1. All product documentation shall be written in the English language.
   1. Product documentation shall include data sheets, quick installation manuals, user manuals, and installation manuals with specific information on configuration, installation, troubleshooting, and maintenance.
1. Training
   1. Two separate training classes shall be provided for up to 10 people in each class.  The audience in these classes will primarily be traffic signal technicians, but will likely include traffic/ITS engineers and IT staff.  CCD will provide the venue for the training classes at their Tech Shop.
   1. The instructor(s) for the class shall be employed by the manufacturer and have hands-on experience installing and troubleshooting the product. The manufacturer’s sales and marketing staff do not qualify for instructing the classes.
1. Technical Support
   1. Maintain an ongoing program of technical support for its system comprised of telephone and/or Internet-based technical support.  Availability of locally, technically knowledgeable support staff either from the manufacturer or the manufacturer’s local representative to provide on-site support is desirable.
   1. Manufacturer to provide an estimate for on-site engineering technical support of two hours for each unit procured by CCD.  The on-site personnel must be manufacturer-certified and technically competent to make configuration changes and adjustments to the system.


