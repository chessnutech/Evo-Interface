## Chessnut Evo Interface
Welcome to the Chessnut Evo Interface project! This interface allows developers to seamlessly connect with the Chessnut Evo electronic chessboard. With this interface, you can directly obtain the position and identity of the pieces on the board and control the LEDs on the chessboard.
### Features
•	Real-time Piece Tracking: Get accurate and real-time data on the position and identity of each piece on the Chessnut Evo board.
•	LED Control: Control the LEDs on the Chessnut Evo board to enhance your chess-playing experience or create custom light patterns.
•	Easy Integration: Simple and easy-to-use APIs for quick integration with your applications or chess engines.
### Getting Started
Chessnut Evo develop guide Android 11 Ver.

in this version we use the AIDL feature to communicate between application and our chessnut evo service. please refer to the sample code included in the zip folder.

something important:

to enable AIDL, you need to add 

    buildFeatures {
        aidl true
    }

in your module's build.gradle file.
### Contributions
We welcome contributions from the community! If you have ideas for new features or improvements, feel free to open an issue or submit a pull request.
### License
This project is licensed under the MIT License.
### Support
If you encounter any issues or have any questions, please open an issue in this repository, and we'll be happy to help.

