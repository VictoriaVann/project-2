<!DOCTYPE html>
<html lang="en" id="projects">
<head>
  <meta charset="utf-8">
  <title>ITMD 361: Fundamentals of Web Development</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
  <link rel="stylesheet" href="css/screen.css" media="screen">
  <link rel="icon" type="image/x-icon" href="images/favicon.ico">
  <!--<script async src="js/site.js"></script>-->
  <script src="https://code.jquery.com/jquery-3.6.0.js"></script>
  <script src="https://code.jquery.com/ui/1.13.2/jquery-ui.js"></script>
  <script>
    $( function() {
      $( "#accordion" ).accordion();
    } );
  </script>
</head>
<body>
  <div id="page">
    <header id="header">
      <h1><small>ITMD 361&#x3a; <!--UPDATE-->Spring 2024</small> Fundamentals&nbsp;of Web Development</h1>
      <p class="tagline">
        This class covers the foundational principles of web development. How to research client-server
        architecture according to current open standards. Taught by
        <a href="index.html#instructor">Professor Daniel Krieglstein</a>. Course developed by IIT 
        Professors <a href="https://appliedtech.iit.edu/people/brian-bailey">Brian Bailey</a>, 
        <a href="https://humansciences.iit.edu/faculty/karl-stolley">Dr. Karl Stolley</a>, &amp; Dr. Daniel Krieglstein.
      </p>
      <nav id="navigation">
        <ul class="nav">
          <li id="nav-cal"><a href="index.html">Calendar</a></li>
          <li id="nav-pro"><a href="#">Projects</a></li>
          <li id="nav-pol"><a href="syllabus.html">Syllabus</a></li>
          <li id="nav-lnk"><a href="links.html">Links</a></li>
        </ul>
      </nav>
    </header>

  <main id="content">
    <section class="primary">
      <h2 class="label">Major Projects</h2>
      <button class="accordion">
        <h3>Project One: Only Use HTML</h3>
      </button>
      <div class="panel">
        <section class="description">
          <h4>Project Description</h4>
          <p>
            Create three HTML pages, each with one desktop size page-scroll worth of content. One of the 
            pages must be your professional resume. The themes of the other two are your choice. 
          </p>
        </section>
        <section class="deliverables">
          <h4>Deliverables &amp; Milestones (see <a href="index.html">calender</a> for due dates)</h4>
          <ol>
            <li>
              <strong>First Deliverable:</strong> Create a Basecamp post. Title the post with your name 
              and project number (example Daniel Krieglstein: Project 1). Your post should include:
              <ul>
                <li>
                  The URL to your Project 1 GitHub repository, and the URL to your index.html Github Pages
                  live link
                </li>
                <li>
                  Three screen capture images of successful html validation. One for each website page.
                </li>
                <li>
                  Two questions eliciting feedback from fellow students
                </li>
              </ul>            
            </li>
            <li>
              <strong>Second Deliverable:</strong> Give constructive comments to help at least three other
              students. Post a picture of those three comments on your Basecamp folder. 
            </li>
            <li>
              <strong>Final Deliverable:</strong> You will receive a list on your Basecamp post of required 
              fixes from the professor or TA. Fix your code and edit your original Basecamp post with the 
              words "FINAL TURN IN"
            </li> 
          </ol>
        </section>
        <section class="requirements">
          <h4>Requirements</h4>
          <ul>
            <li>
              NO CSS IN YOUR HTML FILE!!! This means no style at all. No spacing, no centering, no color, 
              no italics. Just raw html. 
            </li>
            <li>
              <strong>Absolutely no</strong> br tags or use of tables for layout. This is also considered 
              style. 
            </li>
            <li>
              Two spaces indented cascade. Each child element should be indented 2 space right of its parent. 
            </li>
            <li>
              Three images of HTML validation, one for each page. <a href="https://validator.w3.org/">W3C 
              HTML validator</a> (<span class="redfont">-50% if it doesn't validate</span>)
            </li>
            <li>
              Create a bulleted list at the top of each page. The list items will be the file names of all 3 
              pages. This is your basic navigation. 
            </li>
            <li>
              Include at least three HTML images and one other form of media (audio or video)
            </li>
            <li>
              Do not use any pre-build code or frameworks. Write it all from scratch.
            </li>
            <li>
              Directory-based file structure for links and media. Do not use full URLs when linking to your 
              own content. Example: "css/screen.css" vs. 
              "https://dkriegls.github.io/itmd-361-spring2018/css/screen.css"
            </li>
            <li>
              At least 10 commits to your Github repository; with meaningful commit messages that accurately
              reflect your changes
            </li>
            <li>
              Git repository must contain <strong>only</strong> the files and commits from this project. Each 
              website you make for this class should have its own repository.
            </li>
          </ul>
        </section>
  </div>      
</body>
</html>
