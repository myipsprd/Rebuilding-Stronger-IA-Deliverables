# Rebuilding Stronger Website Rebuild

The district is undertaking a website rebuild project to enhance communication and provide a better user experience for staff, parents, and students that aligns with Rebuilding Stronger's academic shifts. This document outlines the key technical & functional requirements and plugins necessary for the project.

# Timeline for Website Redesign Report

- <span style="color:red">&#10003;	
</span> **March 8, 2023:** Begin developing technical and functional requirements, identifying necessary plugins and initial implementation costs.
- <span style="color:red">&#10003;	
</span> **March 15, 2023:** Develop website buckets, their descriptions and timeline of redesign report creation.
- <span style="color:red">&#10003;	
</span> **March 22, 2023:** Information architecture for each website bucket. Information and media retention strategy for older content and media.
- <span style="color:red">&#10003;	
</span> **March 29, 2023:** Develop a training curriculum outline and identify necessary training requirements for staff members.
- <span style="color:red">&#10003;	
</span> **April 5, 2023:** Define overall aesthetics and user experience for the website redesign.
- <span style="color:red">&#10003;	
</span>**April 12, 2023:** Estimate a timeline for website implementation, aiming to initialize before the end of the school year and finalize by the first day of school.
- **April 26, 2023:** Gather feedback from stakeholders and amend the plan as needed. The goal is to rollup unforseen needs into the plan, not a complete rework.
- **May 3, 2023:** Finalize the report and begin executing the plan.

# Technical & Functional Requirements 

*   **Document Management System**: The system should be able to handle links, documents including images, videos, audio files, PDFs and post content. It should have robust version control features to ensure that previous versions of documents are archived and accessible. Additionally, it should have access control features to ensure that only authorized users can access, modify or delete documents. 
*   **Media Document Management**: The system will prevent non-admin users from deleting media documents. Instead, users who do not have permission to delete documents should be able to replace them with new versions to ensure that media documents are always up-to-date and accessible. 
*   **Blog Posting**: The website should allow users to create and publish blog stories on their individual websites, including text, images, videos, and other media. Users should have the ability to manage their own blog posts without requiring admin privileges.
*   **Virtual File Organization**: The system should allow for easy virtual file organization to help users easily navigate and find documents. It should support nested folders, tags, and search functionalities. These folders will be user specific to allow for custom preferences for everyone. 
*   **Complex Tables**: The website infrastructure should support complex tables with features such as sorting, filtering, and pagination. 
*   **Third-party Data Sources**: The system should be able to consume third-party data sources such as APIs to dynamically display data on the website. 
*   **Code Development**: The system should allow for one-off code development to support custom functionality and integrations. 
*   **Program-based Design Approach**: Websites should take a program-based approach instead of individual schools websites, modeling the upcoming Rebuilding Stronger initiative. This is to ensure information consistency across all of our models. Schools that do not have a program will maintain their own individual site. 
*   **Content Approval Mechanism**: There should be a content approval mechanism in place to ensure that all content is vetted and approved before it is published on the website by non-administrator users. 
*   **Language Translation**: The website should have a language translation feature to cater to non-English speaking users. The translation feature should support popular languages and should be easy to use. 
*   **Improved Calendar System**: The system should support an improved calendar system that can integrate with multiple vendors to allow for easy scheduling and event management. 
*   **Staff Custom Post Type**: The website should allow for the creation of custom post types for staff members to create and manage their own staff pages. 
*   **Block Management System**: The website infrastructure should have a heavily restricted block management system to ensure that users are not overwhelmed with the large number of block choices available in the block editor. 
*   **Page Builder System**: A robust page builder system is necessary to allow experienced users to create diverse content layouts without the need for custom code. The page builder system should also support templating to allow for the same content to be used in multiple locations. It also needs to integrate with the native block editor system to allow for long term support. 
*   **Integration with Let's Talk**: The website should heavily leverage the Let's Talk system whenever possible to streamline communication and feedback from users with district and school staff. 
*   **Removal of External Requests**: All external requests and services such as Google Drive, Word Fence, Facebook feeds, and contact forms should be removed to improve security and eliminate the need for external authentication requests. 
*   **Redirection Service**: The website infrastructure should have a redirection service in place to allow for the creation of short links and tracking of links for each website.
# Timeline Estimate for Website Redesign

To successfully implement the website redesign plan between May 1, 2023, and June 30, 2023, a well-structured timeline is crucial. The timeline should outline key milestones and allocate sufficient time for each phase of the project. Here is a suggested timeline for the website redesign:

## May 1-7, 2023: Project Kickoff

* Assemble the project team

* Conduct a project kickoff meeting to discuss objectives, roles, and responsibilities

* Review the existing website and gather initial feedback

## May 8-21, 2023: Planning and Content Development

* Develop a sitemap and wireframes for the new website

* Identify content to be updated, created, or removed

* Assign content creation and editing tasks to team members

## May 22-31, 2023: Design and Development

* Create design mockups based on the wireframes and the approved visual layout

* Obtain feedback and finalize the design

* Begin website development using the finalized design

## June 1-15, 2023: Content Integration and Testing

* Populate the new website with content (text, images, videos, etc.)

* Test the website on various devices and browsers for compatibility

* Address any technical or content-related issues

## June 16-23, 2023: User Acceptance Testing and Training

* Conduct user acceptance testing with a group of stakeholders

* Gather feedback and implement necessary changes

* Train designated school staff on website management and updating

## June 24-29, 2023: Final Review and Launch Preparation

* Conduct a final review of the website to ensure all requirements are met

* Prepare the website for launch (e.g., set up domain and hosting, create backups, etc.)

## June 30, 2023: Website Launch

* Make the new website live

* Monitor the website for any issues and address them promptly

* Announce the website launch through various communication channels

By adhering to this timeline, the website redesign project should be completed successfully within the designated timeframe, ensuring a smooth transition and a user-friendly experience for all stakeholders.
# Visual Layout
## School, Program and Model
The website's visual layout has been meticulously designed to reflect the school's identity and provide a consistent user experience across all devices. A collaboration between our team and VOX has led to the creation of a homepage that embodies the school's spirit and showcases vital information in an organized manner.

* Homepage:
  * The school colors are prominently featured throughout the website, creating a strong visual connection to the school's identity. For program websites with multiple buildings, a dedicated section below the news segment displays the logo, building information, and a link to a school-specific page on that program website.

* Header:
  * The header consists of the school logo on the left with the title adjacent to it. On the opposite end, a cyclic button opens the navigation menu, ensuring a clean and consistent interface across all devices.

* Hero Image:
  * The hero image incorporates a block on the left containing the page title and a brief description, accentuated by a color bar featuring the school colors.

* Welcome Section:
  * Following the hero image is a welcome heading, a brief introduction to the school, and a ribbon-like design showcasing three key facts about the school.

* Latest School News:
  * This section presents the six most recent news stories, complete with a title and featured image (if available). A button below the news stories directs users to a blog post page containing all news items.

* Special Highlight:
  * Another hero image highlights a unique aspect of the school, such as a special food pantry, academic option, or historical fact. This image links to a dedicated page with more information.
* Footer:
  * The footer displays the school's name, address, student hours, office hours, and social media links, all of which are editable by the school. Additionally, prominent text about website accessibility and Title IX reporting ensures compliance with federal law requirements.
## District Homepage

The district homepage shares a cohesive visual layout with the school websites, maintaining a consistent design language throughout the district's online presence. The district homepage boasts additional elements that cater to a broader audience, providing essential information and resources for the entire district.

* Video Elements:
  * Incorporating video content on the district homepage engages visitors and effectively communicates important messages. Videos can showcase district-wide initiatives, highlight success stories, and provide updates on current events.

* Icon Quicklinks:
  * A set of easily identifiable icon quicklinks offers users convenient access to essential resources and frequently visited pages. These may include online portals, school directories, district calendars, and contact information for key district personnel.

* Strategic Plan Focus:
  * The special highlight section on the district homepage emphasizes the district's strategic plan, showcasing its vision, mission, and core values. This section can feature a combination of text, images, and videos that convey the district's commitment to fostering academic excellence and supporting student growth.

By integrating these additional components into the district homepage, the website offers a comprehensive and engaging platform that caters to the diverse needs of the district's community members. The cohesive design language and consistent layout ensure a seamless user experience while effectively showcasing the district's initiatives and priorities.
# Planned Organizational Structure

## District
Serves as the central hub for information about the district, including news and events, academic programs, and administrative services. This site is an essential tool for students, parents, and educators to stay informed and engaged with the IPS community. Programs mentioned in the "Selective Recommendation Programs" section will be folded into the district site as well. 
### Selective Recommendation Programs
Programs are designed to meet the needs of specific groups of students, such as those with special needs or those seeking accelerated learning opportunities. Students are selected for these programs based on their academic abilities and interests, and are provided with tailored educational experiences to support their individual growth and development.
*   Graduation Academy
*   Newcomer Program @ Northwest Middle School
*   Positive Supports Academy
*   ROOTS Program
*   Sidener Academy for High Ability Students
*   Simon Youth Academy
*   Step Ahead Academy
## Standard Models
All participating schools will utilize one design model. Each learning model will share a standardized information architecture and website infrastructure.
### Arts
Focuses on the arts and provides students with specialized education in music, theater, dance, and visual arts.

*   Edison School of the Arts 47
*   James Whitcomb Riley School 43

### Dual Language
Provides specialized education for students who speak languages in addition to English. It aims to foster bilingualism and biliteracy, providing students with the opportunity to develop language skills in both their primary language and English.

*   Theodore Potter School 74

### Environmental

Showcases schools that focus on environmental education and sustainability. These schools provide specialized programs that teach students about environmental issues, conservation, and renewable energy sources.

*   Cold Spring School


### Inquiry Based 
Emphasize experiential learning and critical thinking. Students learn through asking questions, exploring, and investigating.
*   Broad Ripple Middle School
*   Carl Wilde School 79
*   Center for Inquiry School 2
*   Center for Inquiry School 27
*   Center for Inquiry School 70
*   Center for Inquiry School 84
*   George W. Julian School 57
*   Henry W. Longfellow Medical/STEM Middle School 28
*   Northwest Middle School

### Montessori
Follow the Montessori approach to education, emphasizing independence, self-directed learning, and hands-on exploration. Students are encouraged to learn at their own pace and in their own way, with teachers acting as facilitators and guides.
*   Eleanor Skillen School 34
*   George Washington Carver School 87
*   James Russell Lowell School 51
*   Rousseau McClellan School 91

### Paideai
Prioritize a holistic, student-centered approach to education. Emphasizing community involvement, experiential learning, and individual development, Paideai schools strive to create an environment that fosters lifelong learning and personal growth.
*   Ernie Pyle School 90

### Reggio
Follow a student-centered, project-based learning model that fosters creativity, critical thinking, and collaboration. Students learn through exploration and self-directed activities, and teachers act as guides, observing and facilitating their learning.
*   IPS | Butler University Laboratory School 55
*   IPS | Butler University Laboratory School 60

### STEM
Provide students with a strong foundation in science, technology, engineering, and mathematics, preparing them for college and careers in these fields. Students learn through hands-on, project-based activities and have opportunities to apply their learning through internships and other real-world experiences.
*   Anna Brochhausen School 88
*   Arlington Middle School
*   Harshman Middle School
*   James A. Garfield School 31
*   Robert Lee Frost School 106
*   William Penn School 49

## General Enrollment
Designed to provide a well-rounded education to students from various backgrounds and prepare them for success in higher education or their future careers. They offer a diverse range of programs and extracurricular activities that cater to the interests and talents of all students.

All participating schools will utilize one design model, sharing a standardized information architecture. Individual schools will not share website infrastructure. 

*   Brookside School 54
*   Charles Warren Fairbanks School 105
*   Christian Park School 82
*   Clarence Farrington School 61
*   Daniel Webster School 46
*   Emma Donnan Elementary & Middle School
*   Fredrick Douglas
*   Jonathan Jennings School 109
*   Lew Wallace School 107
*   Meredith Nicholson School 96
*   Ralph Waldo Emerson School 58
*   William McKinley School 39

## Career Themed Academies
Career-themed academies with specialized programs provide focused education and training to prepare students for their future careers. These academies offer opportunities for students to gain practical skills and experience in their fields of interest.

All participating schools will utilize one design model. Individual schools will not share information architecture or website infrastructure. 

*   Arsenal Technical High School
*   Crispus Attucks High School
*   George Washington High School
*   Shortridge High School
  
## Recommended for Removal
Schools that will no longer be serving the district due to changes around rebuilding stronger. These websites are recommended for complete removal from the websites. 

*   Floro Torrence School 83
*   Francis Bellamy School 102
*   Francis W. Parker School 56
*   George S. Buck School 94
*   Paul I. Miller School 114
*   Raymond F. Brandes School 65


## Non-participating Innovation Programs
Designed to provide students with unique educational experiences and specialized skill development opportunities. These programs offer a high degree of autonomy to teachers and staff, allowing them to create and implement innovative curricula and teaching methods. <ins>**These websites are not being considered in this plan.**</ins>
*   Avondale Meadows Middle School
*   Christel House Schools @ Manual High School
*   Enlace Academy
*   Global Preparatory Academy @ Riverside 44
*   Herron High School
*   Herron Preparatory Academy
*   Hope Academy High School
*   Kindezi Academy @ Joyce Kilmer 69
*   KIPP Indy College Prep Middle School
*   KIPP Indy Legacy High School
*   KIPP Indy Unite Elementary School
*   Liberty Grove Schools @ Elder Diggs 42
*   Matchbook Learning @ Wendell Phillips School 63
*   Phalen Leadership Academy @ Francis Scott Key 103
*   Phalen Leadership Academy @ George H. Fisher 93
*   Phalen Leadership Academy @ Louis B Russell 48
*   Purdue Polytechnic High School
*   Riverside High School
*   Sankofa School of Success @ Arlington Woods 99
*   The PATH School @ Stephen Foster 67
*   Thomas Gregg Neighborhood School
*   Thrival Indy Academy
*   URBAN ACT Academy @ Washington Irving 14


# Navigation Standards

## District – Full
<ul>
<li>About Us
<ul>
<li>District Overview</li>
<li>Our Superintendent</li>
<li>IPS Schools
<ul>
<li>School Profiles</li>
<li>School Boundaries</li>
<li>School Calendars</li>
<li>School Supply Lists</li>
<li>Student Handbooks</li>
<li>School Improvement Plans</li>
</ul>
</li>
<li>IPS Police Department</li>
<li>Strategic Plan 2025</li>
<li>COVID-19 Health &amp; Safety Protocols and Resources</li>
<li>Accountability Report Card</li>
<li>Website Accessibility</li>
</ul>
</li>
<li>Central Services
<ul>
<li>Athletics
<ul>
<li>Sports Schedules and Scores</li>
<li>Athletic Forms and Documents</li>
</ul>
</li>
<li>Communications and Engagement
<ul>
<li>News and Announcements</li>
<li>Social Media</li>
<li>IPS Newsletter</li>
</ul>
</li>
<li>Teaching and Learning
<ul>
<li>Curriculum and Instruction</li>
<li>Professional Development</li>
<li>Student Assessment</li>
</ul>
</li>
<li>Federal and Special Programs
<ul>
<li>Special Education Services</li>
<li>English Learner Services</li>
<li>Title I Program</li>
</ul>
</li>
<li>Finance &amp; Doing Business with IPS
<ul>
<li>Budget and Finance Reports</li>
<li>Purchasing and Procurement</li>
<li>Vendor Information</li>
</ul>
</li>
<li>Performance and Continuous Improvement
<ul>
<li>District and School Performance Data</li>
<li>Continuous Improvement Process</li>
</ul>
</li>
<li>Portfolio Management
<ul>
<li>Innovation Schools and Programs</li>
<li>Selective Recommendation Programs</li>
</ul>
</li>
<li>Postsecondary Readiness
<ul>
<li>College and Career Readiness</li>
<li>Scholarship Information</li>
<li>Financial Aid Information</li>
</ul>
</li>
<li>Title IX
<ul>
<li>Policy and Compliance</li>
<li>Reporting and Resources</li>
</ul>
</li>
<li>Unified Student Supports
<ul>
<li>Counseling and Social Emotional Learning</li>
<li>Health and Wellness</li>
<li>Homeless Education Services</li>
<li>Student Discipline</li>
</ul>
</li>
</ul>
</li>
<li>Enrollment &amp; Options
<ul>
<li>Enrolling In IPS</li>
<li>Choice Proximity and Zone Maps</li>
<li>Academic Options
<ul>
<li>Early Childhood Education</li>
<li>Elementary Schools</li>
<li>Middle Schools</li>
<li>High Schools</li>
<li>Alternative Education Programs</li>
</ul>
</li>
<li>Tour our High School Options</li>
<li>High Ability Program Eligibility</li>
<li>High School &amp; GED Transcripts</li>
</ul>
</li>
<li>Students &amp; Families
<ul>
<li>School Year Calendar</li>
<li>Enroll in Free IPS Tutoring</li>
<li>&iexcl;Inscr&iacute;base en tutor&iacute;a gratuita con IPS!</li>
<li>Transportation
<ul>
<li>Bus Routes and Schedules</li>
<li>Transportation Forms and Policies</li>
</ul>
</li>
<li>Inclement Weather Policy</li>
<li>Food Service
<ul>
<li>Menus and Meal Prices</li>
<li>Free and Reduced Meal Applications</li>
</ul>
</li>
<li>Uniforms
<ul>
<li>Dress Code and Guidelines</li>
<li>Where to Purchase Uniforms</li>
</ul>
</li>
<li>Health Services
<ul>
<li>Health Forms and Policies</li>
<li>Medication Administration</li>
<li>Health Resources</li>
</ul>
</li>
<li>Student Technology
<ul>
<li>Technology Policies and Procedures</li>
<li>Technology Support</li>
</ul>
</li>
<li>Homelessness Assistance
<ul>
<li>Resources and Support</li>
<li>Homeless Education Services</li>
</ul>
</li>
<li>Student Code of Conduct
<ul>
<li>Rights and Responsibilities</li>
<li>Discipline Policies and Procedures</li>
</ul>
</li>
<li>Textbook and Educational Benefits Assistance
<ul>
<li>Book Rental Fees and Assistance</li>
<li>Educational Benefits and Assistance Programs</li>
</ul>
</li>
<li>Title I Parent Involvement Policy</li>
<li>Pol&iacute;tica de Involucro de los Padres</li>
</ul>
</li>
<li>Employment &amp; Staff
<ul>
<li>Employment Opportunities
<ul>
<li>Job Openings and Application</li>
<li>Substitute Teaching</li>
</ul>
</li>
<li>Benefits and Retirement</li>
<li>Professional Development</li>
<li>Human Resources Forms and Documents</li>
<li>Staff Resources and Services</li>
</ul>
</li>
<li>School Board
<ul>
<li>Board Overview</li>
<li>March Board Meetings</li>
<li>Work Session</li>
</ul>
</li>
</ul>

## All Schools - Full
- About Us
  - School History and Mission
  - Staff List and Bios
  - School Accountability Report Card
- Student & Family Resources
  - Enrollment Information and Forms
  - School Supply List
  - Student and Family Handbook
  - Meal Menu and Nutrition Information
  - Daily Calendar and School Schedule
  - After-School Programs and Activities
  - Health and Wellness Resources
- Academic Programs
  - Curriculum and Instruction
  - Special Education Services and Resources
  - English Learner Services and Resources
  - Gifted and Talented Education Programs
  - Library and Media Services
  - Technology Resources and Support
- District Resources
  - Student Code of Conduct and Discipline Policies
  - Transportation Information and Policies
  - Uniforms and Dress Code
  - Textbook and Other Educational Benefits Assistance
  - School and District Policies and Procedures
- Get Involved
  - Volunteer With Us
  - Parent-Teacher Association (PTA)
  - School Site Council (SSC)
  - Booster Clubs and Parent Organizations
  - Community Partnerships and Outreach

## Arts
- Art Program
  - Overview of the Art Program
  - Course Offerings and Descriptions (Music, Theater, Dance, Visual Arts)
  - Arts Facilities and Resources (Music rooms, Dance studios, Theater stages, Art rooms)
  - Performance and Exhibition Opportunities (Concerts, Plays, Dance recitals, Art shows)
  - Arts Faculty and Instructors (List of arts teachers and their qualifications)
  - Arts Enrichment and Extension Programs (Summer camps, after-school programs)
  - Arts Awards and Recognitions (Student and program awards)

## Dual Language
- Dual Language Program
  - Overview of the Dual Language Program
  - Program Goals and Objectives (Developing bilingualism and biliteracy)
  - Dual Language Curriculum and Instruction
  - Dual Language Faculty and Instructors (List of dual language teachers and their qualifications)
  - Assessment and Evaluation of Dual Language Development
  - Parent and Community Involvement (Opportunities for families to support dual language learning)
  - Dual Language Enrichment and Extension Programs (Summer camps, after-school programs)
  - Dual Language Awards and Recognitions (Student and program awards)

## Environmental
- Environmental Education Program
  - Overview of the Environmental Education Program
  - Program Goals and Objectives (Conservation, environmental issues, renewable energy sources)
  - Environmental Curriculum and Instruction
  - Environmental Faculty and Instructors (List of environmental education teachers and their qualifications)
  - Assessment and Evaluation of Environmental Development
  - Parent and Community Involvement (Opportunities for families to support environmental education)
  - Environmental Enrichment and Extension Programs (Summer camps, after-school programs)
  - Environmental Awards and Recognitions (Student and program awards)


## Inquiry Based
- Inquiry-Based Education Program
  - Overview of the Inquiry-Based Education Program
  - Program Goals and Objectives (Experiential learning, critical thinking)
  - Inquiry-Based Curriculum and Instruction
  - Inquiry-Based Faculty and Instructors (List of inquiry-based teachers and their qualifications)
  - Assessment and Evaluation of Inquiry-Based Development
  - Parent and Community Involvement (Opportunities for families to support inquiry-based education)
  - Inquiry-Based Enrichment and Extension Programs (Summer camps, after-school programs)
  - Inquiry-Based Awards and Recognitions (Student and program awards)


## Montessori
- Montessori Education Program
  - Overview of the Montessori Education Program
  - Program Goals and Objectives (Independence, self-directed learning, hands-on exploration)
  - Montessori Curriculum and Instruction
  - Montessori Faculty and Instructors (List of Montessori teachers and their qualifications)
  - Assessment and Evaluation of Montessori Development
  - Parent and Community Involvement (Opportunities for families to support Montessori education)
  - Montessori Enrichment and Extension Programs (Summer camps, after-school programs)
  - Montessori Awards and Recognitions (Student and program awards)


## Paideai
- Paideai Education Program
  - Overview of the Paideai Education Program
  - Program Goals and Objectives (Holistic, student-center, community involvement, experiential learning, individual development)
  - Paideai Curriculum and Instruction
  - Paideai Faculty and Instructors (List of Paideai teachers and their qualifications)
  - Assessment and Evaluation of Paideai Development
  - Parent and Community Involvement (Opportunities for families to support Paideai education)
  - Paideai Enrichment and Extension Programs (Summer camps, after-school programs)
  - Paideai Awards and Recognitions (Student and program awards)

## Reggio
- Reggio Education Program
  - Overview of the Reggio Education Program
  - Program Goals and Objectives (Student-center, project-based learning, creativity, critical thinking, collaboration)
  - Reggio Curriculum and Instruction
  - Reggio Faculty and Instructors (List of Reggio teachers and their qualifications)
  - Assessment and Evaluation of Reggio Development
  - Parent and Community Involvement (Opportunities for families to support Reggio education)
  - Reggio Enrichment and Extension Programs (Summer camps, after-school programs)
  - Reggio Awards and Recognitions (Student and program awards)

## STEM
- STEM Education Program
  - Overview of the STEM Education Program
  - Program Goals and Objectives (Science, technology, engineering, mathematics, college and career preparation)
  - STEM Curriculum and Instruction
  - STEM Faculty and Instructors (List of STEM teachers and their qualifications)
  - Assessment and Evaluation of STEM Development
  - Parent and Community Involvement (Opportunities for families to support STEM education)
  - STEM Enrichment and Extension Programs (Summer camps, after-school programs, internships)
  - STEM Awards and Recognitions (Student and program awards)
# Necessary Technical Infrastructure
## Sending Messaging from Website
The website will be shifting away from SMTP authentication to send emails. As a result, it will be necessary to collaborate with the Information Technology department to whitelist emails originating from the website's IP address. This will enable the website to send crucial messages like reports, password resets, and other communications. Going forward, the website will be using WordPress's built-in email function to send emails.
## Content Managment System
WordPress is a versatile Content Management System (CMS) utilized by many due to its user-friendly interface and customization capabilities. Its popularity has led to the development of multisite features that allow users to manage multiple websites using a single installation of WordPress. IPS website employs WordPress as its CMS, providing users with an effortless way to create and publish content without needing extensive technical expertise.

## Required Plugins for CMS

<table>
<tbody>
<tr>
<td>Plugin</td>
<td>Description</td>
</tr>
<tr>
<td>Code Snippets&nbsp;</td>
<td>An easy, clean and simple way to run code snippets on your site. No need to edit your theme's functions.php file again!&nbsp;</td>
</tr>
<tr>
<td>Custom Post Types UI&nbsp;</td>
<td>Turn your Google Calendar, Microsoft Office 365 or Apple iCloud Calendar into a seamlessly integrated, auto-updating, zero-maintenance WordPress experience.&nbsp;</td>
</tr>
<tr>
<td>FileBird Lite&nbsp;</td>
<td>Organize thousands of WordPress media files into folders/ categories at ease.&nbsp;</td>
</tr>
<tr>
<td>GTranslate</td>
<td>Translate your website and make it multilingual. For support visit GTranslate Support Forum.&nbsp;</td>
</tr>
<tr>
<td>ICS Calendar&nbsp;</td>
<td>Turn your Google Calendar, Microsoft Office 365 or Apple iCloud Calendar into a seamlessly integrated, auto-updating, zero-maintenance WordPress experience.&nbsp;</td>
</tr>
<tr>
<td>Kadence Blocks &ndash; Gutenberg Blocks for Page Builder Features</td>
<td>Advanced Page Building Blocks for Gutenberg. Create custom column layouts, backgrounds, dual buttons, icons etc.&nbsp;</td>
</tr>
<tr>
<td>Knowledge Base for Documents and FAQs</td>
<td>Create Echo Knowledge Base articles, docs and FAQs.&nbsp;</td>
</tr>
<tr>
<td>Redirection&nbsp;</td>
<td>Manage all your 301 redirects and monitor 404 errors&nbsp;</td>
</tr>
<tr>
<td>SiteGround Optimizer&nbsp;</td>
<td>This plugin will link your WordPress application with all the performance optimizations provided by SiteGround&nbsp;</td>
</tr>
<tr>
<td>SiteGround Security</td>
<td>SiteGround Security is the all-in-one security solution for your WordPress website. Protect login &amp; limit login attempts. User activity log. Lock system folders &amp; more.&nbsp;</td>
</tr>
<tr>
<td>Smart Slider 3&nbsp;</td>
<td>The perfect all-in-one responsive slider solution for WordPress.</td>
</tr>
<tr>
<td>TablePress</td>
<td>Embed beautiful and feature-rich tables into your posts and pages, without having to write code.&nbsp;</td>
</tr>
</tbody>
</table>

## Initial Plugin Costs
*   FileBird
    *   $39; one-time
    *   https://codecanyon.net/item/media-folders-manager-for-wordpress/21715379
*   SmartSlider 3
    *   $49; one-time
    *   https://smartslider3.com/pricing/
*   Knowledge Base for Documents and FAQs
    *   $249; one-time
    *   https://www.echoknowledgebase.com/bundle-pricing/
## CMS Theme
* Astra
  * Free; paid available, but not necessary.
  * https://wordpress.org/themes/astra/
  * Allows for some customization, but not overwhelming.
  * Supports ease of reading and print friendly.
## Information & Media Retention Strategy
As part of our efforts to reduce technical debt and streamline our website infrastructure, we will be implementing an Information & Media Retention Strategy. The purpose of this strategy is to ensure that only current and relevant content is stored on the website, reducing the amount of backend space required and improving website performance.

The following guidelines will be implemented as part of the Information & Media Retention Strategy:

* All media and content on the website will be reviewed annually to determine its relevance and usefulness. Any media or content that is no longer relevant will be removed from the website.

* Only media and content from the current school year and the previous school year will be stored on the website. All media and content from previous years will be removed, reducing the amount of backend space required.

* Site Editors will have the option to group and download their media at any time, ensuring that they can access their content within the retention timeframe, and store it in accordance with their own information archival strategies.

* In the event that a school is consolidated, its information and media will be migrated over following the previous and current school year pattern. This will ensure that important information is not lost during the consolidation process.

By implementing these guidelines, we aim to reduce technical debt, improve website performance, and ensure that only current and relevant information is stored on the website.

# Training Requirements
## Training for Basic Site Editors

### File Management

1. Grouping and downloading files with FileBird
2. Using the Media Manager

### Site Navigation

1. Working with navigation menus
2. Using Redirection for redirects and short URLs

### Calendar and Event Management

1. Using ICS Calendar for calendar feeds

### Content Creation and Editing

1. Working with TablePress
2. Using the Block Editor
3. Utilizing Block Patterns
4. Creating and editing posts
5. Editing non-moderated content
6. Using the Knowledge Base for documents and FAQs
7. Utilizing the Documentation Service

### Advanced Blocks and Features

1. Kadence Blocks for advanced block support
2. Accessing and managing Let's Talk

## Training for Administrators

### Multisite Management

1. Overview of multisite environment
2. Administering users and roles
3. Network updates and upgrades

### Code Editing and Customization

1. Using Code Snippets for editing and adding custom code
2. Working with Smart Slider 3

### Site Configuration

1. Tools and settings overview
2. Embedding Let's Talk on the website

### Security and Maintenance

1. Common security concerns
2. SiteGround infrastructure, caching, and security
3. Managing the Knowledge Base for documents and FAQs
4. Importance of backups and updates
