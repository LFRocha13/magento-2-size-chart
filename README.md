# Magento 2 Size Chart Extension 📏

![Magento 2 Size Chart](https://img.shields.io/badge/Download%20Size%20Chart%20Extension-Click%20Here-blue)

Welcome to the **Magento 2 Size Chart Extension** repository. This extension helps reduce returns by providing accurate product information for various products. With our done-for-you templates, you can easily enhance your customers' shopping experience.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Features ✨

- **Accurate Size Information**: Provide customers with detailed size charts to help them make informed decisions.
- **Customizable Templates**: Use our ready-made templates or create your own to fit your store's design.
- **Easy Integration**: Simple installation process ensures that you can get started quickly.
- **Responsive Design**: Charts look great on all devices, ensuring a seamless shopping experience.
- **Multi-Language Support**: Cater to a global audience with support for multiple languages.

## Installation 🛠️

To install the Magento 2 Size Chart Extension, follow these steps:

1. **Download the Extension**: Visit the [Releases](https://github.com/LFRocha13/magento-2-size-chart/releases) section to download the latest version of the extension.

2. **Upload Files**: Extract the downloaded files and upload them to your Magento installation directory.

3. **Run Commands**: Open your terminal and navigate to your Magento root directory. Run the following commands:

   ```bash
   php bin/magento module:enable Magefan_SizeChart
   php bin/magento setup:upgrade
   php bin/magento setup:di:compile
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. **Verify Installation**: Log in to your Magento admin panel and check under `Stores > Configuration > Magefan > Size Chart` to configure the extension.

## Usage 📊

After installation, you can easily add size charts to your products:

1. **Access Product Settings**: Go to the product for which you want to add a size chart.

2. **Add Size Chart**: In the product edit page, you will find a new tab for the Size Chart. Click on it to upload your chart.

3. **Save Changes**: After adding your size chart, save the product to make the changes live.

4. **View on Frontend**: Visit the product page on your store to see the size chart displayed for customers.

## Customization 🎨

The extension comes with customizable templates. You can modify these templates to fit your store's theme:

1. **Locate Template Files**: Navigate to `app/code/Magefan/SizeChart/view/frontend/templates`.

2. **Edit Templates**: Open the template files in your favorite code editor and make your changes.

3. **Clear Cache**: After making changes, clear the cache to see the updates on the frontend.

## Contributing 🤝

We welcome contributions from the community. If you want to help improve the Magento 2 Size Chart Extension, please follow these steps:

1. **Fork the Repository**: Click the fork button on the top right of this page.

2. **Create a Branch**: Create a new branch for your feature or bug fix.

   ```bash
   git checkout -b feature/my-feature
   ```

3. **Make Changes**: Implement your changes and commit them.

   ```bash
   git commit -m "Add my feature"
   ```

4. **Push Changes**: Push your changes to your forked repository.

   ```bash
   git push origin feature/my-feature
   ```

5. **Create a Pull Request**: Open a pull request to the main repository.

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact 📬

For questions or support, please reach out via:

- **Email**: support@example.com
- **GitHub Issues**: Open an issue in this repository for bugs or feature requests.

## Releases 📦

To download the latest version of the Magento 2 Size Chart Extension, visit the [Releases](https://github.com/LFRocha13/magento-2-size-chart/releases) section. Here, you can find the latest updates and download files to install the extension.

---

We appreciate your interest in the Magento 2 Size Chart Extension. By providing accurate size information, you can enhance your customers' shopping experience and reduce returns. Happy coding!