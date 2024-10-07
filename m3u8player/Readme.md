# M3U8 Video Player

## Overview

The M3U8 Video Player is a simple web application that allows users to play M3U8 (HTTP Live Streaming) video streams directly in their browser. It utilizes the HLS.js library for compatibility across different browsers, ensuring a seamless viewing experience.

## Features

- Input field for entering M3U8 stream URLs.
- Video player that supports both HLS.js and native M3U8 playback.
- User-friendly interface with a responsive design.
- Supports automatic playback upon loading a valid M3U8 URL.

## Technologies Used

- **HTML5**: For structuring the web application.
- **CSS3**: For styling the application and ensuring a responsive layout.
- **JavaScript**: For handling user interactions and video playback logic.
- **HLS.js**: A JavaScript library that enables playback of HLS video streams in browsers that do not support it natively.

## Installation

To run this application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/saurav-z/m3u8-video-player.git
   cd m3u8-video-player
   ```

2. **Open `index.html`** in your preferred web browser. You can do this by simply double-clicking the file or using a local server.

## Usage

1. Open the application in your browser.
2. Enter a valid M3U8 URL in the input field.
3. Click the **Load Video** button to start playing the video.
4. The video will automatically play if the URL is valid and supported.

## Example

You can use any publicly available M3U8 stream for testing. For example:

```
https://example.com/your-video.m3u8
```

Replace the above URL with a valid M3U8 URL to test.

## Browser Compatibility

- The application is designed to work on modern browsers, including:
  - Google Chrome
  - Mozilla Firefox
  - Safari
  - Microsoft Edge

## Limitations

- Some older browsers may not support HLS playback.
- Playback quality and performance depend on the network speed and the capabilities of the device being used.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request. 

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- [HLS.js](https://github.com/video-dev/hls.js/) for making it easy to work with M3U8 streams in the browser.
- The developers of the various open-source libraries and frameworks used in this project.

## Contact

For any inquiries or questions, please feel free to reach out:

- **Email**: github@saurav-phuyal.com.np
- **GitHub**: [saurav-z](https://github.com/saurav-z)

---

Feel free to customize the README with your specific details, such as your GitHub username and contact information!