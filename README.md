
### Main Files

- `Espresso Station.html`: This is the main file that contains the homepage of the website.
- `images/`: This directory includes all the image assets used in the website.
- `pages/`: This directory includes additional pages such as:
  - `about.html`: Information about the coffee shop.
  - `menu.html`: The menu offered by the coffee shop.
  - `contact.html`: Contact information and form.

## Features

- **Responsive Design**: The website is fully responsive and looks great on all devices.
- **Informative Content**: Provides detailed information about the coffee shop and its offerings.
- **Visual Appeal**: High-quality images and a visually appealing layout to attract visitors.

## Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling the content and making the website visually appealing.
- **Git**: For version control.

## How to Run

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Espresso-Station.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Espresso-Station
    ```

3. Open `Espresso Station.html` in your web browser to view the website.

## Contributing

Contributions are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
"""

# Define the path to save the README file
readme_path = os.path.join(extract_to_dir, 'README.md')

# Write the README content to the README.md file
with open(readme_path, 'w') as file:
    file.write(readme_content)

# Confirm that the README file was created
os.listdir(extract_to_dir)
