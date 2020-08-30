# Sprint-0-Assignment
It's a survey form for clarusway.com


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clarusway Survey Form</title>
    <style>
      #title {
        font-size: 75px;
        font-weight: 400;
      }
      
      p {
        font-size: 1.5rem;
      }

      #radio {
        margin-bottom: 15px;
      }

      #check {
        margin-bottom: 15px;
      }

    </style>
</head>

<body>

    <h1 id="title">Clarusway Survey Form</h1>
    
    <p>
      Thank you for taking the time to help us improve the platform
    </p>
    
    <form id="survey-form" action="result.html" method="GET" target="_blank">
      
      <div class="box1">
        <label for="name" id="name-label">Name</label><br>
        <input type="text" name='name' placeholder="Enter your name" id="name" required>
      </div>
      <br>

      <div class="box2">
        <label for="surname" id="surname-label">Surname</label><br>
        <input type="text" name='surname' placeholder="Enter your Surname" id="surname" required>
      </div>
      <br>

      <div class="box3">
        <label for="email" id="email-label">Email</label><br>
        <input type="email" name="email" placeholder="user@clarusway.com" id="email" required>
      </div>

      <div class="box4">
        <label for='currentrole' id="currentrole-label"><p>Which option best describes your current role?</p></label>
        <select name='roles' id="currentrole" required>
          <option disabled selected value>Select current role</option>
          <option value="Student">Student</option>
          <option value="Teacher">Teacher</option>
          <option value="Fulltimejob">Full Time Job</option>
          <option value="Parttimejob">Part Time Job</option>
          <option value="Learner">Full Time Learner</option>
          <option value="Notsay">Prefer not to say</option>
        </select>
      </div>

      <div class="box5">
        <label for="radios" id="radios-label"><p>Would you recommend Clarusway to a friend?</p></label>
        <label><input type="radio" id="radio" name="recomming" value="Yes"> Definitely, Yes</label><br>
        <label><input type="radio" id="radio" name="recomming" value="Maybe"> Maybe</label><br>
        <label><input type="radio" id="radio" name="recomming" value="Not-sure"> Not sure</label><br>
        <label><input type="radio" id="radio" name="recomming" value="No"> Definitely, No</label>
      </div>
      
      <div class="box6">
        <label for='favfeature' id="favfeature-label"><p>What is your favorite feature of Clarusway?</p></label>
        <select name='favorite' id="favfeature" required>
          <option disabled selected value>Select an option</option>
          <option value="Courses">Courses</option>
          <option value="Projects">Projects</option>
          <option value="Community">Community</option>
          <option value="Mentors">Mentors</option>
        </select>
      </div>

      <div class="box7">
        <label id="checkbox"><p>What would you like to see improved? (Check all that apply)</p></label>
        <label><input type="checkbox" id="check" name="choose1" value="Front-end-Projects">Front-end Projects</label><br>
        <label><input type="checkbox" id="check" name="choose2" value="Back-end-Projects">Back-end Projects</label><br>
        <label><input type="checkbox" id="check" name="choose3" value="Data-Science">Data Science</label><br>
        <label><input type="checkbox" id="check" name="choose4" value="Additional-Courses">Additional Courses</label><br>
      </div>

      <div class="box-textarea">
        <label id="comments"><p>Any comments or suggestions?</p></label>
        <textarea class="text-area" name="comments" rows="5" cols="50" placeholder="Enter your comment here...Thanxs for your comments...."></textarea>
        
        <input type="submit" value="Submit">
      </div>
      
    </form>

</body>

</html>
