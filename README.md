# Sankuchit - Open Source Image Resizer & Refactor Service

![Screenshot 2025-03-28 010144](https://github.com/user-attachments/assets/1c5536cf-fc9c-4200-a713-0e85b32254cc)

Sankuchit is a free, fast, and secure image resizing and optimization service built with Golang. It allows users to resize, optimize, and convert images seamlessly through a web interface or API.

## 🚀 Features

- 🌟 **High-Quality Resizing** - Resize images while maintaining the best quality.
- ⚡ **Lightning Fast** - Optimized Golang backend ensures fast image processing.
- 🔄 **Multiple Formats** - Supports PNG, JPEG, and WebP conversions.
- 🔒 **Privacy Focused** - No data is stored after processing.
- 📡 **REST API Available** - Use the API to integrate with your applications.
- 🌍 **Cloud Hosted** - Works anywhere, anytime.

## 📸 Live Demo

Try it out: [Sankuchit Live](https://adityasinghvats.github.io/sankuchit/)

## 🛠 Installation

### Prerequisites

- Go 1.20+
- Docker (optional for containerized deployment)

### Backend yaha milega
- [Backend ka code repo](https://github.com/Adityasinghvats/sankuchit-backend)

### Clone the Repository

```sh
git clone https://github.com/yourusername/sankuchit.git
cd sankuchit
```

### Install Dependencies

```sh
go mod tidy
```

### Run the Server

```sh
go run main.go
```

### Run with Docker

```sh
docker build -t sankuchit .
docker run -p 8080:8080 sankuchit
```

## 📡 API Usage

Sankuchit provides a simple REST API for image resizing.

### Resize an Image

**Endpoint:** `POST /resize`

#### Request Example:
```sh
curl -X POST "https://your-api-url.com/resize" \
     -F "image=@sample.jpg" \
     -F "width=500" \
     -F "height=700" \
     -F "quality=95" \
     -F "format=png"
```

#### Response Example:
```json
{
    "file": "resized_jpeg.jpeg/resized_png.png"
}
```

## 🏗️ Contributing

We welcome contributions! Feel free to fork the repo and submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Support

For any issues or feature requests, please open an issue on GitHub or contact us at [adityakumarbgs6@gmail.com](mailto:adityakumarbgs6@gmail.com).
