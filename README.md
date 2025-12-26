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
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>PHARMACEUTICALS</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body {
            background-color: #fff7cc; /* Yellow background */
            font-family: Arial, Helvetica, sans-serif;
        }

        .top-nav {
            background-color: #b45309; /* Dark orange */
            padding: 10px 0;
        }

        .top-nav a {
            color: #ffffff;
            font-size: 14px;
            text-decoration: none;
            margin: 0 15px;
        }

        .page-header h1 {
            font-size: 28px;
            letter-spacing: 2px;
            color: #92400e;
        }

        .page-header p {
            font-size: 14px;
            color: #7c2d12;
        }

        .item-card {
            background-color: #ffffff;
            border: 1px solid #facc15;
            border-radius: 10px;
            padding: 10px;
            height: 100%;
            box-shadow: 0 4px 8px rgba(0,0,0,0.08);
        }

        .item-card img {
            width: 100%;
            height: 160px;
            object-fit: contain;
            margin-bottom: 8px;
        }

        .item-card h6 {
            font-size: 15px;
            color: #78350f;
        }

        .item-card p {
            font-size: 13px;
            color: #854d0e;
        }

        .grid-item {
            width: 20%;
            padding: 10px;
        }

        @media (max-width: 992px) {
            .grid-item {
                width: 33.33%;
            }
        }

        @media (max-width: 576px) {
            .grid-item {
                width: 100%;
            }
        }
    </style>
</head>

<body>

    <nav class="navbar top-nav">
        <div class="container justify-content-center">
            <a href="#">Home</a>
            <a href="#">Medicines</a>
            <a href="#">Contact</a>
        </div>
    </nav>

    <div class="page-header text-center my-4">
        <h1>JAI HARI PHARMACY</h1>
        <p>Your trusted healthcare partner</p>
    </div>

    <section class="pb-5">
        <div class="container">

            <div class="row justify-content-center">
                <div class="grid-item">
                    <div class="item-card">
                        <img src="AMOXYCLAV.jpg">
                        <h6>Amoxyclav</h6>
                        <p>Used to treat bacterial infections.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Zithrocare.jpg">
                        <h6>Zithrocare</h6>
                        <p>Helps treat throat and lung infections.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Coughnil.jpg">
                        <h6>Coughnil</h6>
                        <p>Relief from cough and cold symptoms.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Painrelax.png">
                        <h6>Painrelax</h6>
                        <p>Reduces pain and inflammation.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Febrex.jpg">
                        <h6>Febrex</h6>
                        <p>Effective for fever and body pain.</p>
                    </div>
                </div>
            </div>

            <div class="row justify-content-center">
                <div class="grid-item">
                    <div class="item-card">
                        <img src="Headclear 650.jpg">
                        <h6>Headclear 650</h6>
                        <p>Relieves headache and fever.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Zithrocare.jpg">
                        <h6>Hydralyte ORS</h6>
                        <p>Prevents dehydration.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="Calmofen.png">
                        <h6>Calmofen</h6>
                        <p>Reduces pain and fever.</p>
                    </div>
                </div>

                <div class="grid-item">
                    <div class="item-card">
                        <img src="ColdRub Plus.jpg">
                        <h6>ColdRub Plus</h6>
                        <p>Relieves cold and nasal blockage.</p>
                    </div>
                </div>
            </div>

        </div>
    </section>

</body>

</html>
```
# OUTPUT
![WhatsApp Image 2025-12-24 at 3 34 08 PM](https://github.com/user-attachments/assets/6e7ac538-bb5e-450d-a4c2-4a4f8a33045f)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
