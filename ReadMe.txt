NeTEX XMl schema
(C) 2009-2012  NeTEX , CEN, Crown Copyright
        
NeTwork EXchange : Core, Part 1. Part 2 Schemas, Part3 Draft Schemas
================================================

This is a work in progress schema that   a few     errors and outstanding issues. See the NeTEx UML Physical and Conceptual models for an UML view

The Part &1 and Part 2 Schema is nearly stable.
The Part3 schema may  still be subject to significant  revision 

There is an XMLSpy project file in the root directory  that provides an organised view  of the schema and examples
    
  - netex-v099.2.spp
  
There is also an Oxygen project file
- netex-v099.2.xpr

====================

Getting Started:
  
	There are two main root schemas

 	 - netex_publication : Embeds NeTEx XML model elements in a bulk output file format for use in asynchronous publication. The intended content scope can be indicated by a filter object. 
	
 	 - netex_siri.xsd : Embeds NeTEx XML model elements in the SIRI protocol  for dynamic exchange of elements between servers. Both Request/response or publish / subscribe is supported

	In addition

  	- nx.xsd : Embeds NeTeX XML model elements within a simple thematic organisation to facilitate browsing and inspection of NeTEx. 
 

There are XML examples  of the use of both protocols

    /publications
            /versioning 
                /Netex_VersioningExample_Step_01.xml
                /Netex_VersioningExample_Step_02.xml
                /Netex_VersioningExample_Step_03.xml
                /Netex_VersioningExample_Step_04.xml
 		/Netex_VersioningExample_Step_05.xml
            /simpleNetwork
 		/ Netex_railNetwork_01_eurostar.xml
                 /Netex_SimpleNetwork_1.xml

            /stopPlace
                /Ifopt_StopPlace_se_NOPTIS_Example_TEH_PA1.xml
                /Ifopt_StopPlace_uk_ComplexStation_Wimbledon_1.xml
                /Netex_Stops1_SingleStopOnStreet_1.xml
                /Netex_Stops2_StopPairOnStreet_1.xml
                /Netex_Stops4_SimpleStation_1.xml
                
           /site
   	    	 /Netex_Sites_OlympicPark_1.xml
   	    	 /Netex_Sites_OlympicPark_2_basic.xml
 	     	 /Netex_Sites_SimpleStadium_1.xml    
                
                
            /patterns
                /Netex_KBIC_ParisNetwork_1.xml

            /variant
                </Netex_VariantExample_Step_05.xml


            /timetable
	    |       Netex_06.2_Bus_FrequencyJourneyTimetable_RhythmicalInterval.xm
	    |       Netex_08.1_BusTram_Timetable_AmbiguousLinks.xml
	    |       Netex_10_Rail_SplittingJoiningTimetable.xml
	    |       Netex_21_Rail_NetworkTimetable_eurostar.xml
	    |       Netex_32_Multimodal_PiFacility.xml
	    |       Netex_01.1_Bus_SimpleTimetable_JourneysOnly.xml
	    |       Netex_01.2_Bus_SimpleTimetable_WithTimings.xml
	    |       Netex_01.3_Bus_SimpleTimetable_WithMultiplePatterns.xml
	    |       Netex_01.4_Bus_SimpleTimetable_WithConnection.xml
	    |       Netex_01.5_Bus_SimpleTimetable_RouteProjection.xml
	    |       Netex_01.5_Bus_SimpleTimetable_StopAssignment.xml
	    |       Netex_01.6_Bus_SimpleTimetable_RouteProjection.xml
	    |       Netex_01.9_Bus_SimpleTimetable_NoFrame.xml
	    |       Netex_02.1_Bus_CircularRoute_Timetable.xml
	    |       Netex_03.1_Bus_BranchedRouteTimetable_SimplePatterns.xml
	    |       Netex_03.2_Bus_BranchedRouteTimetable_SharedPatterns.xml
	    |       Netex_05.1_Bus_TemplateTimetable_HeadwayFrequency.xml
	    |       Netex_05.2_Bus_TemplateTimetable_RhythmicalFrequency.xml
	    |       Netex_06.1_Bus_FrequencyJourneyTimetable_HeadwayInterval.xml
	    
	    
	    
            /fares
 	    |       Netex_51.1_Bus_SimpleFares_PointToPoint_SingleProduct.xml
	    |       Netex_51.2_Bus_SimpleFares_PointToPoint_MultipleProducts.xml 	
	    |       Netex_51.3_Bus_SimpleFares_ZoneToZone_AdultChildProducts.xml	
	    |       Netex_51.4_Bus_SimpleFares_ZoneToZone_OffPeakProduct.xml  
	    |       Netex_61.1_Bus_GeographicFares_UnitDistance_SingleProduct.xml 	
	    |       Netex_61.2_Bus_GeographicFares_UnitZone_MultipleProduct.xml	
	    |       Netex_71.1_Bus_TimeIntervalFares_Zonal_MultipleProduct.xml	
	    |       Netex_81.1_Metro_FlatFare_GroupProduct.xml 		
	    |       Netex_81.2_Metro_TravelCard_MultipleProduct.xml 		 
	    |       Netex_81.3_Metro_WeeklyPass_MultipleProduct.xl 		
	    |       Netex_91.1_Rail_RailCard_MultipleProduct.xml :
	    
	  
	    
	    /standards
	    +---era_uic
	    |       Netex_era_uic_Stations_Se_1.xml
	    |       Netex_era_uic_Stations_SSP_Se_1.xml
	    |       Netex_era_uic_timetable_hack_01.xml
	    |       
	    +---gtfs
	    |       Netex_gtfs_exm1_Agency1.xml 
	    |       Netex_gtfs_exm1_Calendar_1.xml
	    |       Netex_gtfs_exm1_CalendarDates_1.xml 
	    |       Netex_gtfs_exm1_FareAttributes_1.xml
	    |       Netex_gtfs_exm1_FareRules_1.xml 
	    |       Netex_gtfs_exm1_Frequencies_1.xml
	    |       Netex_gtfs_exm1_Routes_1.xml
	    |       Netex_gtfs_exm1_Shapes_1.xml
	    |       Netex_gtfs_exm1_Stops_1.xml
	    |       Netex_gtfs_exm1_StopTimes_1.xml
	    |       Netex_gtfs_exm1_Transfers_1.xml
	    |       Netex_gtfs_exm1_Trips_1.xml
	    |       Netex_gtfs_exm1_zz_Composite.xml
	    |       Netex_gtfs_fares_Example_1_flatFare_unlimitedTransfer.xml 	    	    	    
	    |       Netex_gtfs_fares_Example_2_flatFare_noTransfer.xml 
	    |       Netex_gtfs_fares_Example_3_flatFare_90mTransfer.xml 
	    |       Netex_gtfs_fares_Example_4_flatFare_byLineGroup.xml  
	    |       Netex_gtfs_fares_Example_5_flatFare_feeToTransfer.xml  
	    |       Netex_gtfs_fares_Example_6_pointToPointFare_anyRoute.xml 
	    |       Netex_gtfs_fares_Example_7_zoneSequenceFare.xml  
		neptune
		    RATP_Line7bis-extract-2009-NeTEx.xml

	    +---noptis
	    |       Netex_StopPlace_se_NOPTIS_Example_TEH_PA1.xml
	    |       Netex_StopPlace_se_NOPTIS_TEH_Style1_PB1.xml
=====================================================================================================================


SOME TODOs 
     
    Discussion
      How are timing periods combined with day type assignments?
      How are day types combined ?
      		Timetable values apply to all journeys in table or do they have to be explicit  
      Should there be a timetable ENTITY that is distinct from the Timetable Frame
      Should there be a validity condition/ or day type on   a  Call?   
      
       
      Handling of OperatingDay DayTypeAssignment,
      Technical
      	References to children  point /link  in sequence  
      	Requests and topics  
      
     TXC 
        Registration extensions 
        
      Internal  Tidy up to dos  
      	 Substitution groups need correcting  
      	 Scope of Children  : consistent order  add parent  
      	 Add separate placepointref  for nav path  ref hierarchy
      
    
     Misc	 
  	 	TODO sort admin zone subst groups  
     Examples	     	       	    
    	 Responsibility & Data source example    
    	 Add includes model
    	 Add routing constraint example
         Add varying  time demand example 
         Add Parking & Parking tariff example
         Add Activated equipment examples 
 	 Add Nptg ownership example
         Service pattern  origin dest
         Assessment / validity

       TYPE of wheelchair? 
   MODEL  
      Fares - Add combination price
   
=============================================================================================
Change List
    - Changes affecting existing netex xml docs are marked (MODEL CHANGE),.dx = diagram change.  x xml change

update constraints, update oxygen list, sort wdsl

<xsd:simpleType name="AccessibilityToolEnumeration">
TOD CAPPED FARE where CAP is another fare, price parameters

 
    
   2013.04.08
            Add validable elementref to FareStuctureElement   x ti do dx 
           
            [RJIS] Add MinHolders. MaxPersondsicount  to GroupTicket x dx
            [Tfl ] Add FareDemandType, StartTimeAtStation x dx
            [TfL] Add CappedUSageRight x dx
            [Tfl] Add COllectBt  User parameter to capping to allow rebate
            [Tfl] Add Operator to Line section x
            [Tfl] Add FareSection + directions to access ath assignment x dx.
            [Tfl] Add FareZone  to allow sctions in tariff zonesx dx
            [Tfl} Allow properties on LinseSectionMember
            [Tfl} Add DateOnWHich Age applies to UserProfile
            [Tfl} Add  TariffZone to network to allow (Shoudl really move TZ to ND package?)
            [Tf;] Add Lcoal resident to UserProfile x dx
              [Tf;] Add BaseProfile   to UserProfile x dx
            [Fx] Add FareProduct, SalesPackage to SalesTransaction x
            [Fx] Fix Ref subs groups, unique keys for Group Of Ops etc x
            [Fx] Allow NuisancceFacility and Passenger comms on Accomodation, promote accomodation and onboard stay to be versionined children multiple
            
            [Fx] Add endloop to LineSection enum x
            [Fx] Add FareSections to FareFrame x
            [{fix] Allow multiple l geographical structure factors & time structure factors per    fare structure element
            [Tfl, Tap] Add OperatorRef to Tariff
            [SG9 Paris ] Rename FarePoint to FarePointInPattern x. dx.  
            [SG9 Paris ] Add general FareProduct requires/entitles relationship to FareProduct x dx
            [SG9 Paris ] Rename BackTrip to RoundTrip x. dx.  
             [SG9 Paris ] Allow multiple series per distance Matrix x. dx.  
            [Fx]  Correction: Move DatedSpecialService  to DatedJourney package  x dx.
            [nl Fix]  Add TypeOfResponsibilityRole  x.  dx.
            [nl Fix]  Add Separate arrival/departure ay offset to Passing times  x dx.         
            [nl Fix]  Add Monitoring attribute to Journey  x. dx.
            [nl Fix]  Correction  From and To StopPointRef types on notice assignment to be PointInPattern. x.
        
   2013.03.27 
            [Tap B1] Revise to make delegation via responsibility set x. dx.
            [Tap B1]  Add Text Font name to presentation Add Presentation to StopPoint x. dx.
            [Tap B3]  Add validityCondition to  equipment x dx.
            [Tap B1,2,3] Add Traces & Deltas to VersionFrame. x dx.
            
            [Fix Acs] Make WheelchairACcessEquipment and VehicleAccessEquipment types of passenger equient  type and ref from installed. x dx
            [Fix Acs] Add AssistanceAvailable , Guide dog and WheelchairBoarding to AccessVehicleequipment x dx
            [Fix Acs] Add  AssistanceAvailablity to AssistanceService x dx            
            [Fix Acs]   Add MobilityNeed as SuitableFor to AccessVehicleEquipment x dx
            
            [Tap B2 Code Entity  Add Branding entity to datamanaged object dx
            [Fix Acs] Add AssistanceBooking as a type of LocalService
               
                                        
               
    2013.03.12
     	    [Tap B3] Add Rounding parameters to Fare Frame, Discount fare, Sales Package price package new package dx
     	    [Tap B3] Add ALternative names to usage paramter x. dx
     	    [Tap B3 OFAT] Add ResponsbilityRef to DisctributionScope x. dx.
     	    [Tap B1] Make BorderPoint a type of TimingPoint x. dx.
     	    [SG9 Munich]  Rename Charging Method to CHarging Moment x. dx.
    2013.03.05
     	    [Fix] Correct spelling of connurbation x nx
     	    [Fix] Correct spelling of EntityLegalOwnership x. nx.
     	    [Fix] Add additionalTopographicPlaces to SiteGroup x. nx.
     	    [Fix] VehicleType may include VehicleTypes x. dx.
     	    [Fix] Vehicle installed ActualEquipmentType x. dx.
     	    [Fix] Add an overide accessibilityAssesment to Call x dx 
     	    [Fix[ Replace Seat Class with CLASS OF USE nx. dx.
     	    [FIX] Correct comment on Longitude x. nx
     	    [uk] Add mobilityScooter & roadMobilityScooter to mobilityNeed x dx
    2013.03.04
     	    [Tap B2 Tariff Range ]   Add GroupOFSalesPackages  x dx
            [Tap B2 Tariff] Add AlternativeNames to SalesPackage x dx
            [Tap B2 Tariff] Add GroupOfDistanceMatrixElements x dx.
            [Tap B2 Tariff] Add GroupOFSalesPackages  and DistributionChannel & FulfillmentMethod     to FareFrame x dx.
            [Tap B2 Tariff] Add DistributionCOndition   to SalesPackage & GroupOfSales Packages x.  dx.
            [Tap B2 Tariff] Add DistributionChannel x dx.
            [Tap B2 Tariff] Add TrainNumber to access right Assignment x dx
            [Tap B2 Tariff] Add Group of Timebands to Access Right Assignment x. dx
            [Tap B2 Tariff] Add  Summary to SalesPackageELement and SalesPackagedx x. dx.
            [TAP B2 Sales Conditions] and DistributionScope to SalesPackage x dx
    	    [TAP B2 After Sales Conditions] Add CappedCell Price x dx
    	    [TAP B2 After Sales Conditions] Add Exchanging Usage parameter + attributes  x dx    	    
            [Tap B2 Tariff] Add UsageParameters for MinimumStay, Exchangeable and PurchaseWindow  x dx
    	    [Tap B2 Price] Add Facility, Accommodation , Night Train  to AccessRightParameterAssignment x dx
    	    [Tap B2 Price Train Category] add TypeOfProductCategory to Access Right Assignment x dx
    	    [Tap B2 Price] Add IsDirect to SeriesPattern &  AccessRightParameterAssignment x dx.
    	    [Tap B2 Price] Revise simple validity condition x.nx.
    	    [Tap B3 add berth level & Gender limitation to Accomodation upper | lower both x. dx.
    	    [Tap B1 B3] Add DistanceMatrix to AccessRightParameterAssignment x dx
        2013.02.29
           [FR] Allow NoticeAssignmentRefs on Lines. x dx 
           [FR] Add includes relationship to GroupOfAccessParameterAssignments x dx
           
        2013.02.18 
          [Tap B1, B2 Price ] Add Cell (Combination Price) x dx
          [Tap B1 TCVP-H] Add FareBasis (distance group route) to FareStructureElement x dx
          [TAP B1 TCV-I,H,P] Add FareTablePriceGroup  optimization x dx
          
	2013.02.12 Align model with XML
          [FR] Add Group of Assignment parameters and revise model x dx
          [FR] Add Fare Point & Fare section to Fare structure model x dx
          [NL] Add OperatingDays to AvailabilityCOndition x. dx.
          {xx] Add missing elements to Fare Frame. x dx.
                 
        2012.01.24 TAP TSI TCVS
           [Tap TSI B1 TCVS] Add SeriesPattern (for series) x dx.
           zz[Tap TSI B1 TCVS Add notice assignments to DistanceMatrixElement (for series info)
           [Tap TSI B1 TCVS] Add validity conditions to   DistanceMatrixElement x dx
           [Tap TSI B1 TCVS] Add SeriesPattern to Access Right Assignment and Fare Frame x dx.
                
      	2013.01.24 TAP TSI TCVO
   	   [TAP TSI B2 TCVO] Add SupplementProduct  to Product Model  x dx.  
    
     	2013.01.20 TAP TSI TCVP
	   [Tap TSI B1 TCVP] Add notices to Fare product x dx.
	   [Tap TSI B1 TCVP] Add Price Groups to FareProduct x dx.
	   [Tap TSI B1 TCVP] Add Alternativee names  es to Fare product  x dx.
	   [TAp TSI B1 TCVP] Add Back Trip with isAuthorised &  ReturnFareIsDOuble x dx
	   [Tap TSI B1 TCVP] Factor AlternativeName into separate package and move to RC so it can be reused. x dx.
	   [TAP TSI B1 TCVP] Add Alternative names to TARIFF x. dx.
	   [TAP TSI B1 TCVP] Add Description & extensible TypeOfTariff to Tariff x dx. 
	   [TAP TSI B1 TCVP] Add TypeOfTariff to Tariff to allow for TAP TSI code list b.1.1  x dx.
	   [TAP TSI B1 TCVP] Add ReplacesTariffRef to Tariff x dx.
	     
	2013.01.20 TAP TSI TCVC
	   [TAp TSI B1 TCVC] Add ValidityConditions to Organisation  properties x dx
	   [TAp TSI B1 TCVC] Add DelegatsToOrganisation to Organisation  properties x dx
	   [TAp TSI B1 TCVC] Add CountryName to Address x dx 
	   [TAp TSI B1 TCVC] COuntryRef to Operator == domicile Tap.   Add Country as concrete Entity with alt names. x dx
	   
	2013.01.20 TAP TSI TCVG
	   [TAp TSI B1 TCVG] Add  new  routing   package in ND1 )    x dx
	   [TAp TSI B1 TCVG] Add FareStopPoint, as  subclass of  ScheduledStopPoint    x dx
	   [TAp TSI B1 TCVG] Add AccountingStopPoint  to FareStopPoint  properties x dx
	   [TAp TSI B1 TCVG] Add FareStopPointRef to FareStopPoint  properties x   dx.
	   [TAp TSI B1 TCVG] Add BorderPointRef  to FareStopPoint  properties x dx. 	   
	   [TAp TSI B1 TCVG] Add NameOnRouting to FareStopPoint  properties x dx.
	   [TAp TSI B1 TCVG] Add BorderPoint     (new  routing   package in ND1 )    x  dx.  
	   
	   [TAp TSI B1] add Constraints for new elements x nx.
	   [TAP TSI B1 TCVG] Add CustomsOffice as Financial Facility x dx.
	   [Tap Tsi B1 TCVG] Add BaggageCheckInCheck out facility at station x dx.
	   
	2012.01.07 
	   [UK] add buggy and umbrella and passenger cart  to enum for    Accessibility Tools.  x dx 
	   [UK] Add Secure to Parking x dx
	   [UK] A shoeshiner to SanitaryFacility x dx
	   [UK] Add Medical Facility defibrillator & alcohol test x dx
	   [UK] Add Parking car service: Facility Facility, Carwash, Oilchange, engineWarming x dx
	   [UK] Add Parking User type to Parking Capacity, Parking Tariff x dx.
	   [UK] Allow reuse of parking capacity x nx
	   [UK] Add van, large van and all passenger vehicles to vehicle types x dx.
	   [UK] Add list of vehicle types to parking properties x dx.

        2012.09.03 V099.2  3
	   [FR] Correct absolute reference in Infrastructure link file x nx.
	   [Fr] Correct FlexibleLine UML to match XSD notes, order of elem.ents stopPlaces, flexiblePlaces  dx. tx.
	   [Fr] Change FlexibleLine notice UML to use Notice and allow multiple  dx. tx.
	   [Fr] Revise FLexibleServcie Properties to have CancellationPossible etc x dx tx
	   [Fr} COrrect allowed values in flexible network model x. dx. tx.
	   [ER] Correct ContactDetail elements to match UML and XSD Fax, Phone Email,Url, and  reorder x. dx. tx.  MODEL CHANGE
           [uk] add mobilityScooter     to mobilityNeed x dx
           
        2012.09.03 V099.2  2
           [FR] Update WSDL files
       	   [Fr] Add trainTram to Tram submodes   x. dx. tx
       	   [CH] Clarify use of passingthrough  PointsOnLink to ServiceFrame   x dx 
           [RV] Correct integrity constraints for ValidityCondition ConditionedObjectRef x nx.
           [RV] Rename Namespace to Codespace x dx  tx MODEL CHANGE
           [RV] Add defaut Codespaces to Versionframe  x dx tx    MODEL CHANGE
           [RV] rename SiriLineRef, SiriOperatorRef  etc to ExternalLineRef, etc and make a complex  type x dx  tx.
           [RV] Update definition of AccessEquipment  x dx     
           [RV] Update definition of AssistanceService  x dx     
           [RV] Update definition of CommunicationService  x dx           
           [RV] Update definition of ComplexFeatureProjection x dx   
           [RV] Update definition of ComplaintsService  x dx
           [RV] Update definition of ConnectionEnd  x dx
           [RV] Update definition of Control Centre x dx
           [RV] Update definition of Country x dx               
           [RV] Update definition of CrossingEquipment  x dx   
           [RV] Update definition of CustomerService  x dx           
           [RV] Update definition of CycleStorageEquipment  x dx
           [RV] Update definition of DefaultInterchange x  dx
           [RV] Update definition of DeliveryVariant x   
           [RV] Update definition of DisplayAssignment x  dx
           [RV] Update definition of EntranceEquipment  x dx
           [RV] Update definition of EscalatorEquipment  x dx      
           [RV] Update definition of FlexibleArea  x  d
           [RV] Update definition of FlexibleRoute  x  dx
           [RV] Update definition of HeadingSign  x  dx 
           [RV] Update definition of HeadwayInterval  x  dx            
           [RV] Update definition of HeadwayJourney  x  dx           
           [RV] Update definition of HelpPointEquipment  x dx   
           [RV] Update definition of HireService  x  dx
           [RV] Update definition of JourneyAccounting  x  dx
           [RV] Update definition of JourneyFrequencyGroup  x  dx           
           [RV] Update definition of JourneyHeadway  x dx   
           [RV] Update definition of JourneyPattern x  dx
           [RV] Update definition of JourneyPatternHeadway x  dx            
           [RV] Update definition of JourneyTiming x  dx
           [RV] Update definition of LeftLuggageService  x dx   
           [RV] Update definition of LiftEquipment  x dx
           [RV] Update definition of LinkProjection  x dx
           [RV] Update definition of LostPropertyService  x dx           
           [RV] Update definition of LuggageService  x dx
           [RV] Update definition of LuggageLockerEquipment  x dx
           [RV] Update definition of MeetingPointService  x dx
           [RV] Update definition of MoneyService  x dx           
           [RV] Update definition of NavigationPath  x dx 
           [RV] Update definition of Network  x  
           [RV] Update definition of OtherOrganisation x dx   
           [RV] Update definition of OvertakingPossibility x dx  
           [RV] Update definition of PlaceLightingEquipment  x dx     
           [RV] Update definition of PassengerSafetyEquipment  x dx              
           [RV] Update definition of PointOfInterestClassification  x dx              
           [RV] Update definition of PointOfInterestEntrance  x dx              
           [RV] Update definition of PointOfInterestVehicleEntrance  x dx                           
           [RV] Update definition of PointProjection  x dx    
           [RV] Update definition of QueueingEquipment  x dx   
           [RV] Update definition of RampEquipment  x dx 
           [RV] Update definition of CateringService  x dx     
           [RV] Update definition of RetailService  x dx  
           [RV] Update definition of RoadAddress  x dx       
           [RV] Update definition of RoughSurface  x dx    
           [RV] Update definition of RubbishDisposalEquipment  x dx    
           [RV] Update definition of SanitaryEquipment  x dx    
           [RV] Update definition of SeatingEquipment  x dx    
           [RV] Update definition of ShelterEquipment  x dx 
           [RV] Update definition of SignEquipment  x dx       
           [RV] Update definition of StairEquipment  x dx    
           [RV] Update definition of StaircaseEquipment  x dx             
           [RV] Update definition of StairFlight  x dx       
           [RV] Update definition of StopAssignment  x dx                  
           [RV] Update definition of MoneyService  x dx           
           [RV] Update definition of TemplateVehicleJourney  x dx  
           [RV] Update definition of TicketingEquipment  x dx   
           [RV] Update definition of TicketingService  x dx
           [RV] Update definition of TicketingValidatorEquipment  x dx
           [RV] Update definition of TransferRestriction  x dx    
           [RV] Update definition of Travelator  x dx           
           [RV] Update definition of TrolleyStandEquipment  x dx                         
           [RV] Update definition of TypeOfEqipment  x dx    
           [RV] Update definition of TypeOfHandrail  x dx                  
           [RV] Update definition of TypeOfPaymentMethod  x dx              
           [RV] Update definition of TypeOfStopPlace  x dx                
           [RV] Update definition of TypeOfTransfer  x dx    
           [RV] Update definition of TypeOfValidity  x dx  
           [RV] Update definition of UserNeed  x dx  
           [RV] Update definition of VehicleAccessEquipment  x dx  
           [RV] Update definition of VehicleChargingEquipment  x dx                       
           [RV] Update definition of VehicleEntrance  x dx    
           [RV] Update definition of VehicleJourneyHeadway  x dx    
           [RV] Update definition of Via x dx    
           [RV] Update definition of WaitingRoomEquipment  x dx               
           [RV] Update definition of WheelchairVehicleEquipment  x dx    
           [RV] Update definition of ZoneProjection  x dx  
           
           [TIDY] Rename JourneyTimingsModel to JourneyTimingModel 
           [MTG] Make  ControlCentre a type of Organisation Part  x dx tx,    MODEL CHANGE
           [MTG] Add a Type of Time Demand Type  x dx tx,   
           [RV] Rename OtherSign to GeneralSign x dx  tx     MODEL CHANGE
           [RV] Rename StopPlaceEquipment to SiteEquipment  x dx  tx   
 	   [RV] Add a GeneralOrganisation & make Other Organisation abstract x dx tx.
 	   [RV] Add LineRef   DirectionRef DestinationDIsplayRef to HeadignSign x  dx tx
 	   [RV] Add ClassOfUsSeRef to WaitingRoomEequipment x tx
 	   [RV] Add SuitableforCycles to Ramp, Lift, Entrance. Crossing, tx
 	   [RV] Rename StopPlaceSign to PlaceSIgn x dx tx
 	   [RV] Correct constraints on OverTakingPossibility and Network Restriction x
 	   [RV] Add RelativePosition to TrainStopAssignment x dx.
 	   [RV] Correct type of Vehicle Stopping position x
 	   [RV] Correct types on DataSourceRef x 
 	   [RV] Allow Topic data source to be ref 
 	   [Rv] SImplify FrmaeRequestFilter by dropping AbstarctObejctRequestFilter  x
       2012.08.01 V099.2   1 
	  [CH] Add SiriLineRef and SiriDirection ref to InterchangeRuleLineFilter x. dx.
	  [CH Add Integrity constraints for ControlCentre and TypeOfJourneyPattern x.
	  [CH] Add ControlCentre to ResourceFrame  x dx tx,
	  [CH] Updated VDV example, revised for latest schema. x
	  [UK] Revise and  correct Parking attributes, add Bay  dimensions and power points x dx.
	  [FX] Correct Projection/PointOnLink implementation to be a ref not containment, allow by distance ref too x dx
	          Note that POINT ON LINk can aslo be  defined as part of a LINK.
	  [FX] Revise and simplify dependencies. 
	  	  Modularisation move JourneyTimings from VehicleJourney to JourneyTiming package
   	  [RV] Correct VehicleEntry comments   x dx
   	  	   Correct model for journey daytypes  1:* dx
   	  	   Add default sense of Restricted to InfrastructureFrame x tx.
   	  	   Correct comments in model  dx
   	  	   Correct Dead run diagram. dx
   	  [RV] Rename TimingPointType to TypingPointStatus  x. tx
   	  [RV] Add parent to parking capacity x. 
   	  [RV] Add reverse direction to xml x. tx
   	  
   20120.07.22 V099.1 6
   	  [Schaffhausen] Interchange Rule Rename NextStopPoint etc to Adjacent Stop Point x dx tx. MODEL CHANGE
   	  [Schaffhausen]  Add number to Course of Journeys x dx tx
   	  [Schaffhausen] Correct some public facing strings to be Multilingual x dx
   	  [Schaffhausen] Correct comments on Offset to be relative to Start of journey x dx tx
   	  [Schaffhausen] Add PointNumber to PointGroup  x dx   tx
   	
   2012.06.18  v0.99,1  
        [Schaffhausen] Rename NetworkRestriction possible to Restricted x dx MODEL CHANGE
        [Schaffhausen] Revise OvertakingPossibility, MeetingRestriction and Manouevre; allo multimodal combinations and drop Road/Wire/Railway variants 
                            Revise OvertakingPossibility to have overtaking /overtaken VehicleRef         x dx. MODEL CHANGE
                            Rename Manouevre to RestrictedManoeuvre x dx   MODEL CHANGE
        [Schaffhausen] Add request button to help equipment.  x dx 
        [Schaffhausen] Allow default mode and operator on network x dx
        [Other] Correct HelpPointEquipoment in UML model.  x dx MODEL CHANGE
         [Schaffhausen] Correct HelpPointEquipment in model.  x dx
        [VDV]          Add ActivationPointNumber to ActivationPoin  x dx.
        [VDV] Add Privatecode to CourseOfJourney x dx.
        [VDV] Add Real-time alias  codes x
        	ScheduledStopPoint  SiriStopCode x tx
	       Operator  SiriOrganisationCode  x tx
	       Line SiriLineCode x   SiriProductCategoryCode x tx
	       Direction SiriDirectionCode x tx
	       Connection SiriConnectionCode x tx
	       ProductCategory SiriProductCategoryCode x
	       VehicleJourney  SiriJourneyCode x tx
	       DatedVehicleJourney  SiriDatedVehicleJourneyCode x tx
	       InterchangeRule SiriInterchangeCode x
	     
        [Init] Make TimeZoneOffset fractional x dx.. tx
        [SE] Make DayOffset relative to start of journey.  x dx. tx.
       [ Other] Add missing TypeOFProductCategory element  x   tx
       [Other] Add SuitabletoCycle to Ramp, x dx tx Entrance x dx tx, Lift x dx tx
    
 2012.03.17  v0.99,1 (5)
 	   Add  partial value for LimitationStatus  [RATP] x dx tx
 	    Change to use SIRI 2.0
  	
    
    
   2012.03.17  v0.99,1 (4)
 
  	- Tidy
  		Delete phys relationship 
 		Rename IdType to Ref in UML diagrams x dx tx.
 	-  Paris 
 		Rename OtherSign to GeneralSign x dx tx
 		Add a GeneralOrganisation & Make other Oganisation abstract x dx tx
 		Add GeneralZone x dx tx.
 		Add FareClass to RequiredCapacity and vehicle Passenger  Capacity x dx tx  
 		Make Passenge Capacity first class object x dx tx MODEL CHANGE
 	- Examples
 		Improve flexible stop assignment
 	 
 		
  	- Corrections
   		Revise  attributes on StopAssignment
   		Add Name, ServiceJourneyInterchange Move order of ScheduledStopPoint  x dx MODEL CHANGE
   		Add missing NavigationPathAssignment
   		Make FlexibleService properties a DataManagedObject so can be reused x dx tx
   		Add FlexibleServiceProperties, FlexibleLinkProperties & FlexiblePointProperties to Timetable frame x dx tx 
   		Rename FlexibleLinkProperties to Property TODO x dx MODEL CHANGE
   		Add flexiblePointProperties to call x   tx  TODO
   		Add reverseMembers to LineSection  x  dx tx
   		Add JourneyAccountings to timetable frame x dx tx
   		Rename serviceFacilityLists serviceFacilitySets   x dx MODEL CHANGE
   		VehicelJourneyHeadway shoudl reference TimingPointInPattern, not timingPoint x tx modelchange
   		Move PRivateCode to StopAssignment from PassengerStopAssignment x dx
   		Add runtime tp OnwardLink view x tx
   		Rename notices to noticeAssignments where relevant x dx MODEL CHANGE
   		Correct DatedPassingTime to have DatedJourneyRef x dx
   		Correct Model for PassignTtime to use DayOffset dx tx  
   		Add missing ControlCentreNotifyThreshold to xml x dx tx
   		Change order of Description on JourneyPart x dx MODEL CHANGE
   		Add CoupledJourney to Timetable frame x dx tx
   		Make TrainBlock a type of Block x dx 
   		Add VehicleServceParRef to block x dx tx
   		Add CompoundBlockRef to BlockPart x tx
   		In CompoundBlock Rename FromPoint & ToPoint to StartPointRef & EndPointRef x dx tx MODEL CHANGE
   		For Schematic Map  Change Number of Pixels int to GraphicsUnits float 
   		Rename orgisationTypes to typesOfOrganisation  c dx MODEL CHANGE 
   		Add length  of access area to WheelchairAccessEquipment  x dx 
   		Revise ServceiFacility & SiteFacility order of facilities (Catering, etc)  x dx MODEL CHANGE
   		Rename TypeOfAccesibilityTool to ACcessibilityTool x dx
   		Revise  FacilitySet to be mroe uniform: allow type of equipment as "other facilitry". x dx MODEL CHANGE
  
 		
        - SIRI 
 		Make COntrol Centre a Type of ORGANISATIONAL UNIT to match SIRI definition  x dx cx TODO
 		
 
 
  2012.01.16  v0.98,9

  	- CD Turin: 
  		Pathlink; Add Back heading as well as Towards heading x dx.
 		Add DriverRef x dx
 		Add Control Centre with attributes to TransportOrganisationPackage  (DropControlCentreSupport file)  x dx. CX
 		Merge UIC ValidityCondition Daybits into Availability Codition x
 		Allow TariffZones in SiteFrame x dx
 	- KB Model comparison correcytions
 		Drop  Monitored Vehicle Journey from Part2  (Move to separate MonitoredJourney package for future use) x dx
 		Drop Estimated & Observed Passing times from Part 2 (Move to separate MonitoredJourney package for future use) x dx
 		Make Interchange/ Priority an attribute dx.
 		Move ParkingTariff to separate package in part3, Also move to fare frame  x dx MODEL CHANGE
 		Rename FootnoteAssignment to NoticeAssignment x dx  CX
 		Rename DefaultTransfer to  DefaultConnection  x dx MODEL CHANGE CX
 		Rename AccessRighstModel to  FareRelatedRestriction x dx 
 		Add TimeDemandType to Interchange Rule  parameter  x dx
 		Rename AccessibilityTool to TypeOfAccessibility Tool x dx
 		Split TicketingFacility into TicketingService + TicketingFacility x dx  CX
         -  NK xsd /doc Corrections of  Errors and ommisions nk
	   	Correction : DatedJourney & Journey are types of Journey_ 
  		Revise xsd dependencies to be more specific, correct _support only dependencies x
 		Correct PARKING: Add enhancements to Areas, x dx MODEL CHANGE
 		Rename Refreshments  to Catering  x dx MODEL CHANGE 
 	      	Change Cardinality of  of extensions to be many  x 
 	        Correct names of local service (equipment) and local service (package) x
 	        Add meeting point Equipment to xsd x CX 	  
 	        Add pointonRouteRef to flexiblePointProperties x 
 	        Add notices, DestinationDisplayRef and vias to  PointIn Pattern x dx
 	  	Add runTimes to TimingLinkInJourneyPattern x.
 	  	Make ServiceJourneyPattern a Type of JourneyPattern x.
 	  	Align ServicePatternProperties with JourneyPattern  x.
 	  	Move PrivateCode to LinkSequence (from Route, ServcePattern  x dx MODEL CHANGE
 	  	Rename StopPointInJourneyPattern / notices to noticeAssignments  x dx MODEL CHANGE
 	  	Align diagrams to show GroupOfTimingLinks as part of TimingPattern model, not TimeDemand Model  dx
 	  	Add GeneralFrame example  ex
 	  	Add Entity_Entity example .ex
 	  	Allow Enity_Entity in GeneralFrame x dx  CX
 	  	Add TypeOfValidity x. CX
 	  	Add Organisational Unit & Revise OrganisationPart & Dept x dx CX
 	  	Add TypeOfOrganisatrionalPart  x dx    CX
 	  	Add missing attributes to OrganisationalPArt
 	  	Add TypeOfEntity  x dx  CX
 	  	Add OrganisationRef to OrganisationPart x
 	  	Revise ClassRef to be consistent with Ref x
 	  	Add TransportAdministrativeZone with modes  x   dx CX
		Add TypeOFLinkSequence GroupOfLinkSequences x CX
		Correct LinkInLinkSequence x
		Simplify LimitationsStatus x
		Move Place,   from ifopt to framework  model x
		Move   Accesibility from resuable components to framework  model x
		Change order of PriamryMode on Opeartor x dx MODEL CHANGE
		Move equipmentPlace, topographicPlace from ifoptto resuable components x dx
		Add  TypeOfEquipment   x CX
		Add missing constraints for Equipment, LocalService and added entities,  x
		Correct id constraint on ResponsibilitySet x 
		Add more integrity constraints for Equipment, etc x
		 
 	  - CD  NEPTUNE 
 	  	Add AccessibilityAssesment to Line x dx
 	        Allow equipment places on site as well as site components x dx
 	        Allow InverseRef on Route x dx
 	        Add GeneraGroupOfEntites concrete x dx  CX
 	  - GD VDV
 	  	Add PrivateCode to TypeOfValue x dx doc
 	  	IntrerchangeRuleTiming corrected to add Timings x dx 
 	
 2011.12.10  v0.98,8.
       - Consistency
          - rename TypeOfNavigation to NavigationType x dx MODEL CHANGE  CX
       	  - rename NavigationPath/  features to NavigationPath/  summaries x dx MODEL CHANGE
       	  - Corrections to  comments for spelling and grammar
       	  - Correct type on EntranceRef x
       	  - Add ServiceSite x dx CX
       - Revise spelling and punctuation on comments
       - Correction:  change order of Block Prep and finish duration  x dx MODEL CHANGE
       
       - UB mapping 
       	  - V1
		 - 1.#48 Add Place Ref to ServiceJourney Origin [ub]  x   
		 - 1.#74 Change KeyList to lower case keyList [ub] x   MODEL CHANGE
		 - 1.#73 Add ViaType to Via: StopPoint or name [ub] x dx. 
		 - 1.#101  Add Service requirement to Call to allow for change [ub] x dx 
		 - 2.#15,#16 Add Service CalenderRef to VehicleScheduleFrame [ub] x dx. 
		 - 2.#16 Add Service CalenderRef to VehicleScheduleFrame [ub] x dx. 
		 - 2.#30, #37 Add Vvalidity Conditions to Block [ub] x dx. 
		 - 2. #33, #35 add explicit Start and end time to Block [ub] x dx. 
		 - 2. #47, Add lineRef and Direction to designator [ub] x dx. 
		 - 2. #57, add ArrivalDayOffset  [ub] x dx 
		 - Update Noptis examples
       	 - V2
       	   	 - 1. #35 Add start day offset from current operating day to Block
       	   	 
       	- CD /KB
       	   	 - Add complex feature projection  [cd]  x  dx.
       	   	 - Add Train Block, Train Block Part[cd]  x dx.
       	   	 - Correct Cardinality on sources/DataSource  [cd]  1:*  x
       	   	 - Add TemplateVehicleJourney to XSD  [cd]  x  
       	   	 - Align JourneyDesignator [cd]  dx
       	   	 - Add VehicleTypeRef to VehicleTypePreferenceGroup [cd]   x
       	   	 - 
       	 - GD/MK VDV Mapping  	 
		 - Add  <PrivateCode>, <ShortName> and <Name> to OperationalContext. [vdv] x dx 
		 - Add <DriverDisplayText> to DestinationDisplay:  [vdv]  x dx.
		 - Add  PrivateCode> to  Notice. [vdv]  x  dx. 
		 - Add  PrivateCode> to   ServicePattern:    [vdv] x dx.
		 - Add  PrivateCode> to  Route:  [vdv]   x dx.
		 - Add <NextStopPlaceRef> to  InterchangeRule  filtesr  [vdv] x dx.
		 - AlLlow multiple timings on InterchangeRule   [vdv] x dx..
      
       		
       	 
 2011.11.25  v0.98,7
       - Berlin meeting decisions
     	  - Submode/OperationalContext
 		- Add OperationalContext and use instead of Submode on TimingLink, JouruneyPattern, ServiceLink, ect x dx MODEL CHANGE CX
 		- Add OperationalContext to TimeDemandType x dx MODEL CHANGE
 	
 	  - InterchangeRule
 		- Add InterChangeRuleTimings to Interchangerule x dx MODEL CHANGE  CX
 		- Add validity condition to interchange rule x dx
 		- Add operator to InterchangeRule x dx
 		- Allow exclusion on rule x dx
 		
 	- Rename frequencies to headways on TimeDemandType x dx MODEL CHANGE
 	- Simplifications
 		- Drop use of _entities
 		- modify netex_publication to require the  use of a frame 
 		- Wrap frame defaults in a wrapper
 	- Revise journey designator and allow use on Blocks
 	- Correction: allow journeys in Blocks without course fo Journeys
 	- Fares
 	  - Correct use of Transferability x dx FARE MODEL CHANGE
 	  - Add some validable elemenst and access rights to examples
 	  - Colour for fare demand type DONE x dx
 	  - Add CombinationPrice and use where there is a multidemnsional price  x dx MODEL CHANGE 
 	- Other Changess
 	  - Rename NetworkTopology to LineNetwork  [kb]  x dx MODEL CHANGE
 	  - NPTG Add parts add contact details to organisational [uk]  part  
 	  - Consistency: Rename Responsibility / Description to Responsibility / Name x dx
 	  - Correction: correct  type on TypeOfOrgansiationRef x
 	  - Correction to Topological Place  - Add missing  contained  in rel. Add missing structural types x
 	  - Correction to CoupledJourney add PurposeOfJoourneyPartition  as open value  x dx

    
 2011.11.01  v0.98,6   
     - Revise Fare model
 	- Correction Allow multiple Usage parameters Refs on Usage Parameter Price s  FARE  MODEL CHANGE x dx
 	 -Correction FareStructureElement shouldl reference GeographicalStructureFactro, not GeographicalUnit
 	 - Correction FareStructure  allow declataion of  GeographicalStTructureFactors
 	 - Add draft Travel Document  and Sales Package x dx  CX
 	 - Add integrity constraints for TimeIntervals
 	 - Make order of FareStructure components consistent x dx FARE MODEL CHANGE
 	- Add more examples
 	      -	Add  Zone fare with separate availability & Sale package
 	      -	Add Sales packages to some examples
 	      -	Add a return fare product  to simple direct fare model
      - Minor techncial corrections  after Teleconference on model issues
	   -Equipment  
  	      Make  PassengerEquipment a type of InstalledEquipment (Rather than  a type of Place Equiopment CX
  	      - Simplify: Merge Vehicle Equipment and Actual Vehicle Equipment x dx MODEL CHANGE
    	      - Correction: Rename PasssengerEquipmenetIdType to PassengerEquipmentIdType
    	      - Modularisation: Move PassengerEquipment to base Equipment package   x dx.
    	      - Correction physical model : Each equipment position  points to one Equipment only dx. 
    	      - Simplify: Make Accommodation and BoardingPermission types of Facility
    	      - Simplify: Merge PassengerInfoEquipment and PiFacility and VehicleInfoEquipment as PassengerInformationEquipment CX
    	      - Correction: Rename SanitaryFacilityEquipment to SanitaryEquipment x MODEL CHANGE CX
    	      - Correction Remove duplication SurfaceEnum
    	      - Add optional RoutePointRef to Via 
    	    - Facilities 
    	         - Rename   xxxList  simpleTypes to xxxxListofEnumerations
    	         - Rename xxxFacilities elements  to xxxFacilityList  x dx  
    	         - Rename PtInfoFacility to PassengerInformationFacility
    	         - RenameTypeOfSanityFacility to SanitaryFacilityList
    	         - RenameTypeOFSanityFacility TicketingServiceType to TicketingServiceList
    	         - Rename LuggageServiceType to LuggageServiceFacilutyList
    	         - RenameAssistanceServiceTyupe to AssistanceFacilityList
    	         - Add SafetyFacility List  
    	      - Revise TimeDemandTimings
    	      	 - reanme TimeDemandTiming to JourneyTiming 
    	      	 - Rename TimeDemandTiming to JourneyTiming x dx MODEL CHANGE
    	      	 - Rename TimeDemandRunTime to JourneyRunTime x dx MODEL CHANGE
    	      	 - Rename TimeDemandWaitTime to JourneyWaitTime x dx MODEL CHANGE
    	      	 - Rename TimeDemandLayover to JourneyLayover x dx MODEL CHANGE
    	      	 - Rename TimeDemandHeadwayInterval to JourneyHeadwayInterval x dx MODEL CHANGE
    	         - Allow TimeBandRef on JourneyTiming x dx
    	         - Add timedemandtype to TImingdemandProfile xdx
    	         - Allow TimebandRef as alternative to TimeDemandtypeREf on Call, JourneyPattern etc x dx
    	         - Move vehicle typePreference from VehicelJourneyTimesPackage to  to JourneyTimesPackage
    	         
   	   	-  Correction move VehicleTypePreference to JourneyPattarenTiming pacakge	
    	      -Rename Footnotepackage  to NoticePackage  x dx 
   	   -  Move turnaroundtimelimit to  JoruneyPattern  timings x dx  
     	   -  CorrectionUse VehicleMode where  relevant	 
     	   _ add equipment ref to check constraint
     
     	 Changes to Align models from Kb spreadshee
     	     - JourneyHeadways	
     	  	   - Allow wait times on Timing point in pattern x dx.
     	  	   - Renanme JourneyHeadwayInterval to JourneyHeadway x dx.
     	  	   - Correction: Add JourneyPatternHeadway to JourneyPattern x dx.
     	  	   - Correction rename headwayIdType to JourneyHeadwayIdType x  .
		    - Correction: Add headways to TimingPoints  x dx.
     	     - TimeDemandTypes
     	         - Align: Move TimeDemandTyupe package to Part 1 TP  x dx.
     	         - Align  MoveVehiclePreference to  TimeDemandPackage x dx.
     	         - Move JourneyTiming to TimeDemandPackage x dx.
     	         -  Rename JourneyTiming to JourneyDemand x dx.  CX
     	     - Equipment
     	         StopPlaceEquipment  diagramRenamed SiteEquipment  dx
     	     - InterchangeRule   
     	   	- Move Interchange and InterchangeRule support to part2 JourneyTimes package s
     	        - Rename InterchangeRuleFiler to InterchangeRuleParameter x dx MODEL CHANGE
     	        - Make InterchangeRule a type of Interchange, refactor attributes x dx MODEL CHANGE
    	 
    	 Tidy ups
    	      Correction allow network to  ref an authrity and a grousp of lines   x 
    	      Correction Allow NetworkTopology to refercnhe a group of lines  x dx MODEL CHANGE 
    	      Correction RoutingConstraintsall  ref to  refPointstInPatternbe associated with garage 
    	      Ccorrection allow crewbases to ref garages x
    	      Correct type of StopAReaRef x
    	      Correction add Access ZOne  x
    	      
 2011.09.16  v0.98,5   
 	- Correction Rename WaitPoint PointInJourneyPattern to IsWaitPoint to avoid ambiguity 
 	- Correction add referential integrity check forClassOfUSe etc x
 	- Correctionn add integrity  constraints to check  PointInPatternRefs
 	  - Add draft Fare Schema  x dx
	       -Add Fare Frame	  
       		  - Add draft fare elements
	          - Add fare examples
 	 - Add CurrencyType to Frame	x dx     
	        - Add not working day
	        - Add GroupOfTimebands to enable fares   
   
	 
	 - Simplification/ Correction to PointsInJourneyPattern: 
	        - Make StopPointInJourneyPattern a type of TimingPointInJourneyPattern a type fo PointInJourneyPattern     x.dx    
	 	- Rename LinkInServicePattern  to ServiceLinkInServicePattern, TimingLinkInJourneyPattern  MODEL CHHNGE  x
	 	- Rename LinkInServicePattern/LinkRef to  ServiceLinkRef, TimingLinkRef MODEL  CHANGE  x
	 	- Drop Stop point attributes from PointInJourneyPattern, make StTopPoint in JourneyPattern & JTImingPointInJourneypattern more consistent MODEL  CHANGEx
    
 2011.09.16  v0.98,4
 	- Allow vias on Destination Display. Wrap Vias as Via element and allow name  x dx **  [ub]   MODEL CHANGE
	- Correction rename  StopPlace/ VehicleStoppingPositions, VehicleAlignmentPositions lower camel case   x MODEL CHANGE
	- Correction: rename FacilitySet / Available to availabilityConditions x  MODEL CHANGE
	- Correction: make topics & policies on request upper camel case - all examples x.
	- Correction: Add StopPlaceCompomnent group to StopPlaceEntrance.
	- Technical - rename all relations _RelStructure x.
	- Add Submode as open type x dx. [vdv /delft]
	- Change department ref to SubmodeRef on Line, Route Link, JourneyPattern, ServiceLink, TimedemandTiming , TimingLink , Vehicle Journey   x dx. [vdv /delft]
	- Revise Origin Destination on Servcie Journey to allow name only, and on dead run to allow type x dx.  MODEL CHANGE	 
 	- Correction - Add integrity  constraint for NextStop on Interchange rule x
 	- Add   Day Number to OperatingDay  x @dx. [vdv - delft]
 	- Add Bearing to VehicleStoppingPosition, clarify use or bearing x @dx [vdv - delft]
 	- Examples :
 		add example of feeder / distributor filter on Interchange rule
 		add example of Simple flexible service
 		add exampke of Hail and ride to Netex_01.4_Bus_SimpleTimetable_WithConnection.xml
 	- Add PointRef and PlaceRef to Feeder/Distributor filter  x dx.  [vdv, ub - delft]
 
 	- Revise Footnotes /Notices [vdv - delft]
 		- Combine Notice & Footnote as Notice  x dx. [delft]
 		- Correction - Add noticeAssignmenst to servce frame , revise order to be consistent with tometable frame  x dx MODEL CHANGE
 	  	- Correction - Add referential integrity check for Notice Assignment x
 		- Add Driver Display text to Notice  x dx. [delft]
 		- Distinguish between Advertised (On assignment) and CanBeAdvertised (on Notice    )  x @dx  [ub]
 		- Add PublicCode to Notice x @dx  [vdv - delft]
 		- Dependency: Move FootNoteAssignment to from Part2 JT to  Part1 TP 
 	- Support Vehicle Loading : [era - delft]
 		- Add to StopPlaceType enum : new value of   VehicleRailInterchange, x dx
 		- Add to QuayType enum : new value of  VehicleLoadingPlace, x dx
 		- Add to BoardingPositionType enum : new value of VehicleLoadingRamp, x dx
 		- Add to CheckConstraint Type enum : new value ofvehicle Loading/Unloading to CheckCOnstraint Type 
 		- Add VehicleEntrance to SiteModel, with Public attribute.  x dx ** 
 		- Add StopPlaceVehicleEntrance, PoiVehicleEntrance, x dx, as typt e of   VehicleEntrance
 		- Make existing ParkingVehicleEntrance a type of VehicleEntrance   x dx CX
        - Allow check in times: Add CheckConstraints to ServiceJourney  x dx**  [era - delft] 
	- rename Mode value telecabine to cableway as this is more general x dx MODEL CHANGE
	- Rename FlexibleService Type enumeratioms mixed, fixed, x. dx. MODEL CHANGE
	- Correction add referential integrity check for Flexible Areas etc x
	- Add "checkout" value  to  CheckConstraint processes enum  x dx. [ers]
	- Add OnboardStay + BoardingPermission enum  to facilitoes  x dx.   [era - delft]
	- Add Operator Ref to deadrun x dx [ ub  ]
	- Add DeadRunCall    to deadrun x dx [ ub  ] CX
	  Add Booking Arrangements: BookingMethod, BookingCOntact, LatestBookingTime, MinimumBookingPeriod, booking notes to Flexible line. x dx. [ub -delft]
		 - Add ChangeOfDestinationDisplay to Call etc  [ ub - delft  ]
	 	 - Add ChangeOFServceRequriements  to Call etc  [ ub - delft  ]
	- Added Print advertisement to Service Journey & Special Service   x dx. [ ub - delft  ]
	- Revise Vehicle Type & Service requirements x dx	[  delft  ]
		- Add PassengerCarryingRequrementView to ServiceJourney   x dx	[ ub - delft  ]
		- Correction:  rename PassengerInformationFacilities PassengerInfoFacilities to be consistent x. dx  MODEL CHANGE
		- Correction: AccessibilityInfo to  AccessibilityInfoFacilities x. dx  MODEL CHANGE
		- Move vehicle passneger equipment from ifopt to Resuable components 
		- Correction remove duplicate enum defs for AcecssibilityInfo, PassengerInfo
		- Correction : add actualVehicleEquipments to vehicle x. dx,
		- Correction : Rename equipment to equipments x. dx  MODEL CHANGE
        - Revise  ValidityTrigger and Validity Rule parameter x. dx  MODEL CHANGE
        	- Correction Separate Trigger from rule as COnditions
        	- Correction  Make interchange use  validity Condition (was an availability condition)
        	- CorrectionMake Parking use  validity Condition (was an availability condition)
        	- Add integrity constraints for  ValidityTrigger and Validity Rule parameterx
       
        	 
	
 2011.09.06  v0.98,2
   - Further corrections
   	- Add explicit inFrame relationships
 	  - Correction ServiceFrame - de-nest Type of service x MODEL CHANGE
 	  - Correction make RoutingConstraimntZone a sg of Zone  x
 	  - Simplification ServiceFrame consolidate notices/footnotes in Frame x MODEL change
	  - Correction make all dummy supoertyupe sabstarct x
	  - Simplification - SITE frame add separate rel for flexible  x MODEL CHANGE
	  - COrrection SITE Frame - add ParkingTarriffs
	  - Correction ResourceFrame - Separate out departments, groups of operators x MODEL CHANGE
	  - Correction InfrastructureFrame - Change name to activatedEquipment x MODEL CHANGE
	    - Correction InfrastructureFrame - Separate out garages, crewbases  x MODEL CHANGE
	- Correction: Make PathJunction a point not a   Place x dx MODEL CHANGE
	- Correction: various substitution groups
	- Add journey acocunting to timetabel defaults x dx [txc]
	- Add DayOfYear to Properties of Year,  add RegionalHoliday to HolidayTypes   [x dx txc
	- Example:Add new  example of cancellation / extra journey 
	- Example: Add  holiday day types example to Bus_SimpleTimetable_withtimings. e
	- Example: Add serviced organisation term  holiday day types example to Bus_SimpleTimetable_withConnection. e
	- Add classOfuse to check constraint,  sitecomponent x dx  [opl]
	- Correction:  add SiteFacilities to SiteFrame x dx  [opk]
	- Correction:  add FootnoteAssignments  to TimetableFrame x dx  [opk]
	- Correction - Allow ServiceJourneyInterchanges to be associated with Calls. Update examples  x dx.
	
2011.07.17  v0.98,2
   - Further corrections
   	 -Technical
  		 - Fix dependencies in journey version   
  		 - Update  .sprt file for oxygen
  		 - Restructurue dependencies to make more modula  and rreuse
  		 - Add a "Netex Lite"  netex_pubvlication_timetable  schema  to reference just  timetable related elements. 
  	 	 - Simplifcation: Drop _Class use ref *all or xx_All with XsiType  
  	 	 - Assign one to many relationships to containment etc., uniform ref/version for aggregated elements vs strictContai9nment
  	 - Add TypeOfLine to LINE for OD support  x dx. [osm]
  	 - Add TypeOfKey attribute to KeyValue x. 
  	 - Add Submode to Mode TypeOfValue. x.
  	 - ServiceCalendar file Correct ServiceCalenderFrameRefs to be ServiceCalendarRefs x.
	 _ Correction - Add TypeOfJourneyPattern> use this instead of TypeOfService on JourneyPattern x. dx.
	 - Correction - drop empty sequence from JourneyPartStructures [cd]
	 - Correction - Add  missing TimingAlgorithmType x [cd] 
	 - Correction - Drop spurious sequence from  JourneyPartStructure x [cd] 
	 - Revise SITE  PublicUse to allow for  all | disabledUsersOnly | authorisedUsersOnly | staffOnly | publicOnly [naptan dft] x. dx. [Model CHANGE]
	 - Correction - Rename  InterchangeRuileFilter.ServiceRef  to  InterchangeRuleFilter.ServiceJourneyRef x. dx  [ub]  [Model CHANGE]
 	 - Correction NetworkRef should be a subst group of GroupOfLinesRef x. [nk]
 	 - Corrections - various cardinalities eg on Timings should be 1:0 not 1:*  x.
 	 - Add DestinationViaGroup to PointInJourneyPattern so that can specify at journey pattern level as well as Journey level  x. dx. [ub txc]
 	 - Modularity:  For PointOn Link allow inline Point as alternative to PointRef x. [ub]
 	 - Correction - Drop StopAreaRef from Connection end.  mark mode as derived  x. dx. [ub]
 	 - Add a From & Tto Visit number to Interchange to handle the case of circular journeys with multiple connections at the same stop  x.  dx.  [ub]
 	 - Correction -  Add Parking elements to end of SITE CONNECTION x.   
 	 - Correction ServiceCalendarFrameREf is type of VersionFrameRef x.
 	 - Correction:  correct  Garage GaragePoints containment x.
 	 - Add Monitored to Line  to indicate if real-time data available   x. dx. [dl]
 	 - Correction - Equipment ids. x
 	 - Correction - Comments on Resource farme  ids. x.
 	 - Add RubbishDisposal to passenger  Equipment x dx [BVW] ** CX
 	 - Allow UicOperatingPeriods in Service CalendarFrame x dx [sj-uicj]  **
 	 - Add contact email to DataSource x. dx.  [ub]
 	 - Add TransportMode to DeadRun (on Journey)  x. dx. [ub]
 	   - Make DeadRunTypeOptional  x. [ub]
 	   
 	    - Add JourneyAccounting Element x dx [ub] txc ** CX
 	    - Add PublicityChannel to ServiceElement: all, printed, dynamic, none x, dx, [ub]
 	    - Add PublicityChannel to FootnoteAssignment:  all, printed, dynamic, none x. dx. [ub]
 	 - ADd KEYLIST to DestinationDisplayView   x. [ub]
 	 - Add BookingMethod, BookingCOntact, LatestBookingTime, MinimumBookingPeriod to Flexible line. x dx. [ub]
 	 - Correction: Add FlexibleLineView so FLEXIBLE LINE Line propertie can be shown on service jour.ney x dx. [ub]
 	  - Allow  list of notes for Booking note,     x dx. MODEL CHANGE x dx [ub]
 	 - Allow  list of values for BookingMethod     x dx. MODEL CHANGE
 	 - Add TrainSize requurements to Train x dx [ub]
 	  - Add   hasLiftOrRamp  requrements to VehicleType x. dx. [ub]
 	  - Add VehicleType propertie s to service journey x dx [ub]** 
 	  - Add frame defaultLocale x dx [era] MODEL CHANGE
 	  - Reservation added to StakeholderRole x. dx. [uic]
 	  - Add summer timez zone offset to locale x dx [uic]
 	  - Correction - Revise  SserviceOrganisation etc to match model. Add OrganisationDayType & Reuse servise Calendar  x. dx. [txc]  ++
 	  
	   	  
 	  -Add UicAvailabilitryCondition that allows ValidDayBits  x dx [era] 
 	  - Reservation facilitie sadded for uic 7037 x. dx. [era]
 	   
	  		<xsd:enumeration value="reservationsCompulsory"/>
			<xsd:enumeration value="reservationsCompulsoryForGroups"/>
			<xsd:enumeration value="reservationsCompulsoryForFirstClass"/>
						<xsd:enumeration value="reservationsCompulsoryFromOriginStation"/>
			<xsd:enumeration value="reservationsRecommended"/>
			<xsd:enumeration value="reservationsPossible"/>
			<xsd:enumeration value="reservationsPossibleOnlyInFirstClass"/>
			<xsd:enumeration value="reservationsPossibleOnlyInSecondClass"/>
			<xsd:enumeration value="reservationsPossibleForCertainClasses"/>
			<xsd:enumeration value="groupBookingRestricted"/>
			<xsd:enumeration value="noGroupsAllowed"/>
			<xsd:enumeration value="noReservationsPossible"/>
			<xsd:enumeration value="wheelchairOnlyReservations"/>
			<xsd:enumeration value="bicycleReservationsCompulsory"/>
			<xsd:enumeration value="reservationsSupplementCharged"/>
			
	  
	    -Add BookingProcess  uic 7037  x. dx. [era] 
	    		<xsd:enumeration value="productNotAvailable"/>
	    		<xsd:enumeration value="productNotBookable"/>
	    		<xsd:enumeration value="bookableThroughInternationalSystem"/>
	    		<xsd:enumeration value="bookableThroughNationalSystem"/>
			<xsd:enumeration value="bookableManuallly"/>
	  			
	  -Uic Product Characteristic    UIC 7139 Code list x. dx. [era]  
			<xsd:enumeration value="allIInclusivePrice"/>
			<xsd:enumeration value="eastWestTariff"/>
			<xsd:enumeration value="trainWithTcvAndMarketPrice"/>
			<xsd:enumeration value="noPublishedTariff"/> 
						 
	   - Uic Rate Type UIC 5263Code list</xsd:documentation> x. dx. [era]  
							 
			<xsd:enumeration value="normal"/>
			<xsd:enumeration value="discountInTrain OtherThanTGV"/>
			<xsd:enumeration value="specialFare"/>
			<xsd:enumeration value="supplement"/>	
			<xsd:enumeration value="noPublishedTariff"/>
 	  
 	    -Add Meal   x. dx. [era] 
			<xsd:enumeration value="breakfast"/>
			<xsd:enumeration value="lunch"/>
			<xsd:enumeration value="dinner"/>
			<xsd:enumeration value="snack"/>
 	    
	    `-Add BoardingPermission   x dx [era] 
			<xsd:enumeration value="normal"/>
			<xsd:enumeration value="boardingPossible2HoursBeforeDeparture"/>
			<xsd:enumeration value="alightingPossible2HoursAfterArrival"/> 
			<xsd:enumeration value="boardingPossible30MinutesBeforeDeparture"/>
			<xsd:enumeration value="alightingPossible30MinutesAfterArrival"/>
			`<xsd:enumeration value="overnightStayOnboardAllowed">


		-Add FamilyService   x. dx. [era] 
			<xsd:enumeration value="none"/>
			<xsd:enumeration value="servicesForChildren"/>
			<xsd:enumeration value="servicesForArmyFamilies"/>
			<xsd:enumeration value="nurseryService"/>
 	   -Add DaysOfWeek to UicOperatingPeriod  x dx [era] 
 	     -Allow negative day offset x dx [era] 
 	 - Add linksequenceProjection to handle LineString etc x dx   [gtfs]    
 	     
	
* The physical schema has a DutyStretchModel which is not in the XSD 
2011.07.04  v0.98,1
   - Further VDV enablement changes
  	 - Add VehicleMode to TimeDemandTiming [vdv] x dx. 
  	 - Add VehicleMode to ServiceLink [vdv] x dx.
  	 - Add VehicleRegistrationNumber & OperatorRef  to Vehicle [vdv] x dx. 
  	 - Add PrivateCode to TimeDemandType, InterchangeRule [vdv] x dx. 
 	 - Add ControlCentreRef to  , InterchangeRule [vdv] x dx.  
 	 - Add MaximumTransferTime  to    InterchangeRule , Interchange [vdv] x dx. 
     	 - Add DayTypeRef  to   Block [vdv] x dx. 
         - TransportMode added as Explicit type of value to allow reflection. However   [vdv] x dx,.  
         - Add TypeOfServceRef to Journey    [vdv] x dx,  
         - Add Announcement Support dep
         	-	Add NoticeRef to StopPointInPattern, PointInJourneyPattern, [vdv] x dx. 
         	-	Add TypeOfNotice to footnote package. x dx.  
         - Add Name to Block, InterchangeRule, etc  x dx.
         - Add DepartmentRef to Line and VehicleJourney, TimeDemandTiming and JourneyPattern [vdv] x dx. dep
         - Add FromPointRef and ToPointRef to DeadRun and ServiceJourney  x dx .
   	 - Add explict StopArea and TariffZone rels to ScheduledStopPoint x .
   
   - Revise timetable  examples
    	 - Reorganise folder structure so that examples are not children of schema folder
    	 	0.98 /examples/
    	 	     /xml/
  	 - Reorganize in increasing complexity,  basic, with timings etc 
  	 - Rrevise  branched and simple route examples
   	 - Add circular route example
   	 - Add branching route example 2nd variant
   	 - Add example of use of  Announcement Notices to basic Example with timimngs 
     	 - Revise use of run times in  examples
         - Add PI Facility example
         - Make Journey Patterns Service Journey Patterns in examples
	 - Add examples of Activation points

   - Make relation names more consistent - drop ise of Refs in names
   	- rename ServicePattern/journeyPatternRefs to journeyPatterns x   [Model CHANGE]
   	- rename Line/routeRefs  tpo Line/routes  x   [Model CHANGE]
  	- rename SpatialFeature/PointRefs to SpatialFeature/points x   [Model CHANGE]
   	- rename LocalService/TypeOfServcieFeatureRefs to  LocalService/typesOfServiceFeatures x   [Model CHANGE]
    	- rename NavigationPath/TransferRefs to NavigationPath/transfers x   [Model CHANGE]
    	- rename Site/AdjacentSiteRefs to Site/AdjacentSiteRefs x   [Model CHANGE]
    	- rename TopographicPlace/AdjacentPlaceRefs to TopographhicPlace/AdjacentPlaces x   [Model CHANGE]
    	- rename FootnoteAssignment/ValidityCOnditionRefs to FootnoteAssignment/ValidityCOnditionRefs x   [Model CHANGE]
    	- rename VehicleJourney/TimeDemandTypeRefs to VehicleJourney/TimeDemandTypeRefs x   [Model CHANGE]
   - Correct substitution  hierarchies for Journey, pattern, LinkSequence, LinkInSequence, PointInSequence etc
   - Add destination display  vias, to PointInPattern,  rename displayVias to Vias  x dx.

   - Correct PI facility, add LINE and DIRECTION filters  x dx.
   - For consistency  Change order of description on ServiceJourneyInterchange  x dx. [Model CHANGE]
   - Correct Point on Link not to be abstract.
   - For consistency, Promote Distance to be on LinkSequence - drop from NavigationPath  x dx. [Model CHANGE]
   - Correct JourneyPattern substitutionGroup to JourneyPattern  x
   - Correct to allow RoutePointRef on PointInJourneyPattern as per MODEL  x 
   - Revise Quay assignment on Call to allow separate assignment for arrival and departure. Rename QuayAssignment to QuayAssignmentView x dx. [Model CHANGE]
   - Correct to allow ParkingPoint etc as RoutePoints x
   - Correct name of RunTimeAttribute on DefaultDeadRunTime and DefaultServiceJourneyRunTime x dx. [Model CHANGE]
   - Correct Infrastructure Frame contents to add activation frame elements so that  activation points etc can be populated  x dx.
    	
2011.05.22  v0.98
   - Make id and responsibility set ref an attribute
   - Add more constraints:: unique within object type
   - Add short names to VehicleType, Route,  etc   [vdv] x dx
   - Change order of DirectionType on Route x dx [Model CHANGE]
   - Add Variant to Destination Display x dx.
   - Add Notice to Footnote Packege to support arbitrary ANnouncements x dx.
   - Correct Key List  x  [Model CHANGE]
   - revise examples
 	  - Revise examples to use constraints
 	  - Add branching route example
 	  - Revise use of run times in examples

2011.05.22  v0.97
   - Add Oxygen project.xpr
   - Fix strict validation errors x
   - Examples: Add simple vehicleSchedule example with BLOCKS etc x
   - Add Duty & DriverScheduleFrame x (Add to MODEL?)
   - Correct package dependencies x
   - Correct spelling of WheelchairPassable [MODEL CHANGE] x
   - Corrections to facilities to  remove duplicates
   - Add earliest and latest passing time to TIMETABLED PASSING TIME  x dx.
   - Rename TIMETABLED PASSING TIME elements to drop TimetabledPrefix   (MODEL CHANGE) x
   - Revise INTERCHANGE RULE to align model with xml . Add attributes   X dx (MODEL CHANGE)  
   - Add WheelChairVehicleEquipment and AccessVehicleEequipment  to align with UML  x
   - Examples:Add UIC eurostar stations
   - Examples:Add Train makeup to Eurostar  example 
   - Revise  Stop Assignment to use revised Train Componentes
   - Example add Assignment of boardinng positions to train components for Eurostar example 
   - Add capacity to TrainElement x dx
   - Add LineString to LINK SEQUENCE PROJECTION  and allow on to Vehicle Journey to support  Shape of a specific journey g x
   - Revise Block to drop FrameRef. Add journeys refs to CourseOfJouuneys x dx (MODEL CHANGE) 
   - Drop JourneyPatternFrequency [kb] x dx (MODEL CHANGE) 
   - Add FootnoteVariants to Footnote [kb] x dx
   - Correct ServiceFrame contents: x dx (MODEL CHANGE)
   	- Drop direct containment of ALlowedLineDirection. 
   	- Drop GroupOfLinks, 
   	- TimeDemandAssignment  
   	- Add   identity constraints
     	- Rename identifier of Versioned ChildCid rather than id so that can have different constraints
   	- Add  Id to footnote assignmentView x
   	- Add Id to AccessSummary  x
   	- Add  genericIDentity Constraints  Eid, Id/version   cid/version/ ,  
   	       Special cases Namespace  xmlns,  Datasource/Id
   	       
   	-  Revise NameSpace element : rename to Namespace, rename id to Xmlns, rename Xmlnsurl x dx (MODEL CHANGE) 
   	- Change order of Namespaces in ResourceFrame x (MODEL CHANGE) 
   	- Add Data source & versiouins to resoucre frame  x
   	- NavigationPath make children VersionChildSTructure x
  	- Revise All example to show name  Id types eg nid:Quay:1234
 	- Make responsibility role assignment a versioned child x
 	- Revise examples to use  names space:objectType:identifier   
 	    
    - Rename EquipmentTypeRef	 to TypeOfEquipment
    - Add DataSource
    - Allow displayVias on Call as well as destination display [txc] dx
    - Allow DutyPartRef on Call [txc] x dx
  
  
    - Rename  ModeRef to TransportMode x dx (MODEL CHANGE)
    - Rename EquipmentType to TypeOfEquiment
    - Rename v_vesrioing to _version_version  and _versionAttributes to _versionSupport x

    - Rename ID on ENitity to Eid to allow for separate identity constraints x   (MODEL CHANGE)
    - Add RoutingConstraint Package
    - Add Short Name & Private code to Operating day  [VDV] dx x 
    - Add  Private code to Day Type [VDV gd]   dx x
    - Add Short Name & Private code to Activation Point day  [VDV gd ] dx x 
    - Add Short Name & Private code to Vehicle  [VDVgd ] dx x 
    - Add DefaultResponsibiltySet to Farem dx x
    - Allow list of vals  roles on responsibility role assignment
    - Correct DutyPart too dutyParts

      

2011.03.20  v0.96
   - Add Key List to DataManagedObject   [Paris mtg] 11.03 dx x 
   - Revise Flexible Models & route  dx 
          Replace FlexibleLink with FlexibleRouteProerties
          Replace FlexiblePoint with FlexiblePointProperties
          Move FlexibleServicePackage to Part2
   - Add SystemOfUnits dx x
   - Add submodes [cd] dx x
   - Add variant text to submodes  dx x
   - Change order of some elements  on service journey  (MODEL CHANGE) x 
   - Allow image Uri on footnote assignment dx x
   - add Equipment to ResourceFrame dx x
   - add Vehicle & VehicelType to Resource Frame dx x
   - Allow multiple types on Organisation (MODEL CHANGE) dx x
   - Allow parent on AdministrativeZone dx x
   - Add nightRail & interregional to enable uic/era lists dx x
   - Add connection certainty to distinguish guarantee types dx x  MODEL CHANGE
   - Add baggage connection to baggage service. [era]
   - Move Service Journey Pattern to ServicePatternPAckage dx  [kb]
     - Move Service Journey Pattern from TimetableFrame to ServiceFrame dx  
   - Revise RoutingConstraintModel, 
   	Move to TP dx  (  x to do)
   	Rename dx   (x to do)
   - Add a separate ServiceCalendar element that is distinct from the Frame
        Add new ServiceCalender_version package and   dx x (MODEL CHANGE)
   - Add turistica and prefernte seat Fare classes x dx  [era]
   - Update Sanitary facility to match London data x [nk]
   - Correct TypeOfFrame to be concrete x  x [cd]
   - Change Location coordinates to use gml:Pos x  (MODEL CHANGE)  x [cd]
   - Add LineString to Link, Polygon to ZOne  x [cd]
   - Add CD RATP Neptune XML example   x [cd]
   - Add Purpose of grouping to ServiceFrame  x [cd]
   - In ServiceFrame rename groupOfLines to groupsOfLines  x [cd]
   - Correct spelling of OutputDetailList  to OutputDetailList  x [cd]
   - Revise Facility  x dx [era] (MODEL CHANGE)
       - ALign facility values  xml /uml, break value down 
       - Add ServicefacilitySet and  StopFacilitySet to group facilities
       - Allow association of Facility with journey part
 
   - rename Site frame stopPlaces to StopPlace (MODEL CHANGE)
   - ADD COMPOUND TRAIN and revise TRAIN  to be VEHICLE TYPEx dx [Paris mtg] (MODEL CHANGE)
   - Revise Train Splitting & joining  [Paris mtg] (MODEL CHANGE)  x dx
	Add example of train splitting and joining based on SJ example 
        Add TRAIN NUMBER also include in TIMETABLE FRAME
        Drop TRAIN BLOCK and add  COMPOUND BLOCK
        Revise VEHCILE TYPE, TRAIN COMPOUND TRAIN

2011.02.08  v0.95
   - Allow both WGS and non WGS coordinates in Location xx
   - Allow multiple day types per Journey (CHG) TODO
   - allow Topographic place on Scheduled stop Point  dx x
   - Correct PublicCode on StopArea to be optional dx x
   - Correct Presentation info links not mandatory, add colour name dx x
   - Add public code to organisation  [e]  dx x
   - Change character set to is0-8859-1   xx x
   - Revise ParentZoneRef to be a versionRef (CHG)  xx x
   - Allow multiple Service Calendars in a frame.(affects examples) (CHG) dx
   - Default For Alighting and ForBoarding to true so that less coding needed. xx
   - Add name to timing pattern link and timime demand timing  dx x
   - Add timetable defaults to TimetableFrame [e]  dx
   - Add FootnoteAssignments to ServiceJourney, and Group of Services [e]  dx
   - Refine Group Of Service member to allow properties dx
   - Add Network Topology package [e] dx
   - Add line . network and operator to timetable frame as defaults dx
   - Add IsAvailable to AvailabilityCOndition to allow for exclusions [e] g dx
   - Reorder OperatingDays & DayAssignment on ServiceCalendarFrame (CHG) dx
   - Add Class of user value for use on check constraint delay. Add name to delay. dx  
   - Allow OrganisationType to be list xx
   - Add AtCentre on STopPlace dx
   - Correction to Capitalize isExit, isEntrance, IsCovered on SiteEntrance (CHG) xx
   - Rename Namespace to NameSpace to be consistent xx
   - Revise CountryRef to be consistent(CHG) xx
   - Add type attribute to PrivateCodes and reuse common definition. xx
   - Add BorderCrossing to StopPlace and to RoutePoint [era] dx x
   - Add ServiceCalendarFrame ref to TimetableFrame  [era] dx x
   - Correct Purpose of grouping not to be abstract xx xx x
   - Allow Operating Period Ref on day type assignment [era] dx 
   - Revise service facilities  [era]  TODOxx
   - Change Frames Move  InterchangeRule to separategroup in Service Frame. (CHG) dx
   - Correct to Drop duplicate JourneyPattern reference from Timetable frame (CHG) xx
   - Add Footnotes assignments to an interchange. dx
   - Add url to SCHEDULED STOP POINT gtfs dx
   - Make Service departure time optional gtfs dx
   - Add IsFlexible to call. gtfs dx
   - Add Stop type to scheduled stop Point gtfs dx
   - Add url to LINE gtfs dx
   - Add OPERATOR REf to line gtfs dx
   - Reqvise Journey Frequency to allow timeband to be stated (CHG) gtfs dx
   - Allow reuse of   CheckCOnstraints (ref on entrance)   dx
   - Allow default coordinate system srsname to frame dx
   - Add Value Set to allow grouping of values dx
   - Add Submode to Line & ServiceJourney dx
   - Add primary mode to operator  txc dx
   - Add contact fact number to operator/contact txc dx
   - Add default timingpoint type to SSP txc xx
   - Add alternative Presentation to Line txc dx
   - Add group of services to ServiceJourney txc dx

2011.01.28  v0.94
   - Make explicit Frames Disjoint so that each element is in only one Frame (CHG)
   - Add CompositeFrame and Resource Frame  (Model Change) dx
   - Make DestinationDisplay a DataManagedObject and move to LineRoutePackage (Model & MODEL Change) dx
   - Simplify and clarify use of Derived Views    dx
          Facade: (ServiceJourney, DeadRun, Call ) 
          Derived View: LineView, ShceduledStopPointView, DestinationDisplayView, FootnoteAssignmentView, OperatorView dx
   - Revise CALL to reflect changes.
   - Revise comments to include TM definitions and numerous corrections. xx
   - Rename LevelCode to PublicCode dx
   - Rename TimeDemand to TimeDemandType dx
   - Correct Footnote Deivery Variant type dx
   - Rename Time Demand to TimeDemand Type Type dx
   - Add PI Facility package dx
   - Revise package dependencies dx
   - Validate against XErces xx
   
2011.01.01  v0.93
   - Add Retail equipment etc, tidy up dependenies
   - Move Address to RC package
   - RefFactor Extensions to be on DataManagedObject, Versioned Child
   - Correct Timing types
   - Correct types of organisations
   - Correct responsibility set id  
   - Make PathLink a type of Link, not SIteCOmponent
   - rename NavigationPath/ PlaceRefInSequence to PlaceInSequence
   - Rename TypeOfStopPlace to StopPlaceType
   - Rename TypeOfTopographicPlace to TopographicPlaceType
   - Correct POI elements
   - Numerous label corrections
   - Rename PathLink  FromToUpdown to Transition
   - Add POI classifcatiosn to Site Frame. Add Poi classifcation example
   - Rename accessSpaceEntrances to entrances
   - Revise FlexibleQuay, StopPlace to be simpel - just Places.
   - Rename folders to match conceptual and physical model
        netex_general\    	 ==> netex_reusableComponents\
	netex_framework\   	 ==> netex_genericFramework\
	netex_core\	  	 ==> netex_framework\
	netex_baseTypes\    	 ==> netex_utility\
	netex_entityversion\     ==>netex_responsibility\
	netext_ifopt             ==> netex_part_1/part1_ifopt  etc   
2010.12.01  v0.92
   - Revise Frames: Revise frames Separate package, Split networkFrame into  Infrastructure &  Service , Site  
   - Use list for modes , other modes
   - change encoding to iso-8859-1
   - add capacity
   - Add POI component
   - Make PI facility a type of equipment so it can be located
   - Add course of journey and vehicle service
2010.12.01 v0.91
   - Revise Frames: Add General Frame. Make  Network  Timetable frame explicit
   - Revsie filters to allow frame references
   - Rename Timetable to TimetableFrame, NetworkVersionFrame to NetworkFrame
   - Add mode to vehicle Journey
   - Add views to hold derived data
   - Move Address to be Place not Site
   - revise FlexibleStopPlace to be Place, FlexibleQuay to be SiteElemengt etc
   - rename serve_support to be service_PatternSupport
   - Add frames to examples
   - Revise SIteConnection, ConnectionConstraint
   - Add example of VDV calendar  and simple calndar
   - Add coupled journey example
   - add gtds agency, example, revise stops
   - Add validation condition to transfer etc
   
2010.11.01 v0.90
   - Level is no longer a SiteComponent
   - Add separate XXX_entity wrappers, rename structures _VersionStructure, add separate _entity packages
        eg Quay_entity,  Quay
   - Revise Site TopographicRef to be SIte /TopgraphicView
   - Allow equipment at Site level
   - Remove circular dependency from core organisation  to ifopt address: move address to organisation
   - Add OperatingOrganisation to Site
   - Add PrivateCode to Operatro and Equipment
   - Add flights of stairs, stair end contrast and other attributes
   - Revise Access and Transfer to use AccessEnd, Transfer End 
   - Rename Check to CheckConstraint
   - Revise parking model, support parking costs
   - Move Locale to Site (ie not just StopPlace)
   - Revise Access & Transfer to have separate Accend, TransferEnd elements. ALlow mode on end
   - Add draft SiteConnection
   - Add direction to checkConstraint
   - Add JP frequency to Journeypattern  (CON MODEL TODO?)
   - Add a group of timing links 
   - Allow multiple timedemands per vehiceljourney
   - Add timeDemandProfile to UML and XML
   - Rename ifopt_ and abcs to netex_ifopt_ and netex_acbs_
   - Drop time allowance etc
   - Rename ShortTermDayAssignment DayTypeAssignment
   - DrRop
       Route-TurnStation
       ActualStopEequipment etc
       ActualVehicelEquipment etc
       VehicleStoppingPosition etc
       VehicleService - TimeAllowance etc
   Examples
     versionhistory
     stadium
     uic stations (sweden)
     uic timetable   Add uicOOperting period as tempory experiment
     
2010.09.29
   Added Point to point on lInk
   Added TransportOrganisation, Call, ProductionTimetable Production modules
   Added Footnotes
   Add SimpleTimetable Example
   Added examples of SIRI proptocol & publication proitocol
2010.09.18
   Consolidate in single namespace - drop ifopt, acbs namespaces
   Make StopArea, Place subs  of Zone
   Make Plaze / Zone an association , not inheritance
   Rename GroupOfElements  to Group of Entities
   Add TypeOF Service to Journey

2010.08.06http://www.booking.com/searchresults.html?aid=317836;label=251_searchbox_251withdates;sid=e7fda4f0cfe47a98c7b43435f76686fd;checkin_year_month_monthday=2010-09-28;checkout_year_month_monthday=2010-09-30;class_interval=1;landmark=2028;pr_cur_code=GBP;;radius=100;offset=20;rows=20
   Integrate changes from CD
    
2010.06.29  V086
   General
       Revise VehicleTypePackage  to include Vehicle, VehicleEqipmentProfile etc
       Add AccessRighst support Package
       Add SchematicMapPackage
       Add Train Element Package
   IFOPT
       Revise attributes 
       Add more equipment and attributes
   Part 1
       Add Activation Package
       Addd Flexible Route Package
       Add Vehicle And Crew Point Pacakage

2010.05.21  V085
    
    Add detailed examples 
    Tidy up

2010.05.12  V08
    
    Combine Ifopt & Network hierarchy
    Add Wimbledon  example
    Revise Simple Network Example 
    Extension 


2009.12.31    
    rename NetworkFrame back to NetworkVersion
    split grouping and common object

    rename networkVersion to networkframe
2009.12.31 
   remove Siri dependencies
     create separate folder for base & resuabel netex
    create netex modes etc    
    rename versionedObject to entity in frame
    rename networkVersion to networkframe
