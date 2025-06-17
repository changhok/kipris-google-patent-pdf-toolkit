# kipris-google-patent-pdf-toolkit

Program Description
This application is a comprehensive tool designed for patent research and analysis, specifically developed for handling patent documents from both KIPRIS Plus (Korean patent database) and Google Patents. The program provides an integrated solution for downloading, processing, and analyzing patent documents with advanced text extraction capabilities.

Key Features
1. KIPRIS Plus API Integration
Download PDF documents directly from KIPRIS Plus using API personal keys
Support for Korean patent application numbers.
Batch processing capability for multiple patent numbers

2. Google Patents Content Extraction
Extract Description and Claims sections directly from Google Patents web pages
Support for international patent formats (US, EP, JP, WO, CN, KR, etc.)
Original language content preservation with Unicode normalization
Direct PDF download from Google Patents database
Intelligent URL detection and fallback mechanisms for PDF retrieval

3. Local PDF Processing
Open and process multiple local PDF files simultaneously
Advanced text extraction using PDFMiner library
Batch text extraction for multiple documents
Support for various PDF formats and text layer detection

4. Multi-Tab Text Management
Organized tabbed interface for managing multiple patent documents
Individual text boxes for each processed document
Tab renaming and management capabilities
Text wrapping and formatting for improved readability

5. Prompt Management System
Dedicated prompt creation and management interface
Multiple prompt tabs for different analysis purposes
Save/load prompt collections for reuse
Integrated clipboard functionality for easy text transfer

How It Works
Patent Download: Enter patent numbers in the designated fields and use either KIPRIS Plus API or Google Patents integration to automatically download PDF files or extract web content.
Text Extraction: The program uses text layer detection to extract readable text from PDF documents, preserving formatting and structure(No OCR).
Content Organization: Extracted content is automatically organized in separate tabs, with clear labeling based on patent numbers or document names.
Analysis Preparation: Use the prompt management system to prepare analysis templates and copy extracted text for further processing in AI tools or other analysis software.
Export and Save: Save individual texts or batch export all processed documents for archival or further analysis.

Technical Requirements
Windows operating system
Internet connection for API access and Google Patents integration
Sufficient storage space for downloaded PDF files

How to Obtain KIPRIS Plus API Personal Key
To use the KIPRIS Plus PDF download functionality, you must first register for an API service and obtain a personal key. Please follow these steps:

Step 1: Create KIPRIS Plus Account
Visit the official KIPRIS Plus website: https://plus.kipris.or.kr/
Click on "Sign Up" to create a new account
Complete the registration process with your personal information
Verify your account through email confirmation

Step 2: Apply for API Service
Log in to your KIPRIS Plus account
Navigate to the API service section
Submit an application for API access
Wait for approval (processing time may vary)

Step 3: Obtain Personal Key
Once approved, access your account dashboard
Locate the API management section
Copy your assigned personal API key
Keep this key secure and confidential

Important Notes
Free Service: KIPRIS Plus API service is provided free of charge for legitimate research and educational purposes(1000 free requests/month)
Usage Limits: API calls may be subject to daily/monthly limits as specified in KIPRIS Plus terms of service
Key Security: Never share your personal API key with others or publish it publicly
Terms Compliance: Ensure your usage complies with KIPRIS Plus API terms and conditions

Troubleshooting
If you encounter issues during registration or API key acquisition:
Contact KIPRIS Plus customer support through their official website
Check their FAQ section for common registration problems
Ensure all required information is accurately provided during registration
Note: This application requires a valid KIPRIS Plus API personal key to function properly. The PDF download feature will not work without proper API authentication.

Disclaimer: This application is not affiliated with or endorsed by KIPRIS Plus or the Korean Intellectual Property Office (KIPO). Users are responsible for complying with all KIPRIS Plus terms of service and API usage policies.

License Agreement
© 2025 김창호 (k.changho@gmail.com). All Rights Reserved.

Non-Commercial Use License
This software is provided under a Non-Commercial Use Only license with the following terms and conditions:

PERMITTED USES:

Personal use for research and educational purposes
Academic research and scholarly activities
Non-profit organization use for research purposes
Government agency use for patent examination and research
PROHIBITED USES:

Any commercial use or commercial distribution
Selling, licensing, or sublicensing the software
Using the software in any profit-generating activity
Modification, reverse engineering, or creating derivative works
Redistribution in any form, modified or unmodified
DISCLAIMER OF WARRANTIES: This software is provided "AS IS" without warranty of any kind, either express or implied, including but not limited to the implied warranties of merchantability, fitness for a particular purpose, and non-infringement. The author makes no warranties about the accuracy, reliability, completeness, or timeliness of the software or any content accessed through it.

LIMITATION OF LIABILITY: In no event shall the author be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.

DATA RESPONSIBILITY: Users are solely responsible for ensuring compliance with applicable laws and regulations when accessing patent databases and downloading patent documents. The author assumes no responsibility for any legal consequences arising from the use of this software.

TERMINATION: This license is effective until terminated. Your rights under this license will terminate automatically without notice if you fail to comply with any term of this license.

By using this software, you acknowledge that you have read this license agreement and agree to be bound by its terms and conditions.
