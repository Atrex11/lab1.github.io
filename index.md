</html>
<!DOCTYPE html>
<html lang="en">
<head>
<title>Survey</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="styles/index.css">
<script src="js/index.js"></script>

</head>
<body>

<h1>Survey</h1>
<h4>What do you think of the UI in the <a href="https://www.youtube.com/"> Youtube</a> website?</h4>
<p></p>

<div class="BGI">
  <a href="https://www.youtube.com/"></a>
</div>

<div class="row" style="background-color:rgb(252, 171, 110);">
  <div class="column side" >
    <h2> Personal Information: </h2>
    <div class="question">
        <form>
            <label for="fname">First name:</label><br>
            <input type="text" id="fname" name="fname"><br>
            <label for="lname">Last name:</label><br>
            <input type="text" id="lname" name="lname">
        </form>
    </div>

</div>
  <div class="column middle">
      <h2>Questions: </h2>
    <form>
        <div class="question">
            <h4> What do you prefer most of this website? </h4>
            <textarea rows="5" cols="50" id="txt"></textarea>
 
        </div>
        <div class="question">
            <h4>  Is the recommendation section giving a correct list of videos that you would consider watching ? </h4>
            <input type="radio" id="YesQ2" name="YesQ2" value="Yes">
            <label for="YesQ2">Yes</label><br>
            <input type="radio" id="NoQ2" name="NoQ2" value="No">
            <label for="NoQ2">No</label><br>
        </div>
    
        <div class="question">
            <h4>  On a scale of 1 to 10, what are the odds you would return to this website? </h4>
            <div class="slidecontainer">
                <input type="range" min="1" max="10" value="5" class="slider" id="myRange">
                <p>Value: <span id="demo"></span></p>
            </div>      
        </div>
        <div class="question">
            <h4> Which color stands out the most on this site ?</h4>
            <select id="colors" name="colots">
                <option value="red">red</option>
                <option value="black">black</option>
                <option value="blue">blue</option>
                <option value="Gray">Gray</option>
            </select>    
        </div>
        <div class="question">
            <h4> What did you like about this website ?</h4>
            <input type="checkbox" id="searchalg" name="searchalg" value="searchalg">
            <label for="searchalg"> The search algorithm</label><br>
            <input type="checkbox" id="diversecontent" name="diversecontent" value="diversecontent">
            <label for="diversecontent"> The diverse content</label><br>
            <input type="checkbox" id="community" name="community" value="community">
            <label for="community"> The community</label>  
        </div>
        <div class="question">
            <h4> Write a comment: </h4>
            <textarea rows="5" cols="30" id="txt"></textarea>
        </div>
    </form>

</div>
  <div class="column side">
    <div class="container">
	    <button id="submitButton" type="button" class="Submit">
		    SUBMIT your questionnaire
        </button>
        </div>
    </div>
</div>

<div class="footer">
  <p>Site created by Jean Pierre Sfeir</p>
</div>

</body>
</html>
