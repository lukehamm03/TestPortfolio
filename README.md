<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects</title>
    
    <!-- CSS Styles -->
    <style>
        /* Project card styling */
        .project-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin: 15px 0;
            background-color: #f4f4f4;
            position: relative; /* Position relative for absolute positioning of icons */
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        /* Hover effect for project cards */
        .project-card:hover {
            background-color: #333;
            transform: translateY(-10px);
            cursor: pointer;
        }

        /* Hover effect for text inside the project card */
        .project-card:hover .project-content h3,
        .project-card:hover .project-content p {
            color: #fff;
        }

        /* Download icon positioning and styling */
        .download-icon {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 30px;
            height: 30px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        /* Scale effect on hover for download icons */
        .download-icon:hover {
            transform: scale(1.1);
        }

        /* Adjust the size of the logos if necessary */
        .download-icon img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>

        <!-- MLB Salaries Project Card -->
        <div class="project-card">
            <a href="MLB_Salaries_Project.pdf" target="_blank">
                <div class="project-content">
                    <h3>MLB Salaries Project</h3>
                    <p>Conducted an in-depth analysis of the relationship between MLB player salaries and on-field performance using statistical methods...</p>
                </div>
            </a>
            <!-- R logo for downloading the R code -->
            <a href="https://github.com/your-repo/MLB_Salaries_Project.R" download class="download-icon">
                <img src="R-logo.png" alt="Download R Code">
            </a>
        </div>

        <!-- Reds Hackathon Project Card -->
        <div class="project-card">
            <a href="Hackathon.pdf" target="_blank">
                <div class="project-content">
                    <h3>Reds Hackathon</h3>
                    <p>Collaborative advanced data analysis working with large data sets of MLB statistics...</p>
                </div>
            </a>
            <!-- R logo for downloading the R code -->
            <a href="https://github.com/your-repo/Reds_Hackathon.R" download class="download-icon">
                <img src="R-logo.png" alt="Download R Code">
            </a>
        </div>

        <!-- Fantasy Football Player Value Project Card -->
        <div class="project-card">
            <a href="Unit_1_Project.pdf" target="_blank">
                <div class="project-content">
                    <h3>Fantasy Football Player Value</h3>
                    <p>Developed an analytical tool using historical NFL data to assess fantasy football player performance...</p>
                </div>
            </a>
            <!-- Python logo for downloading the Python code -->
            <a href="https://github.com/your-repo/Fantasy_Football_Player_Value.py" download class="download-icon">
                <img src="Python-logo.png" alt="Download Python Code">
            </a>
        </div>
    </section>

</body>
</html>
