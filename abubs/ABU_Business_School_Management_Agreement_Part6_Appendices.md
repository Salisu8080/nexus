# WEBSITE AND LEARNING MANAGEMENT SYSTEM
# MANAGEMENT SERVICE AGREEMENT
## APPENDICES

---

## APPENDIX A: TECHNICAL SPECIFICATIONS

### A.1 Website Technical Details

**A.1.1 Platform Information**

- **Framework:** Custom PHP-based CMS
- **Server Requirements:**
  - PHP 7.4 or higher
  - MySQL 5.7 or higher
  - Apache/Nginx web server
  - SSL/TLS support
- **Hosting Location:** [Hosting Provider Name]
- **Domain:** businessschool.abu.edu.ng
- **SSL Certificate:** Let's Encrypt or Commercial SSL

**A.1.2 Website Features**

**Public-Facing Pages (27+):**
1. Homepage with dynamic sliders
2. About Us / History
3. Mission, Vision, Values
4. Administrative Structure
5. Programs Overview
6. MBA Programs
7. Executive Programs
8. Short Courses
9. Professional Certifications
10. Faculty Directory
11. Faculty Profiles (individual pages)
12. Research Centers
13. Research Publications
14. News & Updates
15. Events Calendar
16. Blog/Insights
17. Admissions Information
18. Application Process
19. Student Services
20. Alumni Network
21. Contact Us
22. FAQs
23. Gallery
24. Partners & Collaborations
25. Careers
26. Downloads/Resources
27. Privacy Policy & Terms

**Administrative Dashboard Modules (30+):**
1. Dashboard Overview with Statistics
2. Page Management (CRUD operations)
3. Menu Management
4. News/Blog Management
5. Events Management
6. Faculty Profile Management
7. Program Management
8. Course Management
9. Research Publications Management
10. Media Library
11. Image Gallery Management
12. Slider/Banner Management
13. Student Application Management
14. Application Review System
15. Application Status Tracking
16. Partner Logo Management
17. Testimonials Management
18. Newsletter Subscriber Management
19. Contact Form Submissions
20. User Management (Admin Roles)
21. Statistics Display Management
22. SEO Settings (Meta tags, descriptions)
23. Site Settings (General configuration)
24. Email Configuration
25. Social Media Links Management
26. Downloads/Documents Management
27. FAQ Management
28. Career Postings Management
29. Announcement Management
30. Activity Logs
31. Backup Management Interface
32. Analytics Integration Dashboard

**A.1.3 Website Security Features**

- CSRF (Cross-Site Request Forgery) Protection
- SQL Injection Prevention (Prepared Statements)
- XSS (Cross-Site Scripting) Protection
- Input Validation and Sanitization
- Output Encoding
- Secure Session Management
- Password Hashing (bcrypt)
- Role-Based Access Control (RBAC)
- File Upload Restrictions
- HTTPS Encryption
- Security Headers (CSP, HSTS, X-Frame-Options)

**A.1.4 Website Performance Features**

- Browser Caching
- GZIP Compression
- Image Optimization
- CSS/JS Minification
- Lazy Loading for Images
- Database Query Optimization
- CDN Integration (optional)
- Page Caching

---

### A.2 Learning Management System (LMS) Technical Details

**A.2.1 Platform Information**

- **Framework:** Custom PHP-based LMS
- **Database:** MySQL
- **File Storage:** Server file system with secure access
- **Location:** businessschool.abu.edu.ng/lms
- **Responsive Design:** Mobile and tablet compatible

**A.2.2 LMS User Roles**

**Administrator:**
- Full system access
- User management (all roles)
- System settings and configuration
- Course approval and management
- Platform-wide analytics
- Instructor approval workflow
- Payment management
- System maintenance access

**Instructor:**
- Course creation and management
- Content upload (PDFs, videos, documents)
- Module and lesson organization
- Assessment creation:
  - Multiple Choice Questions (MCQs)
  - Essay/Assignment questions
- Grading interface
- Student enrollment management
- Course analytics
- Internal messaging
- Announcement posting
- Certificate generation

**Student:**
- Course browsing and enrollment
- Course material access
- Video playback
- Document downloads
- Assignment submission
- Exam taking
- Progress tracking
- Grade viewing
- Achievement/certification access
- Internal messaging
- Profile management
- Payment history

**A.2.3 LMS Core Features**

**Course Management:**
- Hierarchical structure (Course → Modules → Lessons)
- Rich text editor for content
- File attachments (unlimited types)
- Video embedding (YouTube, Vimeo, direct upload)
- Course prerequisites
- Course duration settings
- Enrollment limits
- Course pricing
- Course categories and tags

**Assessment System:**
- **Assignments:**
  - File submission
  - Text submission
  - Deadline management
  - Late submission handling
  - Manual grading by instructors
  - Feedback and comments
  - Grade tracking

- **Exams (MCQ):**
  - Question bank management
  - Random question selection
  - Question shuffling
  - Answer option shuffling
  - Time limits
  - Attempt limits
  - Automatic grading
  - Instant results
  - Score tracking
  - Pass/fail thresholds

**Progress Tracking:**
- Lesson completion tracking
- Course progress percentage
- Assessment scores
- Time spent on courses
- Completion certificates
- Achievement badges (if implemented)
- Learning path visualization

**Communication System:**
- Internal messaging between users
- Instructor-student communication
- Announcement system
- Email notifications for:
  - Enrollment confirmations
  - Assignment deadlines
  - Exam availability
  - Grade postings
  - System announcements

**Payment Tracking:**
- Payment record management
- Enrollment-payment linkage
- Payment history
- Receipt generation
- Payment status tracking

**Reporting and Analytics:**
- Student performance reports
- Course completion rates
- Assessment analytics
- Engagement metrics
- Instructor activity reports
- Revenue reports (payment-based courses)
- Export functionality (CSV, PDF)

**A.2.4 LMS Security Features**

- Secure authentication system
- Role-based access control
- Session management
- File access control (secure downloads)
- Exam security (anti-cheating measures)
- Data encryption for sensitive information
- Activity logging
- Secure payment data handling

**A.2.5 LMS Technical Requirements**

- **Server Requirements:**
  - PHP 7.4+
  - MySQL 5.7+
  - Minimum 50GB storage (scalable)
  - 2GB RAM minimum
  - Apache/Nginx with mod_rewrite

- **Browser Compatibility:**
  - Chrome (latest)
  - Firefox (latest)
  - Safari (latest)
  - Edge (latest)
  - Mobile browsers (iOS Safari, Chrome Mobile)

- **File Upload Limits:**
  - Configurable per installation
  - Typical: 50MB per file
  - Total storage: As per hosting package

---

### A.3 Integration and Third-Party Services

**A.3.1 Current Integrations**

- **Email Service:** PHPMailer for transactional emails
- **Analytics:** Google Analytics (website)
- **Fonts:** Google Fonts
- **Icons:** Font Awesome or similar
- **Video:** YouTube/Vimeo embedding support

**A.3.2 Potential Integrations (Additional Cost)**

- Payment Gateways: Paystack, Flutterwave, Interswitch
- SMS Notifications: Twilio, BulkSMS Nigeria
- Video Conferencing: Zoom, Google Meet, Microsoft Teams
- Cloud Storage: Google Drive, Dropbox
- Single Sign-On (SSO): SAML, OAuth
- Social Media: Facebook, Twitter, LinkedIn
- Email Marketing: Mailchimp, SendGrid
- CRM Systems: Custom integrations

---

### A.4 Infrastructure Specifications

**A.4.1 Hosting Environment**

- **Server Type:** Shared/VPS/Dedicated (as per selected package)
- **Operating System:** Linux (Ubuntu/CentOS)
- **Control Panel:** cPanel/Plesk or similar
- **Backup Location:** Offsite cloud storage + local

**A.4.2 Performance Specifications**

- **Target Page Load Time:** Under 3 seconds
- **Time to First Byte (TTFB):** Under 600ms
- **Concurrent Users:** Up to 500 (scalable)
- **Database Connections:** Optimized for load
- **CDN:** Optional (recommended for high traffic)

**A.4.3 Capacity Planning**

**Current Capacity:**
- Storage: [Specify current allocation]
- Bandwidth: [Specify current allocation]
- Database Size: [Current size]
- User Accounts: [Current count]

**Scaling Triggers:**
- Storage exceeds 80% capacity
- Bandwidth consistently exceeds monthly limit
- Page load times exceed 5 seconds
- Concurrent users approach server limit
- Database response time degrades

**Scaling Options:**
- Increase hosting resources (RAM, CPU)
- Upgrade to VPS/Dedicated server
- Implement CDN
- Database optimization
- Load balancing (for high-scale scenarios)

---

## APPENDIX B: SERVICE LEVEL AGREEMENT DETAILS

### B.1 Uptime Measurement

**B.1.1 Measurement Method**

- **Monitoring Tool:** Third-party uptime monitoring service (UptimeRobot, Pingdom, or similar)
- **Check Interval:** Every 5 minutes
- **Locations:** Multiple global checkpoints
- **Threshold:** 2 consecutive failed checks = downtime incident

**B.1.2 Uptime Calculation**

```
Monthly Uptime % = [(Total Minutes in Month - Downtime Minutes) / Total Minutes in Month] × 100

Where:
- Total Minutes in Month = Days in month × 24 hours × 60 minutes
- Downtime Minutes = Sum of all downtime incident durations
- Excludes: Scheduled maintenance windows
```

**Example Calculation:**
```
Month: October (31 days)
Total Minutes = 31 × 24 × 60 = 44,640 minutes
Downtime = 120 minutes (2 hours total downtime)
Scheduled Maintenance = 240 minutes (excluded)

Uptime % = [(44,640 - 120) / 44,640] × 100 = 99.73%
```

**B.1.3 Excluded Downtime**

Not counted against SLA:
- Scheduled maintenance (announced 7 days in advance)
- Client-requested downtime
- Force majeure events
- Issues caused by Client's actions
- Third-party service failures (DNS, ISP) beyond Saypeace's control
- DDoS attacks (reasonable protection in place)

### B.2 Response and Resolution Time Measurement

**B.2.1 Response Time Definition**

**Response Time = Time of First Acknowledgment - Time of Ticket Submission**

- **Starts:** When ticket submitted via any official channel
- **Ends:** When Saypeace acknowledges receipt and provides initial assessment
- **Business Hours:** Monday-Friday, 8:00 AM - 5:00 PM WAT
- **Excludes:** Weekends and Nigerian public holidays (for non-critical issues)

**B.2.2 Resolution Time Definition**

**Resolution Time = Time of Resolution Confirmation - Time of Ticket Submission**

- **Resolution:** When issue is fixed and normal functionality restored
- **Confirmation:** Client verifies resolution or 48 hours pass without objection
- **Clock Stops:** When awaiting Client input or third-party action

**B.2.3 Priority Level Definitions**

| Priority | Definition | Examples | Response Time | Resolution Target |
|----------|------------|----------|---------------|-------------------|
| **P1 - Critical** | Complete system outage; Security breach; Data loss; No workaround available | • Website/LMS completely down<br>• Database corruption<br>• Security breach<br>• Payment system failure | 4 hours | 24 hours |
| **P2 - High** | Major functionality broken; Affects multiple users; Workaround available but difficult | • LMS enrollment not working<br>• Admin panel inaccessible<br>• Email notifications failing<br>• Course content not displaying | 12 hours (business hours) | 48 hours |
| **P3 - Medium** | Minor functionality issue; Affects limited users; Easy workaround available | • Formatting issues<br>• Minor display bugs<br>• Single page error<br>• Non-critical feature broken | 24 hours (business hours) | 5 business days |
| **P4 - Low** | Cosmetic issues; Feature requests; Questions; Documentation | • UI tweaks<br>• Color adjustments<br>• Feature suggestions<br>• How-to questions | 72 hours (business hours) | 10 business days |

**B.2.4 Escalation Triggers**

**Automatic Escalation:**
- P1 not responded to within 2 hours → Escalate to Technical Lead
- P1 not resolved within 12 hours → Escalate to Project Manager
- P1 not resolved within 24 hours → Escalate to CEO
- P2 not responded to within 6 hours → Escalate to Technical Lead
- P2 not resolved within 36 hours → Escalate to Project Manager

### B.3 Content Management SLA Details

**B.3.1 Turnaround Time Measurement**

**Turnaround Time = Time of Publication - Time of Complete Submission**

- **Starts:** When Client submits complete, properly formatted content with all required materials
- **Ends:** When content is published live (or preview sent if approval required)
- **Business Days:** Monday-Friday (excluding Nigerian public holidays)
- **Clock Stops:** When awaiting Client approval or additional information

**B.3.2 Content Type SLAs**

| Content Type | Standard Turnaround | Rush (50% surcharge) | Emergency (100% surcharge) |
|--------------|---------------------|----------------------|----------------------------|
| News Article | 2-3 business days | 24 hours | Same business day |
| Event Listing | 1-2 business days | 12 hours | 4 hours |
| Faculty Profile | 3 business days | 24 hours | Same business day |
| Homepage Banner | 2 business days | 12 hours | 4 hours |
| Program Page Update | 3-4 business days | 36 hours | 24 hours |
| Course Material (up to 10GB) | 3-5 business days | 48 hours | 24 hours |
| Exam Questions (up to 100) | 3 business days | 24 hours | 12 hours |
| Student Bulk Upload (100) | 2-3 business days | 24 hours | 12 hours |

**B.3.3 Content Quality Standards**

All content will meet:
- Proper formatting and styling per site standards
- Mobile responsiveness verified
- All links tested and functional
- Images optimized (under 500KB typically)
- SEO elements added (for web content)
- Cross-browser compatibility verified
- No spelling/grammar errors introduced by formatting

**B.3.4 Rejection/Revision Handling**

- Client has 3 business days to review and approve content
- First revision: No additional time added
- Second revision: +1 business day
- Subsequent revisions: +1 business day each
- Major content changes = new request

### B.4 Backup and Recovery SLA

**B.4.1 Backup Success Rate**

- **Target:** 100% of scheduled backups complete successfully
- **Monitoring:** Automated backup verification
- **Notification:** Immediate alert if backup fails
- **Remediation:** Failed backup retried within 2 hours; issue resolved within 24 hours

**B.4.2 Recovery Time Objectives (RTO)**

| Data Type | Recovery Time Objective |
|-----------|-------------------------|
| Critical data (user accounts, enrollment) | 4 hours |
| Recent content (last 7 days) | 8 hours |
| Complete system restoration | 24 hours |
| Historical data (30+ days old) | 48 hours |

**B.4.3 Recovery Point Objectives (RPO)**

| Scenario | Maximum Data Loss |
|----------|-------------------|
| Normal operations | 24 hours (last daily backup) |
| With real-time replication | Near-zero |
| Catastrophic failure | 24 hours |

**B.4.4 Backup Verification**

- **Daily:** Automated integrity check (checksum)
- **Weekly:** Manual spot-check restoration test
- **Monthly:** Documented full restoration test
- **Quarterly:** Complete disaster recovery drill

### B.5 SLA Reporting

**B.5.1 Monthly SLA Report**

Included in monthly service report:
- Uptime percentage with incident breakdown
- Response time compliance by priority level
- Resolution time compliance by priority level
- Average response and resolution times
- Content turnaround time compliance
- Backup success rate
- SLA violations and service credits issued

**B.5.2 Service Credits**

**Uptime Service Credits:**
| Uptime Achieved | Service Credit |
|-----------------|----------------|
| 99.0% - 99.4% | 10% of monthly fee |
| 98.0% - 98.9% | 25% of monthly fee |
| Below 98.0% | 50% of monthly fee |

**Response Time Service Credits:**
- First SLA violation in a month: Warning, no credit
- Second violation: 5% of monthly fee
- Third+ violation: Additional 5% per violation (max 25%)

**Claiming Service Credits:**
- Client must claim within 30 days of monthly report
- Credit applied to following month's invoice
- Credits do not carry over beyond one billing cycle
- Service credits are exclusive remedy for SLA violations

---

## APPENDIX C: CONTENT MANAGEMENT REQUEST FORM TEMPLATE

### CONTENT SUBMISSION FORM

**Submission Date:** ___________________________

**Submitted By:** ___________________________

**Contact Email:** ___________________________

**Contact Phone:** ___________________________

**Priority Level:** ☐ Standard ☐ Rush (+50%) ☐ Emergency (+100%)

---

### CONTENT TYPE (Select One):

☐ News Article
☐ Event Listing
☐ Faculty Profile
☐ Homepage Banner/Slider
☐ Program Page Update
☐ Course Material (LMS)
☐ Exam Questions (LMS)
☐ Student Upload (LMS)
☐ Other: ___________________

---

### CONTENT DETAILS:

**Title/Headline:**
____________________________________________________________

**Publication/Upload Date:** ___________________________

**Target Page/Location:** ___________________________

**Category/Tags:** ___________________________

---

### CONTENT MATERIALS PROVIDED:

**Text Content:**
☐ Attached as Word document (.docx)
☐ Attached as plain text file (.txt)
☐ Provided in email body
☐ Google Docs link: _____________________

**Images:**
☐ Attached (specify count: _____)
☐ Stock images requested (describe: ___________________)
☐ No images required

**Videos:**
☐ YouTube link: _____________________
☐ Vimeo link: _____________________
☐ Uploaded to: _____________________
☐ No video

**Other Attachments:**
☐ PDF documents (specify: ___________________)
☐ Presentations (specify: ___________________)
☐ Excel files (specify: ___________________)
☐ Other: _____________________

---

### SPECIAL INSTRUCTIONS:

____________________________________________________________
____________________________________________________________
____________________________________________________________
____________________________________________________________

---

### FOR LMS CONTENT ONLY:

**Course Name:** ___________________________

**Module/Section:** ___________________________

**Target Audience:** ☐ All Students ☐ Specific Course Enrollees

**Assessment Type (if applicable):**
☐ Multiple Choice Exam
☐ Assignment (file submission)
☐ No assessment

**Number of Questions (if exam):** _____

**Time Limit (if exam):** _____ minutes

**Attempts Allowed:** _____

---

### APPROVAL:

**Approved By:** ___________________________

**Designation:** ___________________________

**Signature:** ___________________________

**Date:** ___________________________

---

### FOR OFFICE USE ONLY:

**Request ID:** ___________________________

**Assigned To:** ___________________________

**Date Received:** ___________________________

**Estimated Completion:** ___________________________

**Status:** ☐ Received ☐ In Progress ☐ Pending Approval ☐ Completed

**Notes:**
____________________________________________________________

---

**SUBMISSION METHODS:**

1. **Email:** content@saypeace.ng
   - Send completed form with all attachments

2. **Support Portal:** portal.saypeace.ng/content
   - Upload form and materials

3. **Shared Drive:** (If configured)
   - Place in designated folder with completed form

**CONTENT FORMAT REQUIREMENTS:**

- **Text:** Microsoft Word (.docx) or plain text
- **Images:** JPEG, PNG (minimum 1200px width for banners; under 5MB)
- **Videos:** MP4 format or YouTube/Vimeo links
- **Documents:** PDF format preferred
- **All files:** Clearly named and organized

**RESPONSE TIME:**

- Acknowledgment within 24 hours (business days)
- Estimated completion date provided upon receipt
- Updates provided if delays occur

---

## APPENDIX D: ESCALATION MATRIX

### SUPPORT ESCALATION PATH

```
┌─────────────────────────────────────────────────────────────┐
│                     LEVEL 1: SUPPORT TEAM                    │
│                                                              │
│  Contact: support@saypeace.ng                                │
│  Response: As per SLA (Priority-dependent)                   │
│  Handles: All initial requests, standard issues              │
│                                                              │
│  Escalate to Level 2 if:                                     │
│  • P1 not responded within 2 hours                          │
│  • P2 not responded within 6 hours                          │
│  • Issue requires senior technical expertise                 │
│  • Customer specifically requests escalation                 │
└─────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────┐
│                   LEVEL 2: TECHNICAL LEAD                    │
│                                                              │
│  Contact: technical-lead@saypeace.ng                         │
│  Response: Within 2 hours of escalation                      │
│  Handles: Complex technical issues, P1/P2 escalations       │
│                                                              │
│  Escalate to Level 3 if:                                     │
│  • P1 not resolved within 12 hours                          │
│  • P2 not resolved within 36 hours                          │
│  • Issue requires management decision                        │
│  • Resource allocation needed                                │
│  • SLA violation imminent                                    │
└─────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────┐
│                   LEVEL 3: PROJECT MANAGER                   │
│                                                              │
│  Contact: manager@saypeace.ng                                │
│  Response: Within 4 hours of escalation                      │
│  Handles: Service quality issues, SLA violations,            │
│           resource allocation, process issues                │
│                                                              │
│  Escalate to Level 4 if:                                     │
│  • P1 not resolved within 24 hours                          │
│  • Repeated SLA violations                                   │
│  • Contract interpretation disputes                          │
│  • Major service failures                                    │
│  • Client relationship issues                                │
└─────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────┐
│                 LEVEL 4: SENIOR MANAGEMENT                   │
│                                                              │
│  Contact: ceo@saypeace.ng                                    │
│  Name: Engr. Salisu Zubairu Gaya (CEO)                      │
│  Response: Within 4 hours of escalation                      │
│  Handles: Critical failures, contract disputes, strategic   │
│           decisions, executive relationship management        │
│                                                              │
│  Final escalation for:                                       │
│  • Unresolved critical issues                                │
│  • Contract termination considerations                       │
│  • Legal or compliance matters                               │
│  • Major financial disputes                                  │
└─────────────────────────────────────────────────────────────┘
```

### CLIENT-INITIATED ESCALATION

**When to Escalate:**
- Issue not resolved within SLA timeframes
- Unsatisfactory response from current level
- Service quality concerns
- Urgent business-critical matters
- Pattern of recurring issues

**How to Escalate:**
1. Reference original ticket number
2. Clearly state reason for escalation
3. Provide timeline of issue
4. Specify desired outcome
5. Contact appropriate escalation level directly

**Escalation Response Commitments:**
- Level 2: Response within 2 hours (business hours)
- Level 3: Response within 4 hours (business hours)
- Level 4: Response within 4 hours (including after-hours for P1)

### ESCALATION FOR SPECIFIC ISSUE TYPES

**Security Incidents:**
- Immediately escalate to Level 3 (Project Manager)
- Level 4 (CEO) notified within 1 hour
- Security specialist engaged immediately

**Data Loss/Corruption:**
- Immediately escalate to Level 2 (Technical Lead)
- Level 3 notified within 2 hours
- Recovery procedures initiated immediately

**Payment/Billing Disputes:**
- Start at Level 3 (Project Manager)
- Financial documentation required
- Resolution within 5 business days

**Contract Interpretation:**
- Direct to Level 4 (CEO)
- Legal review if necessary
- Formal response within 3 business days

---

## APPENDIX E: PAYMENT SCHEDULE TABLE

### OPTION 1: COMPREHENSIVE MONTHLY PACKAGE

**Package:** Full-Service Management Package
**Monthly Fee:** ₦200,000
**Annual Fee (Prepaid):** ₦2,200,000 (1 month free)

#### Monthly Payment Schedule

| Month | Due Date | Amount Due | Payment Status |
|-------|----------|------------|----------------|
| Month 1 | 1st day of Month 1 | ₦200,000 | |
| Month 2 | 1st day of Month 2 | ₦200,000 | |
| Month 3 | 1st day of Month 3 | ₦200,000 | |
| Month 4 | 1st day of Month 4 | ₦200,000 | |
| Month 5 | 1st day of Month 5 | ₦200,000 | |
| Month 6 | 1st day of Month 6 | ₦200,000 | |
| Month 7 | 1st day of Month 7 | ₦200,000 | |
| Month 8 | 1st day of Month 8 | ₦200,000 | |
| Month 9 | 1st day of Month 9 | ₦200,000 | |
| Month 10 | 1st day of Month 10 | ₦200,000 | |
| Month 11 | 1st day of Month 11 | ₦200,000 | |
| Month 12 | 1st day of Month 12 | ₦200,000 | |
| **Annual Total** | | **₦2,400,000** | |

**OR**

#### Annual Prepayment (Recommended)

| Payment | Due Date | Amount Due | Savings | Payment Status |
|---------|----------|------------|---------|----------------|
| Year 1 | January 1, 2025 | ₦2,200,000 | ₦200,000 | |
| Year 2 | January 1, 2026 | ₦2,200,000* | ₦200,000 | |
| Year 3 | January 1, 2027 | ₦2,200,000* | ₦200,000 | |
| Year 4 | January 1, 2028 | ₦2,200,000* | ₦200,000 | |
| Year 5 | January 1, 2029 | ₦2,200,000* | ₦200,000 | |

*Subject to annual price review (maximum 10% increase)

---

### OPTION 2: TIERED SERVICE PACKAGES

#### A. Basic Package

**Monthly Fee:** ₦80,000

| Month | Due Date | Amount Due | Payment Status |
|-------|----------|------------|----------------|
| Month 1 | 1st day of Month 1 | ₦80,000 | |
| Month 2 | 1st day of Month 2 | ₦80,000 | |
| ... | ... | ... | |
| **Annual Total** | | **₦960,000** | |

#### B. Standard Package (Recommended)

**Monthly Fee:** ₦150,000

| Month | Due Date | Amount Due | Payment Status |
|-------|----------|------------|----------------|
| Month 1 | 1st day of Month 1 | ₦150,000 | |
| Month 2 | 1st day of Month 2 | ₦150,000 | |
| ... | ... | ... | |
| **Annual Total** | | **₦1,800,000** | |

#### C. Premium Package

**Monthly Fee:** ₦250,000

| Month | Due Date | Amount Due | Payment Status |
|-------|----------|------------|----------------|
| Month 1 | 1st day of Month 1 | ₦250,000 | |
| Month 2 | 1st day of Month 2 | ₦250,000 | |
| ... | ... | ... | |
| **Annual Total** | | **₦3,000,000** | |

---

### OPTION 3: COMPONENT-BASED PRICING

**Build Your Own Package**

| Service Component | Billing Cycle | Cost | Selected? | Annual Cost |
|-------------------|---------------|------|-----------|-------------|
| Hosting & Infrastructure | Annual | ₦80,000 | ☐ | ₦80,000 |
| Website Management | Monthly | ₦100,000 | ☐ | ₦1,200,000 |
| LMS Management | Monthly | ₦120,000 | ☐ | ₦1,440,000 |
| Monthly Reporting | Monthly | ₦20,000 | ☐ | ₦240,000 |
| Additional Support Hours | Per Hour | ₦8,000 | ☐ | As needed |

**Sample Combination:**
```
Hosting & Infrastructure:        ₦80,000/year
Website Management:        ₦1,200,000/year
LMS Management:           ₦1,440,000/year
Monthly Reporting:          ₦240,000/year
─────────────────────────────────────────
Total Annual Cost:        ₦2,960,000/year
```

---

### ONE-TIME FEES

| Item | Amount | When Due | Status |
|------|--------|----------|--------|
| Initial Setup Fee | ₦100,000 | Upon signing agreement | ☐ Paid ☐ Waived |
| Training Session (additional) | ₦30,000 per session | Upon completion | As needed |
| Custom Development | Per quotation | 50% upfront, 50% on completion | As needed |
| Emergency After-Hours Support | ₦15,000 per incident | Within 7 days of service | As needed |

---

### PAYMENT INSTRUCTIONS

**Bank Details:**

**Account Name:** Saypeace AI Technologies
**Bank:** [Bank Name]
**Account Number:** [Account Number]
**Account Type:** Current Account
**SWIFT Code:** [If applicable]

**Payment Procedure:**

1. Transfer payment to account above
2. Email payment confirmation to: payments@saypeace.ng
3. Include in email:
   - Organization name (ABU Business School)
   - Invoice number (if applicable)
   - Payment date
   - Amount paid
   - Copy of bank transfer receipt/teller

**Invoice Schedule:**

- Invoices sent 5 days before due date
- Email sent to designated financial contact
- PDF invoice attached
- Payment instructions included

**Late Payment:**

- Grace Period: 5 calendar days
- Late Fee: 5% of outstanding amount
- Service Suspension: After 15 days overdue
- Termination: After 30 days overdue

---

### PROJECTED 5-YEAR COST (Option 1 - Comprehensive Package)

Assuming maximum 10% annual increase:

| Year | Base Fee | Increase | Annual Cost | Cumulative Cost |
|------|----------|----------|-------------|-----------------|
| Year 1 | ₦2,200,000 | - | ₦2,200,000 | ₦2,200,000 |
| Year 2 | ₦2,200,000 | 10% | ₦2,420,000 | ₦4,620,000 |
| Year 3 | ₦2,420,000 | 10% | ₦2,662,000 | ₦7,282,000 |
| Year 4 | ₦2,662,000 | 10% | ₦2,928,200 | ₦10,210,200 |
| Year 5 | ₦2,928,200 | 10% | ₦3,221,020 | ₦13,431,220 |

**5-Year Total (Maximum):** ₦13,431,220

**Note:** Actual increases may be less than 10% and will be negotiated annually based on market conditions.

---

**END OF APPENDICES**

---
