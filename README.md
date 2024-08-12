# Dynamic Video-Image Banner Creator 🎥🖼️

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Create eye-catching banners by combining video backgrounds with overlaid images using HTML, CSS.

## 🚀 Features

- Seamless integration of MP4 video backgrounds
- Overlay images positioned at the bottom of the video
- Responsive design for various screen sizes
- Easy customization of video and image sources

## 📁 Project Structure
```
banner/
│
├── index.html
├── assets/
|   ├── css/
│   │   └── style.css
│   ├── video/
│   │   └── 3508353683-preview.mp4
│   └── image/
│       └── IMG_20230825_215634_152.jpg
└── README.md
```
## 🛠️ Usage

1. Clone the repository:
```sh
git clone https://github.com/deepanshu414/banner.git
```
2.Navigate to the project directory:
  ```sh
    cd banner
  ```
3. Replace `3508353683-preview.mp4` in the `assets/video/` directory with your desired video.

4. Replace `IMG_20230825_215634_152.jpg` in the `assets/image/` directory with your overlay image.

5. Adjust the HTML, CSS as needed to customize your banner.

6. Open `index.html` in a web browser to view your banner.

## 📝 Code Snippet

Here's a basic example of the HTML structure:

```html
<div class="banner-container">
<video autoplay loop muted>
 <source src="assets/video/3508353683-preview.mp4" type="video/mp4">
</video>
<img src="assets/image/IMG_20230825_215634_152.jpg" alt="Overlay Image" class="overlay-image">
</div>
```
## 🎨 Customization
Adjust the CSS in `styles.css` to modify:

- Video positioning and size
- Overlay image position and size
- Responsive behavior

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact
If you have any questions or suggestions, please open an issue or contact the repository owner.

Happy banner creating! 🎉
