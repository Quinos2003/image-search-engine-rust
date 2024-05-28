# Image Search Engine in Rust

Image Search Engine in Rust is a reverse image search engine built in Rust. It allows users to upload an image and find similar images from a dataset based on visual content. This project showcases how to combine Rust with image processing, feature extraction, and efficient searching techniques to create a functional reverse image search engine.

## Features

- Image preprocessing (resizing and normalization)
- Feature extraction using pre-trained neural networks
- Efficient image indexing with KD-Tree
- Similarity search using Euclidean distance
- Web interface for image upload and search

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/Quinos2003/image-search-engine-rust.git
    cd image-search-engine-rust
    ```

2. **Install dependencies:**

    Make sure you have [Rust](https://www.rust-lang.org/tools/install) installed. Then, run:

    ```sh
    cargo build
    ```

3. **Run the application:**

    ```sh
    cargo run
    ```

## Usage

1. **Upload an image:**
    Open your web browser and go to `http://localhost:8000`. You will see an interface to upload an image.

2. **Search for similar images:**
    Upload an image, and Image Search Engine in Rust will display images from the dataset that are visually similar to the uploaded image.

## Project Structure

- `src/`
    - `main.rs`: Entry point of the application.
    - `lib.rs`: Contains the core logic for image preprocessing, feature extraction, and searching.
    - `web.rs`: Handles the web server and routes for the web interface.
- `static/`: Contains static files like HTML, CSS, and JavaScript for the web interface.
- `dataset/`: Directory where the dataset images are stored.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [image](https://crates.io/crates/image): Rust crate for image processing.
- [ndarray](https://crates.io/crates/ndarray): Rust crate for numerical operations.
- [kiddo](https://crates.io/crates/kiddo): Rust crate for KD-Tree implementation.
- [Rocket](https://rocket.rs/): Web framework for Rust.

## Contact

If you have any questions or feedback, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/samarth-asthana).
