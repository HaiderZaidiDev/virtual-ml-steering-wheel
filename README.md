<br />
<p align="center">
  <h3 align="center">Virtual Steering Wheel</h3>
  <p align="center">
    A virtual steering wheel, made with Python and pre-trained machine learning models. 
  </p>
</p>


<!-- ABOUT THE PROJECT -->
## About The Project

Recently got a webcam, and I've always wanted to explore using it to play around with computer vision (e.g., hand and gesture tracking); so I decided to create a virtual steering wheel with Python.

## How it Works
Uses Python (OpenCV) and the pre-trained models from [Mediapipe (Google)](http://https://google.github.io/mediapipe/ "Mediapipe (Google)") to capture video, recognize hands in the frame and then calculate the slope between the two hands to determine which direction to turn in. 

Want to see it in action? Click the thumbnail for a demo.
[![demo-thubmnail](https://i.imgur.com/XeL4zIn.png)](https://www.youtube.com/watch?v=q0O3pqBi1xs)

<!-- GETTING STARTED -->
## Getting Started

Looking to demo the app yourself? Check this part out.

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/HaiderZaidiDev/virtual-ml-steering-wheel
   ```
2. Install PIP packages
   ```sh
    pip install -r requirements.txt
   ```
3. Run the Python script
   ```sh
    python3 steeringwheel.py
   ```

<!-- CONTRIBUTING -->
## Contributing

Contributions are welcome, feel free to make a PR!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
