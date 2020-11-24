# Asp-demo
<!DOCTYPE html>
<html lang="">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <link rel="stylesheet" href="">
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" 

href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"

>

    <!-- jQuery library -->
    <script 

src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></scr

ipt>

    <!-- Latest compiled JavaScript -->
    <script 

src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></

script>
    <link rel="stylesheet" 

href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-

datepicker/1.7.1/css/bootstrap-datepicker3.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-

awesome/4.7.0/css/font-awesome.min.css">
   
    <link href="https://use.fontawesome.com/releases/v5.8.2/css/all.css" 

rel="stylesheet" />
    <style>
        .form {
            box-shadow: 0 1px 3px 0 rgba(0, 0, 0, .2), 0 1px 1px 0 rgba(0, 

0, 0, .14), 0 2px 1px -1px rgba(0, 0, 0, .12);
            background: #fff;
            padding: 28px;
            width: 500px;
        }

        .form-control {
            width: 250px;
        }

        .img {
            border-radius: 50%;
            background: green;
            width: 139px;
            height: 134px;

        }

        .img h2 {
            color: wheat;
            font-size: 71px;
            margin: 31px 0 0 47px;
            position: absolute;
        }

        .fa-edit:before {
            content: "\f044";
            margin: -64px 0 0 99px;
            position: absolute;
            /* size: 35px; */
            font-size: 39px;
        }
        }

    </style>
</head>

<body>


    <div class="container" style="margin: 0 0 0 450px;">

        <form action="/action_page.php">
            <div class="form">
                <div class="row">
                    <div class="col-md-1">
                        <i class="fas fa-less-than"></i>
                    </div>
                    <div class="col-md-3">
                        <label for="FullName"> Edit Profile</label>
                    </div>
                </div>

                <hr>

                <div class="row">
                    <div class="col-md-4">
                        <div class="img">
                            <h2>A</h2>
                        </div>
                        <i class="fa fa-edit"></i>
                    </div>
                    <div class="col-md-4">
                        <label for="FullName" style="color:green;    color: 

green;margin: 48px 0 0 0;"> Edit Profile Photo</label>
                    </div>

                </div>
                <br>
                <div class="form-group">
                    <label for="FullName">PROFILE</label>
                    <P>Add Your Basic Info for faster bookinf.</P>
                </div>
                <br>
                <div class="form-group">
                    <label for="FullName">FullName</label>
                    <input type="text" class="form-control input-sm" 

id="email" placeholder="abdul kadir" name="FullName">
                </div>
                <div class="form-group">
                    <label for="Martial Status">Martial Status:</label>
                    <input type="text" class="form-control input-sm" 

id="pwd" placeholder="Single" name="Martial">
                </div>
                <div class="form-group">
                    <label for="Gender">Gender:</label>
                    <input type="text" class="form-control input-sm" 

id="pwd" placeholder="Male" name="Gender">
                </div>
                <label for="Gender">DateOfBirth:</label>
                <div class="input-group date" data-provide="datepicker">
                    <input type="text" class="form-control input-sm">
                    <div class="input-group-addon">
                        <span class="glyphicon glyphicon-th"></span>
                    </div>
                </div>

            </div>
            <br>
            <div class="form">
                <label for="">Save Traveller(s):</label>
                <br>
                <br>
                <div class="row">
                    <div class="col-md-5">
                        <p>Traveller 1</p>
                    </div>
                    <div class="col-md-3">
                        <a href="" class="link">Edit</a>
                    </div>
                </div>
                <label for="">Amritpal Singh(Male,25years)</label>
                <br>
                <br>
                <hr>
                <div class="row">
                    <div class="col-md-5">
                        <p>Traveller 2</p>
                    </div>
                    <div class="col-md-3">
                        <a href="" class="link">Edit</a>
                    </div>
                </div>
                <label for="">Zeeshan Khan(Male,28years)</label>
            </div>
            <br>
            <div class="form">
                <div class="form-group">
                    <label for="">LogIn Details</label>
                    <p>Manage Your Email Address,Mobile and Password</p>
                </div>
                <div class="form-group">
                    <label for="Mobile">Mobile:</label>
                    <input type="text" class="form-control input-sm" 

id="pwd" placeholder="+918108419674" name="Mobile">
                </div>
                <div class="form-group">
                    <label for="Email">Email:</label>
                    <input type="email" class="form-control input-sm" 

id="pwd" placeholder="Male" name="Email">
                </div>

                <div class="form-group">
                    <label for="Password">Password:</label>
                    <div class="row">
                        <div class="col-md-5">
                            <input type="password" class="form-control 

input-sm" id="pwd" placeholder="Male" name="Password">
                        </div>
                        <div class="col-md-6">
                            <a href="" class="link" style="position: 

absolute;margin: 5px 0 0 62px;color: green">Change Password</a>
                        </div>
                    </div>

                </div>

            </div>
        </form>
    </div>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" 

integrity="sha384-

KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" 

crossorigin="anonymous"></script>
    <script 

src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.

js" integrity="sha384-ApNbgh9B

+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" 

crossorigin="anonymous"></script>
    <script 

src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" 

integrity="sha384-

Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" 

crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-

datepicker/1.7.1/js/bootstrap-datepicker.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-

datepicker/1.7.1/locales/bootstrap-datepicker.en-GB.min.js" charset="UTF-

8"></script>

    <script>
        $(document).ready(function() {
            $('#datepicker').datepicker();
        });

    </script>

</body>

</html>
