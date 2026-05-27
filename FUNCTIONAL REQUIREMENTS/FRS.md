FUNCTIONAL REQUIREMENT DOCUMENT (FRD)
INDIA MART – B2B MARKETPLACE

Document Information
Field	Details
Project Name	IndiaMART Web Application
Document Type	Functional Requirement Document (FRD)
Version	1.0
Prepared By	Smriti
Date	26 January 2026
Application Type	B2B Marketplace

1. INTRODUCTION
1.1 Purpose
The purpose of this Functional Requirement Document (FRD) is to define the functional requirements for the IndiaMART web application. The system is designed to connect buyers and suppliers through an online B2B marketplace platform.
This document explains system functionality, user interactions, modules, workflows, validations, business rules, and expected behavior of the application.

1.2 Scope
The IndiaMART application allows:
•	Buyers to search products and suppliers
•	Sellers to list products and business details
•	Users to contact suppliers
•	Users to submit inquiries
•	Product browsing and filtering
•	Account registration and authentication
•	Cart and inquiry management
•	Profile management
The application supports communication between businesses and customers through an online marketplace environment.

1.3 Objectives
The main objectives are:
•	Provide a smooth B2B marketplace experience
•	Allow buyers to discover products easily
•	Allow suppliers to generate business leads
•	Maintain secure user authentication
•	Ensure accurate inquiry processing
•	Improve usability and accessibility

2. SYSTEM OVERVIEW
2.1 Application Overview
IndiaMART is an online marketplace where businesses can showcase products and services while buyers can search, compare, and contact suppliers.
The application includes:
•	User authentication system
•	Product catalog
•	Search engine
•	Supplier directory
•	Inquiry system
•	Cart system
•	Business profile management

2.2 User Types
Buyer
A buyer can:
•	Register and login
•	Search products
•	Contact suppliers
•	Add products to cart
•	Submit inquiries
•	View supplier profiles
Seller/Supplier
A supplier can:
•	Register business account
•	Add products
•	Manage listings
•	Respond to inquiries
•	Update profile details
Admin
Admin can:
•	Manage users
•	Monitor listings
•	Remove invalid products
•	Handle reports and complaints
•	Manage platform content

3. FUNCTIONAL REQUIREMENTS
MODULE 1 – USER REGISTRATION
3.1 Description
The system shall allow new users to register using mobile number, email ID, and business details.

3.2 Functional Requirements
Requirement ID	Requirement Description
FR_REG_001	System shall allow users to access registration page
FR_REG_002	System shall allow user registration using mobile number
FR_REG_003	System shall validate mandatory fields
FR_REG_004	System shall validate email format
FR_REG_005	System shall validate mobile number length
FR_REG_006	System shall prevent duplicate registration
FR_REG_007	System shall send OTP for verification
FR_REG_008	System shall create account after successful verification

3.3 Business Rules
•	Mobile number must contain 10 digits
•	Email format must be valid
•	Mandatory fields cannot remain empty
•	Duplicate mobile number should not be allowed

3.4 Input Fields
Field Name	Type	Validation
Full Name	Text	Mandatory
Mobile Number	Numeric	10 Digits
Email ID	Email	Valid Format
Password	Password	Minimum 8 Characters
Business Name	Text	Mandatory

MODULE 2 – LOGIN AUTHENTICATION
4.1 Description
The system shall allow registered users to login using mobile number, email ID, password, or OTP.

4.2 Functional Requirements
Requirement ID	Requirement Description
FR_LOG_001	System shall display login page
FR_LOG_002	System shall allow login using valid credentials
FR_LOG_003	System shall reject invalid credentials
FR_LOG_004	System shall support OTP login
FR_LOG_005	System shall redirect user to dashboard after login
FR_LOG_006	System shall maintain user session
FR_LOG_007	System shall support logout functionality

4.3 Business Rules
•	Invalid login attempts should display error message
•	Session should expire after inactivity
•	User should logout successfully

MODULE 3 – PRODUCT SEARCH
5.1 Description
The system shall allow users to search products using keywords.

5.2 Functional Requirements
Requirement ID	Requirement Description
FR_SRC_001	System shall provide search bar on homepage
FR_SRC_002	System shall allow keyword-based search
FR_SRC_003	System shall display relevant search results
FR_SRC_004	System shall support category-based search
FR_SRC_005	System shall display no-result message if product unavailable
FR_SRC_006	System shall support auto-suggestions

5.3 Business Rules
•	Search results should match user keyword
•	Product results should display relevant supplier details
•	Search response time should be minimal

MODULE 4 – PRODUCT FILTER
6.1 Description
The system shall allow users to filter products based on categories and business requirements.

6.2 Functional Requirements
Requirement ID	Requirement Description
FR_FIL_001	System shall allow category filtering
FR_FIL_002	System shall allow location filtering
FR_FIL_003	System shall allow price filtering
FR_FIL_004	System shall display filtered products
FR_FIL_005	System shall reset filters when requested

MODULE 5 – PRODUCT DETAILS PAGE
7.1 Description
The system shall display complete product information.

7.2 Functional Requirements
Requirement ID	Requirement Description
FR_PROD_001	System shall display product name
FR_PROD_002	System shall display product images
FR_PROD_003	System shall display supplier details
FR_PROD_004	System shall display pricing information
FR_PROD_005	System shall display product description
FR_PROD_006	System shall display inquiry/contact options

MODULE 6 – CONTACT SUPPLIER
8.1 Description
The system shall allow buyers to contact suppliers.

8.2 Functional Requirements
Requirement ID	Requirement Description
FR_CON_001	System shall provide Contact Supplier button
FR_CON_002	System shall open inquiry form
FR_CON_003	System shall allow message submission
FR_CON_004	System shall send inquiry to supplier
FR_CON_005	System shall display success confirmation

8.3 Business Rules
•	Inquiry message cannot remain empty
•	User contact information should be captured
•	Supplier should receive inquiry notification

MODULE 7 – CART MANAGEMENT
9.1 Description
The system shall allow users to add products to cart.

9.2 Functional Requirements
Requirement ID	Requirement Description
FR_CART_001	System shall allow add to cart functionality
FR_CART_002	System shall display cart items
FR_CART_003	System shall allow item removal
FR_CART_004	System shall update cart quantity
FR_CART_005	System shall maintain cart session

MODULE 8 – SELLER PROFILE
10.1 Description
The system shall display seller business information.

10.2 Functional Requirements
Requirement ID	Requirement Description
FR_SELL_001	System shall display supplier profile
FR_SELL_002	System shall display business name
FR_SELL_003	System shall display contact details
FR_SELL_004	System shall display business location
FR_SELL_005	System shall display listed products

MODULE 9 – FORGOT PASSWORD
11.1 Description
The system shall allow users to reset forgotten passwords.

11.2 Functional Requirements
Requirement ID	Requirement Description
FR_FP_001	System shall provide Forgot Password option
FR_FP_002	System shall verify registered mobile/email
FR_FP_003	System shall send OTP/reset link
FR_FP_004	System shall allow password reset
FR_FP_005	System shall confirm successful reset

MODULE 10 – LOGOUT
12.1 Description
The system shall allow users to logout securely.

12.2 Functional Requirements
Requirement ID	Requirement Description
FR_LO_001	System shall provide logout option
FR_LO_002	System shall terminate active session
FR_LO_003	System shall redirect to login/home page

4. NON-FUNCTIONAL REQUIREMENTS
13.1 Performance Requirements
•	Application should load within acceptable time
•	Search results should appear quickly
•	System should support multiple users simultaneously

13.2 Security Requirements
•	Passwords should remain encrypted
•	User data should remain secure
•	Unauthorized access should be restricted
•	Session management should be secure

13.3 Usability Requirements
•	Application should provide user-friendly navigation
•	UI should be responsive
•	Error messages should be clear and understandable

13.4 Compatibility Requirements
The application should support:
•	Google Chrome
•	Mozilla Firefox
•	Microsoft Edge
•	Mobile browsers

5. VALIDATION REQUIREMENTS
Field	Validation
Mobile Number	Must contain 10 digits
Email ID	Must follow valid email format
Password	Minimum 8 characters
Inquiry Message	Cannot remain empty
Mandatory Fields	Cannot remain blank

6. ERROR HANDLING REQUIREMENTS
Scenario	Expected Behavior
Invalid Login	Display error message
Empty Mandatory Field	Display validation message
Server Failure	Display system error message
Session Expired	Redirect user to login page
Invalid OTP	Display OTP validation message

7. ASSUMPTIONS
•	Users have internet connectivity
•	Users use supported browsers
•	OTP services are functioning properly
•	Product data is available in database

8. CONSTRAINTS
•	System depends on internet availability
•	OTP verification depends on third-party service
•	Performance may vary based on server load

9. ACCEPTANCE CRITERIA
The application shall be considered successful if:
•	Users can register successfully
•	Users can login/logout successfully
•	Search functionality works properly
•	Supplier inquiry submission works correctly
•	Product filters function accurately
•	Validation messages appear correctly
•	No critical defects exist in production

10. TESTING REQUIREMENTS
The following testing types shall be performed:
•	Functional Testing
•	Regression Testing
•	UI Testing
•	Validation Testing
•	Integration Testing
•	Compatibility Testing
•	Smoke Testing
•	User Acceptance Testing (UAT)

11. FUTURE ENHANCEMENTS
Future improvements may include:
•	AI-based product recommendations
•	Live supplier chat support
•	Voice search
•	Online payment integration
•	Multi-language support
•	Real-time order tracking

12. CONCLUSION
This Functional Requirement Document defines the major functionalities and expected behavior of the IndiaMART web application. The document serves as a reference for development, testing, validation, and quality assurance activities.
The system is designed to provide a secure, scalable, and user-friendly B2B marketplace platform for buyers and suppliers.

13. APPROVAL SIGN-OFF
Prepared By	Reviewed By	Approved By	Date
Smriti	__________	__________	26/05/2026

