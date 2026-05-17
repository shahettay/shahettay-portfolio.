# UCTTC Website Development Plan

## Unique Computer Technical Training Center (UCTTC) - Complete Website Specification

---

## 1. PROJECT OVERVIEW

**Institute Name:** Unique Computer Technical Training Center (UCTTC)  
**Location:** Netrakona, Bangladesh  
**Target Audience:** Students seeking IT/computer training in Bangladesh  
**Primary Goal:** Student admissions and course enrollment  
**Design Style:** Modern, professional, educational, trust-building  

---

## 2. DESIGN SPECIFICATIONS

### Color Palette
- **Primary:** #1e40af (Deep Blue)
- **Secondary:** #3b82f6 (Bright Blue)
- **Accent:** #0ea5e9 (Sky Blue)
- **Background Light:** #f8fafc
- **Background Dark:** #0f172a
- **Text Dark:** #1f2937
- **Text Light:** #ffffff
- **Success:** #10b981 (Green)
- **Warning:** #f59e0b (Orange)

### Typography
- **Primary Font:** Inter (English)
- **Bengali Font:** Noto Bengali
- **Font Weights:** 300, 400, 500, 600, 700, 800

### Design Principles
- Mobile-first responsive layout
- Clean, modern, premium education style
- Strong trust-building elements
- Simple navigation with clear CTAs
- Fast loading optimized
- SEO-friendly structure
- Smooth but not excessive animations
- Accessibility-friendly UI

---

## 3. SITE STRUCTURE & PAGES

### 3.1 Homepage (index.html)

#### Sections (In Order):

1. **Top Bar**
   - Phone number with icon
   - Email address
   - Social media links (Facebook, YouTube, LinkedIn)

2. **Header/Navigation**
   - Logo with institute name
   - Navigation menu: Home, About, Courses, Admission, Notice, Result, Gallery, Contact
   - "Apply Now" CTA button
   - Mobile hamburger menu

3. **Hero Section**
   - Headline: "Build Your Career with Professional IT Training"
   - Subheadline about UCTTC offerings
   - Primary CTAs: Apply Now, View Courses, Check Results
   - Trust badges: Govt. Certified, Expert Trainers, Job Placement, Flexible Schedule
   - Hero image with floating stats card

4. **Statistics Section**
   - 5000+ Students Trained
   - 50+ Professional Courses
   - 200+ Successful Batches
   - 95% Success Rate

5. **About Summary**
   - Brief introduction to UCTTC
   - Key features grid
   - "Learn More" link to About page

6. **Featured Courses**
   - 6 popular course cards with:
     - Course icon/image
     - Course name
     - Short description
     - Duration & certificate info
     - Fee in BDT (৳)
     - Apply Now button
   - "View All Courses" CTA

7. **Why Choose UCTTC**
   - 4 key benefits with icons:
     - Government Certified
     - Expert Trainers
     - Modern Labs
     - Job Placement

8. **Notice Board Preview**
   - 3 latest notices with categories (Admission, Exam, Result)
   - Date stamps
   - "View All Notices" CTA

9. **Photo Gallery Preview**
   - 4-image grid (Classroom, Lab, Students, Events)
   - Hover effects
   - "View Full Gallery" CTA

10. **Testimonials**
    - 3 student success stories
    - Student name, batch, photo initial
    - Star ratings
    - Quote text

11. **Contact & Map**
    - Location with icon
    - Phone numbers
    - Email addresses
    - Office hours
    - Social media links
    - Google Maps embed

12. **Footer**
    - Institute info with logo
    - Quick links
    - Popular courses list
    - Contact info
    - Copyright notice
    - Privacy Policy, Terms, Sitemap links

13. **Fixed Quick Contact Buttons**
    - WhatsApp button (bottom-right)
    - Phone call button (bottom-right)

---

### 3.2 About Us Page (about.html)

#### Sections:
1. **Page Header** - Title and breadcrumb
2. **Institute History** - Founding story and evolution
3. **Mission Statement** - Core purpose
4. **Vision Statement** - Future goals
5. **Why Choose UCTTC** - Detailed benefits
6. **Message from Director/Chairman** - Leadership message with photo
7. **Infrastructure** - Facilities overview
8. **Lab Environment** - Computer lab details with photos
9. **Trainer/Instructor Section** - Team highlights
10. **Achievements** - Awards and recognition
11. **Call-to-Action** - Apply now section

---

### 3.3 Courses Page (courses.html)

#### Structure:
1. **Page Header** - Title and intro
2. **Course Categories Filter**
   - All Courses
   - Government Courses
   - Non-Government Courses
   - By Skill Level (Beginner, Intermediate, Advanced)

3. **Course Listings** (Grid Layout)

#### Course Categories:

**Government Courses:**
- Computer Office Application (2 months, ৳5,000)
- Graphic Design (3 months, ৳8,500)
- Web Design & Development (6 months, ৳15,000)
- Hardware & Networking (4 months, ৳12,000)
- Freelancing (3 months, ৳10,000)

**Non-Government Courses:**
- Digital Marketing (4 months, ৳12,000)
- Video Editing (3 months, ৳9,000)
- Motion Graphics (3 months, ৳10,000)
- UI/UX Design (4 months, ৳14,000)
- Programming Basics (Python/Java) (5 months, ৳13,000)
- Database Management (3 months, ৳8,000)
- AI Tools for Productivity (2 months, ৳7,000)
- Spoken English for Freelancing (3 months, ৳6,000)
- e-Commerce Training (3 months, ৳9,000)

#### Each Course Card Includes:
- Course icon/thumbnail
- Course name
- Category badge
- Short description (2-3 lines)
- Duration
- Fee (BDT)
- Class schedule (Morning/Evening/Weekend)
- Skill level indicator
- Certification type
- Admission requirements
- "Apply Now" button
- "Download Syllabus" button (if available)

4. **Course Comparison Table** (Optional)
5. **FAQ Section** - Common course questions
6. **CTA Section** - Enrollment guidance

---

### 3.4 Online Admission Page (admission.html)

#### Admission Form Fields:

**Personal Information:**
- Full Name (Bangla & English)
- Father's Name
- Mother's Name
- Date of Birth
- Gender (Male/Female/Other)
- Nationality
- Religion (optional)

**Contact Information:**
- Mobile Number
- Alternative Phone
- Email Address
- Present Address
- Permanent Address

**Course Selection:**
- Select Course (dropdown)
- Select Batch (dropdown based on course)
- Class Timing Preference (Morning/Evening/Weekend)
- How did you hear about us? (dropdown)

**Educational Background:**
- Highest Education Level
- Institution Name
- Passing Year
- GPA/Marks

**Document Upload:**
- Passport Size Photo (JPG/PNG, max 500KB)
- Signature (JPG/PNG, max 200KB)
- Educational Certificate (PDF, max 2MB)
- National ID/Birth Certificate (PDF, max 2MB)

**Payment Information:**
- Payment Method (Cash/Bank Transfer/Mobile Banking)
- Transaction ID (if online payment)
- Payment Amount (auto-calculated)

**Terms & Conditions:**
- Checkbox for agreement
- Link to terms document

**Submit Button**
- Form validation
- Success confirmation message
- Application reference number generation

#### Post-Submission:
- Confirmation page with application ID
- Next steps instructions
- Payment instructions if pending
- Admin notification concept
- SMS/Email confirmation template

---

### 3.5 Notice Board Page (notice.html)

#### Features:
1. **Search Functionality** - Search by keyword
2. **Category Filter:**
   - All Notices
   - Admission Notices
   - Exam Notices
   - Holiday Notices
   - Class Schedule Updates
   - Result Publications
   - Event Announcements
   - General Notices

3. **Notice List:**
   - Notice title
   - Category badge
   - Publication date
   - Expiry date (if applicable)
   - PDF attachment icon
   - "Read More" or "Download" button

4. **Notice Detail Modal/Page:**
   - Full notice content
   - Attachments download
   - Related notices
   - Share buttons

5. **Pagination**
6. **Archive Section** - Past notices by year/month

---

### 3.6 Result Publication Page (result.html)

#### Features:
1. **Result Search:**
   - Search by Roll Number
   - Search by Registration Number
   - Search by Name
   - Select Batch/Course
   - Select Examination Year

2. **Result Display:**
   - Student information
   - Course/Batch details
   - Subject-wise marks
   - Total marks
   - Grade/CGPA
   - Pass/Fail status
   - Merit position (if applicable)

3. **Result Download:**
   - Download as PDF
   - Print option
   - Share option

4. **Batch-wise Result Lists:**
   - Filterable tables
   - Export options

5. **Merit List Section:**
   - Top performers
   - Scholarship recipients

6. **Result Archive:**
   - Year-wise results
   - Course-wise results

7. **Result Verification:**
   - Certificate verification form
   - Verification code check

---

### 3.7 Photo Gallery Page (gallery.html)

#### Categories:
1. **Classroom Photos**
2. **Computer Lab Photos**
3. **Seminar/Event Photos**
4. **Award/Certificate Distribution**
5. **Student Activities**
6. **Batch Celebrations**
7. **Field Trips**
8. **Guest Lectures**

#### Features:
- Grid layout with category filter
- Lightbox gallery view
- Image captions
- Date information
- Download option (if allowed)
- Share functionality
- Video section (embedded YouTube/Vimeo)
- Pagination or infinite scroll

---

### 3.8 Contact Page (contact.html)

#### Content:
1. **Contact Information:**
   - Full address with map pin
   - Multiple phone numbers
   - Email addresses
   - Office hours

2. **Google Maps Integration:**
   - Interactive map
   - Directions button
   - Nearby landmarks

3. **Contact Form:**
   - Name
   - Email
   - Phone
   - Subject (dropdown)
   - Message
   - Submit button

4. **Quick Contact Options:**
   - WhatsApp button
   - Messenger button
   - Phone call button
   - Email button

5. **Social Media Links:**
   - Facebook
   - YouTube
   - LinkedIn
   - Instagram (if applicable)
   - Twitter (if applicable)

6. **FAQ Preview** - Common questions
7. **Location Photos** - Building exterior/interior

---

### 3.9 Instructor/Trainer Page (trainers.html)

#### Trainer Profile Cards:
- Professional photo
- Full name
- Designation
- Qualification
- Experience (years)
- Specialization/Skill area
- Short bio
- Social media links (optional)
- Courses taught

#### Filter Options:
- By specialization
- By course category
- Full-time/Part-time

---

### 3.10 Testimonials Page (testimonials.html)

#### Content Types:
1. **Written Testimonials**
   - Student photo
   - Name and batch
   - Course completed
   - Current status (job/freelancer/student)
   - testimonial text
   - Star rating

2. **Video Testimonials**
   - Embedded videos
   - Student name and course
   - Duration

3. **Success Stories:**
   - Before/after learning
   - Job placement stories
   - Freelancing success stories
   - Higher education achievements
   - Featured story format with images

4. **Statistics:**
   - Total successful students
   - Job placement rate
   - Average salary after course
   - Top companies where students work

---

### 3.11 FAQ Page (faq.html)

#### Categories:

**Admission Related:**
- How to apply?
- Admission requirements?
- Required documents?
- Admission fee?
- Can I apply online?

**Course Related:**
- Course duration?
- Class schedules?
- Weekend classes available?
- Course materials provided?
- Practical vs theory ratio?

**Fees & Payment:**
- Course fees?
- Installment options?
- Refund policy?
- Payment methods?
- Scholarship opportunities?

**Certificate:**
- Certificate type?
- Government recognized?
- Certificate verification?
- Duplicate certificate?

**Class & Schedule:**
- Class timings?
- Make-up classes?
- Online class options?
- Recorded lectures?

**Results & Exams:**
- Exam process?
- Result publication time?
- Retake policy?
- Grade system?

**Career Support:**
- Job placement support?
- Internship opportunities?
- Freelancing guidance?
- Portfolio development?

Each question expandable with answer (accordion style).

---

### 3.12 Blog/News Page (blog.html)

#### Article Categories:
1. **Computer Tips**
2. **Training Tips**
3. **Career Guidance**
4. **Government Training Updates**
5. **Freelancing Advice**
6. **Institute News**
7. **Technology Trends**
8. **Student Spotlights**

#### Article Components:
- Featured image
- Title
- Author name
- Publication date
- Category tag
- Excerpt
- Read time
- "Read More" button
- Social share buttons
- Related articles

#### Sidebar:
- Search bar
- Recent posts
- Categories
- Tags cloud
- Newsletter subscription

---

### 3.13 Admin Panel (admin/)

#### Dashboard Modules:

**1. Dashboard Overview:**
- Total students
- Active courses
- Pending admissions
- Recent notices
- Quick stats

**2. Course Management:**
- Add/Edit/Delete courses
- Manage course categories
- Set fees and duration
- Upload syllabus
- Manage batches
- Schedule classes

**3. Admission Management:**
- View all applications
- Application status update
- Student database
- Export data (Excel/PDF)
- Generate admission cards
- Payment tracking

**4. Notice Management:**
- Create/Edit/Delete notices
- Categorize notices
- Set publish/expiry dates
- Upload attachments
- Schedule notices

**5. Result Management:**
- Enter student marks
- Generate result cards
- Publish results
- Merit list generation
- Result archive
- Bulk upload (Excel)

**6. Gallery Management:**
- Upload photos/videos
- Create albums
- Add captions
- Categorize images
- Set featured images

**7. Blog Management:**
- Create/Edit/Delete posts
- Manage categories
- Upload featured images
- Schedule posts
- Comments moderation

**8. Instructor Management:**
- Add/Edit trainer profiles
- Assign courses
- Manage availability
- Performance tracking

**9. User Management:**
- Admin accounts
- Staff accounts
- Role-based permissions
- Activity logs

**10. SEO Settings:**
- Meta tags management
- Sitemap generation
- Robots.txt editor
- Google Analytics integration
- Keyword tracking

**11. Homepage Content:**
- Edit hero section
- Manage statistics
- Update testimonials
- Feature courses selection
- Banner management

**12. Settings:**
- Institute information
- Contact details
- Social media links
- Email configuration
- SMS gateway setup
- Payment gateway setup

---

## 4. TECHNICAL REQUIREMENTS

### Frontend:
- HTML5, CSS3, JavaScript
- Tailwind CSS for styling
- Responsive design (mobile, tablet, desktop)
- Cross-browser compatibility
- Fast loading (<3 seconds)
- Lazy loading for images
- Optimized assets

### Backend (Conceptual):
- PHP/Node.js/Python
- MySQL/PostgreSQL database
- RESTful API architecture
- Secure authentication
- File upload handling
- Email/SMS integration

### Security:
- HTTPS/SSL ready
- Input validation
- SQL injection prevention
- XSS protection
- CSRF tokens
- Password hashing
- File upload restrictions

### SEO:
- Meta tags on all pages
- Open Graph tags
- Schema markup
- XML sitemap
- Robots.txt
- Canonical URLs
- Alt text for images
- Semantic HTML

### Performance:
- Image optimization
- Minified CSS/JS
- Browser caching
- CDN integration
- Gzip compression
- Database indexing

---

## 5. CONTENT GUIDELINES

### Tone:
- Professional yet approachable
- Student-friendly language
- Clear and informative
- Conversion-focused
- Trustworthy

### Language Support:
- Primary: English
- Secondary: Bengali (বাংলা)
- Option for bilingual toggle

### Call-to-Actions:
- "Apply Now" - Primary
- "View Courses" - Secondary
- "Contact Us" - Support
- "Download Syllabus" - Information
- "Check Results" - Utility

---

## 6. INTEGRATION REQUIREMENTS

### Third-Party Services:
1. **Google Maps** - Location embedding
2. **Google Analytics** - Traffic tracking
3. **WhatsApp Business API** - Quick contact
4. **Facebook Messenger** - Chat support
5. **Email Service** (SMTP/API) - Notifications
6. **SMS Gateway** - OTP and alerts
7. **Payment Gateway** (optional) - Online fees
8. **YouTube** - Video embedding
9. **Social Media** - Sharing and feeds

---

## 7. TIMELINE & DELIVERABLES

### Phase 1: Foundation (Week 1-2)
- Homepage
- About page
- Basic navigation
- Footer/Header

### Phase 2: Core Features (Week 3-4)
- Courses page
- Admission form
- Contact page
- Notice board

### Phase 3: Advanced Features (Week 5-6)
- Result publication
- Gallery
- Testimonials
- FAQ

### Phase 4: Content & Polish (Week 7-8)
- Blog section
- Admin panel
- SEO optimization
- Testing and launch

---

## 8. SUCCESS METRICS

- Page load time < 3 seconds
- Mobile responsiveness score > 95
- SEO score > 90
- Conversion rate tracking
- User engagement metrics
- Admission form completion rate
- Bounce rate reduction

---

## 9. MAINTENANCE PLAN

- Regular content updates
- Security patches
- Performance monitoring
- Backup schedule
- Bug fixes
- Feature enhancements
- User feedback incorporation

---

**Document Version:** 1.0  
**Last Updated:** January 2025  
**Prepared For:** UCTTC Website Development Project
