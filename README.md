<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Android Developer Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #0f172a;
            color: #f1f5f9;
            line-height: 1.6;
        }

        h1, h2, h3 {
            color: #38bdf8;
        }

        .section {
            margin-bottom: 50px;
        }

        .card {
            background-color: #1e293b;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 20px;
        }

        .badge {
            display: inline-block;
            background-color: #334155;
            padding: 6px 12px;
            border-radius: 20px;
            margin: 4px;
            font-size: 14px;
        }

        .project-table {
            width: 100%;
            border-collapse: collapse;
        }

        .project-table th, .project-table td {
            border: 1px solid #334155;
            padding: 10px;
            text-align: left;
        }

        .project-table th {
            background-color: #1e293b;
        }

        a {
            color: #38bdf8;
            text-decoration: none;
        }

        .center {
            text-align: center;
        }
    </style>
</head>

<body>

    <h1 class="center">Android Developer Portfolio</h1>

    <div class="section">
        <h2>Experience</h2>

        <div class="card">
            <h3>Eva · Junior Android Developer</h3>
            <p><strong>Oct 2025 – Dec 2025</strong> | Remote — Freelance, Iraq</p>
            <ul>
                <li>Developed cross-platform features using Compose Multiplatform (KMP)</li>
                <li>Shared business logic across Android & iOS</li>
                <li>Applied Clean Architecture with modular structure</li>
            </ul>
        </div>

        <div class="card">
            <h3>OTAS · Junior Android Developer</h3>
            <p><strong>May 2025 – Nov 2025</strong> | Remote — Full-time, Saudi Arabia</p>
            <ul>
                <li>Fixed 60+ production bugs in SaaS KMP system</li>
                <li>Built GDS Tourism App from concept to deployment</li>
                <li>Developed Altashirat App from scratch</li>
                <li>Refactored and modularized codebase</li>
            </ul>
        </div>

        <div class="card">
            <h3>OTAS · Android Developer Intern</h3>
            <p><strong>Jan 2025 – May 2025</strong> | Remote — Full-time, Saudi Arabia</p>
            <ul>
                <li>Led internal team projects</li>
                <li>Conducted code reviews</li>
                <li>Built full Android app using Clean Architecture & MVI</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <h2>Technical Expertise</h2>

        <h3>Architecture & Design</h3>
        <div>
            <span class="badge">Clean Architecture</span>
            <span class="badge">MVI</span>
            <span class="badge">MVVM</span>
            <span class="badge">SOLID</span>
            <span class="badge">Repository Pattern</span>
            <span class="badge">Modularization</span>
        </div>

        <h3>Android & UI</h3>
        <div>
            <span class="badge">Jetpack Compose</span>
            <span class="badge">Compose Multiplatform</span>
            <span class="badge">Material 3</span>
            <span class="badge">Navigation</span>
            <span class="badge">StateFlow</span>
            <span class="badge">XML</span>
        </div>

        <h3>Networking & Data</h3>
        <div>
            <span class="badge">Ktor</span>
            <span class="badge">Retrofit</span>
            <span class="badge">Room</span>
            <span class="badge">DataStore</span>
            <span class="badge">Firebase</span>
            <span class="badge">Kotlinx Serialization</span>
        </div>

        <h3>Testing</h3>
        <div>
            <span class="badge">JUnit</span>
            <span class="badge">MockK</span>
            <span class="badge">Mokkery</span>
            <span class="badge">TDD</span>
        </div>
    </div>

    <div class="section">
        <h2>Featured Projects</h2>

        <table class="project-table">
            <tr>
                <th>Project</th>
                <th>Description</th>
                <th>Architecture</th>
            </tr>
            <tr>
                <td>Altashirat</td>
                <td>Visa requesting system built from scratch</td>
                <td>Clean Architecture + MVI</td>
            </tr>
            <tr>
                <td>GDS Tourism</td>
                <td>Tourism management application</td>
                <td>KMP + Compose</td>
            </tr>
            <tr>
                <td>Talkie (Graduation - A+)</td>
                <td>Real-time chat application</td>
                <td>MVVM + Firebase</td>
            </tr>
        </table>
    </div>

    <div class="section center">
        <h2>Let's Connect</h2>
        <p>
            <a href="https://www.linkedin.com/in/rodina-momen-927b991a5/" target="_blank">LinkedIn</a> |
            <a href="mailto:Rodinamobark3@gmail.com">Gmail</a> |
            <a href="https://medium.com/@rodinamobark3" target="_blank">Medium</a>
        </p>
    </div>

</body>
</html>
