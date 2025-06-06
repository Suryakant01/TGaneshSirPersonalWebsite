
# Personal Academic Website of Dr. T. Ganesh Kumar

This repository contains the source code for the personal academic portfolio website of Dr. T. Ganesh Kumar, a Professor at the School of Computer Science & Engineering, Galgotias University.

**[▶️ View the Live Website (placeholder link)](https://suryakant01.github.io/TGaneshSirPersonalWebsite/)**

## About

This website serves as a comprehensive and up-to-date digital profile, detailing Dr. Ganesh Kumar's academic journey, research contributions, and professional activities. It is designed to be a central point of information for students, fellow researchers, academic collaborators, and the wider academic community.

## Features

The website is organized into distinct sections for clarity and ease of navigation:

-   **Personal Profile**: General information, contact details, and current affiliation.
-   **Education**: A detailed history of academic qualifications, including Ph.D. and M.E. degrees, research details, and online certifications.
-   **Experience**: A timeline of research and teaching experience, along with key administrative roles held.
-   **PhD Supervision**: Information on completed and ongoing Ph.D. supervision and mentorship for other degree programs.
-   **Awards & Recognitions**: A list of prestigious fellowships and awards received.
-   **Publications**: A comprehensive catalog of all published works, including edited books, authored books, book chapters, and articles in SCIE, Scopus, and UGC-indexed journals.
-   **Patents**: A complete list of granted and published patents, both international (Australia, Germany) and Indian.
-   **Funded R&D Projects**: Details on government-funded research projects undertaken as a Co-Investigator.
-   **Professional Activities**: Roles as a journal editor, reviewer, and member of esteemed professional bodies like IEEE and ACM.
-   **Conferences & Workshops**: Extensive involvement in academia as a presenter, keynote speaker, session chair, and organizer.

## Technology Stack

This is a static website built with a focus on simplicity, performance, and maintainability.

-   **HTML5**: For the structure and content of the web pages.
-   **Tailwind CSS**: For a modern, utility-first styling approach.
-   **JavaScript**: For dynamic content loading within an `<iframe>` to create a smooth, single-page application (SPA) like experience without full page reloads.

## Project Structure

The repository is organized as follows:

```
.
├── index.html              # Main layout, header, and navigation shell
├── content/                # Directory for individual section pages
│   ├── personal_profile.html
│   ├── education.html
│   ├── experience.html
│   ├── publications.html
│   ├── patents.html
│   └── ... (all other content files)
│
├── shared.css              # Shared styles for all pages in the /content directory
└── README.md               # This file
```

## How It Works

The website operates as a pseudo-Single Page Application:
1.  The `index.html` file acts as the main container.
2.  When a user clicks a navigation link, a JavaScript function is triggered.
3.  This function dynamically sets the `src` attribute of an `<iframe>` in the main content area to the corresponding HTML file from the `/content` directory.
4.  This approach allows for fast content switching and keeps the main navigation persistent, improving user experience.

## Local Development & Deployment

### Running Locally
No complex setup is required. You can view the website by opening the `index.html` file in a modern web browser. For best results and to avoid any potential cross-origin issues with file protocols, it is recommended to use a simple local server.

1.  If you have Python installed, you can run:
    ```bash
    # For Python 3
    python -m http.server
    ```
2.  If you have Node.js and `serve` installed (`npm i -g serve`), you can run:
    ```bash
    serve .
    ```
Then, access the site at `http://localhost:8000` (or the port indicated by the command).


## License

This project is licensed under the MIT License. See the `LICENSE` file for more details. (You may want to create a LICENSE file with the MIT license text).

## Author & Contact

**Dr. T. Ganesh Kumar**
-   **Title**: Professor, School of Computer Science & Engineering
-   **Institution**: Galgotias University, Greater Noida, Delhi NCR, India
-   **Email**: tganeshphd@yahoo.com
-   **Professional Memberships**: IEEE Senior Member, ACM Professional Member
