# Portfolio Website

This is a simple portfolio website built using Python and Flask. It showcases personal information, projects, and provides a contact form for visitors to reach out.

## Features

- **Home Page**: A welcome page with links to other sections.
- **About Me**: A section to describe yourself and your background.
- **Projects**: A list of your projects with brief descriptions.
- **Contact Me**: A contact page with an email address or form for reaching out.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- Python 3.7+
- Flask

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/MakendranG/portfolio-website.git
   cd portfolio-website
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install flask
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://127.0.0.1:5000`.

## File Structure

```
portfolio-website/
│
├── app.py                  # Main application file
├── static/
│   ├── style.css           # CSS styles
│
├── templates/
│   ├── index.html          # Home page
│   ├── about.html          # About Me page
│   ├── projects.html       # Projects page
│   ├── contact.html        # Contact Me page
│
└── README.md               # Project documentation
```

## Contributing

If you'd like to contribute, feel free to fork the repository and submit a pull request. Any contributions are appreciated!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
