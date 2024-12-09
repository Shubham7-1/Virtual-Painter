# Virtual Painter with Hand Gesture Recognition 🎨🖋️

This project, **Virtual Painter**, allows users to draw and erase in real-time using hand gestures captured through a webcam. The tool leverages **MediaPipe** for hand gesture detection and **OpenCV** for drawing and interaction. The user can select colors, switch between drawing and erasing, and even undo or redo actions.

---

## Key Features 🌟
- ✋ **Hand Gesture Recognition**: Detects hand gestures using MediaPipe, enabling drawing and erasing via simple hand movements.
- 🎨 **Dynamic Color Selection**: Allows users to pick a drawing color using a color picker or predefined color options.
- 🔄 **Undo/Redo Functionality**: Undo and redo actions to easily correct mistakes.
- 🖌️ **Real-Time Drawing**: Draw and erase in real-time using hand gestures.
- 🖥️ **FPS Display**: Tracks and displays the frames per second (FPS) for smooth interaction.

---

## Technologies Used 💻
- **Python**: Main programming language.
- **MediaPipe**: For hand gesture recognition.
- **OpenCV**: For image processing and drawing tasks.
- **Tkinter**: For color picker interface.

---

## How to Use 🖋️
1. **Run the script**: Execute the Python script to start the webcam and initialize the drawing interface.
2. **Hand Gestures**:
   - **Drawing**: Hold your index finger up to draw.
   - **Erasing**: Use the 'Eraser' tool by selecting it with your hand.
   - **Undo/Redo**: Press 'Z' to undo and 'Y' to redo actions.
3. **Color Selection**: 
   - Use the predefined color palette at the top to choose from basic colors.
   - Use the color picker to select a custom color.
4. **Clear the Canvas**: Click the "Clear" icon to reset the canvas.
5. **Save Canvas State**: Press 'S' to save the current drawing state.

---

## Features to Explore 🚀
- 🖌️ **Color Palette**: Switch between predefined colors or select custom colors.
- ↩️ **Undo/Redo Stack**: Keep track of changes to your drawing with the undo and redo functionality.
- 🌈 **Color Picker**: Opens a Tkinter color chooser to pick any color for drawing.

---

## Installation Instructions 📦

1. **Clone the Repository**: 
    ```bash
    git clone https://github.com/Shubham7-1/Virtual-Painter.git
    cd virtual-painter
    ```

2. **Install Dependencies**:
    You need **OpenCV**, **MediaPipe**, and **Tkinter**. You can install them using pip:
    ```bash
    pip install opencv-python mediapipe
    ```

3. **Run the Script**:
    Ensure that you have a webcam connected and simply run:
    ```bash
    python virtual_painter.py
    ```

---

## Screenshots 📸

![image](https://github.com/user-attachments/assets/2c8cde0a-eca5-4027-b2c8-3a145e08dc72)
![image](https://github.com/user-attachments/assets/24be363c-f0e8-42ff-ad47-7a13238c91b0)


---

## Future Enhancements ✨
- 🖐️ **Multi-Hand Detection**: Allow multiple users to draw simultaneously.
- ✏️ **Shape Drawing**: Add tools to draw shapes like circles, rectangles, and lines.
- 💾 **Save Functionality**: Save your artwork as an image file.
- 🖌️ **Custom Brushes**: Implement more brush styles and textures.

---


