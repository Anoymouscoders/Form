# Form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
    <style>
        
    </style>
</head>
<body >
    <h2>This is HTML forms tutorial</h2>

    <form action="backend.php">
        <!-- <img src="https://unsplash.com/s/photos/office-desk" alt="Sorry img not found"> -->
        <!-- <img src="image.jpg.jpg" alt="Sorry img not found" width="400" height="600"> -->
        <div background="C:\\Users\\Durga Das\\Desktop\\HTML FILES\\image.jpg.jpg">
            Name: <input type="text"name="myname">
        </div>
        <br>
        <div>
            Roll: <input type="text"name="myroll">
        </div>
        <br>
        <div>
            Class: <input type="text" name="myclass">
        </div>
        <br>
        <div>
            Email: <input type="email" name="myEmail">
        </div>
        <br>
        <div>
            I am not a robot: <input type="checkbox" name="myage">
        </div>
        <br>
        <div>
            Date: <input type="date" name="mydate">
        </div>
        <br>
        <div>
            Enter your age: <input type="number" name="myNumber">
        </div>
        <br>
        <div>
            Gender: Male <input type="checkbox" name="mydate"> Female <input type="checkbox" name="mydate"> Other:<input type="checkbox" name="myOther">
        </div>
        <br>
        <div>
            Write about your self:<br> <textarea name="myTest" id="" cols="30" rows="10"></textarea>
        </div>
        <br>
        <div>
            <input type="submit" value="submit now"> <input type="reset" value="reset Now">
        </div>
        <br>
        <div>
           MyUrl:<input type="url" name="myUrl">
        </div>
        

    </form>


</body>
</html>
