# Java Console Audio Player

A simple Java console-based audio player that plays a `.wav` audio file using the `javax.sound.sampled` package. Users can interact with the player via keyboard input to play, stop, reset, or quit.

## Features

- 🔁 Play, stop, and reset `.wav` audio files
- ⌨️ Interactive console-based UI
- 🔊 Uses Java's built-in `javax.sound.sampled` API

## Requirements

- Java 8 or later
- `.wav` audio file (included or provided by user)

## 🚀 How to Run

### 1. Clone or Download the Project

```bash
git clone https://github.com/Nika-HISK/Java-Music-Player.git
```
### 2. Navigate to the Source Directory
```
cd src
```
### 3. Compile the Program
```
javac Main.java
```
### 4. Run the Program
```bash
java Main
```

### 5. Console Commands

| Command | Action            |
| ------- | ----------------- |
| `P`     | ▶️  Play          |
| `S`     | ⏹️  Stop          |
| `R`     | 🔄 Reset playback |
| `Q`     | ❌ Quit           |

### 6. ⚙️ Customization
To play a different audio file:
1. Replace Tomorrow.wav in the src/ folder with your own .wav file.
2. Update the filePath in Main.java accordingly:
```bash
String filePath = "src\\YourFileName.wav";
```



