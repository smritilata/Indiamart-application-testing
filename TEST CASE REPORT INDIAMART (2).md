# TEST CASE REPORT -- INDIA MART

## Project Details

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**             **Details**                                   |
|   --------------------- --------------------------------------------  |
|   Project Name          IndiaMART Web Application Testing             |
|                                                                       |
|   Module Name           Buyer & Seller Marketplace System             |
|                                                                       |
|   Testing Type          Manual Black Box Testing                      |
|                                                                       |
|   Tested By             Smritilata Sarkar                             |
|                                                                       |
|   Browser Used          Google Chrome                                 |
|                                                                       |
|   Platform              Web Application & Mobile Application          |
|                                                                       |
|   Operating System      Windows 10 / Android                          |
|                                                                       |
|   Test Environment      Stable Broadband Internet                     |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

# 1. INTRODUCTION

IndiaMART is an online B2B marketplace platform that connects buyers and
sellers across different industries. The application allows users to
search products, post requirements, contact suppliers, manage business
profiles, and perform product inquiries.

This report covers functional, usability, UI, globalization, and
validation testing of the IndiaMART application.

# 2. OBJECTIVE

The objective of testing is:

-   To verify all major functionalities of the IndiaMART platform

-   To validate buyer and seller workflows

-   To ensure proper form validation

-   To verify search and inquiry functionalities

-   To check UI behavior and navigation

-   To identify usability and globalization defects

-   To ensure system stability and user friendliness

# 3. PRE-CONDITIONS

Before executing test cases:

-   System should be powered ON

-   Stable internet connection should be available

-   Browser/application should be installed properly

-   IndiaMART website/application should be accessible

-   Test data should be available

-   User account should exist for login testing

# 4. TEST SCENARIOS

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Test Scenario    **Test Scenario**                                |
|   ID**                                                                |
|   ------------------ -----------------------------------------------  |
|   TS_001             Verify homepage loads successfully               |
|                                                                       |
|   TS_002             Verify registration with valid details           |
|                                                                       |
|   TS_003             Verify registration with invalid mobile number   |
|                                                                       |
|   TS_004             Verify login with valid credentials              |
|                                                                       |
|   TS_005             Verify login with invalid credentials            |
|                                                                       |
|   TS_006             Verify search functionality                      |
|                                                                       |
|   TS_007             Verify product filter functionality              |
|                                                                       |
|   TS_008             Verify product inquiry submission                |
|                                                                       |
|   TS_009             Verify seller profile display                    |
|                                                                       |
|   TS_010             Verify add to cart functionality                 |
|                                                                       |
|   TS_011             Verify logout functionality                      |
|                                                                       |
|   TS_012             Verify forgot password functionality             |
|                                                                       |
|   TS_013             Verify contact supplier functionality            |
|                                                                       |
|   TS_014             Verify empty field validation                    |
|                                                                       |
|   TS_015             Verify navigation menu links                     |
|                                                                       |
|   TS_016             Verify location consistency                      |
|                                                                       |
|   TS_017             Verify Hindi language localization               |
|                                                                       |
|   TS_018             Verify location-based product filtering          |
|                                                                       |
|   TS_019             Verify English language localization             |
|                                                                       |
|   TS_020             Verify homepage navigation availability          |
|                                                                       |
|   TS_021             Verify Bank Name placeholder visibility          |
|                                                                       |
|   TS_022             Verify mandatory field astrix symbol             |
|                                                                       |
|   TS_023             Verify proper placeholder visibility             |
|                                                                       |
|   TS_024             Verify dropdown button visibility                |
|                                                                       |
|   TS_025             Verify hyperlink visibility                      |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

# 5. TEST CASES

# TEST CASE 1

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_001                                       |
|                                                                       |
|   Test Scenario       Verify homepage loads successfully              |
|                                                                       |
|   Module              Homepage                                        |
|                                                                       |
|   Priority            High                                            |
|                                                                       |
|   Severity            Critical                                        |
|                                                                       |
|   Test Type           Functional Testing                              |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Preconditions

Browser and internet connection should be available.

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**      **Expected Result**   **Actual         **Status** |
|   No**                                           Result**             |
|   -------                                                             |
| - --------------- --------------------- ---------------- ------------ |
|                                                                       |
|  1        Open browser    Browser should launch Browser launched Pass |
|                            successfully          successfully         |
|                                                                       |
|                                                                       |
|  2        Enter IndiaMART Website should open   Website opened   Pass |
|            URL                                   successfully         |
|                                                                       |
|                                                                       |
|  3        Press Enter     Homepage should load  Homepage loaded  Pass |
|                            successfully          successfully         |
|                                                                       |
|                                                                       |
|  4        Observe         Logo, search bar,     All elements     Pass |
|            homepage        categories should     displayed            |
|            elements        display               properly             |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Expected Result

Homepage should load properly without errors.

### Actual Result

Homepage loaded successfully.

### Status

Pass

# TEST CASE 2

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_002                                       |
|                                                                       |
|   Test Scenario       Verify registration with valid details          |
|                                                                       |
|   Module              Registration                                    |
|                                                                       |
|   Priority            High                                            |
|                                                                       |
|   Severity            Major                                           |
|                                                                       |
|   Test Type           Functional Testing                              |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Data

-   Name: Smriti

-   Mobile: 9876543210

-   Email: test@gmail.com

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**       **Expected Result** **Actual Result** **Status** |
|   No**                                                                |
|   -------                                                             |
| - ---------------- ------------------- ----------------- ------------ |
|                                                                       |
|  1        Open IndiaMART   Website should open Website opened    Pass |
|            website                                                    |
|                                                                       |
|                                                                       |
|  2        Click Sign Up    Registration page   Registration page Pass |
|                             should open         opened                |
|                                                                       |
|                                                                       |
|  3        Enter valid      Inputs should be    Inputs accepted   Pass |
|            details          accepted                                  |
|                                                                       |
|                                                                       |
|  4        Click Register   Account should be   Registration      Pass |
|                             created             successful            |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 3

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**        **Details**                                        |
|   ---------------- -------------------------------------------------  |
|   Test Case ID     TC_IM_003                                          |
|                                                                       |
|   Test Scenario    Verify registration with invalid mobile number     |
|                                                                       |
|   Module           Registration                                       |
|                                                                       |
|   Priority         High                                               |
|                                                                       |
|   Severity         Major                                              |
|                                                                       |
|   Test Type        Boundary Value Analysis                            |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Data

Mobile Number: 12345

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**        **Expected        **Actual Result**  **Status** |
|   No**                       Result**                                 |
|   -------                                                             |
| - ----------------- ----------------- ------------------ ------------ |
|                                                                       |
|  1        Open registration Form should       Form displayed     Pass |
|            form              display                                  |
|                                                                       |
|                                                                       |
|  2        Enter invalid     Validation should Validation         Pass |
|            mobile number     trigger           triggered              |
|                                                                       |
|                                                                       |
|  3        Click Register    Error message     Validation message Pass |
|                              should display    displayed              |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 4

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**            **Details**                                    |
|   -------------------- ---------------------------------------------  |
|   Test Case ID         TC_IM_004                                      |
|                                                                       |
|   Test Scenario        Verify login with valid credentials            |
|                                                                       |
|   Module               Login                                          |
|                                                                       |
|   Priority             High                                           |
|                                                                       |
|   Severity             Critical                                       |
|                                                                       |
|   Test Type            Functional Testing                             |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**       **Expected Result**   **Actual        **Status** |
|   No**                                            Result**            |
|   -------                                                             |
| - ---------------- --------------------- --------------- ------------ |
|                                                                       |
|  1        Open login page  Login page should     Login page      Pass |
|                             display               displayed           |
|                                                                       |
|                                                                       |
|  2        Enter valid      Inputs should be      Credentials     Pass |
|            credentials      accepted              accepted            |
|                                                                       |
|                                                                       |
|  3        Click Login      User should login     Login           Pass |
|                             successfully          successful          |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 5

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_005                                       |
|                                                                       |
|   Test Scenario       Verify login with invalid credentials           |
|                                                                       |
|   Module              Login                                           |
|                                                                       |
|   Priority            High                                            |
|                                                                       |
|   Severity            Major                                           |
|                                                                       |
|   Test Type           Negative Testing                                |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**         **Expected Result**    **Actual     **Status** |
|   No**                                               Result**         |
|   -------                                                             |
| - ------------------ ---------------------- ------------ ------------ |
|                                                                       |
|  1        Enter invalid      Invalid data should be Data entered Pass |
|            credentials        entered                                 |
|                                                                       |
|                                                                       |
|  2        Click Login        Error message should   Error        Pass |
|                               display                displayed        |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 6

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**               **Details**                                 |
|   ----------------------- ------------------------------------------  |
|   Test Case ID            TC_IM_006                                   |
|                                                                       |
|   Test Scenario           Verify search functionality                 |
|                                                                       |
|   Module                  Search                                      |
|                                                                       |
|   Priority                High                                        |
|                                                                       |
|   Severity                Major                                       |
|                                                                       |
|   Test Type               Functional Testing                          |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Data

Product: Mobile Phone

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**         **Expected         **Actual         **Status** |
|   No**                        Result**           Result**             |
|   -------                                                             |
| - ------------------ ------------------ ---------------- ------------ |
|                                                                       |
|  1        Enter product name Search input       Text accepted    Pass |
|            in search bar      should accept text                      |
|                                                                       |
|                                                                       |
|  2        Click Search       Related products   Relevant         Pass |
|                               should display     products             |
|                                                  displayed            |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 7

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**            **Details**                                    |
|   -------------------- ---------------------------------------------  |
|   Test Case ID         TC_IM_007                                      |
|                                                                       |
|   Test Scenario        Verify product filter functionality            |
|                                                                       |
|   Module               Product Listing                                |
|                                                                       |
|   Priority             Medium                                         |
|                                                                       |
|   Severity             Minor                                          |
|                                                                       |
|   Test Type            Functional Testing                             |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**    **Expected Result**   **Actual Result**  **Status** |
|   No**                                                                |
|   -------                                                             |
| - ------------- --------------------- ------------------ ------------ |
|                                                                       |
|  1        Search for    Product list should   Products displayed Pass |
|            product       display                                      |
|                                                                       |
|                                                                       |
|  2        Apply filter  Filter should apply   Filter applied     Pass |
|                                                                       |
|                                                                       |
|  3        Observe       Filtered products     Correct products   Pass |
|            results       should display        displayed              |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 8

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**            **Details**                                    |
|   -------------------- ---------------------------------------------  |
|   Test Case ID         TC_IM_008                                      |
|                                                                       |
|   Test Scenario        Verify product inquiry submission              |
|                                                                       |
|   Module               Inquiry                                        |
|                                                                       |
|   Priority             High                                           |
|                                                                       |
|   Severity             Major                                          |
|                                                                       |
|   Test Type            Functional Testing                             |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**     **Expected Result**    **Actual         **Status** |
|   No**                                           Result**             |
|   -------                                                             |
| - -------------- ---------------------- ---------------- ------------ |
|                                                                       |
|  1        Open product   Product details should Product details  Pass |
|            page           display                displayed            |
|                                                                       |
|                                                                       |
|  2        Click Contact  Inquiry form should    Inquiry form     Pass |
|            Supplier       open                   opened               |
|                                                                       |
|                                                                       |
|  3        Submit inquiry Inquiry should submit  Inquiry          Pass |
|                           successfully           submitted            |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 9

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**               **Details**                                 |
|   ----------------------- ------------------------------------------  |
|   Test Case ID            TC_IM_009                                   |
|                                                                       |
|   Test Scenario           Verify seller profile display               |
|                                                                       |
|   Module                  Seller Profile                              |
|                                                                       |
|   Priority                Medium                                      |
|                                                                       |
|   Severity                Minor                                       |
|                                                                       |
|   Test Type               UI Testing                                  |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   --------                                                            |
| --------------------------------------------------------------------- |
|   **Step                                                              |
|    **Action**        **Expected         **Actual Result**  **Status** |
|   No**                       Result**                                 |
|   --------                                                            |
|  ----------------- ------------------ ------------------ ------------ |
|                                                                       |
| 1        Open seller       Seller details     Details displayed  Pass |
|            profile           should display                           |
|                                                                       |
|                                                                       |
| 2        Verify business   Information should Correct            Pass |
|            information       be correct         information           |
|                                                 displayed             |
|   --------                                                            |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 10

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**             **Details**                                   |
|   --------------------- --------------------------------------------  |
|   Test Case ID          TC_IM_010                                     |
|                                                                       |
|   Test Scenario         Verify add to cart functionality              |
|                                                                       |
|   Module                Cart                                          |
|                                                                       |
|   Priority              Medium                                        |
|                                                                       |
|   Severity              Major                                         |
|                                                                       |
|   Test Type             Functional Testing                            |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   -------                                                             |
| --------------------------------------------------------------------- |
|   **Ste                                                               |
| p   **Action**    **Expected Result**     **Actual         **Status** |
|   No**                                           Result**             |
|   -------                                                             |
| - ------------- ----------------------- ---------------- ------------ |
|                                                                       |
|  1        Select        Product page should     Product page     Pass |
|            product       open                    opened               |
|                                                                       |
|                                                                       |
|  2        Click Add to  Product should add      Product added    Pass |
|            Cart          successfully                                 |
|                                                                       |
|                                                                       |
|  3        Open cart     Product should display  Product          Pass |
|                          in cart                 displayed            |
|   -------                                                             |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 11

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**               **Details**                                 |
|   ----------------------- ------------------------------------------  |
|   Test Case ID            TC_IM_011                                   |
|                                                                       |
|   Test Scenario           Verify logout functionality                 |
|                                                                       |
|   Module                  Logout                                      |
|                                                                       |
|   Priority                High                                        |
|                                                                       |
|   Severity                Major                                       |
|                                                                       |
|   Test Type               Functional Testing                          |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   -----                                                               |
| --------------------------------------------------------------------- |
|   **S                                                                 |
| tep   **Action**   **Expected Result**   **Actual Result** **Status** |
|   No**                                                                |
|   -----                                                               |
| --- ------------ --------------------- ----------------- ------------ |
|   1        Click Logout Session should end    Session ended     Pass  |
|                                                                       |
|   2        Observe page Login page should     Login page        Pass  |
|                         display               displayed               |
|   -----                                                               |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 12

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_012                                       |
|                                                                       |
|   Test Scenario       Verify forgot password functionality            |
|                                                                       |
|   Module              Forgot Password                                 |
|                                                                       |
|   Priority            High                                            |
|                                                                       |
|   Severity            Major                                           |
|                                                                       |
|   Test Type           Functional Testing                              |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   --------                                                            |
| --------------------------------------------------------------------- |
|   **Step                                                              |
|    **Action**           **Expected         **Actual        **Status** |
|   No**                          Result**           Result**           |
|   --------                                                            |
|  -------------------- ------------------ --------------- ------------ |
|                                                                       |
| 1        Click Forgot         Reset page should  Reset page      Pass |
|            Password             open               opened             |
|                                                                       |
|                                                                       |
| 2        Enter registered     Input should be    Accepted        Pass |
|            email/mobile         accepted           successfully       |
|                                                                       |
|                                                                       |
| 3        Submit request       OTP/reset link     OTP sent        Pass |
|                                 should send                           |
|   --------                                                            |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 13

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_013                                       |
|                                                                       |
|   Test Scenario       Verify contact supplier functionality           |
|                                                                       |
|   Module              Supplier Contact                                |
|                                                                       |
|   Priority            High                                            |
|                                                                       |
|   Severity            Major                                           |
|                                                                       |
|   Test Type           Functional Testing                              |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   ------                                                              |
| --------------------------------------------------------------------- |
|   **St                                                                |
| ep   **Action**         **Expected Result** **Actual       **Status** |
|   No**                                            Result**            |
|   ------                                                              |
| -- ------------------ ------------------- -------------- ------------ |
|   1        Click Contact      Contact form should Form opened    Pass |
|            Supplier           open                                    |
|                                                                       |
|   2        Submit supplier    Request should      Request        Pass |
|            request            submit              submitted           |
|   ------                                                              |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 14

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**              **Details**                                  |
|   ---------------------- -------------------------------------------  |
|   Test Case ID           TC_IM_014                                    |
|                                                                       |
|   Test Scenario          Verify empty field validation                |
|                                                                       |
|   Module                 Validation                                   |
|                                                                       |
|   Priority               High                                         |
|                                                                       |
|   Severity               Major                                        |
|                                                                       |
|   Test Type              Negative Testing                             |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   --------                                                            |
| --------------------------------------------------------------------- |
|   **Step                                                              |
|    **Action**        **Expected Result** **Actual Result** **Status** |
|   No**                                                                |
|   --------                                                            |
|  ----------------- ------------------- ----------------- ------------ |
|                                                                       |
| 1        Leave mandatory   Fields should       Blank fields      Pass |
|            fields empty      remain blank        observed             |
|                                                                       |
|                                                                       |
| 2        Click Submit      Validation messages Validation        Pass |
|                              should display      messages             |
|                                                  displayed            |
|   --------                                                            |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# TEST CASE 15

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**              **Details**                                  |
|   ---------------------- -------------------------------------------  |
|   Test Case ID           TC_IM_015                                    |
|                                                                       |
|   Test Scenario          Verify navigation menu links                 |
|                                                                       |
|   Module                 Navigation                                   |
|                                                                       |
|   Priority               Medium                                       |
|                                                                       |
|   Severity               Minor                                        |
|                                                                       |
|   Test Type              UI Testing                                   |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Test Steps

+-----------------------------------------------------------------------+
|   ------                                                              |
| --------------------------------------------------------------------- |
|   **St                                                                |
| ep   **Action**      **Expected Result** **Actual Result** **Status** |
|   No**                                                                |
|   ------                                                              |
| -- --------------- ------------------- ----------------- ------------ |
|   1        Click           Correct pages       Pages opened      Pass |
|            navigation      should open         correctly              |
|            links                                                      |
|                                                                       |
|   ------                                                              |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

### Status

Pass

# DEFECT TEST CASES

# TEST CASE 16

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**               **Details**                                 |
|   ----------------------- ------------------------------------------  |
|   Test Case ID            TC_IM_016                                   |
|                                                                       |
|   Test Scenario           Verify location consistency                 |
|                                                                       |
|   Module                  Location                                    |
|                                                                       |
|   Priority                High                                        |
|                                                                       |
|   Severity                Medium                                      |
|                                                                       |
|   Test Type               Usability Testing                           |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Homepage displayed Balurghat but selected location changed to Kolkata.

### Status

Fail

# TEST CASE 17

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**            **Details**                                    |
|   -------------------- ---------------------------------------------  |
|   Test Case ID         TC_IM_017                                      |
|                                                                       |
|   Test Scenario        Verify Hindi language localization             |
|                                                                       |
|   Module               Globalization                                  |
|                                                                       |
|   Priority             High                                           |
|                                                                       |
|   Severity             High                                           |
|                                                                       |
|   Test Type            Globalization Testing                          |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Selected Hindi language but contents displayed in English.

### Status

Fail

# TEST CASE 18

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**          **Details**                                      |
|   ------------------ -----------------------------------------------  |
|   Test Case ID       TC_IM_018                                        |
|                                                                       |
|   Test Scenario      Verify location-based product filtering          |
|                                                                       |
|   Module             Product Search                                   |
|                                                                       |
|   Priority           High                                             |
|                                                                       |
|   Severity           High                                             |
|                                                                       |
|   Test Type          Usability Testing                                |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Selected Bangalore location but products displayed from Kolkata.

### Status

Fail

# TEST CASE 19

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_019                                       |
|                                                                       |
|   Test Scenario       Verify English language localization            |
|                                                                       |
|   Module              Globalization                                   |
|                                                                       |
|   Priority            High                                            |
|                                                                       |
|   Severity            High                                            |
|                                                                       |
|   Test Type           Globalization Testing                           |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Selected English language but contents displayed in Hindi.

### Status

Fail

# TEST CASE 20

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_020                                       |
|                                                                       |
|   Test Scenario       Verify homepage navigation option               |
|                                                                       |
|   Module              Navigation                                      |
|                                                                       |
|   Priority            Medium                                          |
|                                                                       |
|   Severity            Medium                                          |
|                                                                       |
|   Test Type           Usability Testing                               |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Back/home navigation option missing from page.

### Status

Fail

# TEST CASE 21

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**             **Details**                                   |
|   --------------------- --------------------------------------------  |
|   Test Case ID          TC_IM_021                                     |
|                                                                       |
|   Test Scenario         Verify Bank Name placeholder                  |
|                                                                       |
|   Module                Form Validation                               |
|                                                                       |
|   Priority              Medium                                        |
|                                                                       |
|   Severity              Low                                           |
|                                                                       |
|   Test Type             Usability Testing                             |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Placeholder missing under Bank Name field.

### Status

Fail

# TEST CASE 22

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_022                                       |
|                                                                       |
|   Test Scenario       Verify mandatory field astrix symbol            |
|                                                                       |
|   Module              Form Validation                                 |
|                                                                       |
|   Priority            Medium                                          |
|                                                                       |
|   Severity            Medium                                          |
|                                                                       |
|   Test Type           Usability Testing                               |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Mandatory fields do not contain astrix (\*) symbol.

### Status

Fail

# TEST CASE 23

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**           **Details**                                     |
|   ------------------- ----------------------------------------------  |
|   Test Case ID        TC_IM_023                                       |
|                                                                       |
|   Test Scenario       Verify proper placeholder visibility            |
|                                                                       |
|   Module              UI                                              |
|                                                                       |
|   Priority            Medium                                          |
|                                                                       |
|   Severity            Low                                             |
|                                                                       |
|   Test Type           Usability Testing                               |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Proper placeholder text not present.

### Status

Fail

# TEST CASE 24

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**            **Details**                                    |
|   -------------------- ---------------------------------------------  |
|   Test Case ID         TC_IM_024                                      |
|                                                                       |
|   Test Scenario        Verify dropdown button visibility              |
|                                                                       |
|   Module               Dropdown                                       |
|                                                                       |
|   Priority             High                                           |
|                                                                       |
|   Severity             Medium                                         |
|                                                                       |
|   Test Type            Usability Testing                              |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Dropdown button missing from page.

### Status

Fail

# TEST CASE 25

+-----------------------------------------------------------------------+
|   ------------------------------------------------------------------  |
|   **Field**                **Details**                                |
|   ------------------------ -----------------------------------------  |
|   Test Case ID             TC_IM_025                                  |
|                                                                       |
|   Test Scenario            Verify hyperlink visibility                |
|                                                                       |
|   Module                   Hyperlink                                  |
|                                                                       |
|   Priority                 Low                                        |
|                                                                       |
|   Severity                 Low                                        |
|                                                                       |
|   Test Type                Usability Testing                          |
|   ------------------------------------------------------------------  |
+=======================================================================+
+-----------------------------------------------------------------------+

### Defect Observed

Hyperlinks are not underlined and not clearly visible.

### Status

Fail

# 6. DEFECT SUMMARY

+-----------------------------------------------------------------------+
|   --------                                                            |
| --------------------------------------------------------------------- |
|   **Defe                                                              |
| ct   **Defect Description**                 **Severity**   **Status** |
|   ID**                                                                |
|   --------                                                            |
| -- -------------------------------------- -------------- ------------ |
|                                                                       |
| DEF_001    Location mismatch issue                Medium         Open |
|                                                                       |
|                                                                       |
| DEF_002    Hindi language displaying English      High           Open |
|              content                                                  |
|                                                                       |
|                                                                       |
| DEF_003    Incorrect location-based product       High           Open |
|              display                                                  |
|                                                                       |
|                                                                       |
| DEF_004    English language displaying Hindi      High           Open |
|              content                                                  |
|                                                                       |
|                                                                       |
| DEF_005    Missing homepage navigation option     Medium         Open |
|                                                                       |
|                                                                       |
| DEF_006    Missing Bank Name placeholder          Low            Open |
|                                                                       |
|                                                                       |
| DEF_007    Mandatory fields missing astrix symbol Medium         Open |
|                                                                       |
|                                                                       |
| DEF_008    Improper placeholder text              Low            Open |
|                                                                       |
|                                                                       |
| DEF_009    Missing dropdown button                Medium         Open |
|                                                                       |
|                                                                       |
| DEF_010    Hyperlinks not highlighted properly    Low            Open |
|   --------                                                            |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

# 7. TEST EXECUTION SUMMARY

+-----------------------------------------------------------------------+
|                                                                       |
|  -------------------------------------------------------------------- |
|   **Total Test Cases**       **Passed**    **Failed**   **Blocked**   |
|                                                                       |
|  -------------------------- ------------- ------------ -------------- |
|   25                         15            10           0             |
|                                                                       |
|                                                                       |
|  -------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

# 8. ENHANCEMENT SUGGESTIONS

-   Improve UI user friendliness

-   Add proper back navigation button

-   Improve language localization functionality

-   Improve location-based filtering

-   Add proper placeholders

-   Add astrix (\*) for mandatory fields

-   Highlight hyperlinks properly

-   Improve dropdown visibility

# 9. CONCLUSION

All major functionalities of the IndiaMART web application were tested
successfully. Functional modules such as registration, login, search,
inquiry submission, contact supplier, cart management, and logout worked
properly.

However, several usability and globalization defects were identified
related to navigation, localization, placeholder visibility, dropdown
visibility, and UI consistency. These issues should be fixed to improve
user experience and application usability.

+-----------------------------------------------------------------------+
|   ----------                                                          |
| --------------------------------------------------------------------- |
|   **Pre                                                               |
| pared By**     **Reviewed By**        **Approved By**        **Date** |
|   ----------                                                          |
| --------- ---------------------- ---------------------- ------------- |
|   Smritil                                                             |
| ata Sarkar   \_\_\_\_\_\_\_\_\_\_   \_\_\_\_\_\_\_\_\_\_   20/05/2026 |
|                                                                       |
|   ----------                                                          |
| --------------------------------------------------------------------- |
+=======================================================================+
+-----------------------------------------------------------------------+

Bottom of Form
