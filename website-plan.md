# Rebuilding Stronger Website Rebuild

The district is undertaking a website rebuild project to enhance communication and provide a better user experience for staff, parents, and students that aligns with Rebuilding Stronger's academic shifts. This document outlines the key technical & functional requirements and plugins necessary for the project.

# Timeline for Website Redesign Report

- <span style="color:red">&#10003;	
</span> **March 8, 2023:** Begin developing technical and functional requirements, identifying necessary plugins and initial implementation costs.
- <span style="color:red">&#10003;	
</span> **March 15, 2023:** Develop website buckets, their descriptions and timeline of redisgn report creation.
- **March 22, 2023:** Information architecture for each website bucket. Information and media retention strategy for older content and media.
- **March 29, 2023:** Develop a training curriculum outline and identify necessary training requirements for staff members.
- **April 5, 2023:** Begin considering design aspects for the website, including layout, color schemes, typography, and other visual elements.
- **April 12, 2023:** Define design requirements for the website, including user interface (UI) and user experience (UX) design considerations.
- **April 19, 2023:** Estimate a timeline for website implementation, aiming to initialize before the end of the school year and finalize by the first day of school.
- **May 3, 2023:** Gather feedback from stakeholders and amend the plan as needed. The goal is to rollup unforseen needs into the plan, not a a complete rework.
- **May 10, 2023:** Finalize the report and begin executing the plan.

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

# Planned Organizational Structure

## District
Serves as the central hub for information about the district, including news and events, academic programs, and administrative services. This site is an essential tool for students, parents, and educators to stay informed and engaged with the IPS community. Programs mentioned in the "Selective Recommendation Programs" section will be folded into the district site as well. 

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

### Selective Recommendation Programs
Programs are designed to meet the needs of specific groups of students, such as those with special needs or those seeking accelerated learning opportunities. Students are selected for these programs based on their academic abilities and interests, and are provided with tailored educational experiences to support their individual growth and development.
*   Graduation Academy
*   Newcomer Program @ Northwest Middle School
*   Positive Supports Academy
*   ROOTS Program
*   Sidener Academy for High Ability Students
*   Simon Youth Academy
*   Step Ahead Academy

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


## School Website Taxonomies
(Fill IN)

# Information & Media Retention Strategy
As part of our efforts to reduce technical debt and streamline our website infrastructure, we will be implementing an Information & Media Retention Strategy. The purpose of this strategy is to ensure that only current and relevant content is stored on the website, reducing the amount of backend space required and improving website performance.

The following guidelines will be implemented as part of the Information & Media Retention Strategy:

* All media and content on the website will be reviewed annually to determine its relevance and usefulness. Any media or content that is no longer relevant will be removed from the website.

* Only media and content from the current school year and the previous school year will be stored on the website. All media and content from previous years will be removed, reducing the amount of backend space required.

* Site Editors will have the option to group and download their media at any time, ensuring that they can access their content within the retention timeframe, and store it in accordance with their own information archival strategies.

* In the event that a school is consolidated, its information and media will be migrated over following the previous and current school year pattern. This will ensure that important information is not lost during the consolidation process.

By implementing these guidelines, we aim to reduce technical debt, improve website performance, and ensure that only current and relevant information is stored on the website.
# Required WordPress Plugins 

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

# Plugin Costs
*   FileBird
    *   $39; one-time
    *   https://codecanyon.net/item/media-folders-manager-for-wordpress/21715379
*   SmartSlider 3
    *   $49; one-time
    *   https://smartslider3.com/pricing/
*   Knowledge Base for Documents and FAQs
    *   $249; one-time
    *   https://www.echoknowledgebase.com/bundle-pricing/