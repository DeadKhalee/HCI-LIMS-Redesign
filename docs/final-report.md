# Human-Computer Interaction Redesign Project
## Malawi Land Information Management System (LIMS) Portal

**Student ID:** 23313351001  
**Module:** 351 CP 81 - Comprehension: Human-Computer Interaction  
**Prototyping Tool:** Penpot  
**Submission Date:** December 3, 2025

---

## 1. Executive Summary

This report documents the comprehensive redesign of the Malawi Land Information Management System (LIMS) portal, a critical government service platform that enables citizens to register land, make payments, and access property-related services. Through systematic heuristic evaluation using Nielsen's 10 Usability Heuristics, this project identified significant usability barriers in the current interface and developed an improved prototype that prioritizes user-centered design, accessibility, and task efficiency.

The original LIMS portal suffers from numerous usability problems including text-heavy content organization, bureaucratic language, poor visual hierarchy, unclear navigation, and intimidating legal disclaimers that create barriers to access for average citizens. The redesigned prototype addresses these issues through a modern, task-oriented interface that uses plain language, visual cards, clear navigation aids, and welcoming messaging. The final deliverable consists of three fully interactive prototype screens (Homepage, Login, and Registration Selection) created in Penpot, demonstrating significant improvements in usability and user experience.

---

## 2. Introduction and Context

### 2.1 Interface Selection

The Malawi Land Information Management System (LIMS) portal, accessible at http://lims.lands.gov.mw/, was selected for this redesign project due to its critical importance as a public service platform and its significant usability challenges. As the digital gateway to land registration, property management, and related services provided by the Ministry of Lands, this system serves a diverse user base including property owners, land buyers, professional surveyors, lawyers, physical planners, and government officials.

Land services are fundamental to economic activity, property rights, and citizen welfare in Malawi. When such an essential service is difficult to use, it creates barriers that disproportionately affect citizens with lower digital literacy, limited education, or unfamiliarity with government bureaucracy. Improving the usability of this system has direct, tangible benefits for Malawian society.

### 2.2 System Purpose and User Goals

The LIMS portal provides the following core functionalities:
- User account registration for different user types (property owners, professionals)
- Secure login and authentication
- Land parcel information viewing and management
- Payment processing for leases, ground rent, and application fees
- Document submission and tracking
- Personal information updates
- Notification system for important updates

Primary user goals include registering property, making timely payments, tracking application status, accessing certificates and documents, and updating account information. The current interface, however, makes these tasks unnecessarily difficult through poor information architecture and design choices that prioritize organizational information over user needs.

---

## 3. Methodology

### 3.1 Heuristic Evaluation Framework

The evaluation employed Nielsen's 10 Usability Heuristics as the primary framework for identifying usability problems. This industry-standard methodology provides systematic coverage of key usability principles:

1. **Visibility of System Status** - Users should know what's happening through timely feedback
2. **Match Between System and Real World** - Use familiar language and concepts
3. **User Control and Freedom** - Provide clear exits and undo options
4. **Consistency and Standards** - Follow platform conventions
5. **Error Prevention** - Design to prevent problems before they occur
6. **Recognition Rather Than Recall** - Minimize memory load with visible options
7. **Flexibility and Efficiency of Use** - Support both novice and expert users
8. **Aesthetic and Minimalist Design** - Remove irrelevant information
9. **Help Users Recognize, Diagnose, and Recover from Errors** - Clear error messages
10. **Help and Documentation** - Provide accessible assistance

### 3.2 Evaluation Process

The evaluation involved systematic review of all publicly accessible pages (homepage, registration selection, and login pages). Each page was examined against all ten heuristics, with problems documented using screenshots, severity ratings, and specific examples from the interface. Severity ratings ranged from 0 (not a problem) to 4 (usability catastrophe), with problems rated 2 or 3 prioritized for the redesign.

The evaluation was limited to public-facing pages as authenticated areas were not accessible. However, these entry pages are critical as they represent users' first interaction with the system and significantly influence whether users successfully complete registration and login processes.

---

## 4. Identified Usability Problems

### 4.1 Critical Issues (Severity 3 - Major)

**Problem 1: Text-Heavy Homepage with Organizational Focus**
The homepage immediately confronts users with lengthy paragraphs about the Ministry of Lands' establishment, mandate, vision, and mission. This organizational information obscures the actual services available, forcing users to read and comprehend bureaucratic text before finding actionable options. As stated on the homepage: "The Ministry of Lands was established to administer and manage land housing issues by ensuring equitable access and secure tenure to land and housing for everyone." While this information may be relevant to some stakeholders, it creates unnecessary cognitive load for citizens who simply want to register property or make a payment.

This violates Heuristic #8 (Aesthetic and Minimalist Design) by prioritizing rarely needed organizational information over primary user tasks, and Heuristic #6 (Recognition Rather Than Recall) by requiring users to read and remember information rather than providing scannable visual options.

**Problem 2: Poor Visual Hierarchy**
Throughout the interface, text appears in similar sizes and weights, making it difficult to distinguish headings from body text or primary actions from secondary information. The lack of clear visual prioritization means users must carefully read all content to understand what actions are available and which are most important. This violates multiple heuristics including #8 (Minimalist Design) and #6 (Recognition over Recall).

**Problem 3: Unclear Account Type Selection**
The registration process presents four account type options using professional terminology: "Lessee/Applicant Account Registration," "Surveyor Account Registration," "Registered Lawyer Account Registration," and "Registered Physical Planner Account Registration." These labels assume users understand legal and professional terminology. Average citizens are unlikely to know whether they are a "lessee" or "applicant," creating confusion and potential for wrong selections.

This violates Heuristic #2 (Match Between System and Real World) by using internal jargon rather than user-familiar language, and Heuristic #5 (Error Prevention) by not providing enough information to make correct choices.

**Problem 4: No Navigation Aids**
The interface completely lacks breadcrumb navigation or any visual indication of users' location within the site hierarchy. Page URLs use meaningless GUIDs (e.g., PageID=b4ee5d9b-c6da-412f-a78a-2db607d7fa1c) that provide no context. This violates Heuristic #1 (Visibility of System Status) by failing to keep users informed of their location and making it difficult to navigate back without using browser controls.

**Problem 5: Intimidating Login Experience**
The login page immediately displays threatening legal language: "Access to this Land Information Management System by any person other than an authorized individual or an authorized agent for a company is strictly prohibited and may result in legal action against such person." This creates anxiety and fear rather than confidence and welcome, potentially deterring legitimate users from accessing the system.

This violates Heuristic #2 (Match Between System and Real World) by using threatening rather than welcoming language, creating an adversarial rather than supportive relationship with users.

**Problem 6: Hidden Help Resources**
Help, FAQ, or support contact information is not prominently accessible from pages where users most need it. When users encounter difficulties with registration or login, they must search for assistance rather than having it readily available. This violates Heuristic #10 (Help and Documentation) by making support difficult to find when problems occur.

### 4.2 Additional Issues Identified

Beyond the six major problems prioritized for the redesign, the evaluation identified additional issues including inconsistent button styling, lack of input validation guidance on forms, absence of "forgot password" options, no progress indicators for multi-step processes, and missing confirmation messages after actions. While these problems were not all addressed in the prototype due to time and scope constraints, they represent opportunities for future iteration.

---

## 5. Redesign Process and Rationale

### 5.1 Design Principles and Goals

The redesign was guided by several core principles:

**User-Centered Task Focus:** Shift from organizational information to user goals. The interface should answer "What can I do here?" rather than "Who runs this system?"

**Plain Language Communication:** Replace bureaucratic and technical terminology with conversational language that average citizens understand.

**Visual Hierarchy and Scannability:** Use size, weight, color, and spacing to clearly communicate importance and guide user attention.

**Progressive Disclosure:** Show users what they need when they need it, rather than overwhelming them with all information at once.

**Welcoming and Supportive Tone:** Create confidence rather than anxiety, treating users as valued constituents rather than potential violators.

**Accessibility and Inclusivity:** Design for users with varying levels of digital literacy, education, and familiarity with government processes.

### 5.2 Wireframing Phase

Before creating the final prototype, low-fidelity paper wireframes were sketched to explore layout options and information architecture without the distraction of visual design details. These wireframes focused on:
- Placement of primary actions (register, login, pay)
- Content hierarchy and organization
- Navigation structure and wayfinding aids
- Form layout and input guidance
- Balance between information and action

The wireframes were crucial for solving structural problems before investing time in visual design, and they were documented in the project repository to show design iteration.

---

## 6. Redesigned Interface Solution

### 6.1 Homepage Redesign

**Visual Structure:**
The redesigned homepage employs a clean, modern layout with clear visual hierarchy. A simple header contains the Ministry of Lands logo, main navigation menu (Home, Services, Help, Contact), and a prominent Login button. Below this, a hero section immediately communicates the site's purpose with the heading "Manage Your Land and Property" and subtitle "Register property, make payments, and access land services online."

**Action Cards:**
The primary content area features three large, visually distinct action cards arranged horizontally:

1. **Register Account** (📝 icon) - "Create your account to access land services and manage properties" with "Get Started" button
2. **Login** (🔐 icon) - "Access your account to view properties and make payments" with "Sign In" button  
3. **Make Payment** (💳 icon) - "Pay lease fees, ground rent, or application charges quickly" with "Pay Now" button

These cards use white backgrounds with subtle shadows, clear iconography, and prominent call-to-action buttons. The visual design makes the page immediately scannable, allowing users to identify their desired action within seconds rather than reading paragraphs of text.

**Quick Links Section:**
Below the primary actions, a grid of smaller boxes provides access to secondary functions like downloading forms, accessing FAQs, contacting support, finding office locations, tracking applications, viewing user guides, and accessing live chat. This organization ensures common but secondary tasks remain accessible without cluttering the primary interface.

**Footer Redesign:**
Organizational information previously dominating the homepage has been moved to the footer, organized into three columns: About (ministry information, vision, leadership, policies), Services (land registration, property search, payments, document submission), and Support (help center, contact information, terms of service, privacy policy). This ensures the information remains available for stakeholders who need it while removing it from the primary user path.

**Heuristics Addressed:**
- H#2 (Real World Match): Task-oriented language replaces bureaucratic text
- H#6 (Recognition over Recall): Visual cards with icons enable quick scanning
- H#8 (Minimalist Design): Removed organizational clutter, focused on user tasks
- H#10 (Help Documentation): Help clearly visible and accessible

### 6.2 Login Page Redesign

**Split Layout Approach:**
The login page uses a two-column split layout. The left side (50% width) contains the login form on a white background, while the right side features an information panel on a light gray background. This division creates clear focus on the primary task (logging in) while providing supportive information alongside.

**Welcoming Messaging:**
Instead of legal warnings, the page greets users with "Welcome Back" as the main heading and "Sign in to access your land and property services" as the subtitle. This welcoming tone establishes a supportive rather than adversarial relationship.

**Form Design:**
The login form includes clearly labeled input fields for "Email Address or National ID" and "Password," each with helper text below explaining requirements ("Enter your registered email or ID number" and "Minimum 8 characters"). This guidance prevents errors by communicating expectations upfront (Heuristic #5: Error Prevention).

The form includes a "Remember me" checkbox and prominently displays a "Forgot password?" link in a contrasting blue color, making error recovery easy (Heuristic #9: Error Recovery). A large "Sign In" button uses the primary blue color to clearly indicate the main action.

**Security Reassurance:**
Rather than threatening legal text, the page includes a positive security note: "🔒 Your data is secure: We use industry-standard encryption to protect your information. Never share your password with anyone." This communicates security without creating fear.

**Information Panel:**
The right side features a "What You Can Do" section that lists the benefits of logging in:
- View and manage your properties
- Make payments for leases and fees  
- Submit and track applications
- Download certificates and documents
- Update your account information
- Receive important notifications

This reminds users why they're logging in and the value the system provides. Below this, a help box offers support through "Call Support" and "Live Chat" buttons, ensuring assistance is immediately available (Heuristic #10: Help Documentation).

**Heuristics Addressed:**
- H#2 (Real World Match): Friendly, welcoming language throughout
- H#3 (User Control): Clear back option, remember me feature
- H#5 (Error Prevention): Helper text prevents input errors
- H#9 (Error Recovery): Forgot password prominently displayed
- H#10 (Help Documentation): Support immediately accessible

### 6.3 Registration Selection Redesign

**Navigation Context:**
The page begins with a breadcrumb trail: "Home → Create Account → Select Account Type," immediately showing users their location in the process and providing an easy way to navigate back (Heuristic #1: Visibility of System Status and Heuristic #3: User Control).

**Clear Heading with Reassurance:**
The main heading "Choose Your Account Type" is followed by the reassuring subtitle: "Select the option that best describes you. You can change this later in your account settings if needed." This reduces decision anxiety by clarifying that mistakes can be corrected (Heuristic #3: User Control and Heuristic #5: Error Prevention).

**Simplified Account Types:**
Rather than four confusing professional titles, the redesign presents two clear categories in large, side-by-side cards:

**Card 1: Property Owner or Buyer** (🏠 icon)
- Subtitle: "For individuals managing personal property"
- Description: "Choose this if you own property, are buying land, or need to manage residential or commercial properties"
- Feature list with green checkmarks:
  - Register and view your properties
  - Make lease and ground rent payments
  - Submit required documents
  - Track application status
  - Receive notifications and reminders
- "Select This Account" button
- "Learn more →" link

**Card 2: Land Professional** (💼 icon)
- Subtitle: "For surveyors, lawyers, and planners"
- Description: "Choose this if you're a registered professional working with land transactions on behalf of clients"
- Feature list with green checkmarks:
  - Manage multiple client properties
  - Submit professional reports and surveys
  - Access advanced land search tools
  - Bulk document submission
  - Professional dashboard and analytics
- "Select This Account" button
- "Learn more →" link

This simplification from four to two categories recognizes that most professionals can self-identify as professionals versus property owners. The detailed feature lists help users understand exactly what each account type enables, preventing wrong choices (Heuristic #5: Error Prevention). The plain language headings ("Property Owner or Buyer" instead of "Lessee/Applicant") immediately communicate purpose (Heuristic #2: Real World Match).

**Help Section:**
At the bottom of the page, a help section with dashed border asks "Not Sure Which Account is Right for You?" and offers "Contact Support" and "Live Chat" buttons. This explicit help option catches confused users before they make wrong choices (Heuristic #10: Help Documentation).

**Heuristics Addressed:**
- H#1 (System Status): Breadcrumb shows location
- H#2 (Real World Match): Plain language categories
- H#3 (User Control): Can change account type later
- H#5 (Error Prevention): Clear descriptions prevent wrong choices
- H#6 (Recognition over Recall): Icons and visual cards aid scanning
- H#10 (Help Documentation): Help section prominent

---

## 7. Design System and Visual Design

### 7.1 Color Palette

A consistent color system was established to create visual harmony and communicate meaning:

- **Primary Blue (#2c3e50)**: Used for headers, buttons, and main headings. This dark blue conveys professionalism and trust appropriate for a government service.
- **Secondary Blue (#3498db)**: Used for links, secondary buttons, and interactive elements requiring less emphasis.
- **Success Green (#27ae60)**: Used for checkmarks, success messages, and positive confirmations.
- **Warning Orange (#f39c12)**: Reserved for warnings and important notices requiring attention.
- **Background Light (#f8f9fa)**: Very light gray for section backgrounds, providing subtle visual separation.
- **Border Gray (#dee2e6)**: Light gray for borders and dividers.
- **Text Primary (#212529)**: Near-black for main body text, ensuring high contrast and readability.
- **Text Secondary (#6c757d)**: Medium gray for secondary text like descriptions and labels.

This palette provides sufficient contrast for accessibility (meeting WCAG 2.1 AA standards) while maintaining a modern, professional appearance.

### 7.2 Typography

A clear typographic hierarchy guides users through content:

- **H1 (48px Bold)**: Main page headings ("Manage Your Land and Property")
- **H2 (36px Bold)**: Section headings ("Welcome Back")
- **H3 (24px Semi-bold)**: Card titles ("Register Account")
- **Body Large (18px Regular)**: Hero section subtitles and important descriptions
- **Body Regular (16px Regular)**: Standard body text and form labels
- **Small (14px Regular)**: Helper text, secondary information, and breadcrumbs

The font choice (system default or Inter/Roboto if available) prioritizes readability and load performance. Consistent sizing and weight create clear information hierarchy without requiring users to consciously process formatting.

### 7.3 Spacing and Layout

Generous white space prevents the cluttered feeling of the original interface. A spacing system based on 8px increments (8px, 16px, 24px, 32px, 48px) creates rhythm and consistency. Cards use sufficient padding (32-40px) to prevent cramped text. Section spacing (48-60px between major sections) provides clear visual separation.

The 1440px canvas width accommodates modern desktop displays while remaining manageable. All layouts use responsive grid systems that could adapt to mobile devices in future development.

### 7.4 Interactive Elements

Buttons follow clear visual conventions:
- **Primary buttons**: Solid primary blue background, white text, 4px border radius
- **Secondary buttons**: White background, blue border, blue text
- **Button states**: Hover effects (subtle darkening) provide feedback

Cards include subtle shadows (0px 4px 12px rgba(0,0,0,0.1)) to create depth and indicate interactivity. All interactive elements have hover states and maintain sufficient touch target sizes (minimum 44x44px) for accessibility.

---

## 8. Prototyping and Implementation

### 8.1 Tool Selection: Penpot

Penpot, an open-source design and prototyping tool, was used to create the final interactive prototype. Penpot was selected because it was assigned for this project and offers several advantages:
- Open-source and freely accessible
- Browser-based with no installation required
- Supports interactive prototyping with page linking
- Provides design token systems for consistent colors and spacing
- Exports high-quality images for documentation
- Generates shareable links for presentation

### 8.2 Interactive Prototype Features

The prototype includes functional navigation between pages:
- Homepage "Login" button links to Login page
- Homepage "Register" button links to Registration page
- Login page "Sign In" button links back to Homepage (simulating successful login)
- Login page "Register Now" link connects to Registration page
- Registration page "Select This Account" buttons link to Homepage (simulating successful registration)
- Registration page breadcrumb "Home" link returns to Homepage
- All pages maintain consistent header with working logo and navigation

These interactions allow the prototype to be tested as a working demonstration, enabling stakeholders to experience the improved user flow rather than just viewing static screens.

### 8.3 Development Process

The prototype was built iteratively:
1. **Design tokens created** for colors and spacing
2. **Homepage built first** as the foundation, establishing the header and footer patterns
3. **Header and footer copied** to Login and Registration pages for consistency
4. **Login page developed** with split layout and form elements
5. **Registration page completed** with account type cards
6. **Interactive links added** to connect all pages
7. **Testing conducted** in preview mode to verify all navigation worked correctly
8. **Screenshots exported** for documentation
9. **Shareable link generated** for stakeholder review

---

## 9. Comparison: Before and After

### 9.1 Quantitative Improvements

| Metric | Original Interface | Redesigned Interface | Improvement |
|--------|-------------------|---------------------|-------------|
| Primary actions visible on homepage | 0 (buried in text) | 3 (prominent cards) | Significant |
| Paragraphs of text on homepage | 3 large blocks | 0 (moved to footer) | 100% reduction |
| Account type options | 4 unclear | 2 clear | 50% reduction in complexity |
| Breadcrumb navigation | None | All pages | New feature |
| Helper text on forms | None visible | All inputs | New feature |
| Help accessibility | Hidden/unclear | Prominent on all pages | Significant improvement |
| Visual icons | None | Throughout interface | New feature |

### 9.2 Qualitative Improvements

**Homepage:**
- Before: Text-heavy, organization-focused, requires extensive reading
- After: Visual, task-focused, scannable within seconds

**Login:**
- Before: Intimidating legal warnings, unclear structure
- After: Welcoming message, clear form with guidance, reassuring tone

**Registration:**
- Before: Four confusing professional terms, minimal explanation
- After: Two plain-language categories, detailed feature lists, help section

**Overall Experience:**
- Before: Bureaucratic, formal, assumes user knowledge, creates barriers
- After: Conversational, supportive, guides users, reduces friction

---

## 10. Reflection and Lessons Learned

### 10.1 HCI Principles in Practice

This project demonstrated the practical application of Human-Computer Interaction principles in solving real-world usability problems. The systematic heuristic evaluation provided objective criteria for identifying issues rather than relying solely on subjective impressions. Understanding the theoretical foundation (Nielsen's heuristics, Schneiderman's rules) enabled informed design decisions rather than arbitrary aesthetic choices.

The process reinforced that good design is not about making interfaces "look pretty" but about making them work effectively for users. The most impactful changes—removing organizational text, simplifying account types, adding breadcrumbs—were structural and content decisions, not visual embellishments.

### 10.2 User-Centered Design Process

Approaching the redesign from the user's perspective rather than the organization's perspective was crucial. The original interface reflected the internal structure and concerns of the Ministry of Lands. The redesign focused on external user goals and mental models. This shift in perspective—from "What does the organization want to communicate?" to "What does the user want to accomplish?"—drove all major design decisions.

Wireframing before visual design proved valuable for exploring solutions without premature commitment to aesthetics. The ability to quickly sketch and iterate on paper enabled more experimentation than would have been practical in a digital tool.

### 10.3 Constraints and Trade-offs

Several limitations affected the project:

**Access Restrictions:** Inability to access authenticated areas meant problems in account dashboards, payment processes, and document submission flows could not be evaluated or redesigned. The prototype focuses on entry points (homepage, login, registration) which, while critical, represent only part of the complete user journey.

**Time Constraints:** A comprehensive redesign would address all ten heuristics across all pages, create responsive mobile versions, conduct user testing with actual Malawian citizens, and implement additional screens (password reset, registration form completion, confirmation messages, error states). The current prototype demonstrates core improvements but represents a starting point rather than a complete solution.

**Technical Limitations:** The prototype is static; actual implementation would require addressing technical challenges like form validation, data persistence, security measures, integration with backend systems, and performance optimization.

**Scope Decisions:** Some identified problems (inconsistent button styling, lack of loading indicators, absence of search functionality) were not addressed due to time constraints. Prioritization focused on the most severe issues affecting the largest number of users.

### 10.4 Future Improvements

Given additional time and resources, several enhancements would strengthen the solution:

**User Testing:** Conducting usability testing with actual target users (Malawian property owners, surveyors, lawyers) would validate design decisions and identify problems not apparent in heuristic evaluation. Observing real users attempting tasks would reveal cognitive friction points and inform further iteration.

**Mobile Optimization:** Creating responsive mobile versions is critical, as many Malawians access internet services primarily through smartphones. The current desktop design principles (card layouts, clear hierarchy) would translate well to mobile, but specific adaptations for touch interaction and smaller screens are needed.

**Accessibility Audit:** While basic accessibility considerations (color contrast, font size, clear labels) were incorporated, a comprehensive WCAG 2.1 evaluation and testing with assistive technologies would ensure inclusivity for users with disabilities.

**Content Strategy:** Collaborating with the Ministry of Lands to rewrite all interface content in plain Malawian English, possibly with Chichewa translations, would further improve accessibility for users with limited English proficiency.

**Additional Screens:** Completing the registration flow (form inputs, document upload, email verification), password reset process, account dashboard, payment interface, and application tracking would create a complete prototype covering all major user tasks.

**Animation and Microinteractions:** Subtle animations (button hovers, page transitions, loading indicators, success confirmations) would enhance feedback and delight without compromising usability.

### 10.5 Broader Implications

This project highlights broader issues with government digital services. Many government portals prioritize organizational structure and legal compliance over user experience, creating barriers that disproportionately affect citizens who most need public services. Applying user-centered design principles to government systems is not merely aesthetic improvement—it is a matter of equitable access to essential services.

The redesigned LIMS interface demonstrates that improved usability need not compromise professionalism or legal requirements. Legal disclaimers and organizational information remain accessible but do not block primary user tasks. Welcoming language does not reduce security. Clear guidance prevents errors without limiting functionality.

Governments worldwide could benefit from systematic usability evaluations and user-centered redesigns of digital services. The methodology employed in this project—heuristic evaluation, wireframing, prototyping, iterative refinement—is applicable to any digital system requiring usability improvement.

---

## 11. Conclusion

This project successfully identified and addressed major usability problems in the Malawi Land Information Management System through systematic application of Human-Computer Interaction principles. The heuristic evaluation revealed critical issues including text-heavy organization-focused content, poor visual hierarchy, unclear account type selection, absence of navigation aids, intimidating login experience, and hidden help resources.

The redesigned prototype demonstrates significant improvements through task-oriented layout, plain language communication, clear visual hierarchy, simplified account selection, welcoming messaging, and prominent help access. Three fully interactive prototype screens (Homepage, Login, and Registration Selection) were created in Penpot, incorporating a cohesive design system with consistent colors, typography, spacing, and interactive elements.

The final solution addresses six major heuristic violations and numerous minor issues, creating an interface that is more usable, accessible, and welcoming for Malawian citizens seeking land services. While the prototype represents a strong foundation, additional work including user testing, mobile optimization, accessibility auditing, and completion of additional screens would further enhance the solution.

This project reinforced the practical value of Human-Computer Interaction principles in solving real-world design problems and demonstrated that systematic, user-centered design processes yield measurably better outcomes than intuition-based approaches. The skills developed—heuristic evaluation, wireframing, prototyping, design system creation, and design justification—are applicable to any digital product design or redesign challenge.

The redesigned LIMS interface provides a model for how government digital services can balance organizational needs with user needs, proving that public sector systems need not sacrifice usability for formality. By prioritizing citizens' goals, using familiar language, providing clear guidance, and offering supportive assistance, digital government services can be both professional and genuinely helpful to the people they serve.

---

## 12. References and Resources

**Heuristic Evaluation Frameworks:**
- Nielsen, J. (1994). "10 Usability Heuristics for User Interface Design." Nielsen Norman Group.
- Schneiderman, B., Plaisant, C., Cohen, M., Jacobs, S., Elmqvist, N., & Diakopoulos, N. (2016). "Designing the User Interface: Strategies for Effective Human-Computer Interaction" (6th ed.). Pearson.

**Design Tools and Resources:**
- Penpot: https://penpot.app/ (Open-source design and prototyping platform)
- Web Content Accessibility Guidelines (WCAG) 2.1: https://www.w3.org/WAI/WCAG21/quickref/
- Nielsen Norman Group: https://www.nngroup.com/ (HCI research and usability resources)

**Original Interface:**
- Malawi Land Information Management System: http://lims.lands.gov.mw/

**Project Repository:**
- GitHub: https://github.com/DeadKhalee/HCI-LIMS-Redesign
- Contains: Wireframes, screenshots, heuristic evaluation documentation, prototype files, and weekly progress commits

---

## Appendices

**Appendix A: Complete Heuristic Evaluation**  
See `docs/heuristic-evaluation.md` in project repository

**Appendix B: Wireframe Documentation**  
See `wireframes/` folder in project repository

**Appendix C: Prototype Link**  
See `prototype/penpot-link.md` for live interactive prototype

**Appendix D: Screenshots**  
See `prototype/screenshots/` folder for high-resolution images of all three redesigned pages

---

**Word Count:** 5,847 words

**Total Project Hours:** ~20 hours (Evaluation: 4h, Wireframing: 3h, Prototyping: 8h, Documentation: 5h)

**Completion Date:** December 2, 2025