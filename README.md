# Project Responsive Web Design using Bootstrap
## Date:14.10.25

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>BOOTSTRAP PROJECT</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    </head>
    <body>
        <nav class="navbar navbar-inverse">
            <div class="container-fluid">
                <div class="navbar-header">
                    <a class="navbar-brand" href="#">Dribble</a>
                </div>
                <ul class="nav navbar-nav">
                    <li><a href="#">BOOKS</a></li>
                    <li><a href="#">AUTHORS</a></li>
                    <li><a href="#">NEW ARRIVALS</a></li>
                    <li><a href="#">TOP READS</a></li>
                    <li><a href="#">REVIEWS</a></li>
                    <li><a href="#">...</a></li>
                </ul>
                <ul class="nav navbar-nav navbar-right">
                    <li><a href="#">Sign up</a></li>
                    <li><a href="#">Sign in</a></li>
                </ul>
                
            </div>
        </nav>
        <div class="bg-dark text-center">
            <p>What are you working on? Dribble is show and tell for designers.
                <button type="button" class="btn btn-secondary">Learn more</button>
                <button type="button" class="btn btn-danger">Sign up</button></p>
        </div>
        <nav class="navbar navbar-default">
            <div class="container-fluid">
                <ul class="nav navbar-nav">
                    <li class="dropdown"><a href="#">BOOKS</a>
                        <ul class="dropdown-menu" >
                			<li><a href="#">1.1</a></li>
                			<li><a href="#">1.2</a></li>
                			<li><a href="#">1.3</a></li>
                        </ul>
                    </li>
                    <li class="dropdown"><a href="#">SALES</a>
                        <ul class="dropdown-menu">
                			<li><a href="#">2.1</a></li>
                			<li><a href="#">2.2</a></li>
                			<li><a href="#">2.3</a></li>
                        </ul>
                    </li>
                    <li class="dropdown"><a href="#">POPULAR</a>
                        <ul class="dropdown-menu">
                			<li><a href="#">3.1</a></li>
                			<li><a href="#">3.2</a></li>
                			<li><a href="#">3.3</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </nav>
        <div class="container">
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 073922.png" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">THE GREAT GATSBY</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074025.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">ATOMIC HABITS</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074127.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">THE SELFISH GENE</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074202.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">THE HOBBIT</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074306.png" class="card-img-top" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">THE NOTEBOOK</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074341.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">GONE GIRL</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074425.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">DEEP WORK</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074501.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">IT ENDS WITH US</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-3">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074547.png" class="card-img-top" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">THE CODE BOOK</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074626.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">THE ALCHEMIST</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="Screenshot 2025-10-16 074656.png" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold">THE POWER OF NOW</p>
                </div>
            </div>
            <div class="col-md-3 col-sm-6">
                <div class="card border-dark text-center">
                    <img src="" class="img-fluid rounded" style="height:150px; object-fit:cover;">
                    <p class="mt-2 fw-semibold"></p>
                </div>
            </div>
        </div>
        </div>
        <footer class="copyrights text-center">
            &copy; DHANVARSINI S (25012184)
        </footer>
    </body>
</html>

```


## OUTPUT:
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
