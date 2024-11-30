# BVilale9T-Q1SW2-VilaleBeatrix
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Robotics Club Registration</title>

	<div style="background: url(images/computer.jpg);">
		
	</div>

	<!-- SETUP BOOTSTAP: link to Bootstrap -->
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

	<!-- link to JS -->
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

	<!-- Add style -->
	<link rel="stylesheet" type="text/css" href="style.css">	
	
</head>
<body>
<div class="alert alert-success" alert-dismissible fade show>
	


</div>
<div class="container">
	<h2>Robotics Club Registration Form</h2>
	<form>
		<form>
	    <div class="mb-3">
	        <label for="form-label" for="inputName">Name</label>
	        <input type="Name" class="form-control" id="inputName" placeholder="Name">
	    </div>
	    <div class="mb-3">
	    </div>
	   
	    <div class="mb-3">
	        <label for="form-label" for="inputEmail">Age</label>
	        <input type="age" class="form-control" id="inputAge" placeholder="Age">
	    </div>
	    <div class="mb-3">
	    </div>
        <div class="mb-3">
	        <label for="form-label" for="inputAge">Email Address</label>
	        <input type="age" class="form-control" id="inputEmail" placeholder="Email">
	    </div>
        <div class="mb-3">
	        <label for="form-label" for="inputPhone Number">Phone Number</label>
	        <input type="phone number" class="form-control" id="inputPhone Number" placeholder="Phone Number">
	   </div>
	   <h6>Preferred Robotics Topics</h6>

	   <div > <!--div for checkbox-->
	        <div >
	            <input type="checkbox" id="checkProgramming">
	            <label for="checkRemember">Programming</label>
	        </div>
	    </div>
	    <div > <!--div for checkbox-->
	        <div >
	            <input type="checkbox" id="checkElectronics">
	            <label for="checkRemember">Electronics</label>
	        </div>
	    </div>
	    <div > <!--div for checkbox-->
	        <div >
	            <input type="checkbox" id="checkMechanical Design">
	            <label for="checkRemember">Mechanical Design</label>
	        </div>
	    </div>
	</form>
	    
	    <h6>Robotics Experience Level</h6>

	    <div > <!--div for checkbox-->
	        <div >
	            <input type="checkbox" id="checkBeginner">
	            <label for="checkRemember">Beginner</label>
	        </div>
	    </div>
	    <div > <!--div for checkbox-->
	        <div >
	            <input type="checkbox" id="checkIntermediate">
	            <label for="checkRemember">Intermediate</label>
	        </div>
	    </div>
	    <div > <!--div for checkbox-->
	        <div >
	            <input type="checkbox" id="checkAdvanced">
	            <label for="checkRemember">Advanced</label>
	        </div>
	    </div>
        </form>

        <h6>Preferred Robotics Project</h6>
        <div class="mb-3">
	        <label for="form-label" for="inputPreferred Robotics Project">
	        <input type="Preferred Robotics Project" class="form-control" id="inputPreferredRoboticsProject" placeholder="Preferred Robotics Project">
	    </div>
	    <div class="mb-3">
	    </div>
	        
        
	    <h6>Statement of Interest</h6>
        <div class="mb-3">
	        <label for="form-label" for="inputStatement of Interest">
	        <input type="Statement of Interest" class="form-control" id="inputStatementofInterest" maxlength="3000">
	    </div>
	    <div class="mb-3">
	    </div>
	    <button type="submit" class="btn btn-primary">Submit</button>
	</form>
</div>
