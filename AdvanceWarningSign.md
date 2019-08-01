# Specification for Advance Warning Sign at Mid-Block Pedestrian Crossing
## Advanced Transportation Congestion Management Technology Deployment (ATCMTD)
### Department of Public Works
### City and County of Denver, Colorado

---
#### Contents
* [General](AdvanceWarningSign.md#General)
* [Quality Assurance](AdvanceWarningSign.md#Quality-Assurance)
* [Applicable Codes and Standards](AdvanceWarningSign.md#Applicable-Codes-and-Standards)
* [Warranty](AdvanceWarningSign.md#Warranty)
* [AWS Type](AdvanceWarningSign.md#AWS-Type)
* [AWS Display Considerations](AdvanceWarningSign.md#AWS-Display-Considerations)
* [AWS Functional Description](AdvanceWarningSign.md#AWS-Functional-Description)
* [Access to Communications for Activation/Deactivation of AWS](AdvanceWarningSign.md#Access-to-Communications-for-Activation/Deactivation-of-AWS)
* [Cabinet Needs for Corresponding AWS Equipment](AdvanceWarningSign.md#Cabinet-Needs-for-Corresponding-AWS-Equipment)
* [AWS Construction](AdvanceWarningSign.md#AWS-Construction)
* [Certifications](AdvanceWarningSign.md#Certifications)
* [Maintenance Considerations](AdvanceWarningSign.md#Maintenance-Considerations)
* [Documentation, Training, and Technical Support](AdvanceWarningSign.md#Documentation,-Training,-and-Technical-Support)

---

#### General
1. Summary  
This specification is for either a blank out sign or a dynamic message sign (henceforth referenced as Advance Warning Sign or AWS) that will be utilized in advance of existing Pedestrian Hybrid Beacon (PHB) locations in the City and County of Denver (CCD) to warn approaching motorists of the presence of pedestrians in the crosswalk.  The purpose of utilizing the AWS at PHB locations are as follows:
   1. To utilize a pedestrian detection system that identifies the presence of pedestrians in the crosswalk, regardless of whether or not the PHB is active, and to notify the AWS to activate its display until such time that the pedestrians are no longer in the crosswalk.  At that time, the AWS can be notified to deactivate its display.
   1. To demonstrate the use of Dedicated Short Range Communications (DSRC) to transport notifications and acknowledgements between the PHB location, where the pedestrian detection system is deployed, and two AWS locations on each approach to the PHB.  Notifications shall be used to activate and deactivate the display on the AWS, while acknowledgements shall be confirmations from the AWS that the message display is activated and deactivated.  

#### Quality Assurance
1. The manufacturer of the AWS shall possess valid ISO 9001 certification for its Quality Management System.

#### Applicable Codes and Standards
1. Sign Display Size, Color, and Graphic/Message Content: Federal Highway Administration (FHWA) Manual on Uniform Traffic Control Devices (MUTCD) with Revision Numbers 1 and 2 incorporated (May 2012)
1. Dynamic Message Sign (DMS) Standards: National Electrical Manufacturers Association (NEMA) TS 4 (2016) Hardware Standards for DMS with NTCIP Requirements
1. Printed Circuit Boards
   1. NEMA LI 1 (1998) Industrial Laminating Thermosetting Products
   1. UL 94 (6th Edition) UL Standard for Safety Tests for Flammability of Plastic Materials for Parts in Devices and Appliances
1. Environmental Requirements: NEMA TS 4 (2016)
   1. Shock and Vibration: NEMA TS 4 (2016), NEMA TS 2 (2016) Traffic Controller Assemblies with NTCIP Requirements, or MIL-STD-883 (Revision K) Test Method Standard Microcircuits
1. AWS Housing Enclosure Type: Applicable National Electrical Manufacturers Association (NEMA) rating for outdoor use
1. AWS Housing Construction
   1. Applicable load designs (e.g., live, snow, wind, seismic, etc.) shall conform to the International Code Council (ICC) 2015 International Building Code (IBC) and 2016 Amendments to the Building and Fire Code for the City and County of Denver, as appropriate
   1. Applicable American Welding Society (AmWS) requirements, standards, and certifications
   1. The AWS manufacturer shall describe the Ingress Protection rating of the sign.
1. AWS Mounting: CCD plans to install the AWS at a standard sign height of seven feet using their standard pedestal pole details (refer to Pedestal Pole Details in PWES-009.1 CCD Traffic Signal, Signs and Pavement Marking Standards, dated March 2019, which can be found at https://www.denvergov.org/content/denvergov/en/denver-department-of-public-works/documents/standards-details-manuals.html).  The AWS manufacturer shall advise CCD if the pedestal pole and corresponding foundation is acceptable for mounting of the AWS.  Any redesign shall conform to the AASHTO Standard Specifications for Structural Supports for Highway Signs, Luminaires, and Traffic Signals (6th Edition with 2019 interim revisions) and other applicable design standards.  The AWS manufacturer shall also provide a mounting detail for mounting its AWS to CCD’s standard pedestal pole or modified pedestal pole design.
1. AWS Housing Finish and Sign Face: Applicable American Society for Testing and Materials (ASTM) requirements and standards
1. AWS Electrical Wiring, Power, and Power Distribution:
   1. Underwriters Laboratories (UL) 48 Standard for Electric Signs (2018) and other applicable UL standards
   1. National Fire Protection Association (NFPA) 70, National Electric Code (NEC), 2017 Edition, Article 600 Electric Signs and Outline Lighting and other applicable NEC requirements, including the 2016 Amendments to the Building and Fire Code for the City and County of Denver
1. Electromagnetic Compatibility: Applicable portions of FCC 47 CFR Part 15, Subpart B; AWS manufacturer to describe further in its response.
1. DSRC: The AWS manufacturer shall indicate if it complies with the standards listed below and what Roadside Units (RSU)/Onboard Unit (OBU) manufacturers they are currently compatible with based on actual field testing or implementation.  Manufacturer shall also describe if additional licensing is required to utilize DSRC and any corresponding costs.
   1. IEEE 802.11p
   1. IEEE 1609.3 WAVE Wave Short Message Protocol (WSMP)
   1. SAE J2735
      1. Basic Safety Message (BSM)
      1. Map Data (MAP)
      1. Personal Safety Message (PSM)
      1. Signal Phase and Timing (SPaT)
1. ITS Standards: National Transportation Communications for ITS Protocol (NTCIP)
   1. NTCIP 1201 v03, Global Object (GO) Definitions (March 2011)
   1. NTCIP 1203 v03, Object Definitions for Dynamic Message Signs (DMS) (September 2014)

#### Warranty  
The AWS manufacturer’s warranty shall cover a minimum of two years for replacement or repair of defective equipment.  The manufacturer shall describe if it meets or exceeds this requirement, if there are additional tiers of warranties that are available for purchase (and price), and if there are separate warranties for various components of its AWS.

#### AWS Type
1. AWS shall utilize LED technology.
1. AWS shall be either a blankout type sign (one display that is either on or off) or a Dynamic Message Sign (DMS) that conforms to the NEMA TS 4 (2016) standard.  A DMS will have the ability to display multiple messages and graphics.

#### AWS Display Considerations
1. For this project, all AWS must have the capability to display a W11-2 sign (shown in Figure 1), per MUTCD requirements, with a sign display size of at least 36 inches×36 inches for approaching drivers whenever a pedestrian is detected in the crosswalk at PHB locations.  The background color of the sign shall be standard yellow or fluorescent yellow-green as stipulated by the MUTCD and can be accomplished by the manufacturer using commercially available discrete LED technology.  

![Figure 1 - W11-2 Pedestrian Sign](https://github.com/DenverConnectedVehicle/ConnectedPedestrian/blob/master/W11-2.png)  
_Figure 1 - W11-2 Pedestrian Sign_  

1. All graphics and messages displayed on the AWS shall be clearly legible for drivers approaching the PHB location under any lighting conditions.
1. The AWS manufacturer shall describe the cone of vision about the central optical axis of the LEDs it plans to use in the AWS, the corresponding intensity (i.e., how hard the LEDs are driven) to achieve this, and the impact to the placement of the sign for driver viewing and legibility.

#### AWS Functional Description
1. All AWS will be placed on the shoulder side of the roadway (typically the right side at most locations for approaching drivers, but there is at least one exception).
1. All graphics and messages displayed on the AWS shall be clearly legible for approaching drivers under any lighting conditions.
1. Access to Power
   1. The AWS shall be energized either through the use of solar or utility power with solar being the preferred method.
   1. For the solar power option, the AWS manufacturer shall provide an estimate of the load for its sign and corresponding equipment.  It is anticipated that the worst case scenario for PHB is a crossing length of about 90 feet. At 3.5 feet per second (fps), the crossing time would be 25.7 seconds, but CCD plans to keep the AWS activated for people that walk slower than 3.5 fps, consequently an additional 10 seconds of extension or 36 seconds per crossing is assumed. Based on camera video at one of the PHB locations, the crosswalk was utilized about 40 times per day.  As a conservative estimate that the candidate PHB locations will get three times as many pedestrian crossings, this amounts to 120 activations per day. Having 120 activations per day and 36 seconds per activation, the assumption is that the AWS is on about 72 minutes per day and this is the assumption the AWS manufacturer should use for providing its calculations for sizing the photovoltaic (PV) panels, batteries, charge regulator, converter/inverter (if required), wiring, and mounting hardware.
   1. For the utility power option, CCD plans to add a breaker to the existing 120/240 VAC, 60 Hz, single phase metered service  used for the PHB.  The AWS manufacturer shall provide an estimate of the load for its sign and corresponding equipment along with the required circuit breaker size so the existing panel can be evaluated to see if it can accommodate the additional breaker.

#### Access to Communications for Activation/Deactivation of AWS
1. The preferred methodology to activate and deactivate the AWS is through the use of DSRC from a RSU that will be located at the PHB location.  The AWS manufacturer shall provide additional detail if it already has operational units that have supported this functionality using DSRC.  The manufacturer shall also describe if it used a RSU or OBU at the sign location and if this capability currently only works with select RSU/OBU vendors.
1. As an alternate to DSRC, the AWS manufacturer can describe a process where contact closures are utilized to activate and deactivate the AWS.  The manufacturer shall provide additional detail on how the transport of contact closure signals are accomplished, such as wireless using unlicensed radios or IP-based using hardwired Ethernet switches.  
1. For both Section 7.4.1 and Section 7.4.2, additional discussion by the manufacturer for remote confirmation options is required such as through contact closures or a tattletale light on the back of the AWS viewable via CCTV camera.  The purpose of the remote confirmation is to verify that the sign has been activated and deactivated.
1. For DMS AWS, it is assumed that a controller will be used for sign control and the AWS manufacturer shall describe if the controller is internal to the sign or if an external cabinet is required to house the controller.  Controllers shall be NTCIP compliant in accordance with NEMA TS 4 (2016).

#### Cabinet Needs for Corresponding AWS Equipment  
If cabinets are required to house AWS-related equipment, they shall conform to the requirements stated below.
1. The AWS manufacturer shall provide the minimum sizing of the cabinet needed to house the corresponding sign equipment.  This shall include the cabinet material, height, width, depth, and weight along with access requirements and proposed mounting scheme.
1. Pole mounted cabinets are preferred and shall be utilized where minimal space is required.  It is also assumed that this will be suitable for AWS utilizing utility electrical service.
1. Ground mounted cabinets are acceptable where additional space is required and the need for battery storage is necessary due to the use of solar electrical power.
1. The AWS manufacturer shall recommend foundation requirements for the cabinet type needed to support its sign.  The foundations may be concrete or polymer concrete with fiberglass reinforcement as approved by CCD.

#### AWS Construction
1. Mechanical
    1. Sign Housing
       1. Physical Dimensions
          1. The overall physical dimensions of the AWS shall be provided along with its weight.  The size of the AWS shall be sufficient to support the display area needed to replicate the W11-2 sign size as stated in Section 6.
       1. The AWS housing shall be constructed of extruded aluminum.  The AWS manufacturer shall provide more detail on the type of aluminum and thicknesses used.
       1. The methodology used to construct the corners and seams of the AWS shall be described to ensure that it forms a weatherproof seal.
       1. Fasteners, hinges, and locks shall be constructed out of corrosion resistant stainless steel.
       1. All doors and removable parts shall use neoprene or silicone gaskets between it and the housing to form a weatherproof seal.
       1. The AWS shall provide safe and convenient front service access for all modular assemblies, components, wiring, and other materials located within the housing.  All internal components shall be removable and replaceable by a single technician with basic hand tools.  A locking mechanism to support the access door or sign face while technicians work on the sign must be provided.
       1. The face of the AWS shall be flat black to maximize contrast and legibility of the LEDs when the sign is active.
       1. The face of the AWS shall be protected by a clear polycarbonate face with UV inhibitors; visors shall be provided as required.
       1. Screened drain hole(s) shall be provided to remove condensation build up in the sign, but prevent the ingress of insects and rodents.
       1. Exterior finish on the sign shall be enamel or powder coat with the appropriate surface preparation needed for the finish to bond properly.
       1. If lifting hardware is needed to assist with AWS mounting, lifting eyebolts shall be galvanized or stainless steel mounted to the top of the sign.  The eyebolts shall attach directly to the housing’s frame and be installed at the factory during the fabrication process.  It shall be sealed to prevent water from entering the housing and be protected from damaging the sign during shipment.
       1. Where welding is involved during the fabrication process, the AWS manufacturer shall identify the type of welding utilized.  The manufacturer shall provide documentation that the welds conform to in-house or AmWS welding procedures and that welders performing the work are certified for the processes used. 
       1. Where chemical bonding is utilized, the AWS manufacture shall provide documentation on the adhesive used along with the adhesive manufacturer’s specifications.
   1. Sign Components
       1. Discrete LEDs
          1. Discrete LEDs shall be driven at a current level that is in accordance with their operating environment per the LED manufacturer’s recommendations.
          1. The AWS manufacturer shall describe the diameter of the discrete LEDs utilized in its AWS.
          1. The AWS manufacturer shall describe the cone of vision about the central optical axis of the discrete LEDs it plans to use in the AWS and the corresponding intensity (i.e., how hard the LEDs are driven) to achieve this.
          1. The expected lifetime in hours of the LEDs shall be identified by the AWS manufacturer.
          1. The manufacturer(s) of the LED and its chemical materials (e.g., AlInGaP) used for manufacturing shall be identified by the AWS manufacturer.
          1. The operating wavelengths and brightness for each color of LED shall be identified by the AWS manufacturer.
       1. LED Display Modules
          1. The AWS manufacturer shall describe how the LEDs are mounted within the panels of the sign.
          1. Each LED shall be individually serviceable with spares included from the same batch to ensure color uniformity during replacement.
          1. The pixel spacing for the AWS resolution shall be described by the AWS manufacturer.
          1. The LED Printed Circuit Boards (PCB) shall be a glass-reinforced epoxy laminate material conforming to NEMA LI 1 (1998) and carry a Flame Retardant (FR) designation in accordance with UL 94.  The classification under UL 94 shall be V-0 so that burning stops within 10 seconds on a vertical specimen.  The side facing the front of the AWS shall be printed with black UV cure ink or black paint.
          1. Exposed traces, vias, and solder joints on the LED PCB, with the exception of connector contacts and terminals, shall be protected from water and humidity by application of a conformal coating.  The conformal coating shall contain a UV brightener to aid in visual inspection.
          1. A ground plane to provide noise shielding, and a heat sink for LEDs, as determined to be necessary by the AWS manufacturer, shall be provided on LED PCB.
          1. LEDs shall be connected in a configuration insuring that the remaining LEDs will continue operating should a failure occur in another path.
          1. The AWS manufacturer shall indicate how dimming is performed for improved nighttime visibility and to provide flicker free operation.
          1. Power supplies utilized with the AWS shall be UL recognized.
          1. Power supplies should be arranged in a redundant configuration and rated for operation such that the failure of one power supply does not affect operation for 100% of the LEDs in the AWS graphic being displayed.  The AWS manufacturer shall highlight in its submittal if a single or redundant power supply system is being proposed with its sign.
          1. Power supplies utilized for the AWS shall have a minimum efficiency of 80% and a minimum power factor rating of 0.90.  Power supply input circuits shall be fused.
          1. Power supplies shall have the capability for automatic output shutdown and restart if it experiences output faults such as over current, over voltage, and short circuit.
1. Environmental Requirements
    1. AWS shall conform to the environmental requirements stipulated in Section 2 of NEMA TS 4 (2016), except as provided below.
       1. Shock and vibration testing for the sign and its electrical components can alternatively conform to NEMA TS 2 (2016) or MIL-STD-883.
    1. The AWS shall have an operating altitude range up to 5,700 feet. 
1. Electrical Wiring and Power Distribution
    1. Wiring for internal AWS components shall be installed in a neat and professional manner.  It shall not impede the removal of power supplies or other sign components during repair or routine maintenance by technicians.
    1. Wiring shall not make contact with or bend around sharp edges.  All wiring shall conform to the NEC.
    1. All internal wiring shall employ drip loops.  All internal components shall be placed to avoid drip points.
    1. The AWS housing shall have at least one earth ground lug that is electrically bonded to the housing.  All earth grounding shall conform to Article 250 of the NEC and resistance values for ground shall be per the NEC unless otherwise specified by the AWS manufacturer.
    1. The AWS shall be UL Listed for wet locations.
    1. LED Display Requirements
       1. The AWS manufacturer shall describe how photocells will be implemented on the AWS for nighttime conditions and sun position to adjust brightness.  A minimum of two photocells should be provided to operate in a redundant manner should one photocell fail.  The remaining photocell shall continue to adjust the LED light intensity to a level that creates a legible graphic on the sign display.  The LED automatic dimming capability shall continue normally with only one photocell operational.
    1. Power Requirements
       1. The AWS manufacturer shall describe the operating voltage of its sign based on the solar or utility power option it needs to use.  The manufacturer shall also provide information on the use of transformers, converters, and inverters expected to be employed with the sign.  The thermal classes, per NEMA or UL, shall be provided for applicable electrical components for temperature and temperature rise.
       1. CCD will provide a UPS for power conditioning and backup power at the AWS only if the location utilizes utility power.

#### Certifications  
Certification shall be provided to confirm that the environmental requirements of the AWS are met.  This certification can be from the AWS manufacturer for in-house testing following accepted testing procedures or through a 3rd party testing organization.  Certifications shall also be provided, as applicable, for AmWS, NEMA, and UL requirements.

#### Maintenance Considerations  
The AWS manufacturer shall provide information on the Mean Time Between Failures (MTBF) and Mean Time To Repair (MTTR) of its sign to gauge the reliability and maintainability of its system, respectively.
1. Identify a local supplier that maintains an adequate inventory of parts to support maintenance and repair of its system, including estimated lead times for procuring these parts.
1. A list of spare parts shall be generated to assist CCD in knowing what to keep on hand for preventive maintenance and emergency repairs.
1. A list of test equipment and tools shall be prepared to assist CCD in knowing what must be made available to technicians for maintaining, testing, troubleshooting, and repairing the system.

#### Documentation, Training, and Technical Support  
The AWS manufacturer shall provide the following from the list below.
1. Product Documentation
    1. All product documentation shall be written in the English language.
    1. Product documentation shall include data sheets, quick installation manuals, user manuals, and installation manuals with specific information on configuration, installation, troubleshooting, and maintenance.
1. Training
    1. Two separate training classes shall be provided for up to 10 people in each class.  The audience in these classes will primarily be traffic signal technicians, but will likely include traffic/ITS engineers and IT staff.  CCD will provide the venue for the training classes at their Tech Shop.
    1. The instructor(s) for the class shall be employed by the manufacturer and have hands-on experience installing and troubleshooting the product.  They must be technically competent with the product; the manufacturer’s sales and marketing staff do not qualify for instructing the classes.
1. Technical Support
    1. Maintain an ongoing program of technical support for its system comprised of telephone and/or Internet-based technical support.  Availability of locally, technically knowledgeable support staff either from the manufacturer or the manufacturer’s local representative to provide on-site support is desirable.
    1. Manufacturer to provide an estimate for on-site engineering technical support of two hours for each unit procured by CCD.  The on-site personnel must be manufacturer-certified and technically competent to make configuration changes and adjustments to the system.

