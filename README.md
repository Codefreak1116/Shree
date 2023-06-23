# **build a survey form**
** start of undefined **


<DOCTYPE! html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>FreeCodeCamp Survey Form</title>
    <link rel="stylesheet" href="styles.css">

    </head>
 <body>
   <h1 id="title">FreeCodeCamp Survey Form</h1>
   <p id="description">Thank you for taking the time to help us improve the platform</p>
   
   <form id="survey-form">
    <fieldset>
    <label id="name-label">Name</label><input id="name" type="text" placeholder="enter your name" required>
    <label id="email-label">Email</label><input id="email" type="email" placeholder="enter your email" required>
    <label id="number-label">Age</label><input id="number" type="number" placeholder="enter your age" min="18" max="120"></label>
    <label>Which option best describes your current role?</label>
    <select id="dropdown">
      <option value="">select current role</option>
      <option>Student</option>
      <option>Full time job</option>
      <option>other</option>
     </select>
     <!-- <fieldset>
      
    <legend>Would you recommend freeCodeCamp to a friend?</legend>
    <div>
    <input type="radio" class="radio-group" name="definitely" value="definitely" checked><label>definitely</label></div>
    <div>
    <input type="radio" name="not sure" class="radio-group" value="not sure"><label>not sure</label></div>
    <div>
    <input type="radio" name="maybe" class="radio-group" value="maybe"><label>Maybe</label></div>
    
    </fieldset> -->
    
    <label>What is your favorite feature of freeCodeCamp?</label>
    <select id="dropdown">
      <option value="">Select an option</option>
      <option>Challenges</option>
      <option>Projects</option>
      <option>Community</option>
      <option>open source</option>
    </select>
      <label>What would you like to see improved? (Check all that apply)</label>
      <label><input type="checkbox" value="FD">Frontend projects</label>
      <label><input type="checkbox" value="BD">Backend projects</label>
      <label><input type="checkbox" value="DV">Data Visualization</label>
      <label><input type="checkbox" value="challenges">Challenges</label>
      <label>Any comments or suggestions?</label>
      <textarea id="text" name="comment" placeholder="Enter your comment here.."></textarea>
      
      <button type="submit" id="submit">Submit</button>
      </fielset>
      <div class="form-group">
          <p>Would you recommend freeCodeCamp to a friend?</p>
          <label>
            <input
              name="user-recommend"
              value="definitely"
              type="radio"
              class="input-radio"
              checked
            />Definitely</label
          >
          <label>
            <input
              name="user-recommend"
              value="maybe"
              type="radio"
              class="input-radio"
            />Maybe</label
          >

          <label
            ><input
              name="user-recommend"
              value="not-sure"
              type="radio"
              class="input-radio"
            />Not sure</label
          >
        </div>

  </body>
  </html>  
    


** end of undefined **

** start of undefined **

label{
  display:block;
  margin: 0.5rem auto;
}
fieldset{
  background-color: darkblue
  
}
body{
  background-image: url(https://tse1.mm.bing.net/th?id=OIP.7gxgdVLJWduzl-jt6yg0pQHaE7&pid=Api&P=0)
}
h1,p{
  text-align: center;
  
}

** end of undefined **

