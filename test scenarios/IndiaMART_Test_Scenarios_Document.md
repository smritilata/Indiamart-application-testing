# TEST SCENARIO DOCUMENT -- INDIA MART WEB APPLICATION

This document contains the detailed test scenarios prepared for the
IndiaMART Web Application based on the Functional Requirement Document
(FRD). The scenarios cover functional, usability, validation,
globalization, and UI testing.

## 1. Project Information

  -----------------------------------------------------------------------
  Project Name                        IndiaMART Web Application
  ----------------------------------- -----------------------------------
  Application Type                    B2B Marketplace

  Testing Type                        Manual Black Box Testing

  Prepared By                         Smritilata Sarkar

  Document Version                    1.0
  -----------------------------------------------------------------------

## 2. Test Scenarios

  ------------------------------------------------------------------------------
  Scenario ID    Module          Test Scenario    Priority       Testing Type
  -------------- --------------- ---------------- -------------- ---------------
  TS_001         Homepage        Verify homepage  High           Functional
                                 loads                           Testing
                                 successfully                    

  TS_002         Registration    Verify           High           Functional
                                 registration                    Testing
                                 with valid                      
                                 details                         

  TS_003         Registration    Verify           High           Boundary Value
                                 registration                    Testing
                                 with invalid                    
                                 mobile number                   

  TS_004         Login           Verify login     High           Functional
                                 with valid                      Testing
                                 credentials                     

  TS_005         Login           Verify login     High           Negative
                                 with invalid                    Testing
                                 credentials                     

  TS_006         Search          Verify product   High           Functional
                                 search                          Testing
                                 functionality                   

  TS_007         Product Filter  Verify product   Medium         Functional
                                 filter                          Testing
                                 functionality                   

  TS_008         Inquiry         Verify product   High           Functional
                                 inquiry                         Testing
                                 submission                      

  TS_009         Seller Profile  Verify seller    Medium         UI Testing
                                 profile display                 

  TS_010         Cart            Verify add to    Medium         Functional
                                 cart                            Testing
                                 functionality                   

  TS_011         Logout          Verify logout    High           Functional
                                 functionality                   Testing

  TS_012         Forgot Password Verify forgot    High           Functional
                                 password                        Testing
                                 functionality                   

  TS_013         Supplier        Verify contact   High           Functional
                 Contact         supplier                        Testing
                                 functionality                   

  TS_014         Validation      Verify empty     High           Negative
                                 field validation                Testing

  TS_015         Navigation      Verify           Medium         UI Testing
                                 navigation menu                 
                                 links                           

  TS_016         Location        Verify location  High           Usability
                                 consistency                     Testing

  TS_017         Globalization   Verify Hindi     High           Globalization
                                 language                        Testing
                                 localization                    

  TS_018         Product Search  Verify           High           Usability
                                 location-based                  Testing
                                 product                         
                                 filtering                       

  TS_019         Globalization   Verify English   High           Globalization
                                 language                        Testing
                                 localization                    

  TS_020         Navigation      Verify homepage  Medium         Usability
                                 navigation                      Testing
                                 availability                    

  TS_021         Form Validation Verify Bank Name Medium         Usability
                                 placeholder                     Testing
                                 visibility                      

  TS_022         Form Validation Verify mandatory Medium         Usability
                                 field astrix                    Testing
                                 (\*) symbol                     

  TS_023         UI              Verify proper    Medium         Usability
                                 placeholder                     Testing
                                 visibility                      

  TS_024         Dropdown        Verify dropdown  High           Usability
                                 button                          Testing
                                 visibility                      

  TS_025         Hyperlink       Verify hyperlink Low            UI Testing
                                 visibility                      
  ------------------------------------------------------------------------------

## 3. Scope of Testing

-   Registration and Login validation

-   Search and Filter functionalities

-   Inquiry and Contact Supplier modules

-   Cart and Seller Profile functionalities

-   Forgot Password and Logout modules

-   UI and Navigation validation

-   Localization and Globalization testing

-   Usability and Placeholder validation

## 4. Conclusion

The test scenarios defined in this document ensure proper validation of
the IndiaMART application functionalities, usability, UI consistency,
and localization behavior. These scenarios will be used as the base for
preparing detailed test cases and execution reports.
