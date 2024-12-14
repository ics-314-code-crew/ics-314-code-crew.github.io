<h1>Da Club</h1>
<img src="/doc/daClubLogo.png">
[![daclub](https://github.com/ics-314-code-crew/daclub/actions/workflows/ci.yml/badge.svg)](https://github.com/ics-314-code-crew/daclub/actions/workflows/ci.yml)
<h2>Overview</h2>
<b><i>The problem:</i></b> UH Manoa has over 200 <a href="https://manoa.hawaii.edu/studentlife/involvement/registered-independent-organizations/">Registered Independent Organizations</a>, plus many more that do not have this "official" status but are nonetheless active organizations. Unfortunately, there is no easy way for students to learn (a) what student clubs (both registered and unregistered) exist, what they do, and how to get further involved.
<b><i>The solution:</i></b> The Club Hub application will provide a centralized directory for UH Manoa student clubs. UH Manoa students can login to browse a well organized directory of all current student clubs, with brief descriptions, meeting times and locations, URLs to their websites (if any), contact information for officers, and a few select photos.
<h2>Approach</h2>
Club Hub will have the following roles, requiring a UH ID to register: 
<ul>
   <li>Regular users will be able to browse the directory or create clubs and become club owners.</li>
   <li>Super Admins will ensure site content is appropriate and have higher privileges than club owners.</li>
</ul>
In addition, users will not only be able to view the directory of clubs but also filter the directory to find clubs associated with different areas of interest. For example, "athletic" clubs, "art" clubs, "music" clubs, etc. A club can belong to multiple areas of interest.
Some possible mockup pages include:
<h2>Sign up Page</h2>
An Sign up form to create an account.
<img src="doc/sign-up-register-page.png">
<h2>Sign in Page</h2>
An sign page form to sign in.
<img src="doc/sign-in-page.png">
<h2>Landing Page</h2>
An Landing page after you have signed in.
<img src="doc/da-club-landing-2.png">
<h2>Add Club</h2>
<p>An add form to add a club as a club admin. Filling out the respective prompts.</p>
<img src="doc/add-club.png">
<h2>List Club</h2>
<p>A page that lists all of the clubs in a compact manner.</p>
<img src="doc/list-club.png">
<h2>Installation</h2>
<p>Here are the directions to accessing our app:</p>
<p>Go to our <a href="https://github.com/ics-314-code-crew/daclub">Project Repo</a>. Click on the Code button to and you can either open with github desktop or download a zip file.</p>
<p>Once you have it in you computer, go to your terminal and input the commands:</p>
<p>npm install</p>
<p>Then finally type this command into the terminal:</p>
<p>npm run dev</p>
<p>This should take you to a http://localhost:3000 which will openup the app in your brower.</p>

<h1>Milestone 1</h1>
<h2>
Landing Page
<h2>
<img src="doc/revisedLanding.png">
<h2>
Sign In Page
<h2>
<img src="doc/rSignInPage.png">
<h2>
Sign Out Page
<h2>
<img src="doc/signout-page.png">
<h2>
Change Password Page
<h2>
<img src="doc/change-password-page.png">
<h2>
Sign Up Page
<h2>
<img src="doc/rSignUpPage.png">

<h1>Milestone 2</h1>
<h2>Landing Page</h2>
<img src="doc/new-landing-page.png">
<h2>Adding a Club</h2>
<h3>Top of Add Club Form</h3>
<img src="doc/add-club-page1.png">
<h3>Bottom of Add Club Form</h3>
<img src="doc/add-club-page2.png">
<h2>Club List Page</h2>
<img src="doc/club-list-page.png">
<h2>Editing a Club</h2>
This page for club admins when they want to make changes to their club's information.
<h3>Managing Club Page</h3>
<img src="doc/edit-club-page1.png">
<h3>Top of the Edit Club Form</h3>
<img src="doc/edit-club-page2.png">
<h3>Bottom of the Edit Club Form</h3>
<img src="doc/edit-club-page3.png">
<h2>More details of the Club Page</h2>
<img src="doc/club-page-details.png">

<h1>Milestone 3</h1>
<h2>Landing Page</h2>
<h3>For Unauthenticated Users</h3>
<img src="doc/unauth-landing-m3.png">
<h3>For Authenticated Users</h3>
<img src="doc/auth-landing-m3.png">
<h2>Sign In Page</h2>
<img src="doc/sign-in-m3.png">
<h2>Sign Up Page</h2>
<img src="doc/sign-up.png">
<h2>User Profile</h2>
<img src="doc/profile-m3.png">
<img src="doc/edit-profile-m3.png">
<h2>Adding a Club</h2>  
<h3>Top of Add Club Form</h3>
<p>Site Admins or Club Owners can add clubs with a diverse set of parameters to allow for club expressiveness.</p>
<img src="doc/add-club-m3-1.png">
<h3>Bottom of Add Club Form</h3>
<img src="doc/add-club-m3-2.png">
<h2>Editing a Club</h2>
<p>Site Admins or Club Owners can Edit clubs.</p>
<img src="doc/editclubbutton.png">
<p>Then the user can modify pre-filled fields:</p>
<img src="doc/populated-edit.png">
<h2>Club List</h2>
<h3>Search</h3>
<p>All site users can utilize the semantic search functionality and search for clubs based on name or interest areas. For example:</p>
<img src="doc/search.png">
<h3>Copy to Clipboard!</h3>
<p>For streamlining access to information. Users can copy club admin emails with a button.</p>
<img src="doc/copytoclip.png">
<h3>View Club Information</h3>
<p>The club table was seeded with actual RIO data from the approved UH Manoa [RIO Excel sheet](https://docs.google.com/spreadsheets/d/1vK_ixq3a86uXjHXy9oNnyYHwAvyU9smNPKuJU6OYd-Q/edit?gid=828154192#gid=828154192). Note that some information was randomly generated, e.g., room number, since the source data did not provide such information.</p>
<img src="doc/clubpage.png">

<h2>Review Form</h2>
<p>Here is the <a href="https://docs.google.com/forms/d/e/1FAIpQLSfkbjbfGLN90bl0CNdPvrDSTuAIf0_C34MfQDvW4K79vFWJkA/viewform?usp=sf_link">form to review our app</a>.</p>
<h2>Community Feedback</h2>
<p>Of the feedback given, DaClub seems to accomplish its objective of being a central directory for UH Manoa's student clubs. The community feedback given points out the site's ease of use and smooth navigation across pages and features. Clubs were presented in a neat and aesthetic fashion. When it came to functionality, the users commented on the minimalistic and intuitive approach in the features, noting how easy it was to sign up, edit profiles, and even changing passwords. As for the design aspects, they were described as organized and simple yet well executed.</p>
<p>The community did highlight some of the site's shortcomings. The most prominent was the lack of a way to quickly sort through clubs via a lack of a bottom or top page button and a proper filter. A recommended improvement was to add a sort based on category like 'computer' for computer science related clubs. Another suggestion talked about chat rooms or bulletins where clubs can post events or news, helping people to get a gaige of what to expect for events rather than just looking at the descriptions.</p>

<h2>Team</h2>
Da Club is designed, implemented, and maintained by <a href="https://github.com/Dodie-Mad">Dodie Madriaga</a>, <a href="https://github.com/edenkp">Eden K. Parungao</a>, <a href="https://github.com/jaked332">Jake Dickinson</a>, <a href="https://github.com/JaySaga22">Jayden Sagayaga</a>, and <a href="https://github.com/Nate2389">Nathan Chee</a>.
<h2>Team Contract</h2>
Our team has developed a <a href="https://docs.google.com/document/d/1PiApV3qOrppXNGaRf1kudZ24YolmkLwuc0Uw49lqp0w/edit?usp=sharing">team contract</a> to establish clear expectations within the group. The contract outlines several criteria, such as each member’s contributions and behaviors, and includes solutions to conflicts that may arise during our time as a group. If a member fails to meet the agreed-upon terms, there will be a process to attempt to de-escalate the situation. If that does not work, it will be escalated to the instructor.

<h2>Milestones</h2>
<ul>
   <li><a href="https://github.com/orgs/ics-314-code-crew/projects/1">Milestone 1</a></li>
   <li><a href="https://github.com/orgs/ics-314-code-crew/projects/5">Milestone 2</a></li>
   <li><a href="https://github.com/orgs/ics-314-code-crew/projects/8">Milestone 3</a></li>
</ul>

<h2>Deployment</h2>
Link to running <a href="https://daclub-omega.vercel.app/">Vercel</a>.

<h2>GitHub Organization</h2>
<a href="https://github.com/ics-314-code-crew">View organization on GitHub</a>.