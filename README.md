**1. Bottle Flip Game with Computer Vision**
**Overview**

This is a 2-player bottle flip game where users interact with a bottle in real life. The game uses computer vision to detect bottle flips, detect cheating (such as manual flips), and prevent stopping the bottle to prevent falling. The game uses one or more cameras to detect the bottle's motion in real-time with less than 1-second latency.
Key Features

    Real-time Bottle Flip Detection: Detects the orientation of the bottle using computer vision techniques.
    Cheating Detection: Identifies manual flipping and attempts to stop the bottle using hand movements or other methods.
    Game Mechanics: Players take turns flipping a bottle in real life. The game calculates the success of each flip and updates scores accordingly.
    Real-time Feedback: Provides immediate feedback on the success or failure of each flip.

**Libraries & Tools**

    OpenCV: Used for real-time video processing and bottle orientation detection.
    NumPy: For mathematical computations and image transformations.
    MoviePy (optional): If needed, for video processing features such as video capture.

**Approach**

    Use a camera to capture the bottle’s motion.
    Process frames using OpenCV to detect flip trajectories and bottle landing orientation.
    Use color detection, shape recognition, and motion analysis to distinguish legitimate flips from manual interference (e.g., hand-assisted flips or bottle stabilization).

**Setup**

To run the Bottle Flip Game:

    Install dependencies:

    pip install opencv-python numpy

    Ensure a camera is connected and accessible by OpenCV. Run the Python script to start the game.

## **2. Video Highlight Generator for Social Media**
**Overview**

The Video Highlight Generator creates engaging highlight reels from videos. The application detects significant scenes based on motion intensity and generates a final video that fits the social media format (e.g., Instagram Reels, TikTok, YouTube Shorts). It also adds optional background music to enhance the viewing experience.

**Key Features**

    Scene Detection: Automatically detects scenes with significant motion or content change.
    Social Media Optimization: Resizes and formats the video for various platforms (Instagram, YouTube Shorts, etc.).
    Audio Addition: Adds background music to the highlight reel, with automatic looping and synchronization to video length.
    Customizable Output: Generates highlight reels with a target duration and format, optimized for specific social media platforms.

**Libraries & Tools**

    OpenCV: For motion detection and analyzing video frames.
    MoviePy: Used for video editing, such as resizing, subclipping, and adding audio.
    NumPy: For mathematical operations and frame analysis.
    Pathlib/OS: For file path handling and validation.

**Approach**

    Motion Detection: The application analyzes the video frames using OpenCV to detect high-motion scenes.
    Scene Scoring: Each scene is given a score based on its motion intensity, and the most engaging scenes are selected.
    Video Resizing: MoviePy is used to resize the video for social media formats, ensuring no aspect ratio distortion.
    Music Addition: Background music is optionally added using MoviePy, synchronized to the video duration.

**Setup**

To run the Video Highlight Generator:

    Install dependencies:

    pip install opencv-python numpy moviepy

    Ensure the video file and optional music file are placed correctly in the file paths.

    Run the script to generate the highlight reel.

**Watch the video generated from this script: **https://drive.google.com/file/d/12juBEtaszYCqKz7bsl4lAUTOaYxO8On_/view?usp=sharing
**Watch the video demo of the script execution:**https://drive.google.com/file/d/106T4JU9xtj45imyTl3u_S8EjFRhTiCWy/view?usp=sharing

## **Conclusion**

This repository demonstrates the integration of computer vision and video processing techniques to solve real-world problems. Whether it’s creating a real-time bottle flip game or generating professional-quality highlight reels for social media, these applications showcase advanced Python capabilities in the domain of computer vision and video processing.
