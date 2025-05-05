# requirement-analysis

## Requirement Analysis in Software Development

This repository contains the requirement analysis documentation for a hotel booking management system similar to Airbnb or OYO. It includes functional and non-functional requirements, use case diagrams, and acceptance criteria.

## What is Requirement Analysis?

Requirement Analysis is the process of determining user expectations for a new or modified product. It involves:
- Gathering and documenting requirements
- Analyzing and prioritizing needs
- Validating requirements with stakeholders

In SDLC, it's the crucial first phase that bridges business needs with technical implementation.

## Why is Requirement Analysis Important?

1. **Prevents Costly Changes**: Identifying requirements early reduces expensive changes later
2. **Sets Clear Expectations**: Aligns stakeholders and developers on system functionality
3. **Forms Development Foundation**: Provides blueprint for design, coding, and testing

## Key Activities in Requirement Analysis

- **Requirement Gathering**: Collect needs through interviews, surveys (e.g., hotel managers need property management tools)
- **Requirement Elicitation**: Refine requirements via workshops and prototypes
- **Requirement Documentation**: Create SRS document with functional/non-functional requirements
- **Analysis & Modeling**: Develop use cases and data models (like hotel booking flow)
- **Requirement Validation**: Review requirements for completeness and consistency

## Types of Requirements

### Functional Requirements
1. Property Search: Users can filter hotels by location, price, amenities
2. Booking System: Secure reservation process with payment integration
3. User Profiles: Registration/login with authentication

### Non-functional Requirements
1. Performance: Handle 1000 concurrent users with <2s response time
2. Security: Encrypt sensitive data like payment information
3. Scalability: Microservices architecture to handle peak loads

## Use Case Diagrams

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="741px" height="451px" viewBox="-0.5 -0.5 741 451">
  <defs/>
  <g>
    <rect x="200" y="0" width="360" height="450" fill="#f5f5f5" stroke="#666666" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 358px; height: 1px; padding-top: 7px; margin-left: 201px;">
            <div data-drawio-colors="color: #333333; " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(51, 51, 51); line-height: 1.2; pointer-events: all; font-weight: bold; white-space: normal; overflow-wrap: normal;">
                Booking Management System
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="380" y="19" fill="#333333" font-family="Helvetica" font-size="12px" text-anchor="middle" font-weight="bold">
          Booking Management System
        </text>
      </switch>
    </g>
    <ellipse cx="380" cy="60" rx="70" ry="30" fill="#dae8fc" stroke="#6c8ebf" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 138px; height: 1px; padding-top: 60px; margin-left: 311px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">
                Search Properties
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="380" y="64" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Search Properties
        </text>
      </switch>
    </g>
    <ellipse cx="380" cy="130" rx="70" ry="30" fill="#dae8fc" stroke="#6c8ebf" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 138px; height: 1px; padding-top: 130px; margin-left: 311px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">
                View Property Details
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="380" y="134" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          View Property Details
        </text>
      </switch>
    </g>
    <ellipse cx="380" cy="200" rx="70" ry="30" fill="#dae8fc" stroke="#6c8ebf" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 138px; height: 1px; padding-top: 200px; margin-left: 311px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">
                Make Booking
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="380" y="204" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Make Booking
        </text>
      </switch>
    </g>
    <ellipse cx="380" cy="270" rx="70" ry="30" fill="#dae8fc" stroke="#6c8ebf" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 138px; height: 1px; padding-top: 270px; margin-left: 311px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">
                Manage Property Listings
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="380" y="274" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Manage Property Listings
        </text>
      </switch>
    </g>
    <ellipse cx="380" cy="340" rx="70" ry="30" fill="#dae8fc" stroke="#6c8ebf" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 138px; height: 1px; padding-top: 340px; margin-left: 311px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">
                Manage User Accounts
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="380" y="344" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Manage User Accounts
        </text>
      </switch>
    </g>
    <ellipse cx="380" cy="410" rx="70" ry="30" fill="#dae8fc" stroke="#6c8ebf" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 138px; height: 1px; padding-top: 410px; margin-left: 311px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: normal; overflow-wrap: normal;">
                Process Payments
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="380" y="414" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Process Payments
        </text>
      </switch>
    </g>
    <ellipse cx="100" cy="60" rx="15" ry="15" fill="#ffffff" stroke="#000000" pointer-events="all"/>
    <path d="M 100 75 L 100 125 M 100 85 L 70 85 M 100 85 L 130 85 M 100 125 L 70 165 M 100 125 L 130 165" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 175px; margin-left: 100px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">
                Guest User
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="100" y="187" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Guest User
        </text>
      </switch>
    </g>
    <ellipse cx="100" cy="270" rx="15" ry="15" fill="#ffffff" stroke="#000000" pointer-events="all"/>
    <path d="M 100 285 L 100 335 M 100 295 L 70 295 M 100 295 L 130 295 M 100 335 L 70 375 M 100 335 L 130 375" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 385px; margin-left: 100px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">
                Registered User
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="100" y="397" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Registered User
        </text>
      </switch>
    </g>
    <ellipse cx="640" cy="270" rx="15" ry="15" fill="#ffffff" stroke="#000000" pointer-events="all"/>
    <path d="M 640 285 L 640 335 M 640 295 L 610 295 M 640 295 L 670 295 M 640 335 L 610 375 M 640 335 L 670 375" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 385px; margin-left: 640px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">
                Property Owner
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="640" y="397" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Property Owner
        </text>
      </switch>
    </g>
    <ellipse cx="640" cy="60" rx="15" ry="15" fill="#ffffff" stroke="#000000" pointer-events="all"/>
    <path d="M 640 75 L 640 125 M 640 85 L 610 85 M 640 85 L 670 85 M 640 125 L 610 165 M 640 125 L 670 165" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe flex-start; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 175px; margin-left: 640px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; white-space: nowrap;">
                Admin
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="640" y="187" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="12px" text-anchor="middle">
          Admin
        </text>
      </switch>
    </g>
    <path d="M 130 85 L 302.65 60.8" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 130 85 L 302.96 130.44" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 130 295 L 302.65 200.8" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 130 295 L 300.01 130.56" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 130 295 L 302.65 60.8" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 610 295 L 456.89 270.24" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 610 85 L 456.89 340.24" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 610 85 L 456.89 270.24" fill="none" stroke="#000000" stroke-miterlimit="10" pointer-events="stroke"/>
    <path d="M 449.67 391.87 L 449.97 229.97" fill="none" stroke="#000000" stroke-miterlimit="10" stroke-dasharray="3 3" pointer-events="stroke"/>
    <path d="M 449.66 398.87 L 446.17 391.87 L 453.17 391.87 Z" fill="#000000" stroke="#000000" stroke-miterlimit="10" pointer-events="all"/>
    <g transform="translate(-0.5 -0.5)">
      <switch>
        <foreignObject pointer-events="none" width="100%" height="100%" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility" style="overflow: visible; text-align: left;">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: unsafe center; justify-content: unsafe center; width: 1px; height: 1px; padding-top: 310px; margin-left: 475px;">
            <div data-drawio-colors="color: rgb(0, 0, 0); " style="box-sizing: border-box; font-size: 0px; text-align: center;">
              <div style="display: inline-block; font-size: 11px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; pointer-events: all; background-color: rgb(255, 255, 255); white-space: nowrap;">
                &lt;&lt;include&gt;&gt;
              </div>
            </div>
          </div>
        </foreignObject>
        <text x="475" y="313" fill="rgb(0, 0, 0)" font-family="Helvetica" font-size="11px" text-anchor="middle">
          &lt;&lt;include&gt;&gt;
        </text>
      </switch>
    </g>
  </g>
  <switch>
    <g requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"/>
    <a transform="translate(0,-5)" xlink:href="https://www.drawio.com/doc/faq/svg-export-text-problems" target="_blank">
      <text text-anchor="middle" font-size="10px" x="50%" y="100%">
        Text is not SVG - cannot display
      </text>
    </a>
  </switch>
</svg>

Benefits:
- Visualizes system interactions
- Identifies all user roles and functions
- Guides development and testing

## Acceptance Criteria

Example for Booking Feature:
1. User can select available dates from calendar
2. System displays total price including taxes
3. Confirmation email sent within 2 minutes
4. Booking appears in user's profile immediately
5. Hotel manager receives notification of new booking
