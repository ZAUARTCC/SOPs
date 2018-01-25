Chicago Air Route Traffic Control Center (ZAU)
===
Chicago Center
===
Standard Operating Procedures
===

##### Disclaimer
The follow are the standard operating procedures for use by Chicago Center controllers involved in providing air traffic control services on the VATSIM Network. Controllers are required to be familiar with the provisions of these procedures that pertain to their operational responsibilities and to exercise their best judgement if they encounter situations not covered by in this document. 
These procedures and the information within this document are designed for and specifically for use in a virtual controlling environment and **should not be used nor referenced for live operations in the National Airspace System**. The procedures in this document outline how the positions are to be operated and will be the basis for performance evaluations, training, and certification.

### Revisions
Change | Description | Effective Date
:---: | :--- | :---:
2015.1 | Document is first published for review. | 10/16/2015
2016.1 | Document is published. | 9/15/2016
2017.1 | 1-4 -- EuroScope removed. | 1/1/2017
2017.2 | 1-5 -- Updated to reflect C90 Minor Positions | 1/1/2017
2017.3 | 1-5 -- Updated to reflect C90 as all Major | 5/1/2017
2018.1 | Change to markdown format. | XX/XX/2018


### Chapter 1. General Information
1. General Information
    1. **Purpose of this Document**: This directive prescribes air traffic control procedures and position responsibilities for use by controllers providing air traffic control services and traffic management functions at the Chicago Center. The provisions of this directive are supplemental to procedures and phraseology prescribed in FAAO 7110.65. All controllers working the Chicago Center are required to be familiar with and apply the provisions prescribed in this directive, other related facility directives and current Letters of Agreement with the Chicago Center. 

    2. **Audience**: All vZAU Chicago ARTCC members and visiting controllers certified or working toward certification to provide ATC services on a Chicago Center position. 
    3. **What this Order Cancels**: This order cancels any previous operating procedures prescribed for Chicago Center.
    4. **Software Utilization**: vZAU has standardized on the Virtual Radar Client (VRC), vSTARS, and the vERAM software as its operating software of choice. Any references to software in this and other facility documents are written with this software in mind. 
    5. **Global Ratings**: All positions of operation outlined within this document shall be staffed in compliance with [VATSIM Global Ratings Policy (GRP)](https://www.vatsim.net/documents/global-ratings-policy).  All controllers staffing Center while C90 is offline Center while C90 is offline Center while C90 is offline shall either possess, or be in training (certified to be monitored), for the appropriate major facility endorsements. A controller may staff a center position without a C90 Major endorsement as long as a C90 controller is online OR if the center sector does not work C90 traffic.
    6. **Emergencies**: Controllers shall reference the [VATSIM Code of Conduct](https://www.vatsim.net/documents/code-of-conduct) and [Code of Regulations](https://www.vatsim.net/documents/code-of-regulations) policies regarding emergencies at all times, and have the right to request the termination of an emergency should it interfere with operations. Non-compliant pilots should be referred to a VATSIM Supervisor by utilizing the `.WALLOP` command on the radar client software. 
    7. **Updates**: This SOP is to be reviewed and, if necessary, updated every six months to remain as current as possible. Senior Staff will convene during the months of June and December to release any necessary updates effective each July and January.


### Chapter 2. Positions of Operation
2. Positions of Operation
    1. **General**: Chicago Center operates over an airspace that includes a designated airspace. Controllers staffing Center positions that would require control of C90 airspace shall hold at least a Center Controller (C1) rating, along with an Chicago C90 TRACON major endorsement, or shall be in training for such. Controllers staffing positions that would not require control of C90 airspace shall hold at least a Center Controller (C1) rating. 
    2. **Communications**: The following are the Center positions that require duty familiarization and the transfer of position responsibility. These positions are but a few of the many ZAU positions that exist in the real world. For the purposes of VATSIM, the LO and HI sectors of the ZAU airspace have been combined into four LO and four HI positions. The name of the position, the frequency, the online callsign, and the voice channel are as follows: 
    
        Position Name | Frequency | Callsign | Voice Channel
        :---: | :---: | :---: | :---:
        KUBBS (LO) | 133.200 | CHI_26_CTR // CHI_2A_CTR | chi_26_ctr
        BEARZ (LO)* | 127.800 | CHI_35_CTR // CHI_3A_CTR | chi_35_ctr
        PLANO (LO) | 135.150 | CHI_51_CTR // CHI_5A_CTR | chi_51_ctr
        FARMM (LO) | 133.350 | CHI_74_CTR // CHI_7A_CTR | chi_74_ctr
        ||
        Roberts* (HI) | 134.020 | CHI_45_CTR // CHI_4A_CTR | chi_45_ctr
        Badger (HI) | 126.870 | CHI_60_CTR // CHI_6A_CTR | chi_60_ctr
        Keeler (HI) | 127.620 | CHI_88_CTR // CHI_8A_CTR | chi_88_ctr
        Iowa City (HI) | 125.570 | CHI_94_CTR // CHI_9A_CTR | chi_94_ctr

        >NOTE -- * in the above table indicates the primary combined frequency to be connected first. 
        
        1. Every controller shall utilize a primary frequency in their ATC client program for communications with aircraft. Every controller is encouraged to use voice as the primary method of communication with aircraft per VATSIM regulations. However, aircraft utilizing non-voice communications (text or receive only) will never be denied ATC services, nor will controllers executing text or receive only commands be denied the ability to control. Controllers shall use text as they are able to clarify instructions and/or when instructed by an aircraft. 
        2. Every Center position will maintain a standard and common position ATIS. VRC’s Controller Info dialog automates many of these elements of a standard position ATIS. The position ATIS will include the following elements at minimum: 
            ```
            Position
            Current ATIS Letter ID for KORD
            Active Runways
            ```
        3. Voice ATIS. At Class D, C and B airports located within Center airspace, Local Control shall be responsible for keeping an updated voice ATIS with all necessary information pertaining to operations its respective airport. The standard VOICE ATIS for Center if no other controller is online, is ORD_ATIS. The secondary Voice ATIS will be MDW_ATIS. If both of those airports have a voice ATIS currently active, it will be up to the Center controller on whether to connect an ATIS for another airport, however it is not required to do so. The ATIS should also be recorded with the voice server as rw.liveatc.net. Sample voice ATIS templates can be found below. 
            1. O’Hare Airport Information (code), (time of wx observation) Zulu, (weather sequence – wind,
vis, precip/phenomena, clouds, temp, dewpoint, altimeter)
            2. Arrivals expect vectors (choose one: ILS, Visual) Runway (#) approach
            3. Departures expect runways (#, #, #)
            4. Notices to Airmen: PIREP; Closures; Birds; Noise abatement, MU readings Wind shear;
SIGMET; HIWAS; Braking action; SWAP.
            5. For Clearance Delivery contact (position name) on frequency (frequency)
            6. VFR aircraft say direction of flight, aircraft type and requested altitude
            7. Pilots readback all runway hold short and taxi instructions.
            8. Advise on initial contact you have information (code). 
            
            >Note -- When LAHSO operations are in effect, place an appropriate message in the voice ATIS. 
            
            >NOTE -- Prior to broadcasting, review the pending ATIS to ensure accuracy and inform pilots via voice and text of the update information code being broadcast. 

        4. If no C90 controller is online, CHI_35_CTR will always control C90 airspace even when Center is split multiple ways. 
    3. **Hierarchy of Opening Positions**: The following is the order in which positions will be opened/split in the event more than one controller wishes to control Center.
        1. Center LO Hierarchy
        
            Position Name | Frequency | Callsign | Airspace Delegation
            :---: | :---: | :---: | :---:
            BEARZ (LO) | 127.800 | CHI_35_CTR // CHI_3A_CTR | All ZAU
            PLANO (LO) | 135.150 | CHI_51_CTR // CHI_5A_CTR | NE/SW Split
            KUBBS (LO) | 133.200 | CHI_26_CTR // CHI_2A_CTR | NE/S/W Split OR N/E/S/W Split
            FARMM (LO) | 133.350 | CHI_74_CTR // CHI_7A_CTR | N/E/SW Split OR N/E/S/W Split
            
            >NOTE -- CHI_26_CTR and CHI_74_CTR have no hierarchy. Either can sign on to help 35 and 51. 26 splits 35’s airspace and 74 splits 51’s airspace. 

        2. Center HI Hierarchy
        
            Position Name | Frequency | Callsign | Airspace Delegation
            :---: | :---: | :---: | :---:
            Roberts (HI) | 134.020 | CHI_45_CTR // CHI_4A_CTR  | All HI
            Badger (HI) | 126.870 | CHI_60_CTR // CHI_6A_CTR | HI NW/SE Split
            Keeler (HI) | 127.620 | CHI_88_CTR // CHI_8A_CTR | HI W/N/SE Split OR HI N/E/S/W Split
            Iowa City (HI) | 125.570 | CHI_94_CTR // CHI_9A_CTR | HI N/W/S/SE Split OR HI N/E/S/W Split
            
            >NOTE -- CHI_88_CTR and CHI_94_CTR have no hierarchy. Either can sign on to help 45 and 60. 88 splits 45’s airspace and 94 splits 60’s airspace.
            
            >NOTE -- At least one LO Center position must be online before HI Center can open. 
            
            >NOTE -- LO Center positions will operate HI Center airspace within their lateral boundaries unless at least one HI Center is online. HI Center will never operate LO Center airspace. 
            
    4. **ZAU Sector Boundaries**:
        1. The vertical boundaries of the ZAU Center airspace are SFC-FL600. If there is a HI/LO Split, LO sector vertical boundaries are SFC-FL239 and HI sector vertical boundaries are FL240-FL600. 
        2. The vertical boundaries of the ZAU Center airspace are limited in areas by which TRACONs governed by other ARTCCs extend within the lateral boundaries of ZAU airspace. These TRACONs include Des Monies, Lansing, Indianapolis, and Springfield. The floor of ZAU airspace is at but not including the ceiling of those TRACONs.
        3. The vertical boundaries of the ZAU Center airspace are extended in areas by which TRACONs governed by ZAU extend beyond the lateral boundaries of ZAU airspace. These TRACONs include Waterloo, Kalamazoo, Fort Wayne, Champaign, and Volk RAPCON.
        4. The lateral boundaries of the ZAU Center airspace are depicted in the diagrams below. As stated above with regard to vertical boundaries, lateral boundaries are also limited by neighboring TRACONs and also extended with our own TRACONs. 
        5. If the ZAU TRACONs mentioned in 2-4.3 are staffed at the time, then the TRACON controller will own their own airspace as it extends beyond the ZAU Center boundary. 


## ZAU LO Sectors
![CHI_35_CTR Lateral Boundaries](https://i.gyazo.com/39cfc2e5c5c984964a6a580474169d3c.png)

![CHI_51_CTR Lateral Boundaries](https://i.gyazo.com/e487359cb86d860433cc6245269051de.png)

![CHI_26_CTR Lateral Boundaries](https://i.gyazo.com/149248ccca7b355a9db1260cc4a75721.png)

![CHI_74_CTR Lateral Boundaries](https://i.gyazo.com/74e007f284b6a650922abe05770b1790.png)

## ZAU HI Sectors
![CHI_45_CTR Lateral Boundaries](https://i.gyazo.com/b8b3a14b58e6e839310a232abb7a94e6.png)

![CHI_60_CTR Lateral Boundaries](https://i.gyazo.com/6b3628f825fce3b2c502c7b122a086e2.png)

![CHI_88_CTR Lateral Boundaries](https://i.gyazo.com/629fc9ae3caca58d22aeb76ba216e4c4.png)

![CHI_94_CTR Lateral Boundaries](https://i.gyazo.com/c1eca512f964f8d2b7578591b2a1d797.png)


### Chapter 3. ZAU and C90 TRACON Coordination
3. ZAU and C90 TRACON Coordination
    1. **Arrivals into C90**: Chicago Center shall provide in-trail radar separation between successive arrivals crossing the arrival fixes at an interval of at least 5nm, unless coordinated otherwise with C90, along with any speed restriction coordinated with C90. If more than one altitude is published at the handoff point, the lower altitude shall be the primary altitude with the higher one solely used by faster aircraft when resolving overtakes by dissimilar aircraft types.
    2. **NORTHEAST Arrivals (KUBBS Feeder)**: The KORD arrival routes include the ERNNY, PAITN and WYNDE STARs. The Satellite airport arrival route is direct WURKO or FIYER direct OBK then to the aircraft’s destination. Chicago Center releases control for descent and turns upon completion of radar and communications handoff. 
        1. Arrival Route Altitude Restrictions: ORD inbound aircraft should cross WYNDE at 10,000ft and not descend further until past FIYER. Satellite aircraft should cross WURKO or FIYER at or below 9,000ft. If a satellite aircraft is not filed WURKO or FIYER, they should cross 30 DME of OBK at 3,000ft. and be handed to the controller working North Satellite.
    3. **SOUTHEAST Arrivals (OKK Feeder)**: The KORD arrival routes include the WATSN, ESSPO, VEECK, and OXI STARs. When KORD is utilizing West flow, RNAV aircraft should fly the WATSN STAR and non-RNAV the OXI STAR. When KORD is utilizing East flow, RNAV aircraft should fly the ESSPO or VEECK STARs and non-RNAV be vectored HALIE ORD. The VEECK STAR can be used for both East and West flows. The KMDW arrival routes include the FISSK, PANGG, and GSH STARs. Chicago Center releases control for descent and turns upon completion of radar and communications handoff. 
        1. Arrival Route Altitude Restrictions: KORD inbound aircraft should cross either HULLS, ESSPO, or HALIE (non-RNAV) AT 12,000ft. VEECK arrivals should cross BOONE at 12,000ft. KMDW inbound aircraft should cross HALIE at 6,000ft. 
    4. **SOUTHWEST Arrivals (PLANO Feeder)**: The KORD arrival routes include the BENKY, TRTLL, SHAIN and BDF STARs. When KORD is utilizing West flow, RNAV aircraft should fly the BENKY and/or TRTLL STARs. When KORD is utilizing East flow, RNAV aircraft should fly the BENKY and/or SHAIN STARs. Non-RNAV aircraft should fly the BDF STAR regardless of runway flow at KORD. The Satellite airport arrival route is PLANO OBK for North Satellite arrivals, PLANO for west South Satellite arrivals and JOT for east South Satellite arrivals. The KMDW arrival routes include the ENDEE and MOTIF STARs. Chicago Center releases control for descent and turns upon completion of radar and communications handoff.
        1. Arrival Route Altitude Restrictions: KORD inbound aircraft should cross either SHAIN or BENKY at 12,000ft. TRTLL arrivals should cross TRTLL at 11,000ft. Satellite aircraft should cross the C90 boundary at 6,000ft. KMDW inbound aircraft should cross ENDEE or MINOK at 6,000ft. 
    5. **NORTHWEST Arrivals (FARMM Feeder)**: The KORD arrival routes include the FYTTE, MADII and JVL STARs. Chicago Center releases control for descent and turns upon completion of radar and communications handoff. 
        1. Arrival Route Altitude Restrictions: KORD inbound aircraft should cross TEDDY at 11,000ft. Satellite aircraft should cross 30 DME of OBK at 3,000ft. and be handed to the controller working North Satellite. 
    6. **Departures from C90**: C90 will complete handoffs to Chicago Center prior to aircraft leaving the vertical boundary of 15,000ft and/or the lateral airspace governed by the TRACON where not governed by a neighboring TRACON. 
        1. Departure Route Communication Transfers: Aircraft departing C90 to the north will be handed to the controller working the FARMM sector (74). Aircraft departing C90 to the east will be handed to the controller working the KUBBS sector (26). Aircraft departing C90 to the south will be handed to the controller working the BEARZ (35). Aircraft departing C90 to the west will be handed to the controller working the FARMM (74). 
        2. Aircraft navigating to an initial waypoint outside of C90 will have been assigned a 360, 090, 180, or 270 upon handoff respective to the appropriate Center controller and direction of flight. 


### Chapter 4. ZAU and MKE TRACON Coordination
4. ZAU and MKE TRACON Coordination
    1. **Arrivals into MKE Area via MKE TRACON**: Chicago Center shall provide in-trail radar separation between successive arrivals crossing the arrival fixes at an interval of at least 5nm, unless coordinated otherwise with MKE TRACON, along with any speed restriction coordinated with MKE TRACON. If more than one altitude is published at the handoff point, the lower altitude shall be the primary altitude with the higher one solely used by faster aircraft when resolving overtakes by dissimilar aircraft types. 
    2. **NORTHEAST Arrivals**: The KMKE arrival route includes SUDDS. The Satellite airport arrival route is the same. Chicago Center releases control for descent and turns upon completion of radar and communications handoff.
        1. Arrival Route Altitude Restrictions: KMKE inbound aircraft should cross SUDDS at 8,000ft. Satellite aircraft should cross SUDDS at 6,000ft. 
    3. **SOUTHEAST Arrivals**: The KMKE arrival routes include SQUIB and PETTY. The Satellite airport arrival routes are the same. Chicago Center releases control for descent and turns upon completion of radar and communications handoff.
        1. Arrival Route Altitude Restrictions: KMKE inbound aircraft should cross SQUIB at 10,000ft. or PETTY at 6,000ft. Satellite aircraft should cross SQUIB at 6,000ft. or PETTY at 4,000ft.
    4. **SOUTHWEST Arrivals**: The KMKE arrival routes include the GOPAC STAR and JOT-VEENA or JVL-VEENA. The Satellite airport arrival routes for airports are the same. Chicago Center releases control for descent and turns upon completion of radar and communications handoff. 
        1. Arrival Route Altitude Restrictions: KMKE inbound aircraft should cross either GOPAC or VEENA at 6,000ft. Satellite aircraft should cross either GOPAC or VEENA at 4,000ft. UGN arrivals should not be filed via JOT-VEENA. 
    5. **NORTH and NORTHWEST Arrivals**: The KMKE arrival route includes BAE. The satellite airport arrival route is the same. Chicago Center releases control for descent and turns upon completion of radar and communications handoff. 
        1. Arrival Route Altitude Restrictions: KMKE inbound aircraft should cross BAE at 8,000ft. Satellite aircraft should cross BAE at 4,000ft. 
    6. **Departures from the MKE Area of MKE TRACON**: MKE TRACON will complete handoffs to Chicago Center prior to aircraft leaving the vertical boundary of 13,000ft. and/or the lateral airspace governed by the TRACON where not governed by a neighboring TRACON.
        1. Departure Route Communication Transfers: All aircraft departing the MKE Area to the South, West, or North that will be entering Chicago Center airspace will be handed to the controller working the FARMM sector (74). All aircraft departing the MKE Area to the east that will be entering Chicago Center airspace will be handed to the controller working the KUBBS sector (26). 
        2. Aircraft navigating to an initial waypoint outside of MKE TRACON will have been assigned a 360, 090, 180, or 270 upon handoff respective to the appropriate Center controller and direction of flight. 
    7. **Arrivals into North Sector of MKE TRACON (Oshkosh Area)**: Chicago Center shall provide in-trail radar separation between successive arrivals crossing the arrival fixes at an interval of at least 5nm, unless coordinated otherwise with MKE TRACON, along with any speed restriction coordinated with MKE TRACON. 
    8. **EAST Arrivals**: The TRACON arrival route includes FAH. Chicago Center releases control for descent and turns upon completion of radar and communications handoff.
        1. Arrival Route Altitude Restrictions: Satellite aircraft should cross FAH at or below 6,000ft.
    9. **SOUTH Arrivals**: The TRACON arrival route includes BAE. Chicago Center releases control for descent and turns upon completion of radar and communications handoff. 
        1. Arrival Route Altitude Restrictions: Satellite aircraft should cross BAE at or below 10,000ft. with a pointout made to Chicago Approach. 
    10. **WEST Arrivals**: The TRACON arrival route includes DLL. Chicago Center releases control for descent and turns upon completion of radar and communications handoff.
        1. Arrival Route Altitude Restrictions: Satellite aircraft should cross DLL at or below 11,000ft. with a pointout made to Madison Approach.
    11. **NORT Hand NORTHWEST Arrivals**: The MKE TRACON is bordered to the north by Minneapolis Center. Aircraft inbound to the north sector of MKE TRACON will cross STE or GRB at or below 10,000ft and handed directly to MKE Approach by a ZMP controller, if online.
    12. **DEPARTURES from the North Area of MKE TRACON**: MKE TRACON will complete handoffs to Chicago Center prior to aircraft leaving the vertical boundary of 13,000ft and/or the lateral airspace governed by the TRACON where not governed by a neighboring TRACON.
        1. Departure Route Communication Transfers: All aircraft departing the MKE TRACON to the south or west that will be entering Chicago Center airspace will be handed to the FARMM sector (74). All aircraft departing the MKE Area to the east that will be entering Chicago Center airspace will be handed to the controller working the KUBBS sector (26). If leaving MKE TRACON to the north, handoffs can be made to Minneapolis Center, if online, with a pointout to Chicago Center FARMM sector (74). 
        2. Aircraft navigating to an initial waypoint outside of MKE TRACON will have been assigned a 360, 090, 180, or 270 upon handoff respective to the appropriate Center controller and direction of flight. 


### Chapter 5. Glossary of Terms

Term | Definition
--- | ---
ARTCC | Air Route Traffic Control Center.
ATIS | Automatic Terminal Information System, provided by airports with towers utilized on a frequency that gives weather and airport information to pilots.
C90 | Refers to the Chicago TRACON, which serves Chicago O'Hare, Chicago Midway, and the area airports.
DME | Distance Measuring Equipment. Transponder-based radio navigation technology that measures slant range distance by timing the propagation delay of VHF or UHF radio signals.
FAAO | Federal Aviation Administration Order 7110.65. The [Job Order](https://www.faa.gov/documentLibrary/media/Order/ATC.pdf) that all real world controllers adhere to. 
GRP | The [VATSIM Global Ratings Policy](https://www.vatsim.net/documents/global-ratings-policy), a document governing the training and promotion of controllers to be used throughout the Network.
HI | "HI"gh. Refers to the Center sectors covering FL240-FL600.
HIWAS | Hazardous Inflight Weather Advisory Service. A continuous broadcast of inflight weather advisories. 
IFR | Instrument Flight Rules.
ILS | Instrument Landing System, a primary method of instrument approaches. A precision approach providing both lateral and vertical guidance to the runway.
LAHSO | Land and Hold Short of, for when an aircraft lands and must stop prior to a certain runway or taxiway intersection.
LO | "LO"w. Refers to the Center sectors covering SFC-FL239.
LOA | Letter(s) of Agreement. A set of Standard Operating procedures to be used by neighboring facilities to speed up the communication process between facilities.
LOCAL | Another name for a Tower controller.
MKE TRACON | Milwaukee TRACON.
MU | Greek term meaning the co-efficient of friction. Used for braking action reports.
PIREP | A pilot report of actual weather conditions encountered by an aircraft in flight.
RAPCON | Radar Approach Control (Air Force/FAA).
RNAV | Area navigation allowing an aircraft to choose any course within a network of navigation beacons, rather than navigating directly to and from the beacons.
SIGMET | Significant Meteorological Information. A weather advisory that contains meteorological information concerning the safety of all aircraft.
SOP | Standard Operating Procedure(s).
STAR | Standard Terminal Arrival Route. A published flight procedure IFR aircraft fly into an airport. Transition aircraft from high altitudes to the low altitudes required for an approach.
SWAP | Severe Weather Avoidance Program. A formalized program that is developed for areas susceptible to disruption in air traffic flows, caused by thunderstorms.
TRACON | Terminal Radar Approach Control.
TWR | The VATSIM designation of a Tower Position.
vERAM | [vERAM](http://veram.metacraft.com/) is an air traffic control radar simulation program for use on the VATSIM network. It is a high-fidelity simulation of the real ATC system used in many enroute control facilities in the United States.
VFR | Visual Flight Rules.
VRC | [Virtual Radar Client](http://www1.metacraft.com/VRC/), one of the radar clients supported by our facility. The most popular client in the United States.
vSTARS | [vSTARS](http://vstars.metacraft.com/) is an air traffic control radar simulation program for use on the VATSIM network. It is a high-fidelity simulation of the real ATC system used in many approach control facilities in the United States.
vZAU | ZAU is the designator for the Chicago ARTCC facility. *v* is used to designate a virtual environment. *Z* is assigned to each facility in the United States, and *AU* represents the town of Aurora where the facility is physically located.
ZMP | ZMP is the designator for the Minneapolis ARTCC facility. *Z* is assigned to each facility in the United States, and *MP* represents the city of Minneapolis where the facility was first located.

---
Signed,  
/s/  
Jakob Kruse  
Air Traffic Manager  
vZAU Chicago ARTCC  

Signed,  
/s/  
XX XXX  
Deputy Air Traffic Manager  
vZAU Chicago ARTCC  

Signed,  
/s/  
XXX XXXX  
Training Administrator  
vZAU Chicago ARTCC  