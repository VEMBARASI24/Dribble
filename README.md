# Project Responsive Web Design using Bootstrap
## Date:24.05.2025
## Name: VEMBARASI.A.R
## Reg no: 212224220120

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="dribble.css">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('your-image-url.jpg'); 
            background-size: cover; 
            background-position: center; 
            background-repeat: no-repeat; 
            color: #2c3e50; 
        }
        .gallery-item {
            transition: transform 0.4s ease-in-out, box-shadow 0.3s ease;
        }
        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .gallery-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
    </style>
    
    
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#"><h2>Dribbble</h2></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
               <h2> <li class="nav-item"><a class="nav-link" href="#">Shot</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Designers</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Teams</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Community</a></li></h2>
               <h2> <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li></h2>
               <h2> <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li></h2>
            </ul>
        </div>
    </nav>

    
    <div class="container mt-4">
        <div class="text-center mb-4 header-section">
            <h2>What are you working on?</h2>
            <p class="lead"><h2>Dribbble is show and tell for designers.</h2></p>
        </div>

        
        <div class="row gallery-section">
            
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="nexxus.jpeg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">NEXXUS</p>
                        <small class="text-muted">NYKAA</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="semme.webp" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">SEMME</p>
                        <small class="text-muted">AJIO</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="sleek and shine.webp" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">SLEEK AND SHINE</p>
                        <small class="text-muted">PURPLLE</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="gucci.avif" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">GUCCI HANDABAG</p>
                        <small class="text-muted">ZARA</small>
                    </div>
                </div>
            </div>
            
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="CHANNel.webp" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">PERFUME</p>
                        <small class="text-muted">CHANNEL</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="puma.webp" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">PUMA</p>
                        <small class="text-muted">AMAZON</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="casio.avif" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">CASIO</p>
                        <small class="text-muted">MYNTRA</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="louis.jpg" class="card-img-top gallery-img">
                    <div class="card-body text-center">
                        <p class="card-title">HEELS</p>
                        <small class="text-muted">LOUIS</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

    
    <footer class="bg-dark text-white text-center py-3">
        <p><h2>© Dribbble. All rights reserved.</h2></p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
![Screenshot 2025-05-24 141553](https://github.com/user-attachments/assets/8791097f-3a4c-4a21-ba1f-39cf0a947a33)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
