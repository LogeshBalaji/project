# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
### Project page
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #f8f9fa;
        }
        .navbar-dark {
            background-color: #333;
        }
        .navbar-dark .navbar-brand {
            color: #fff;
        }
        .navbar-dark .nav-link {
            color: #ddd;
        }
        .hero-section {
            padding: 4rem 0;
            background-color: #f0f0f0;
        }
        .card {
            border: none;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card-footer img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="index.html">dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Designers</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Teams</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Jobs</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-primary btn-sm ms-3" href="s.html" target="_blank">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section text-center">
        <div class="container">
            <h1 class="display-5">What are you working on?</h1>
            <p class="lead">Dribbble is the leading destination to find & showcase creative work.</p>
            <button class="btn btn-dark btn-lg">Learn More</button>
            <button class="btn btn-pink btn-lg">Sign Up</button>
        </div>
    </section>

    <!-- Content Section -->
    <section class="py-5">
        <div class="container">
            <div class="row row-cols-1 row-cols-md-5 g-5">
                <div class="col">
                    <div class="card">
                        <img src="temp1,1.webp" class="card-img-top" alt="Design">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="rajini.jpg" alt="Author">
                            <span class="ms-2">Rajini kanth</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp2.webp" class="card-img-top" alt="Portfolio">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="thor.jpg" alt="Author">
                            <span class="ms-2">Thor</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp3.webp" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="KGF.jpg" alt="Author">
                            <span class="ms-2">Yash</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp4.webp" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="jane.jpg" alt="Author">
                            <span class="ms-2">Jane Foster</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp5.webp" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="drstrange.jpg" alt="Author">
                            <span class="ms-2">DR Strange</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp6,1.jpg" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="dhoni.jpg" alt="Author">
                            <span class="ms-2">MS Dhoni</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp7.avif" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="tony.jpg" alt="Author">
                            <span class="ms-2">Tony</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp8.jpg" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="vijay.jpg" alt="Author">
                            <span class="ms-2">Vijay</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp9.avif" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="ajith.jpg" alt="Author">
                            <span class="ms-2">Ajith</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp10.jpg" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="prabhas.jpg" alt="Author">
                            <span class="ms-2">prabhas</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp11.png" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="loki.jpg" alt="Author">
                            <span class="ms-2">Loki</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp12.png" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="jadaja.webp" alt="Author">
                            <span class="ms-2">Ravindera jadaja</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp13.png" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="stalin.jpg" alt="Author">
                            <span class="ms-2">MK Stalin</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp14.png" class="card-img-top" alt="Networking">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="spb.jpg" alt="Author">
                            <span class="ms-2">SP Balasupramaniyam</span>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="temp15.jpg" class="card-img-top" alt="Inspiration">
                        <div class="card-body">
                            <p class="card-text"></p>
                        </div>
                            <div class="ms-auto">
                                <button class="btn btn-outline-primary btn-sm">❤️</button>
                                <button class="btn btn-outline-secondary btn-sm">💬</button>
                                <button class="btn btn-outline-success btn-sm">🔗</button>
                            </div>
                        </div>
                        <div class="card-footer d-flex align-items-center">
                            <img src="a2d.jpg" alt="Author">
                            <span class="ms-2">Nandha</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center py-3 bg-dark text-white">
        <p>Designed by Logesh B</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
~~~
# OUTPUT:
## Main Page
![Screenshot 2024-12-22 154202](https://github.com/user-attachments/assets/aecf8bb4-4d2c-4f55-a099-8b34f95bdf2c)
![Screenshot 2024-12-22 154214](https://github.com/user-attachments/assets/4ed9c369-b43a-489c-8412-cc8078082d92)
## Sign In Page
![Screenshot 2024-12-22 154312](https://github.com/user-attachments/assets/87eacd1c-699b-45f5-afc3-eb9aba935c4c)
## Sub Page
![Screenshot 2024-12-22 154503](https://github.com/user-attachments/assets/d088051b-7d49-4df4-9944-93b83bd8a128)
![Screenshot 2024-12-22 154513](https://github.com/user-attachments/assets/e13b47bc-2a4a-4b65-a616-66b8362f0cf7)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
