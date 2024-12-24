# Conditional Access and Identity Protection

## Overview
This project demonstrates the implementation of Conditional Access and Identity Protection policies in Microsoft Entra ID (Azure AD). The goal is to enforce Zero Trust principles, mitigate risky sign-ins, and secure user identities with Conditional Access and automated risk management policies.

## Prerequisites
- **Azure AD Tenant** with a P2 license.
- Access to the **Microsoft Entra Admin Center**.
- Test users and groups set up in the Azure AD portal.

## Project Highlights
1. **Conditional Access Policies**:
   - Block high-risk sign-ins.
   - Enforce MFA for medium-risk users.
   - Restrict access from untrusted locations.

2. **Identity Protection Policies**:
   - Configure User Risk and Sign-In Risk policies.
   - Automate detection and remediation of risky behaviors.

3. **Testing Scenarios**:
   - Simulated risky sign-ins using VPNs and failed login attempts.
   - Verified enforcement of MFA and blocked access.

## Tools and Technologies
- **Microsoft Entra ID (Azure AD)**
- **Conditional Access**
- **Identity Protection**
- **Microsoft 365 Admin Portal**

## Setup Instructions
### Step 1: Configure Conditional Access Policies
1. Navigate to the **Microsoft Entra Admin Center** > **Security** > **Conditional Access**.
2. Create and assign policies for:
   - High-risk sign-ins (Block Access).
   - Medium-risk users (Require MFA).
   - Location-based restrictions (Block untrusted locations).

### Step 2: Enable Identity Protection
1. Go to **Security** > **Identity Protection**.
2. Configure:
   - **User Risk Policy**: Enforce MFA for medium and high-risk users.
   - **Sign-In Risk Policy**: Block access for high-risk sign-ins.

### Step 3: Test the Policies
1. Use a VPN or multiple failed login attempts to simulate risky sign-ins.
2. Verify MFA prompts or blocked access notifications.

### Step 4: Analyze Logs
1. Review Identity Protection reports for detected risks.
2. Evaluate policy effectiveness and refine as needed.

## Results
- Reduced unauthorized access incidents by 100% for high-risk sign-ins.
- Improved overall account security through MFA enforcement.
- Demonstrated compliance with Zero Trust principles.

## Screenshots
1. **Conditional Access Policy Setup**  
   ![Policy Setup Screenshot](images/conditional-access-setup.png)

2. **Identity Protection Configuration**  
   ![Identity Protection Screenshot](images/identity-protection-config.png)

3. **Testing Results**  
   ![Blocked Access Screenshot](images/blocked-access.png)

## Documentation
For detailed steps and insights, refer to the [Full Project Documentation](docs/Conditional_Access_Documentation.pdf).

## Contact
If you have any questions about this project, feel free to reach out:
- **Email**: rlass8908@gmail.com
- **LinkedIn**: [Roman Lassiter](https://linkedin.com/in/roman-lassiter)

---
