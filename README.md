//survey form
<html>
  <head>
    <h1 id="title">SURVEY FORM</h1>
  </head>
  <body>
    <div id="form-outer">
      <p id="description">How much you know about your college/university</p>
      <form id="Survey-form" method="get" action="https://www.freecodecamp.org">
        <div class="rowtab">
          <div class="labels">
            <label id="name-label" for="name">*NAME:</label>
          </div>
          <div class ="righttab">
            <input type="text" autofocus name="name" id="name" class="input-field" placeholder="enter your name here" required>
          </div>
        </div>
        
        <div class="rowtab">
          <div class="labels">
            <label id="email-label" for="email">*E-MAIL:</label>
          </div>
          <div class="rightTab">
            <input type="email" name="email" id="email" class="input-field" placeholder="enter your email-id" required>
          </div>
        </div>
        
        <div class="rowtab">
          <div class="labels">
            <label id="number-label" for="mobilenumber">*Mobile Number:</label>
          </div>
          <div class ="righttab">
            <input type="
                         number" name="mobilenumber" id="number" min="1" max="125" class="input-field" placeholder="mobile">
          </div>
        </div>
        
        <div class="rowtab">
          <div class="labels">
            <label for="role">Current role in the college:</label>
          </div>
          <div class="righttab">
            <select id="dropdown" name="role" class="dropdown">
              <option disabled value>select an option</option>
              <option value="student">Student</option>
              <option value="student">Faculty</option>
              <option value="trainee">Trainee</option>
            </select>
          </div>
        </div>
        
        <div class="rowtab">
          <div class="labels">
            <label for="experience">*Do you love this college?</label>
          </div>
          <div class="righttab">
            <ul style="list-style:none;">
              <li class="radio">
                <label>YES<input type="radio" name="radio-buttons" value="1"  class="experience">
                </label>
              </li>
          <li class="radio">
            <label>NO<input type="radio" name="radio-buttons" value="2" class="experience"></label></li>
          <li class="radio">
            <label>NOT SURE<input type="radio" name="radio-buttons"  value="3" class="experience"></label></li>
          </ul>
          </div>
        </div>
        
      <div class="rowtab">
        <div class="labels">
          <label for="improvement">what needs to be improved in this college?</label>
        </div>
        <div class="righttab">
          <ul id="preferences" style="list-style:none;">
            <li class="checkbox">
              <label><input type="checkbox" name="improvement" value="1" class="experience">Teaching</label></li>
            <li  class="checkbox"><label><input type="checkbox" name="improvement" value="2" class="experience">Faculties</label></li>
            <li class="checkbox"><label><input type="checkbox" name="improvement" value="3" class="experience">Environment</label></li>
            <li class="checkbox"><label>
              <input type="checkbox" name="improvement" value="4" class="experience">Everything</label></li>
          </ul>
        </div>
        </div>
        
        <div class="rowtab">
          <label for="suggestion">Would you like to give any suggestions?</label>
        </div>
        <div class="righttab">
          <textarea id="suggestions" class="input-field" name="suggestions" placeholder="Enter your suggestions here"></textarea>
        </div>
        </div>
      <button id="submit"  type="submit">SUBMIT</button>
      </form>
    </div>
  </>
</html>
            
            
          // CSS Code.
          
        
        
        
        
        
body{
  background-color: #a9d7d1;
  text-align:center;

}
h1{
  text-align:center;
  color:red;
  font-size:50px;
}
p{
  font-size:30px;
  font-family:sans-serif;
}
.labels{
  display:inline block;
  font-size:20px;
  font-style:oblique;
}
.input-field{
  width:300px;
}
#suggestions{
  width:400px;
  height:150px;
}
.checkbox{
  font-size:17.5px;
  font-family:lobster;
  font-style:oblique;
}
#submit{
  background-color: #59ace0;
}
@media screen and (max-width: 833px) {
  .input-field {
    width: 80%;
  }

          
          
     
          
          
