# Specification for Pedestrian Detection at Mid-Block Pedestrian Crossings
## Advanced Transportation Congestion Management Technology Deployment (ATCMTD)
### Department of Public Works
### City and County of Denver, Colorado

---

#### General
1. Summary  
This specification is for either a thermal imaging detection system or a video detection system (henceforth referenced as pedestrian detection system) that will be utilized at existing Pedestrian Hybrid Beacon (PHB) locations in the City and County of Denver (CCD) to determine the presence of pedestrians in the crosswalk.  The purpose of utilizing the pedestrian detection system at PHB locations are as follows:
   1. To extend the alternating flashing red indication (wig-wag) of the PHB if pedestrian activity is still detected in the crosswalk, and
   1. To activate an Advance Warning Sign (AWS), typically a W11-2 displayed on either a blankout color LED sign or a full matrix color LED Dynamic Message Sign (DMS), for both directions of travel at each PHB location.  Each AWS will remain activated as long as a pedestrian is detected in the crosswalk no matter the state of the PHB beacon.   
1. Quality Assurance
   1. The manufacturer of the pedestrian detection system shall possess valid ISO 9001 certification for its Quality Management Systems.
1.	Applicable Codes and Standards
    1. Electromagnetic Compatibility Germane portions of FCC 47 CFR Part 15 Subpart B pedestrian detection system manufacturer to describe further in its response
    1. Environmental Compliance
        1. Ingress Protection (IP) rating of 67 (dust tight and submersible up to three feet depth) or better.
        2. Operating temperature of -35°F to +165°F or better.
        3. Humidity of 0% to 95%, non-condensing or better.
        4. Operating altitude range up to 5,700 feet.
        5. Shock and vibration in accordance with NEMA TS 2 (2016) requirements or better.
        6. Heater or similar protection to prevent the accumulation of frost, ice, and snow on the sensor side of the pedestrian detection system; pedestrian detection system manufacturer to elaborate on how it addresses this requirement so that detection of pedestrians is not obscured.
    1. Hazardous Substances: Compliance with Reduction of Hazardous Substances (RoHS) Directive 2011/65/EU.
    1. Dedicated Short Range Communications (DSRC):  If applicable, the pedestrian detection system manufacturer shall indicate if it complies with the standards listed below and what Roadside Unit (RSU)/Onboard Unit (OBU) manufacturers they are currently compatible with based on actual field testing or implementation.  Manufacturer shall also describe if additional licensing is required to support DSRC and any corresponding costs.
        1. IEEE 802.11p
        1. IEEE 1609.3 WAVE Wave Short Message Protocol (WSMP)
        1. SAE J2735
           1. Basic Safety Message (BSM)
           1. Map Data (MAP)
           1. Personal Safety Message (PSM)
           1. Signal Phase and Timing (SPaT)
    1. Open Standards:
       1. Open Network Video Interface Forum (ONVIF) conformance, as applicable for pedestrian detection systems that utilize video.  Pedestrian detection system manufacturer to describe which profile(s) it conforms to.
       1. Open Source Software (OSS) conformance that allows inspection, modification, and enhancement of source code in accordance with the corresponding OSS license.  Pedestrian detection system manufacturer shall describe how it conforms to OSS or if it utilizes a proprietary software.  If a proprietary software is utilized, please describe the terms of the license and the corresponding cost structure, if any.
       1. Application Programming Interface (API) support; pedestrian detection system manufacturer shall describe the type of API (e.g., web-based, operating system, etc.), its corresponding specifications, and if there is an additional fee for use of the API.
1. Warranty: The pedestrian detection system manufacturer’s warranty shall cover three years for replacement or repair of defective equipment.  The pedestrian detection system manufacturer shall describe if it meets or exceeds this requirement, additional tiers of warranty that are available for purchase (and price), and if there are separate warranties for various components of its pedestrian detection system.

#### Detection Requirements
The pedestrian detection system shall be capable of detecting the presence of pedestrians in the crosswalk.  It must be able to differentiate between vehicles and bicycles traveling perpendicular to the crosswalk and have the capability to determine that vehicles and bicyclists traversing the crosswalk in this direction are not pedestrians.
1. Image/Processor: The pedestrian detection system manufacturer shall describe the processor utilized for thermal sensing and/or video image processing.
   1. The pedestrian detection system manufacturer shall indicate if any external devices (e.g., additional illumination, image intensifiers, etc.) are required to detect and identify images.
   1. For thermal processors, the pedestrian detection system manufacturer shall indicate how the sensor adjusts to ambient temperature changes at the installation location.
   1. For video processors, the pedestrian detection system must not be susceptible to horizontal and vertical blooming due to brightly lit objects, such as car headlights, that may obscure image detail and blind the image processor.
   1. Please describe your system’s anticipated pedestrian detection rate and false alarm rate for this intended application.

